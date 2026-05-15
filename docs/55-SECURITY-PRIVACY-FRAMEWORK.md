**GRAFFITI KINGS – SECURITY & PRIVACY FRAMEWORK**

**Purpose:**
Trust is everything. This document outlines how the app protects user data, API keys, location information, and creative work — while staying true to the 100% decentralised philosophy.

---

### **Core Principles**

1. **User Data Stays With the User**
   - No central database of user information
   - All personal data, preferences, and history stored locally on the device
   - Users can export or delete everything with one tap

2. **API Keys Are Sacred**
   - API keys (Claude, Groq, Grok, etc.) are stored encrypted on-device only
   - Never sent to any GRAFFITI KINGS servers
   - User has full control and can revoke access anytime

3. **Location Data is Optional and Private**
   - Geofencing and location features are completely optional
   - All location processing happens on-device when possible
   - No location history is stored or shared without explicit consent

4. **Creative Work Belongs to the User**
   - All campaigns, lore, press releases, and Map Art created by the user belong to them
   - No GRAFFITI KINGS claim on user-generated content
   - Users can export everything in open formats

---

### **Technical Protections**

**Local-First Architecture**
- Core brain and all user data run locally
- Optional cloud sync is encrypted end-to-end (user controls the key)
- No telemetry or analytics sent without explicit opt-in

**Encryption**
- All sensitive data (API keys, location history, personal notes) encrypted at rest using device-native encryption
- API calls to external models use secure connections only

**Minimal Data Collection**
- The app collects almost nothing by default
- Only anonymous crash reports (opt-in)
- No advertising or tracking pixels

**Open Source Potential**
- Long-term goal: Make core components open source so the community can audit and improve security

---

### **SPARK Security Behavior**

**SPARK should:**
- Never ask for unnecessary personal information
- Warn users clearly before any data leaves the device
- Help users understand privacy implications of each feature
- Make it easy to stay in maximum privacy mode (LITE + no location + no cloud)
- Regularly remind users of their privacy controls

**Example SPARK Message:**
“Just a reminder — everything you create here stays on your device unless you choose to connect an API or enable cloud features. You’re in full control.”

---

### **User Controls**

- One-tap “Privacy Mode” that disables all optional features
- Clear dashboard showing exactly what data is stored and where
- Easy export of all personal data and creative work
- One-tap permanent deletion of everything

---

**Final Truth:**
In a world where most apps harvest your data, GRAFFITI KINGS does the opposite. We give you tools to create, not tools to be tracked. Your art, your data, your power. That’s the promise.
**SPARK VOICE LISTENING MODE – New Feature Spec**

**Feature Name:** SPARK Ears (Voice Context + Dictaphone)

**Tagline:** “The more I hear, the better I can help.”

---

### **Why This Feature Exists**

Two powerful use cases:

**1. Learning Mode (Context Enrichment)**
- SPARK listens to your phone’s microphone (with permission) to understand your world better.
- Learns your habits, interests, environment, and energy levels.
- Uses this to give more relevant, personalized suggestions.
- Example: Hears you talking about street art in Bristol → suggests local walls, Bristol-specific lore, or nearby events.

**2. Dictaphone Mode (Audio Expansion)**
- Record voice notes, YouTube clips, conversations, or ideas.
- Ask SPARK to expand, analyze, or turn it into content.
- Example: Record a 30-second YouTube clip about a new trend → SPARK transcribes it and suggests 5 guerrilla campaign ideas based on it.

---

### **Core Controls (User-Facing)**

**Main Toggle:**
- SPARK Listening: **On / Off** (big, clear switch)

**Granular Permissions (when On):**
- Always listening (background)
- Only when app is open
- Only when I tap the mic button (manual dictaphone mode)
- Never listen to calls or private conversations (hardcoded filter)

**Privacy First:**
- All audio is processed locally when possible
- Transcripts are stored encrypted on device
- User can delete all voice data with one tap
- No audio is ever sent to servers without explicit consent
- Clear indicator (red dot or icon) when listening is active

---

### **How It Works**

**Learning Mode:**
- SPARK periodically samples audio (every 5–10 mins when active)
- Uses on-device speech-to-text (local LLM)
- Extracts high-level context only (topics, mood, location hints)
- Never stores full conversations
- Feeds into Living Brain for better personalization

**Dictaphone Mode:**
- User taps mic icon → records audio
- SPARK transcribes + analyzes
- User can ask:
  - “Expand this into 5 campaign ideas”
  - “Turn this into a poster slogan”
  - “What’s the trend here?”
  - “Make this into lore for my universe”
- Results appear instantly in chat with SPARK

---

### **SPARK Dialogue Examples**

**Learning Mode Active:**
- “I noticed you’re in Bristol a lot. Want me to suggest some local walls and events?”
- “You’ve been talking about music lately. Want to turn that into a sound-based campaign?”

**Dictaphone Mode:**
- “Got it. I heard you talking about [topic]. Want me to expand this into content or campaign ideas?”
- “Transcribed. Here’s 5 ways we can turn this into guerrilla gold.”

---

### **Safety & Trust Rules (Hardcoded)**

- Red indicator light/icon when listening is active
- One-tap “Delete All Voice Data” button
- No cloud upload without explicit user approval
- Never listens during phone calls or sensitive moments (AI filter)
- User can set “Do Not Listen” time windows (e.g. 10pm–6am)
- Full transparency log: “SPARK listened for 47 minutes today. Here’s what it learned.”

---

### **Technical Notes**

- Uses on-device speech-to-text (Whisper or local LLM equivalent)
- Falls back to cloud only if user enables “Higher Accuracy Mode”
- Audio never leaves device unless user explicitly shares a clip with SPARK
- Integrates with Living Brain context system

---

**Status:** Ready for MVP in Phase 2 (after core features are stable)

**User Benefit:**
This turns SPARK from a reactive assistant into a truly proactive, context-aware partner that understands your world without you having to explain everything every time.
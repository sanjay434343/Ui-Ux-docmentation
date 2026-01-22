# 🎧 Voice Reels App — UI & UX Design README

An audio-first, reels-style social application where users scroll through short voice clips.
No video. No comments. Minimal UI. The experience is fast, calm, and human.

---

## 🧠 Product Philosophy

- Audio-first experience
- Gesture-driven navigation
- Minimal text, minimal buttons
- No pressure to engage
- UI should disappear once audio starts

> The app should feel like listening, not browsing.

---

## 🎨 Global Design Principles

- Dark-first UI (reduces eye strain, enhances audio focus)
- One primary action per screen
- Soft motion only (no aggressive animations)
- No visible metrics by default (likes, counts hidden)
- Abstract visuals (waveforms, gradients)

---

## 📱 Screen-by-Screen UI Plan

---

## 1. Splash Screen

**Purpose**
- Brand introduction
- Smooth app entry

**UI Elements**
- App logo (center)
- Subtle animated waveform or gradient pulse

**UX Notes**
- Duration < 1.5s
- No text
- No loading indicators

---

## 2. Authentication Screen

**Purpose**
- Allow entry with minimal friction

**UI Elements**
- App logo (top)
- Primary button:
  - “Continue with Google”
  - or “Continue”
- Optional micro-text:
  - “No posts. Just voices.”

**UX Notes**
- No forms
- No username selection here
- Simple, quiet layout

---

## 3. Home Screen (Core Experience)

**Purpose**
- Primary voice reels feed

**Layout**
- Full-screen vertical feed
- One voice per screen

**UI Elements**
- Background: abstract gradient / blurred waveform
- Center: animated waveform synced to audio
- Bottom-right:
  - ❤️ Like
  - 🔖 Save
- Bottom-left:
  - 🎙 Record (floating action)
- Subtle paragraph prompt (low opacity)

**Gestures**
- Swipe up → next voice
- Swipe down → previous voice
- Tap → pause / play
- Long press → options (report)

**UX Notes**
- No usernames visible initially
- UI fades during playback
- Infinite scroll feel without feed clutter

---

## 4. Record Voice Screen

**Purpose**
- Let users post a voice quickly

**UI Elements**
- Full-screen dark background
- Large circular “Hold to Record” button (center)
- Animated waveform ring while recording
- Subtle text:
  - “15 seconds max”

**UX Notes**
- Hold-to-record only
- Auto-stop at max duration
- No complex editing tools

---

## 5. Upload / Processing State

**Purpose**
- Feedback without delay

**UI Elements**
- Full-screen overlay
- Soft animated loader
- Text:
  - “Uploading your voice…”

**UX Notes**
- No progress percentage
- Auto-dismiss
- Non-blocking

---

## 6. Upload Success State

**Purpose**
- Confirm action gently

**UI Elements**
- Center text:
  - “Your voice is live.”

**UX Notes**
- Display for ~2 seconds
- No buttons
- Fade out smoothly

---

## 7. Profile Screen (Self)

**Purpose**
- Personal identity & content overview

**UI Elements**
- Abstract avatar
- Username (prominent)
- Stats row:
  - Voices
  - Followers
  - Following

**Sections**
- My Voices
- Saved Voices

**UX Notes**
- No visible like counts
- Clean, calm layout

---

## 8. Profile Screen (Other Users)

**Purpose**
- Explore another user’s voice identity

**UI Elements**
- Avatar
- Username
- Follow / Unfollow button
- Voice list

**UX Notes**
- Follow button is subtle
- No bios required

---

## 9. Followers / Following List

**Purpose**
- Social connection view

**UI Elements**
- List with:
  - Avatar
  - Username
  - Follow state

**UX Notes**
- No activity status
- No recommendations inside list

---

## 10. Saved Voices Screen

**Purpose**
- Private listening space

**UI Elements**
- List of saved voices
- Tap to play
- Long press to remove

**UX Notes**
- No social signals
- Personal-only content

---

## 11. Settings Screen

**Purpose**
- Control & trust

**Sections**
- Account
  - Username
  - Email
- Notifications
- Privacy
- Log out

**UX Notes**
- Plain list UI
- High contrast
- No animations

---

## 12. Report / Safety Modal

**Purpose**
- Content moderation

**UI Elements**
- Bottom sheet modal
- Options:
  - Abuse
  - Spam
  - Inappropriate
- Submit button

**UX Notes**
- One-tap reporting
- No follow-up questions

---

## 🌀 Motion & Animation Guidelines

- Duration: 200–300ms max
- Ease-in-out curves only
- Waveform animations synced to audio amplitude
- Avoid bounce or elastic effects

---

## 🔤 Typography Guidelines

- Rounded, modern sans-serif font
- Large text only for:
  - Username
  - Core prompts
- Paragraphs max 3 lines on UI

---

## 🎨 Color Guidelines

- Dark base background
- Single accent color for:
  - Waveforms
  - Record button
- Red reserved only for reports

---

## 🧩 UX Golden Rule

> The interface should fade into the background once the voice starts playing.

---

## ✅ Deliverables for Designer

- Figma frames per screen
- Component library (buttons, waveform, icons)
- Light & dark states (if needed)
- Motion reference (Lottie / prototype)

---

## 🏁 End Note

This app is not about interaction.
It is about **listening without pressure**.

Design accordingly.

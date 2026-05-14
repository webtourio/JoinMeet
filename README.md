# Voom
Free Online Meeting Site

 MeetSpace


A lightweight, browser-based video meeting platform built with pure HTML, CSS, and JavaScript. No frameworks, no backend — just open the file and meet.


---


 Features


 Meeting Management
- Create a Meeting — Generates a unique Meeting ID and a shareable link instantly
- Join a Meeting — Enter any Meeting ID to join an existing session
- Share Meeting — Copy the meeting link or ID to clipboard with a single click


 In-Meeting Controls
- Camera toggle — Turn your video on or off
- Microphone toggle — Mute or unmute yourself
- Screen sharing — Share your screen with all participants
- Leave meeting — Exit the session cleanly at any time


 Host Controls
- Mute All — A host-only button that mutes every participant simultaneously. Guests are notified that the host muted everyone


 Notifications
- Join / Leave Toast Notifications — Small pop-up cards slide in from the bottom-right corner when a participant joins or leaves. Each toast auto-dismisses after 3 seconds and stacks cleanly if multiple events happen at once
- Screen share alerts — Screen share start/stop events are shown in the chat panel


 Participants Panel
- Live list of all participants in the current session
- Host is marked with a Host badge
- Participant count updates in real time


 Chat
- In-meeting text chat visible to all participants
- Clean message bubbles with sender name and timestamp


---


 Tech Stack


| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, Flexbox, Grid) |
| Logic | Vanilla JavaScript (ES6+) |
| Icons | Font Awesome 6.5 |
| Fonts | Segoe UI / System UI |


No npm, no build step, no server required.


---


 Design System


| Token | Value |
|-------|-------|
| Background | `ffffff` |
| Primary / Accent | `47008E` |
| Primary Hover | `5a00b5` |
| Danger | `d7263d` |
| Success | `1a8a4a` |
| Border Radius | `14px` |


---


 Getting Started


1. Download `index.html`
2. Open it in any modern browser (Chrome, Edge, Firefox, Safari)
3. Click New Meeting to start a session or Join Meeting to enter an existing one
4. Share the Meeting ID or link with others


> No installation, no account, no dependencies beyond an internet connection for the Font Awesome CDN.


---


 File Structure


```
meetspace/
└── index.html       Everything — HTML, CSS, and JS in a single file
└── README.md        This file
```


---


 Browser Support


Works on all modern browsers that support:
- WebRTC (camera / microphone / screen share)
- CSS custom properties
- ES6 JavaScript


---


 Notes


- This project uses the WebRTC API for media access. Browsers will prompt for camera and microphone permissions when starting or joining a meeting
- Screen sharing requires browser support for `getDisplayMedia`
- The host role is assigned to the user who creates the meeting. Joining resets the host state, so the Mute All button will not appear for guests
- Toast notifications are purely UI-side and do not rely on a signaling server


---


 License


MIT — free to use, modify, and distribute.





# _AIR-CANVAS_


An AI-powered Air Canvas that lets users draw in the air using hand gestures captured via a webcam. Built with MediaPipe Hands, HTML5 Canvas, and JavaScript, this project enables real-time finger tracking for drawing, erasing, and color selection—no mouse or touch required.

⸻

🚀 Features
	•	✋ Finger-based Drawing
	•	Draw using your index finger
	•	Drawing activates when index finger is up and middle finger is down
	•	🎨 Multiple Color Palette
	•	Red, Orange, Yellow, Green, Cyan, Blue, Indigo, Purple, White
	•	Hover over a color to select (no clicking needed)
	•	🧽 Eraser Tool
	•	Erase parts of the drawing using air gestures
	•	🧼 Clear Canvas
	•	Instantly clear the entire canvas
	•	👁️ Hand Skeleton Toggle
	•	Show or hide MediaPipe hand landmarks and connections
	•	🪟 Glassmorphism UI
	•	Modern floating toolbar with hover-based progress selection
	•	🔄 Real-time Webcam Processing
	•	Fully immersive mirrored video and canvas alignment

⸻

🛠️ Tech Stack
	•	Frontend: HTML5, CSS (TailwindCSS), JavaScript
	•	Computer Vision: MediaPipe Hands
	•	Rendering: HTML Canvas API
	•	UI Styling: Glassmorphism + TailwindCSS
	•	Webcam Access: MediaDevices API




  ⚙️ How It Works
	1.	Webcam Feed
	•	Captures real-time video using the browser camera
	•	Video is mirrored for natural interaction
	2.	Hand Tracking
	•	MediaPipe detects 21 hand landmarks
	•	Index finger tip is used for drawing coordinates
	3.	Gesture Logic
	•	✅ Index finger up + middle finger down → Draw
	•	❌ Other gestures → Stop drawing
	4.	Hover-Based Tool Selection
	•	Hover your finger over toolbar icons
	•	Progress ring fills → tool gets selected
	5.	Canvas Drawing
	•	Draws smooth strokes on canvas
	•	Uses compositing for eraser functionality

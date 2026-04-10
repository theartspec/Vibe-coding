# Gesture controlled Drawing System

Turn your hand into a pen.
No mouse. No touch. Just vibes.

---

## What this does?

- Tracks your hand in real-time
- Uses your index finger to draw on screen
- Lets you clear everything with a simple pinch

Basically, you’re drawing in the air and it shows up instantly.

---

## Behind the scenes

- Webcam captures your hand
- MediaPipe detects 21 hand landmarks
- Index finger position → drawing point
- Points connect → smooth lines
- Finger distance → gesture control

---


## Tech Stack

- Python
- OpenCV
- MediaPipe
- NumPy

---

## Project Structure

gesture-project/

│

├── main.py          # Main application file

├── README.md        # Project documentation

---

## Setup

```bash
git clone https://github.com/YOUR_USERNAME/vibecoding.git
cd vibecoding

py -3.10 -m venv venv
venv\Scripts\activate

pip install opencv-python mediapipe numpy

python main.py
```

### Create virtual environment

<pre class="overflow-visible! px-0!" data-start="1157" data-end="1212"><div class="relative w-full mt-4 mb-1"><div class=""><div class="relative"><div class="h-full min-h-0 min-w-0"><div class="h-full min-h-0 min-w-0"><div class="border border-token-border-light border-radius-3xl corner-superellipse/1.1 rounded-3xl"><div class="h-full w-full border-radius-3xl bg-token-bg-elevated-secondary corner-superellipse/1.1 overflow-clip rounded-3xl lxnfua_clipPathFallback"><div class="pointer-events-none absolute inset-x-4 top-12 bottom-4"><div class="pointer-events-none sticky z-40 shrink-0 z-1!"><div class="sticky bg-token-border-light"></div></div></div><div class="relative"><div class="w-full overflow-x-hidden overflow-y-auto"><div class="relative z-0 flex max-w-full"><div id="code-block-viewer" dir="ltr" class="q9tKkq_viewer cm-editor z-10 light:cm-light dark:cm-light flex h-full w-full flex-col items-stretch ͼk ͼy"><div class="cm-scroller"><div class="cm-content q9tKkq_readonly"><span>py </span><span class="ͼu">-3</span><span>.10 </span><span class="ͼu">-m</span><span> venv venv</span><br/><span>venv\Scripts\activate</span></div></div></div></div></div></div></div></div></div></div><div class=""><div class=""></div></div></div></div></div></pre>

---

### Install dependencies

<pre class="overflow-visible! px-0!" data-start="1248" data-end="1301"><div class="relative w-full mt-4 mb-1"><div class=""><div class="relative"><div class="h-full min-h-0 min-w-0"><div class="h-full min-h-0 min-w-0"><div class="border border-token-border-light border-radius-3xl corner-superellipse/1.1 rounded-3xl"><div class="h-full w-full border-radius-3xl bg-token-bg-elevated-secondary corner-superellipse/1.1 overflow-clip rounded-3xl lxnfua_clipPathFallback"><div class="pointer-events-none absolute inset-x-4 top-12 bottom-4"><div class="pointer-events-none sticky z-40 shrink-0 z-1!"><div class="sticky bg-token-border-light"></div></div></div><div class="relative"><div class="w-full overflow-x-hidden overflow-y-auto"><div class="relative z-0 flex max-w-full"><div id="code-block-viewer" dir="ltr" class="q9tKkq_viewer cm-editor z-10 light:cm-light dark:cm-light flex h-full w-full flex-col items-stretch ͼk ͼy"><div class="cm-scroller"><div class="cm-content q9tKkq_readonly"><span>pip install opencv-python mediapipe numpy</span></div></div></div></div></div></div></div></div></div></div><div class=""><div class=""></div></div></div></div></div></pre>

---

## Usage

Run the application:

<pre class="overflow-visible! px-0!" data-start="1343" data-end="1369"><div class="relative w-full mt-4 mb-1"><div class=""><div class="relative"><div class="h-full min-h-0 min-w-0"><div class="h-full min-h-0 min-w-0"><div class="border border-token-border-light border-radius-3xl corner-superellipse/1.1 rounded-3xl"><div class="h-full w-full border-radius-3xl bg-token-bg-elevated-secondary corner-superellipse/1.1 overflow-clip rounded-3xl lxnfua_clipPathFallback"><div class="pointer-events-none absolute inset-x-4 top-12 bottom-4"><div class="pointer-events-none sticky z-40 shrink-0 z-1!"><div class="sticky bg-token-border-light"></div></div></div><div class="relative"><div class="w-full overflow-x-hidden overflow-y-auto"><div class="relative z-0 flex max-w-full"><div id="code-block-viewer" dir="ltr" class="q9tKkq_viewer cm-editor z-10 light:cm-light dark:cm-light flex h-full w-full flex-col items-stretch ͼk ͼy"><div class="cm-scroller"><div class="cm-content q9tKkq_readonly"><span>python main.py</span></div></div></div></div></div></div></div></div></div></div><div class=""><div class=""></div></div></div></div></div></pre>

---

## Controls

* Move index finger → Draw
* Pinch (thumb + index) → Clear screen
* Press `Q` → Exit application

---

## How It Works

1. Webcam captures real-time video
2. MediaPipe detects hand landmarks (21 points)
3. Index finger position is tracked
4. Drawing points are stored and rendered
5. Gesture recognition (distance between fingers) triggers actions

---

## Future Improvements

* Color selection using gestures
* Eraser mode
* Neon glow effects
* Gesture-based UI controls
* AI gesture recognition

Author : Anu Ann Biju

# GroqVision // Neural Image Intelligence Studio

A high-speed, creative vision studio powered by **Groq LPU** inference and multimodal vision models like **`qwen/qwen3.8-27b`** and **`meta-models/muse-spark-open`**.

---

## 🔒 Security & Hidden API Key Entry

* **Masked by Default:** The Groq API key is entered in a secure `type="password"` input field, completely hidden from onlookers and screen recordings.
* **Eye Toggle:** You can click the eye icon to temporarily reveal/inspect the key.
* **Local-Only Storage:** Saved only in your browser's `localStorage` and sent **directly to `https://api.groq.com`** via client-side `fetch`. Never routed through any proxy or backend.
* **Instant Wipe:** Click the trash icon to instantly purge the key from memory and storage.

---

## 🚀 Quick Start: How to Open & Use

### Option 1: macOS Terminal Command (Single Line)
```bash
open -a "Google Chrome" /Users/himanshu/.gemini/antigravity/scratch/groq-vision-studio/index.html
```

### Option 2: Directly in Google Chrome
1. Open Google Chrome.
2. Paste this exact file URL into your address bar and hit **Enter**:
   ```text
   file:///Users/himanshu/.gemini/antigravity/scratch/groq-vision-studio/index.html
   ```

---

## 🎨 Creative Features

1. **Multiple Input Methods:**
   * **Drag & Drop** or file browse.
   * **Clipboard Paste** (`Cmd + V` / `Ctrl + V` anywhere).
   * **Live Webcam Snapshot** (Capture directly from your camera).
   * **1-Click Sample Demos** (Cyber City, Gourmet Dish, Misty Peaks, Analytics UI).

2. **Creative Vision Lenses (Prompt Presets):**
   * 👁️ **Holistic Scene:** Deep breakdown of subjects, spatial layout, mood, and fine details.
   * 🔍 **OCR & Details:** Forensic extraction of all visible text, signage, labels, brands, and numbers.
   * 🎨 **Aesthetics & Art:** Composition analysis (rule of thirds, framing), color harmony, simulated camera aperture/focal length.
   * 📖 **Cinematic Lore:** Generates an atmospheric narrative and fictional backstory inspired by the scene.
   * ❓ **Custom Prompt:** Ask any specific question (e.g., *"What brand of shoes is the person wearing?"*).

3. **Dominant Color Palette Extraction:**
   * Client-side HTML5 canvas automatically extracts the top 6 dominant colors from the image with 1-click hex copy.

4. **Groq LPU Ultra-Fast Streaming:**
   * Character-by-character live stream with real-time **Tokens/second** and **Latency (ms)** counters.

5. **Text-to-Speech & Export:**
   * **Read Aloud** button reads the AI's description out loud via browser speech synthesis.
   * **Copy Report** button copies clean Markdown to your clipboard.

6. **Multi-Turn Visual Q&A:**
   * After the initial description, continue asking follow-up questions about the image with full conversational context.

# ⚡ NeonClipping Cloud Studio (Google Colab + Google Drive)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akashrajgm/neonclipping-colab/blob/main/NeonClipping_Google_Colab.ipynb)

Turn long YouTube videos, Twitch streams, and podcasts into viral **9:16 vertical shorts** (Instagram Reels, YouTube Shorts, TikTok) with **zero local disk usage** on your Mac or PC.

---

## 🌟 Why Use Google Colab?

- ☁️ **100% Cloud-Powered:** Heavy video downloads (1–3 GB), Whisper AI transcription, and video encoding happen completely on Google's cloud servers.
- 💾 **Automatic Google Drive Export:** All finished vertical clips are automatically saved directly into your Google Drive (`/MyDrive/NeonClips`).
- ⚡ **Zero Local Storage:** Your local Mac/PC SSD uses **0 MB** of disk space.
- 🚀 **Free GPU Acceleration:** Runs on Google cloud GPUs (T4), making AI transcription and video rendering 5x faster.

---

## 🚀 How to Use (3 Simple Steps)

### Step 1: Open the Notebook
Click the button below to open the notebook directly in your browser:

👉 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akashrajgm/neonclipping-colab/blob/main/NeonClipping_Google_Colab.ipynb)

### Step 2: Connect Google Drive & Setup
1. In Colab, make sure GPU is active (`Runtime` -> `Change runtime type` -> `T4 GPU`).
2. Run **Step 1: Connect Google Drive** (grant permission to save clips to your Drive).
3. Run **Step 2: Setup NeonClipping Cloud Engine** (~40 seconds to install dependencies).

### Step 3: Generate Your Clips (Choose Method A or B)

#### Method A: Instant Form Clipper
- Paste your YouTube URL.
- Select your layout (`blur`, `split`, `crop`, `cam_tl`, `circle`).
- Select your caption style (`gta`, `hormozi`, `mrbeast`, `impact`, `clean`).
- Click **Run**. All rendered vertical clips are saved directly to `Google Drive / NeonClips`!

#### Method B: Interactive Web Studio
- Run **Step 3 (Method B)**.
- Colab generates a secure public Cloudflare URL (e.g. `https://xxxx.trycloudflare.com`).
- Open the URL in your browser to use the full visual drag-and-drop facecam editor and transcript browser hosted on Colab!

---

## 📜 Credits & License
Powered by [NeonClipping](https://github.com/iamajmeena/neonclipping) by Ajay K Meena.

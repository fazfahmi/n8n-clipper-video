# 🎬 n8n Workflow – Automated Video Clipping & Text Overlay (In Progress)

## 📝 Description
This workflow is being developed in **n8n** to automate the process of preparing short video clips with dynamic text overlays.  
The workflow is still **in progress**, but the main idea is to combine **Google Sheets integration** for text overlays with **automated video editing** (splitting + overlay).  

It consists of two main parts:

1. **Overlay Text Management** – Retrieve overlay texts from **Google Sheets**.  
2. **Video Processing** – Split input videos into clips (max 30 seconds) and apply the overlay text.  

---

## ⚙️ Workflow Steps (Planned)

### Part 1 – Overlay Text (Google Sheets)
- **Google Sheets Node** → Stores and retrieves overlay text.  
- Text can be updated anytime by editing the Google Sheet.  
- This ensures flexibility in changing captions, hooks, or CTAs without re-editing the video manually.  

### Part 2 – Video Processing
- **Input Video** → Original video file uploaded into the workflow.  
- **Video Split Node** → Cuts the video into 30-second clips.  
- **Overlay Node** → Applies text overlay fetched from Google Sheets to each clip.  
- **Output Storage** → Saves final processed clips with overlay applied.  

---

## 🖼️ Workflow Example (Conceptual)
<img width="2066" height="359" alt="image" src="https://github.com/user-attachments/assets/b6930271-7751-450b-905d-89ad0fb1d3e0" />


*(A screenshot of the current workflow in the n8n editor can be added here, showing the progress so far.)*  

---

## 🚀 Current Status
- **Overlay text integration with Google Sheets** → ✅ implemented.  
- **Basic video splitting logic** → ✅ implemented.  
- **Applying overlay text to split clips** → 🚧 work in progress.  
- **Output optimization & final testing** → 🚧 pending.  

---

## 🎯 Expected Results
- Automatically generates multiple short clips from one long video.  
- Each clip will contain overlay text (captions, hooks, CTAs).  
- Will reduce manual editing time and ensure consistency for marketing/social media content.  

---

## ⚠️ Notes
- This workflow export uses **dummy credentials and file paths** for security.  
- The project is **still under development** and not yet production-ready.  
- Actual implementation requires Google Sheets API access and FFmpeg integration in n8n.  

---

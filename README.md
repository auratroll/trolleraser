# TrollEraser 🧌

Paper / document watermark remover that runs 100% in the browser. No server, no API keys, no limits.

## Features
- **Manual (Auto Clean):** removes light gray and colored watermarks, fixes shadows, keeps text sharp
- **Batch:** clean many images at once and download them as one ZIP
- **AI Brush:** paint over logos and stamps, and the LaMa AI model fills the area (model is about 200MB, downloaded once and cached in the browser)

## Deploy on Vercel
1. Create a new GitHub repository and upload `index.html` (and this README).
2. On vercel.com, click **Add New → Project**, import the repository, and click **Deploy**.
3. No build settings or environment variables are needed.

## Credits
AI inpainting: LaMa (Samsung Research, Apache-2.0), ONNX export by Carve (Carve/LaMa-ONNX, Apache-2.0).

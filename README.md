# My Live Stream Site

This project lets you stream any `.m3u8` link on your own site with a proxy to bypass CORS issues.

## 🚀 Setup & Deployment

1. **Clone or Fork this Repo**
   ```bash
   git clone https://github.com/YOUR_USERNAME/my-live-stream-site.git
   cd my-live-stream-site
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Run Locally**
   ```bash
   npm start
   ```
   Test at [http://localhost:3000/proxy?url=YOUR_M3U8](http://localhost:3000/proxy?url=YOUR_M3U8)

4. **Deploy Proxy on Render**
   - Go to [https://render.com](https://render.com)
   - Create a "Web Service"
   - Connect this repo
   - Set `Start Command` to:
     ```
     npm start
     ```
   - Deploy — copy your Render URL (example: `https://myproxy.onrender.com`)

5. **Update `index.html`**
   - Replace `https://your-proxy-service.onrender.com` with your Render URL
   - Commit and push changes

6. **Deploy Frontend on GitHub Pages**
   - Go to GitHub repo → Settings → Pages → Deploy from `main` branch
   - Open your live link and enjoy 🚀

## ⚠️ Legal Disclaimer
This is for educational use only. Do not use to restream copyrighted content without permission.

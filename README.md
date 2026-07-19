# 🥋 Shinobi Ultimate — DevOps Deployment Project

Live fighting game deployed using a complete free-tier DevOps pipeline.

## 🔗 Live Demo
[Play Now](your-live-link-here)

## ⚙️ Tech Stack
- **Containerization:** Docker
- **CI/CD:** GitHub Actions (automated build → test → deploy)
- **Reverse Proxy / Traffic Control:** Nginx
- **Hosting:** Free-tier cloud (Oracle Cloud / Render)
- **CDN + DNS + SSL:** Cloudflare (free)
- **Domain:** Free custom domain

## 🚀 Pipeline Flow
1. Code pushed to `main` branch
2. GitHub Actions triggers automatically
3. Docker image built & tested
4. Auto-deployed to live server
5. Nginx handles traffic routing & rate limiting
6. Cloudflare provides CDN caching + DDoS protection

## 📦 Run Locally
\`\`\`bash
docker-compose up --build
\`\`\`

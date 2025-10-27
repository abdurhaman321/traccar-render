# Traccar Render Mobile-Ready

Deploy the official Traccar GPS server on Render for free using Docker.

## Quick steps
1. Connect this repo to Render.com (create free account).
2. New Web Service → connect GitHub repo.
3. Environment: Docker
4. Instance type: Free
5. Leave Start Command empty
6. Add environment variable: `PORT=8082`
7. Deploy
8. When logs show “Server started”, open your site:
   https://your-app-name.onrender.com
9. Login: admin / admin

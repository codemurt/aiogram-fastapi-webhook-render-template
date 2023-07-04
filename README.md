# Aiogram FastAPI template with webhooks to deploy to Render

Start command:
```
gunicorn -k uvicorn.workers.UvicornWorker main:app --timeout 15
```

Set telegram webhook:
```
https://api.telegram.org/bot<TOKEN>/setWebhook?url=https://<YOUR_RENDER_WEB_SERVICE_NAME>.onrender.com/bot/<TOKEN>
```
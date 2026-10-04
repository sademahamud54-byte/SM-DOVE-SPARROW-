# 🕊️ SM DOVE SPARROW — Official Telegram Mini App & Bot

Production-ready Telegram Mini App + Telegram Bot + Firebase Backend + Admin Panel for **SM DOVE SPARROW 🕊️**.

---

## ⚙️ Active Project Configuration

| Setting | Value |
|---|---|
| **APP_NAME** | `SM DOVE SPARROW` |
| **BOT_NAME** | `SM DOVE SPARROW 🕊️` |
| **BOT_USERNAME** | `@SMDOVESPARROW_bot` |
| **WEB_APP_URL** | `https://YOUR-RENDER-URL.onrender.com` |
| **ADMIN_TELEGRAM_ID** | `8801424830` |
| **ADMIN_USERNAME** | `@sadimahomud247` |
| **ADMIN_PHONE** | `01915921501` |
| **FIREBASE_PROJECT_ID** | `sm-dove-sparrow-f041c` |
| **FIREBASE_DATABASE_URL** | `https://sm-dove-sparrow-f041c-default-rtdb.firebaseio.com` |
| **MONETAG_ZONE_1** | `11924593` (Interstitial) |
| **MONETAG_ZONE_2** | `11924529` (Rewarded) |
| **MONETAG_ZONE_3** | `11924571` (In-App) |
| **MONETAG_ZONE_4** | `11949016` (Direct Push/Pop) |
| **MAX_REWARDED_ADS_PER_DAY** | `20` |
| **AD_COOLDOWN_SECONDS** | `30` |

---

## 🚀 Deployment Instructions (Render)

1. **Deploy to Render**:
   - Create a Web Service connected to your repository.
   - **Build Command**: `npm install && npm run build`
   - **Start Command**: `npm start`
   - Set the environment variables from `.env.example`.

2. **Telegram @BotFather Setup**:
   - Talk to [@BotFather](https://t.me/BotFather) on Telegram.
   - Run `/newbot` or edit your bot `@SMDOVESPARROW_bot`.
   - Run `/newapp` or `/setmenubutton` and link your Web App URL.
   - Set webhook to `https://your-service.onrender.com/api/telegram-webhook`.

3. **Firebase Realtime Database Setup**:
   - Deploy the security rules from `firebase/database-rules.json`.

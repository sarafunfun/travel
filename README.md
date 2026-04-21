# Travel Planner App

這是可直接上傳到 GitHub 的旅遊規劃前端專案，使用：

- React + TypeScript
- Vite
- framer-motion
- lucide-react

## 本地執行

```bash
npm install
npm run dev
```

## 打包

```bash
npm run build
```

## 部署到 Vercel

1. 把整個資料夾上傳到 GitHub
2. 到 Vercel 匯入這個 GitHub repository
3. Deploy

## Google Calendar 同步

若要使用 Google Calendar 功能，需要：

1. 在 Google Cloud 建立 OAuth Client ID
2. 啟用 Google Calendar API
3. 將部署網址加入 Authorized JavaScript origins
4. 把 Client ID 填入網站中的欄位

## 注意

目前分享與多人協作是前端示意版，資料儲存在 localStorage。若要真正共編，需要再接 Firebase / Supabase。

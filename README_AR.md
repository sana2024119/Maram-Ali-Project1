# SushiRestaurant

## طريقة التشغيل الصحيحة

1. افتحي مجلد `Client` في VS Code، وليس ملف `public/index.html` مباشرة.
2. افتحي Terminal داخل مجلد `Client`.
3. شغّلي:

```bash
npm install
npm start
```

4. افتحي الرابط الذي يظهر في Terminal، غالبًا `http://localhost:3000`.

## ملاحظات

- لا تستخدمي Live Server لفتح `public/index.html`؛ هذا مشروع React ويحتاج `npm start`.
- تم إصلاح اعتماد `react-router-dom`، وتحذير مفتاح عناصر السلة، وأسماء CSS الخاصة بصفحة Menu.
- صور القائمة تحتاج أن تكون داخل `Client/public/images` إذا أردتِ عرضها.

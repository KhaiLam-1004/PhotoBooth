# Photobooth App

Ứng dụng web chụp ảnh photobooth với các tính năng:
- Chụp ảnh với khung hình mùa hè và cá voi
- Nhiều layout khác nhau (2, 3, 4, 6 pose)
- Đếm ngược 4 giây trước khi chụp
- Lưu ảnh về máy tính

## Cài đặt

1. Clone repository:
```bash
git clone https://github.com/your-username/photobooth-app.git
cd photobooth-app
```

2. Cài đặt dependencies:
```bash
npm install
```

3. Chạy ứng dụng:
```bash
npm start
```

Ứng dụng sẽ chạy tại http://localhost:3000

## Sử dụng

1. Chọn layout mong muốn (2, 3, 4, hoặc 6 pose)
2. Nhấn nút "Chụp ảnh"
3. Đợi đếm ngược 4 giây
4. Sau khi chụp xong, bạn có thể:
   - Xem lại ảnh
   - Tải ảnh về máy
   - Chụp lại

## Deploy

Để deploy ứng dụng lên GitHub Pages:

1. Thêm vào package.json:
```json
"homepage": "https://your-username.github.io/photobooth-app",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
```

2. Cài đặt gh-pages:
```bash
npm install --save-dev gh-pages
```

3. Deploy:
```bash
npm run deploy
``` 
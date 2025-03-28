# HUTECH Event Frontend

Dự án quản lý sự kiện HUTECH - Giao diện người dùng được xây dựng với React và Vite.

## Giới thiệu

Đây là phần frontend của hệ thống quản lý sự kiện HUTECH, cung cấp giao diện người dùng cho các chức năng:
- Quản lý người dùng
- Quản lý sự kiện
- Quản lý chứng chỉ
- Theo dõi và báo cáo

## Công nghệ sử dụng

- React.js
- Vite
- Tailwind CSS
- React Router
- Các thư viện fonts: Roboto, Open Sans, Montserrat

## Cài đặt

### Yêu cầu hệ thống
- Node.js (phiên bản 14.x trở lên)
- npm hoặc yarn

### Các bước cài đặt

1. Clone repository về máy:
```bash
git clone https://github.com/username/hutech-event-frontend.git
cd hutech-event-frontend
```

2. Cài đặt các dependencies:
```bash
npm install
# hoặc
yarn install
```

## Cách chạy

1. Chạy ứng dụng ở môi trường phát triển:
```bash
npm run dev
# hoặc
yarn dev
```

2. Ứng dụng sẽ được chạy tại địa chỉ: `http://localhost:5173`

## Cấu trúc dự án

- `/src/pages/Admin`: Các trang quản trị viên
- `/src/pages/Colab`: Các trang dành cho cộng tác viên
- `/src/components`: Các thành phần UI có thể tái sử dụng
- `/src/services`: Các service gọi API
- `/src/assets`: Tài nguyên tĩnh (hình ảnh, icon,...)

## Build và triển khai

1. Build ứng dụng cho môi trường production:
```bash
npm run build
# hoặc
yarn build
```

2. Kết quả build sẽ được lưu trong thư mục `/dist`

## Thông tin thêm

Đây là dự án được phát triển bởi Nhóm 10. Để biết thêm thông tin chi tiết, vui lòng liên hệ với quản trị viên của dự án.

---

### Thông tin cơ bản về React + Vite

Dự án này được tạo bằng template React + Vite, cung cấp cấu hình tối thiểu để chạy React với Vite, hỗ trợ HMR và các quy tắc ESLint.

Hiện tại có hai plugin chính thức:
- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) sử dụng [Babel](https://babeljs.io/) cho Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) sử dụng [SWC](https://swc.rs/) cho Fast Refresh
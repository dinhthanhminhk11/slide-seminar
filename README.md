# Mobile Reverse Engineering & Security - Slidev Presentation

Presentation chuyên nghiệp về Mobile Reverse Engineering và các kỹ thuật bảo vệ ứng dụng.

## Cài đặt

```bash
# Cài đặt dependencies
npm install

# Hoặc sử dụng yarn
yarn install
```

## Chạy Presentation

```bash
# Development mode (với hot reload)
npm run dev

# Build static site
npm run build

# Export PDF
npm run export
```

## Cấu trúc

- `slides.md` - File chính chứa tất cả slides
- `package.json` - Dependencies và scripts
- `README.md` - Hướng dẫn này

## Nội dung Presentation

1. **Title Slide** - Giới thiệu chủ đề
2. **Introduction** - Tại sao cần Reverse Engineering
3. **Static Analysis** - Sử dụng JADX để phân tích APK
4. **Traffic Inspection** - MITM với Burp Suite
5. **Frida Introduction** - Dynamic Instrumentation
6. **Demo 1** - Bypass SSL Pinning
7. **Demo 2** - Bypass In-App Purchase
8. **Protection & Defense** - Các kỹ thuật bảo vệ cho developers
9. **Conclusion & Q&A** - Tổng kết

## Theme

Presentation sử dụng dark theme với màu nền `#0a0e27` để tạo cảm giác high-tech, phù hợp với chủ đề security.

## Lưu ý

- Đảm bảo có Node.js 16+ để chạy Slidev
- Code snippets được syntax-highlighted tự động
- Mermaid diagrams được hỗ trợ cho flowcharts


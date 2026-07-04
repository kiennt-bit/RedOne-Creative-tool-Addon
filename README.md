# RedOne Creative Tool — Addon Repository

Kho tính năng mở rộng cho [RedOne Creative Tool](https://github.com/kiennt-bit/RedOne-Creative-tool).

## Tính năng có sẵn

| ID | Tên | Loại | Kích thước | Mô tả |
|----|-----|------|-----------|-------|
| `video-editor` | Trình dựng video | frontend | ~33 KB | Timeline video editor |
| `video-upscale` | Video Upscale (AI) | asset | ~43 MB | Real-ESRGAN NCNN-Vulkan upscaler |

## Cấu trúc

```
features/
  index.json         ← Catalog chính, được RedOne fetch từ đây
```

## Releases

Các addon bundle được đính kèm dưới dạng GitHub Release assets:
- `video-editor-v1.0.0.zip` — Frontend JS bundle
- `realesrgan-ncnn-vulkan-windows.zip` — NCNN EXE + model realesr-general-x4v3

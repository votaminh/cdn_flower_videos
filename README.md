# cdn_flower_videos

Video hình nền "Một ngày của hoa": cảnh hoa nhìn từ dưới gốc ngước lên, 24 khung giờ (`h00` đến `h23`), mỗi cây một bộ.
Ảnh và video là hình minh hoạ do AI tạo.

## Cấu trúc

```
hevc/<cây>/hXX.mp4       bản tiết kiệm, HEVC ~1MB/video
original/<cây>/hXX.mp4   bản gốc, H.264 ~2,4 đến 3,8MB/video
```

Cây hiện có: `cu`, `sen`, `dong_hoa` (mỗi cây 24 video).

## Link tải

Qua jsDelivr (nên dùng tag thay vì `main` để cache ổn định):

```
https://cdn.jsdelivr.net/gh/votaminh/cdn_flower_videos@main/hevc/sen/h12.mp4
```

Hoặc raw:

```
https://raw.githubusercontent.com/votaminh/cdn_flower_videos/main/hevc/sen/h12.mp4
```

## Ghi chú

- 9,5 giây mỗi video, loop kín, không âm thanh.
- `dong_hoa`: 1088x1920. `sen` và `cu`: 720x1280.
- Repo chỉ chứa video để thử CDN, chưa phải bộ đầy đủ.

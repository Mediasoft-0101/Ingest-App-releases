# MediaSoft Ingest App: bộ cài

Repo này chỉ dùng để phát bộ cài, không chứa mã nguồn. Tải bản mới nhất ở https://mediasoft-0101.github.io/Ingest-App-releases/

| Hệ điều hành | Tệp | Cách cài |
|---|---|---|
| Windows 10/11 | `.msi` | Chạy tệp. Bản mới tự thay thế bản đang cài. |
| macOS 13 trở lên | `.dmg` | Kéo app vào Applications. Xem lưu ý bên dưới. |
| Ubuntu 22.04 / Debian 12 | `.deb` | `sudo dpkg -i <tệp>.deb` |

**Máy nào cũng cần cài [VLC](https://www.videolan.org/vlc/) trước** thì app mới phát được video.

**macOS:** bộ cài chưa được ký, nên lần mở đầu tiên macOS sẽ báo *"ứng dụng bị hỏng"*. Tệp không hỏng; đó là cờ cách ly của macOS. Mở Terminal và chạy:

```
xattr -dr com.apple.quarantine /Applications/MediaSoftMediaApp.app
```

**Windows:** bộ cài chưa được ký, nên Windows có thể hiện *"Windows protected your PC"*. Bấm **More info**, rồi chọn **Run anyway**.

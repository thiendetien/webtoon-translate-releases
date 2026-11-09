# G5 Translate

Bản phát hành của tool dịch truyện G5. Chỉ chứa file chạy, không có source code.

## Cài đặt

1. Vào mục [Releases](https://github.com/thiendetien/webtoon-translate-releases/releases/latest), tải `G5Translate-x.y.z.zip`.
2. Giải nén ra một thư mục bất kỳ (Desktop, ổ D…), **không** để trong `Program Files`.
3. Chạy `G5Translate.exe`. Nếu Windows cảnh báo: bấm **More info → Run anyway**.
4. Đăng nhập tài khoản G5 Media. Máy mới cần gửi **mã máy** (nút ở màn đăng nhập) cho quản lý để kích hoạt.
5. Bảng **Kiểm tra cài đặt** hiện ra nếu máy còn thiếu:
   - **Node.js**: bấm *Tải Node.js*, cài bản LTS, rồi bấm *Kiểm tra lại*.
   - **Codex**: bấm *Cài giúp Codex* (tự cài, 1–3 phút).
   - **Tài khoản Codex**: vào tool → *Cài đặt → Tài khoản Codex*, đăng nhập ChatGPT hoặc nhập gói `.wsacc`.

Model AI đã có sẵn trong gói, không cần tải thêm.

## Kiểm tra file tải về

Mỗi bản có file `.sha256` đi kèm. Trong PowerShell:

```powershell
Get-FileHash .\G5Translate-1.0.0.zip -Algorithm SHA256
```

Mã in ra phải trùng với nội dung file `.sha256`.

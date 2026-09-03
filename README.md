# Quảng cáo PhimRạp

Repo này chứa nội dung từ xa cho nút giỏ hàng **Mua Fshare VIP** của ứng dụng PhimRạp.

## Tệp cấu hình

Ứng dụng đọc trực tiếp tệp [`fshare-vip.json`](./fshare-vip.json) qua địa chỉ raw:

```text
https://raw.githubusercontent.com/TNB88/QuangCaoPhimRap/main/fshare-vip.json
```

Các trường được hỗ trợ:

- `schema_version`: phiên bản cấu trúc, hiện là `1`.
- `title`: tiêu đề hộp thoại.
- `message`: nội dung; dùng `\n` để xuống dòng.
- `close_button`: chữ trên nút đóng.

Chỉ sửa giá trị chuỗi, giữ JSON hợp lệ và không đổi tên trường. Không đưa mật khẩu, API key hoặc dữ liệu bí mật vào repo công khai này.

Nếu GitHub không truy cập được hoặc JSON bị lỗi, APK tự dùng nội dung dự phòng đã đóng gói sẵn.

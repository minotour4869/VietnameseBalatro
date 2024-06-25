# Vietnamese Balatro 🇻🇳

Đây là một bản mod cài tiếng Việt vào Balatro.
Dự án này độc lập với [bản mod của Kanbei](https://github.com/Kanbei-Kikuchiyo/balatro-vietnamese-translation), với điểm nhấn duy nhất nằm ở việc nó sử dụng font chữ bạn vẫn thường thấy khi dùng tiếng Anh.

# Hướng Dẫn cài mod

## Chuẩn bị Steamodded 1.0.0
- Bản 0.9.8 chưa có API cho Ngôn Ngữ. [Bản mod của Kanbei](https://github.com/Kanbei-Kikuchiyo/balatro-vietnamese-translation) sử dụng lovely thuần tuý và không có hướng dẫn cách cài đặt cho bất kì hệ điều hành nào khác ngoài Windows.
- Bạn có thể xem hướng dẫn cách cài Steamodded 1.0.0 [tại đây](https://github.com/Steamopollys/Steamodded?tab=readme-ov-file#how-to-install-the-alpha). Người chơi Balatro chí ít cũng hiểu được tiếng Anh nên sẽ không cần bản hướng dẫn Việt hoá.

## Cài đặt thủ công
- Không có cài đặt tự động nha, dùng Steamodded thì phải làm quen với điều đó.
- [Nhấn vào đây](https://github.com/HuyTheKiller/VietnameseBalatro/archive/refs/heads/main.zip) để tải bản mod này xuống.
- Giải nén rồi kéo thả thư mục VietnameseBalatro vào trong thư mục Mods. Địa chỉ tương ứng của nó sẽ là:
**Windows:** `%AppData%/Balatro`; **Mac:** `~/Library/Application Support/Balatro`; **Linux (WINE/Proton):** `~/.local/share/Steam/steamapps/compatdata/2379780/pfx/drive_c/users/steamuser/AppData/Roaming/Balatro`

# Lưu ý
- Sẽ có trường hợp Balatro bị crash do lỗi: `attempt to index field 'localization' (a nil value)`
- Để hạn chế tối đa điều đó, trả về tiếng Anh trước khi đóng Balatro.
## Cách giải quyết nếu nó xảy ra:
1. **Nếu bạn dùng Windows:**
- Đổi tên tệp version.dll
- Khởi chạy Balatro từ Steam để tái thiết tuỳ chọn ngôn ngữ
- Trả tên tệp về như cũ
2. **Nếu bạn dùng Linux (WINE/Proton):**
- Đổi tên tệp version.dll
- Xoá dòng lệnh `WINEDLLOVERRIDES="version=n,b" %command%` khỏi tuỳ chọn khởi động của Steam
- Khởi chạy Balatro từ Steam để tái thiết tuỳ chọn ngôn ngữ
- Trả tên tệp về như cũ, thêm lại dòng lệnh trên vào tuỳ chọn khởi động của Steam
3. **Nếu bạn dùng Mac (khá tiện):**
- Khi dùng lovely, bạn phải chạy dòng lệnh `sh địa_chỉ/đến_tệp/run_lovely.sh` trong Terminal
- Vì thế nên chỉ cần khởi chạy Balatro từ Steam để tái thiết tuỳ chọn ngôn ngữ
# Danh sách tính năng/công việc đang chờ
- Đóng góp để mở rộng hỗ trợ dịch thuật cho Steamodded
- Việt hoá hoàn toàn giao diện Steamodded trong game
# SeaTech Mod

Các addon Minecraft do **Lowzii** chia sẻ. Bản hiện có: **SeaTechCrafter** — bộ công cụ hỗ trợ thiết lập và kiểm tra Crafter trong farm.

## Tải SeaTechCrafter

**[Tải SeaTechCrafter 1.0.0 (.jar)](https://github.com/lowziim3tech/SeaTech-Mod/raw/refs/heads/main/mods/SeaTechCrafter-1.21.11-1.0.0.jar)**

| Phiên bản addon | Minecraft | Loại |
| --- | --- | --- |
| 1.0.0 | 1.21.11 | Addon Meteor Client |

Trên điện thoại, bấm liên kết tải phía trên để tải file. Giữ nguyên đuôi `.jar`, không cần giải nén khi cài mod.

## Các module

| Module | Chức năng |
| --- | --- |
| **Crafter Setup** | Áp dụng mẫu bật/tắt cho 9 ô Crafter; xử lý vật phẩm đang chiếm ô theo tùy chọn. |
| **Crafter Output ESP** | Đánh dấu và vẽ đường tới những Crafter chưa xuất vật phẩm kể từ lúc bật module. |
| **Crafter Cleaner** | Giữ lại vật phẩm trong whitelist; lấy vào túi hoặc vứt các vật phẩm ngoài danh sách khỏi Crafter đang mở. |
| **GUI Close** | Tự đóng những loại giao diện được chọn sau khoảng trễ cấu hình, gồm Crafter, rương, hopper và nhiều giao diện block khác. |

**Lưu ý về Output ESP:** được đánh dấu có nghĩa là module chưa ghi nhận Crafter xuất vật phẩm từ lúc kích hoạt. Đây không phải kết luận rằng Crafter bị hỏng.

## Yêu cầu

- Minecraft **1.21.11**.
- **Java 21** trở lên.
- **Fabric Loader 0.18.2** trở lên.
- **Meteor Client tương thích Minecraft 1.21.11**.

SeaTechCrafter hoạt động độc lập với SeaTech Farm. Bốn module này không yêu cầu MaLiLib, Litematica hoặc Baritone.

## Cài đặt

1. Cài Fabric Loader và Meteor Client đúng phiên bản Minecraft.
2. Tải file SeaTechCrafter từ liên kết ở đầu trang.
3. Chép file `.jar` vào thư mục `mods` của bản Minecraft đang dùng.
4. Khởi động game, mở giao diện Meteor và chọn nhóm **SeaTechCrafter**.
5. Mở cài đặt của module cần dùng, cấu hình rồi bật.

## Cách dùng nhanh

### Crafter Setup

- Chọn mẫu 9 ô: ô được bật sẽ dùng để chế tạo, ô bị khóa sẽ không nhận nguyên liệu.
- Chọn cách xử lý ô đang có vật phẩm và thời gian chờ áp dụng mẫu.
- Bật module, mở từng Crafter để áp dụng cấu hình.

### Crafter Output ESP

- Bật module trước khi chạy thử dàn farm.
- Quan sát các Crafter còn được đánh dấu và kiểm tra chúng trực tiếp.
- Có thể bật hoặc tắt đường dẫn từ camera trong cài đặt.

### Crafter Cleaner

- Đặt các vật phẩm muốn giữ trong **Whitelist Items**.
- Chọn **Loot** để lấy vật phẩm ngoài whitelist vào túi, hoặc **Drop** để vứt ra.
- Bật module và mở Crafter cần dọn.

### GUI Close

- Chọn những loại giao diện muốn tự đóng.
- Đặt **Close Delay** theo tick.
- Nếu dùng cùng Crafter Setup hoặc Cleaner, đặt thời gian đủ để thao tác xử lý hoàn tất trước khi GUI đóng.

## Cấu hình riêng

SeaTechCrafter có mod ID, nhóm module và mã lưu cấu hình riêng. Cấu hình từ SeaTech Farm không được tự động nhập sang.

Nếu cài cả hai addon, chọn một bản của từng chức năng để bật, tránh hai module cùng thao tác trên một giao diện.

## Kiểm tra và phạm vi

Bản 1.0.0 được tách từ **SeaTech Farm 2.3.6**, giữ nguyên bytecode logic của bốn module và thay các tham chiếu thuộc addon sang namespace riêng.

Đã kiểm tra đóng gói, tham chiếu nội bộ, bảo toàn mã lệnh và đăng ký đúng bốn module bằng fixture Java 21. **Chưa kiểm thử đầy đủ trực tiếp trong Minecraft.**

Mã SHA-256 của file tải nằm trong [SHA256SUMS.txt](./SHA256SUMS.txt). Bộ dựng lại được đóng kèm bên trong JAR tại `META-INF/seatechcrafter/rebuild/`; bộ này giữ các class gốc, không phải toàn bộ mã nguồn Java của chúng.

## Tác giả và ghi nhận

Đóng gói addon: **Lowzii**. Các giấy phép và ghi nhận từ bản gốc được giữ trong `META-INF/licenses/` bên trong file JAR.

Để báo lỗi hoặc đề xuất tính năng, mở [Issue](https://github.com/lowziim3tech/SeaTech-Mod/issues) và gửi phiên bản Minecraft, Meteor Client, mô tả cách tái hiện cùng log hoặc ảnh liên quan.

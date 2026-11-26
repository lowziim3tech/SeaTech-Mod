# SeaTech Mod

Bộ tiện ích Minecraft hỗ trợ xây farm, đặt block theo schematic và quản lý Crafter.

**Minecraft 1.21.11 · Fabric · Meteor Client**

[Tham gia Discord SeaTech](https://discord.gg/seatechh) để nhận mod, schematic miễn phí và hỗ trợ sử dụng.

## Tải xuống

| Mod | Phiên bản | Công dụng | Download |
| --- | --- | --- | --- |
| **SeaTech Easyplace** | **1.0.5** | Hỗ trợ đặt block theo schematic, căn hướng và Main Menu SeaTech. | **[Tải file .jar](https://github.com/lowziim3tech/SeaTech-Mod/raw/refs/heads/main/mods/SeaTech-Easyplace-1.21.11-1.0.5.jar)** |
| **SeaTechCrafter** | **1.0.0** | Thiết lập mẫu ô chế tạo, kiểm tra và dọn dàn Crafter. | **[Tải file .jar](https://github.com/lowziim3tech/SeaTech-Mod/raw/refs/heads/main/mods/SeaTechCrafter-1.21.11-1.0.0.jar)** |

## SeaTech Easyplace

Hỗ trợ chọn vật liệu và căn hướng block theo schematic khi xây farm.

- **Đặt theo schematic:** tìm góc đặt phù hợp với hướng block trong bản thiết kế.
- **Chọn vật liệu:** tự chọn vật liệu trên hotbar hoặc lấy từ túi đồ khi bật tùy chọn tương ứng.
- **Kiểm tra hướng:** chặn lượt đặt khi không tìm được góc phù hợp nếu bật `block-wrong-facing`.
- **Hướng thủ công:** chọn Auto, Up, Down, Front, Back, Left hoặc Right.
- **Đặt không cần sneak:** hỗ trợ đặt block lên các khối có giao diện.
- **Tùy chỉnh Easy Place:** thời gian chờ lấy vật liệu, biên góc và thông báo trong game.
- **Easyplace V2:** dùng cách đặt block từ SeaTech Farm 2.3.6. Trong **Items**, chọn **Return Hotbar Slot** (1–9) để **Auto Swap Back** quay về ô đó sau khi đặt block theo schematic. Mặc định là ô 1.

### Main Menu SeaTech

Giao diện giấy vẽ tay với thương hiệu SeaTech và đường dẫn **discord.gg/seatechh**.

Các nút Singleplayer, Multiplayer, Options và Quit Game giữ chức năng tương ứng. Nút **Discord** mở cộng đồng SeaTech khi bấm. Bố cục tự căn theo kích thước cửa sổ và GUI Scale.

### Bật chế độ Auto

Trong Meteor, mở nhóm **SeaTech Easyplace** và bật **Easy Place** hoặc **Easyplace V2**. Bật **Rotation Spoofer**, **Litematica Smart Placement**, rồi chọn **Direction: Auto**.

Nạp và căn vị trí schematic bằng Litematica trước khi đặt block. Nếu Easy Place báo không tìm được hướng phù hợp, hãy thử bấm một mặt khác của khối.

## SeaTechCrafter

Bộ công cụ hỗ trợ thiết lập và kiểm tra dàn Crafter.

| Module | Chức năng |
| --- | --- |
| **Crafter Setup** | Chọn mẫu bật/tắt cho 9 ô, sau đó mở từng Crafter để áp dụng cấu hình. |
| **Crafter Output ESP** | Đánh dấu và vẽ đường tới những Crafter chưa xuất vật phẩm kể từ khi bật module. |
| **Crafter Cleaner** | Giữ vật phẩm trong whitelist; tự lấy vào túi hoặc vứt vật phẩm ngoài danh sách khỏi Crafter đang mở. |
| **GUI Close** | Tự đóng giao diện Crafter, rương, hopper và các giao diện được chọn sau thời gian tùy chỉnh. |

## Cài đặt

1. Chuẩn bị **Minecraft 1.21.11**, **Java 21 trở lên**, **Fabric Loader** và **Meteor Client** tương thích. Easyplace 1.0.5 yêu cầu Fabric Loader **0.19.5 trở lên**.
2. Để dùng Easyplace theo schematic, cài **Litematica** và các thư viện mà Litematica yêu cầu, gồm **MaLiLib**.
3. Tải mod cần dùng ở bảng phía trên, rồi đặt file `.jar` vào thư mục `.minecraft/mods`.
4. Nếu cập nhật Easyplace, xóa file Easyplace phiên bản cũ trước khi thêm bản mới.
5. Khởi động game bằng Fabric và mở giao diện Meteor để cấu hình module.

Chỉ bật một công cụ tự động đặt block tại một thời điểm. Các mod thay Main Menu khác có thể ảnh hưởng đến giao diện SeaTech.

## Cộng đồng

**[discord.gg/seatechh](https://discord.gg/seatechh)**

Nhận mod, schematic, thông báo cập nhật và hỗ trợ từ cộng đồng SeaTech.

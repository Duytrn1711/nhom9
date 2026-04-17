# ShopVip - Giao Diện Website Cửa Hàng Hiện Đại

Chào mừng bạn đến với dự án **ShopVip**! Đây là một mẫu giao diện website bán hàng/thương mại điện tử tĩnh, được xây dựng bằng HTML, CSS (thuần), và JavaScript (thuần). Dự án có bố cục hiện đại, chuẩn Responsive và có một số tính năng tương tác người dùng cơ bản ở phía client.

## Cấu Trúc Dự Án

- `ShopVip.html`: Trang đích (Home) của website, hiển thị banner quảng cáo, các danh mục sản phẩm nổi bật và một số sản phẩm hiển thị.
- `category.html`: Trang hiển thị danh sách sản phẩm theo từng danh mục riêng biệt.
- `style.css`: File chứa toàn bộ mã nguồn CSS, được chia nhỏ thành các section rõ ràng đảm nhận cấu trúc giao diện và hiệu ứng Animation.
- `script.js`: File chứa mã nguồn JavaScript đảm nhận việc render dữ liệu tĩnh/mẫu (mock data) lên trang, xử lý giỏ hàng, và các tính năng tương tác khác.
- `favicon.ico`, `*.png`: Các file icon biểu tượng cho website trên thanh tab trình duyệt.

## Hướng Dẫn Sử Dụng Code (Dành Cho Lập Trình Viên)

Giao diện được thiết kế để dễ dàng tuỳ chỉnh hoặc tích hợp vào một dự án có Backend.

1. **Hiển thị sản phẩm (Danh sách sản phẩm mẫu):** 
   Dữ liệu sản phẩm mẫu hiện đang được khởi tạo cứng hoặc lấy từ API giả lập bên trong `script.js`. Bạn có thể thay thế nguồn dữ liệu này (ví dụ dùng `fetch`) để kết nối tới REST API của bạn và đổ vào biến mảng.
2. **Tuỳ chỉnh màu sắc & Fonts:**
   Hệ thống dùng font chữ `Inter` thông qua Google Fonts. Bạn có thể thay đổi thiết kế chung bằng cách cập nhật các biến `--primary-color`, `--text-color` hoặc các class liên quan trong `style.css`.
3. **Thêm trang/ Tính năng mới:**
   Tái sử dụng các class UI có sẵn trong CSS như `.btn`, `.container`, `.section-padding`,... để tạo ra các trang mới đồng nhất với thiết kế.

## Hướng Dẫn Chạy & Sử Dụng Website

Do đây là một dự án dựa thuần tuý trên HTML, CSS, và JS phía Client nên việc triển khai cực kỳ đơn giản.

### Cách 1: Mở trực tiếp trên trình duyệt (Cơ bản nhất)
1. Mở thư mục chứa mã nguồn (`shop-ui`).
2. Tìm tới file `index.html`.
3. Nhấn đúp chuột để mở trực tiếp trên trình duyệt web mặc định của bạn (Chrome, Edge, Safari...).

### Cách 2: Sử Dụng Live Server trên VS Code (Khuyến nghị)
Việc sử dụng Live Server giúp website có trải nghiệm mượt mà hơn (có Auto-reload khi code thay đổi).
1. Mở thư mục dự án này bằng **Visual Studio Code (VS Code)**.
2. Tải và cài đặt Extension có tên **Live Server** của tác giả Ritwick Dey.
3. Chuột phải vào file `index.html` và chọn **"Open with Live Server"**.
4. Website sẽ tự động được bật trên trình duyệt ở địa chỉ Localhost (VD: `http://127.0.0.1:5500/index.html`).

### Các Tính Năng Có Thể Trải Nghiệm Trên Web
- **Điều hướng trang:** Bấm vào Logo hoặc các phím "Trang chủ", "Danh mục" để cuộn và qua các trang.
- **Danh mục sản phẩm:** Bấm vào các block thẻ Danh Mục trên trang chủ để sang trang Danh sách mặt hàng tương ứng.
- **Giỏ Hàng:** Nhấn vào icon Giỏ hàng ở góc phải trên cùng để mở thanh Sidebar quản lý giỏ hàng.

Chúc bạn có trải nghiệm tốt với mã nguồn này! Đừng ngại tuỳ chỉnh thêm để có được ứng dụng mong muốn nhé.

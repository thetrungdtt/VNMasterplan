Phát triển web app là Prototype Hệ thống Dashboard Quản Trị Việc Thực Thi NQ57

**Yêu cầu chung:**

*   Phát triển prototype cho hệ thống web Dashboard Quản Trị Việc Thực Thi NQ57.
*   Sử dụng HTML, CSS, JavaScript cho frontend.
*   Sử dụng dữ liệu giả định (được cung cấp) để hiển thị.
*   Tập trung vào giao diện người dùng (UI) và luồng tương tác cơ bản.
*   Tuân thủ UI Design Guideline (được cung cấp).
*   Chưa cần kết nối API với backend, chưa cần xử lý logic phức tạp.

**Dữ liệu giả định:** 

**1.1. KPIs vĩ mô**

| STT | KPIs vĩ mô                                   | Mục tiêu 2030 | Mục tiêu 2045 | Giá trị hiện tại (giả định) | % Hoàn thành (giả định) | Xu hướng (giả định) |
| :-: | :------------------------------------------- | :----------- | :----------- | :------------------------ | :--------------------- | :------------------ |
| 1   | Năng suất nhân tố tổng hợp (TFP)              | >55%        | ~60%        | 50%                      | 90.9%                  | Tăng                |
| 2   | Chi tiêu R&D / GDP                           | ~2%         | >2.5%       | 1.5%                     | 75%                    | Tăng                |
| 3   | Tỷ trọng Kinh tế số trong GDP               | ≥30%        | ≥50%        | 25%                      | 83.3%                  | Tăng                |
| 4   | Tỷ lệ phủ sóng 5G                            | Toàn quốc   |  N/A        | 70%                      | 70%                    | Tăng                |
| 5   | Xuất khẩu sản phẩm Công nghệ cao             | >50%        | >70%        | 45%                      | 90%                    | Tăng                |
| 6   | Chỉ số phát triển ICT tổng thể              |  N/A        |  N/A        | 65 (điểm)                |  N/A                   | Tăng                |
| 7   | Tăng trưởng Năng suất Lao động               |  N/A        |  N/A        | 4.5%                     |  N/A                   | Ổn định             |
| 8   | Tỷ lệ DN công nghệ cao/ĐMST                 |  N/A        |  N/A        | 3.5%                     |  N/A                   | Tăng                |
| 9   | Chỉ số Đổi mới sáng tạo quốc gia (GII)        |  N/A        | ≤ 30        | 48 (thứ hạng)            |  N/A                   | Tăng                |
| 10  | Chỉ số Xanh & Bền vững                     |  N/A        |  N/A        | 70 (điểm)                |  N/A                   | Tăng                |
| 11  | Nhân lực R&D (người/10.000 dân)             | ≥12        | ≥15        | 9                        | 75%                    | Tăng                |
| 12  | Chính phủ điện tử / Dịch vụ công trực tuyến |  N/A        |  N/A        | 75 (điểm)                |  N/A                   | Tăng                |

**1.2. Chỉ tiêu CP (giả định cho 5 chỉ tiêu đầu)**

| STT | Chỉ tiêu CP                                                                                                        | Mục tiêu 2030 | Giá trị hiện tại (giả định) | % Hoàn thành (giả định) |
| :-: | :----------------------------------------------------------------------------------------------------------------- | :----------- | :------------------------ | :--------------------- |
| 1   | Tiềm lực, trình độ khoa học, công nghệ và đổi mới sáng tạo                                                          | Đạt mức tiên tiến | Mức khá                   | 70%                    |
| 2   | Trình độ, năng lực công nghệ, đổi mới sáng tạo của doanh nghiệp                                                      | Đạt mức trên trung bình của thế giới | Mức trung bình            | 60%                    |
| 3   | Lĩnh vực khoa học, công nghệ                                                                                       | Một số lĩnh vực đạt trình độ quốc tế | Một số lĩnh vực đạt mức khá | 50%                    |
| 4   | Xếp hạng năng lực cạnh tranh số                                                                                   | ≤ 3 Đông Nam Á; ≤ 50 Thế giới | 4 Đông Nam Á; 55 Thế giới   | 80%                    |
| 5   | Xếp hạng chỉ số phát triển Chính phủ điện tử, Chính phủ số                                                           | ≤ 3 Đông Nam Á; ≤ 50 Thế giới | 4 Đông Nam Á; 52 Thế giới   | 85%                    |

**(Các chỉ tiêu CP còn lại sẽ được bổ sung sau)**

**1.3. Danh mục nhiệm vụ (giả định cho 5 nhiệm vụ đầu, nhóm I)**

| STT | Nhóm NV | Tên nhiệm vụ                                                                                                                                      | Đơn vị chủ trì         | Trạng thái       | Tiến độ (giả định) | Thời hạn     |
| :-: | :------ | :------------------------------------------------------------------------------------------------------------------------------------------------ | :--------------------- | :-------------- | :----------------- | :----------- |
| 1   | I       | Xây dựng, trình Thủ tướng Chính phủ ban hành và tổ chức triển khai chương trình tuyên truyền thường xuyên, sâu rộng về nội dung Nghị quyết 57-NQ/TW | Bộ Khoa học và Công nghệ | Hoàn thành      | 100%               | 6/2025      |
| 2   | I       | Xây dựng chương trình chuyên biệt về khoa học, công nghệ, đổi mới sáng tạo và chuyển đổi số trên truyền hình, phát thanh và mạng xã hội.           | VTV, VOV, TTXVN        | Đang triển khai | 80%                | Thường xuyên |
| 3   | I       | Xây dựng chương trình, kế hoạch phát động phong trào học tập trên các nền tảng số                                                                 | Các bộ, ngành, địa phương | Đang triển khai | 70%                | Thường xuyên |
| 4   | I       | Xây dựng văn bản quy định trách nhiệm người đứng đầu các cơ quan nhà nước trực tiếp phụ trách                                                       | Bộ Khoa học và Công nghệ | Đang triển khai | 50%                | 6/2025      |
| 5   | I       | Xây dựng, ban hành Đề án đánh giá mức độ hoàn thành nhiệm vụ chuyển đổi số của cơ quan nhà nước                                                  | Bộ Nội vụ             | Chưa bắt đầu   | 0%                 | 6/2025      |

**(Các nhiệm vụ còn lại sẽ được bổ sung sau)**

**1.4. Chất lượng và Tuân thủ (giả định)**

| Nhóm Nhiệm vụ | Tỷ lệ nhiệm vụ đạt chất lượng (giả định) | Số nhiệm vụ vi phạm (giả định) |
| :------------ | :--------------------------------------- | :------------------------------ |
| I             | 90%                                     | 2                               |
| II            | 85%                                     | 3                               |
| III           | 80%                                     | 5                               |
| IV            | 95%                                     | 1                               |
| V             | 88%                                     | 2                               |
| VI            | 75%                                     | 4                               |
| VII           | 92%                                     | 0                               |

**(Chi tiết các nhiệm vụ vi phạm và lý do sẽ được bổ sung sau)**

**Lưu ý:** Bộ dữ liệu giả định này sẽ được đội ngũ phát triển sử dụng để xây dựng Prototype. Dữ liệu sẽ được lưu trữ dưới dạng file JSON hoặc CSV để dễ dàng import vào cơ sở dữ liệu của Prototype.




**UI Design Guideline:** Cung cấp file PDF chứa UI Design Guideline đã được đề cập ở phần trên.

Wireframe là bản phác thảo bố cục cơ bản của giao diện, tập trung vào cấu trúc và luồng tương tác, không chú trọng vào màu sắc, hình ảnh chi tiết. Dưới đây là Wireframe cho các Dashboard chính của hệ thống:

**1.1. Dashboard Tổng Quan**

```
+------------------------------------------------------------------------------------+
| Logo | Hệ thống Dashboard Quản Trị Việc Thực Thi NQ57                               |
+------------------------------------------------------------------------------------+
| Menu: [Dashboard Tổng Quan] [KPI Liên Kết] [Chất Lượng & Tuân Thủ] [Theo Nhóm NV] |
|       [Báo Cáo] [Tài Khoản]                                                        |
+------------------------------------------------------------------------------------+
| User: [Tên người dùng] - [Chức vụ]                                                  |
| [Đăng Xuất]                                                                       |
+------------------------------------------------------------------------------------+
|                                                                                    |
| +-------+ +-------+ +-------+ +-------+                                            |
| | KPI 1 | | KPI 2 | | KPI 3 | | KPI 4 |                                            |
| | Giá trị| | Giá trị| | Giá trị| | Giá trị|                                            |
| | +/-   | | +/-   | | +/-   | | +/-   |                                            |
| +-------+ +-------+ +-------+ +-------+                                            |
|                                                                                    |
| +-----------------------------------+  +----------------------------------------+  |
| | Biểu đồ tròn: Tỷ lệ hoàn thành   |  | Biểu đồ thanh: Tiến độ nhóm nhiệm vụ    |  |
| | (Hoàn thành, Đang, Trễ)          |  | (Nhóm 1, Nhóm 2, Nhóm 3,...)           |  |
| |                                   |  |                                        |  |
| |  [Hình tròn]                     |  |  [Các thanh]                          |  |
| |                                   |  |                                        |  |
| +-----------------------------------+  +----------------------------------------+  |
|                                                                                    |
| +--------------------------------------------------------------------------------+  |
| | Biểu đồ đường: Xu hướng tiến độ                                                 |  |
| |                                                                                |  |
| |  [Đồ thị đường]                                                                |  |
| |                                                                                |  |
| +--------------------------------------------------------------------------------+  |
|                                                                                    |
+------------------------------------------------------------------------------------+
| Copyright © 2023                                                                    |
+------------------------------------------------------------------------------------+
```

**1.2. Dashboard KPI Liên Kết**

```
+------------------------------------------------------------------------------------+
| Logo | Hệ thống Dashboard Quản Trị Việc Thực Thi NQ57                               |
+------------------------------------------------------------------------------------+
| Menu: [Dashboard Tổng Quan] [KPI Liên Kết] [Chất Lượng & Tuân Thủ] [Theo Nhóm NV] |
|       [Báo Cáo] [Tài Khoản]                                                        |
+------------------------------------------------------------------------------------+
| User: [Tên người dùng] - [Chức vụ]                                                  |
| [Đăng Xuất]                                                                       |
+------------------------------------------------------------------------------------+
|                                                                                    |
| +---------------------+ +---------------------+                                     |
| | KPI 1: [Tên KPI]    | | KPI 7: [Tên KPI]    |                                     |
| | [Giá trị] [+/-]     | | [Giá trị] [+/-]     |                                     |
| | [Mục tiêu]          | | [Mục tiêu]          |                                     |
| | [Chi tiết >]        | | [Chi tiết >]        |                                     |
| +---------------------+ +---------------------+                                     |
| | KPI 2: [Tên KPI]    | | KPI 8: [Tên KPI]    |                                     |
| | [Giá trị] [+/-]     | | [Giá trị] [+/-]     |                                     |
| | [Mục tiêu]          | | [Mục tiêu]          |                                     |
| | [Chi tiết >]        | | [Chi tiết >]        |                                     |
| +---------------------+ +---------------------+                                     |
| | ...                 | | ...                 |                                     |
| +---------------------+ +---------------------+                                     |
|                                                                                    |
| +--------------------------------------------------------------------------------+  |
| | Biểu đồ Radar: Mức độ hoàn thành các KPIs                                       |  |
| |                                                                                |  |
| | [Biểu đồ Radar]                                                                |  |
| |                                                                                |  |
| +--------------------------------------------------------------------------------+  |
|                                                                                    |
+------------------------------------------------------------------------------------+
| Copyright © 2023                                                                    |
+------------------------------------------------------------------------------------+
```

**(Chi tiết KPI - Khi click vào "Chi tiết >")**

```
+------------------------------------------------------------------------------------+
| KPI: [Tên KPI]                                                                     |
+------------------------------------------------------------------------------------+
| Mô tả: [Mô tả KPI]                                                                 |
| Cách tính: [Công thức tính]                                                        |
| Đơn vị: [Đơn vị tính]                                                              |
+------------------------------------------------------------------------------------+
| Giá trị hiện tại: [Giá trị]                                                        |
| Mục tiêu: [Mục tiêu]                                                               |
| % Hoàn thành: [Phần trăm]                                                          |
+------------------------------------------------------------------------------------+
| +--------------------------------------------------------------------------------+  |
| | Biểu đồ đường: Xu hướng KPI                                                     |  |
| |                                                                                |  |
| | [Biểu đồ đường]                                                                |  |
| |                                                                                |  |
| +--------------------------------------------------------------------------------+  |
+------------------------------------------------------------------------------------+
| Chỉ tiêu CP liên quan:                                                             |
| +--------------------------------------------------------------------------------+  |
| | STT | Chỉ tiêu CP                                    | Giá trị | Mục tiêu | % HT |  |
| | --- | ---------------------------------------------- | ------- | -------- | ---- |  |
| | 1   | [Tên chỉ tiêu]                                | [Giá trị] | [Mục tiêu] | [Phần trăm] |  |
| | 2   | [Tên chỉ tiêu]                                | [Giá trị] | [Mục tiêu] | [Phần trăm] |  |
| | ... | ...                                            | ...     | ...      | ... |  |
| +--------------------------------------------------------------------------------+  |
+------------------------------------------------------------------------------------+
```

**1.3. Dashboard Chất lượng & Tuân thủ**

```
+------------------------------------------------------------------------------------+
| Logo | Hệ thống Dashboard Quản Trị Việc Thực Thi NQ57                               |
+------------------------------------------------------------------------------------+
| Menu: [Dashboard Tổng Quan] [KPI Liên Kết] [Chất Lượng & Tuân Thủ] [Theo Nhóm NV] |
|       [Báo Cáo] [Tài Khoản]                                                        |
+------------------------------------------------------------------------------------+
| User: [Tên người dùng] - [Chức vụ]                                                  |
| [Đăng Xuất]                                                                       |
+------------------------------------------------------------------------------------+
|                                                                                    |
| +-----------------------------+ +---------------------------------+              |
| | Tỷ lệ nhiệm vụ đạt chất lượng | | Số nhiệm vụ vi phạm/không tuân thủ |              |
| | [Giá trị]                   | | [Giá trị]                         |              |
| +-----------------------------+ +---------------------------------+              |
|                                                                                    |
| +--------------------------------------------------------------------------------+  |
| | Biểu đồ thanh ngang: Tỷ lệ đạt chất lượng theo nhóm NV                          |  |
| |                                                                                |  |
| | [Các thanh ngang] (Nhóm 1, Nhóm 2,...)                                         |  |
| |                                                                                |  |
| +--------------------------------------------------------------------------------+  |
|                                                                                    |
| +--------------------------------------------------------------------------------+  |
| | Danh sách nhiệm vụ vi phạm:                                                     |  |
| | +-----+----------+--------------+-----------------+                            |  |
| | | STT | Tên NV   | Lý do        | Biện pháp       |                            |  |
| | | --- | -------- | ------------ | --------------- |                            |  |
| | | 1   | [Tên NV] | [Lý do]      | [Biện pháp]     |                            |  |
| | | 2   | [Tên NV] | [Lý do]      | [Biện pháp]     |                            |  |
| | | ... | ...      | ...          | ...             |                            |  |
| | +-----+----------+--------------+-----------------+                            |  |
| +--------------------------------------------------------------------------------+  |
|                                                                                    |
+------------------------------------------------------------------------------------+
| Copyright © 2023                                                                    |
+------------------------------------------------------------------------------------+
```

**1.4. Dashboard Theo Nhóm Nhiệm vụ**

```
+------------------------------------------------------------------------------------+
| Logo | Hệ thống Dashboard Quản Trị Việc Thực Thi NQ57                               |
+------------------------------------------------------------------------------------+
| Menu: [Dashboard Tổng Quan] [KPI Liên Kết] [Chất Lượng & Tuân Thủ] [Theo Nhóm NV] |
|       [Báo Cáo] [Tài Khoản]                                                        |
+------------------------------------------------------------------------------------+
| User: [Tên người dùng] - [Chức vụ]                                                  |
| [Đăng Xuất]                                                                       |
+------------------------------------------------------------------------------------+
|                                                                                    |
| Nhóm nhiệm vụ: [Chọn nhóm nhiệm vụ] (Dropdown)                                     |
|                                                                                    |
| +--------------------------------------------------------------------------------+  |
| | Biểu đồ Gantt: Tiến độ các nhiệm vụ                                             |  |
| |                                                                                |  |
| | [Biểu đồ Gantt]                                                                |  |
| |                                                                                |  |
| +--------------------------------------------------------------------------------+  |
|                                                                                    |
| +--------------------------------------------------------------------------------+  |
| | Danh sách nhiệm vụ:                                                             |  |
| | +-----+----------+--------------+----------+-----------+----------+          |  |
| | | STT | Tên NV   | Đơn vị C.Trì | Trạng thái | Tiến độ  | KPIs LQ  |          |  |
| | | --- | -------- | ------------ | -------- | --------- | -------- |          |  |
| | | 1   | [Tên NV] | [Đơn vị]     | [TT]     | [Tiến độ] | [KPIs]   |          |  |
| | | 2   | [Tên NV] | [Đơn vị]     | [TT]     | [Tiến độ] | [KPIs]   |          |  |
| | | ... | ...      | ...          | ...      | ...       | ...      |          |  |
| | +-----+----------+--------------+----------+-----------+----------+          |  |
| +--------------------------------------------------------------------------------+  |
|                                                                                    |
+------------------------------------------------------------------------------------+
| Copyright © 2023                                                                    |
+------------------------------------------------------------------------------------+
```

**(Chi tiết nhiệm vụ - Khi click vào một nhiệm vụ trong danh sách)**

```
+------------------------------------------------------------------------------------+
| Nhiệm vụ: [Tên nhiệm vụ]                                                           |
+------------------------------------------------------------------------------------+
| Nhóm nhiệm vụ: [Nhóm nhiệm vụ]                                                     |
| Đơn vị chủ trì: [Đơn vị chủ trì]                                                   |
| Đơn vị phối hợp: [Đơn vị phối hợp]                                                 |
| Trạng thái: [Trạng thái]                                                           |
| Tiến độ: [Tiến độ]                                                                 |
| Thời hạn: [Thời hạn]                                                               |
| KPIs vĩ mô liên quan: [Danh sách KPIs vĩ mô]                                       |
+------------------------------------------------------------------------------------+
```

**1.5. eForm Nhập liệu (Ví dụ: Báo cáo tiến độ nhiệm vụ)**

```
+------------------------------------------------------------------------------------+
| Form: Báo cáo tiến độ nhiệm vụ                                                     |
+------------------------------------------------------------------------------------+
| Ngày báo cáo: [Ngày tháng năm]                                                     |
| Đơn vị báo cáo: [Tên đơn vị]                                                       |
| Người lập báo cáo: [Họ và tên]                                                     |
+------------------------------------------------------------------------------------+
| Danh sách nhiệm vụ:                                                                 |
| +-----+----------+--------------+-------------+-----------------+-----------------+
| | STT | Tên NV   | Tiến độ      | Kết quả      | Khó khăn        | Đề xuất         |
| | --- | -------- | ------------ | ------------- | --------------- | --------------- |
| | 1   | [Tên NV] | [%]          | [Mô tả]       | [Mô tả]         | [Mô tả]         |
| | 2   | [Tên NV] | [%]          | [Mô tả]       | [Mô tả]         | [Mô tả]         |
| | ... | ...      | ...          | ...           | ...             | ...             |
| +-----+----------+--------------+-------------+-----------------+-----------------+
+------------------------------------------------------------------------------------+
| [Lưu] [Hủy]                                                                       |
+------------------------------------------------------------------------------------+
```

## 2. Mockup

Mockup là bản thiết kế chi tiết hơn Wireframe, thể hiện giao diện trực quan với màu sắc, hình ảnh, font chữ. Dưới đây là mô tả Mockup cho một số màn hình chính (đội ngũ thiết kế sẽ cung cấp file Mockup dưới dạng ảnh hoặc file thiết kế):

**2.1. Dashboard Tổng Quan**

*   **Màu sắc:** Sử dụng màu xanh dương làm chủ đạo (màu của Chính phủ), kết hợp với các màu sắc khác để tạo điểm nhấn.
*   **Font chữ:** Sử dụng font chữ Roboto, Arial hoặc các font sans-serif dễ đọc.
*   **Hình ảnh:**
    *   Logo của Chính phủ, logo NQ57.
    *   Biểu tượng (icon) cho các KPIs.
*   **Biểu đồ:**
    *   Biểu đồ tròn: Sử dụng màu sắc khác nhau để phân biệt các phần (hoàn thành, đang triển khai, trễ hạn).
    *   Biểu đồ thanh: Sử dụng màu sắc để phân biệt các nhóm nhiệm vụ.
    *   Biểu đồ đường: Sử dụng đường nét rõ ràng, màu sắc dễ nhìn.
*   **Thẻ KPIs:** Thiết kế dạng thẻ (card) nổi bật, hiển thị rõ ràng giá trị, đơn vị, xu hướng (mũi tên lên/xuống).

**2.2. Dashboard KPI Liên Kết**

*   **Màu sắc:** Nhất quán với Dashboard Tổng Quan.
*   **Bố cục:** Danh sách KPIs vĩ mô hiển thị dạng lưới 2 cột, mỗi KPI có nút "Chi tiết" để xem thông tin chi tiết.
*   **Biểu đồ Radar:** Sử dụng màu sắc khác nhau cho các KPIs, có chú thích rõ ràng.
*   **Chi tiết KPI:** Thiết kế trang chi tiết KPI với đầy đủ thông tin (mô tả, cách tính, biểu đồ, bảng chỉ tiêu CP liên quan).

**2.3. Dashboard Chất lượng & Tuân thủ**

*   **Màu sắc:** Nhất quán với Dashboard Tổng Quan.
*   **Biểu đồ thanh ngang:** Sử dụng màu sắc để phân biệt các nhóm nhiệm vụ, có chú thích rõ ràng.
*   **Bảng danh sách nhiệm vụ vi phạm:** Thiết kế bảng rõ ràng, dễ đọc, có thể sắp xếp theo các cột.

**2.4. Dashboard Theo Nhóm Nhiệm vụ**

*   **Màu sắc:** Nhất quán với Dashboard Tổng Quan.
*   **Dropdown:** Thiết kế dropdown chọn nhóm nhiệm vụ rõ ràng, dễ sử dụng.
*   **Biểu đồ Gantt:** Sử dụng màu sắc để phân biệt các nhiệm vụ, trạng thái, đường găng. Cho phép người dùng zoom in/out, di chuyển để xem chi tiết.
*   **Bảng danh sách nhiệm vụ:** Thiết kế bảng rõ ràng, dễ đọc, có thể sắp xếp theo các cột.

## 3. UI Design Guideline

UI Design Guideline là tài liệu hướng dẫn chi tiết về các thành phần giao diện, giúp đảm bảo tính nhất quán trong thiết kế.

**3.1. Màu sắc**

| Màu          | Mã Hex     | Sử dụng                                   |
| :------------ | :--------- | :---------------------------------------- |
| Xanh dương chính | #007bff   | Nút bấm chính, tiêu đề, liên kết          |
| Xanh lá cây   | #28a745   | Trạng thái "Hoàn thành", "Đạt"            |
| Vàng          | #ffc107   | Trạng thái "Đang triển khai", "Cảnh báo" |
| Đỏ           | #dc3545   | Trạng thái "Trễ hạn", "Vi phạm", "Lỗi"     |
| Xám nhạt      | #f8f9fa   | Nền                                       |
| Xám đậm       | #343a40   | Chữ, viền                                |
| Trắng         | #ffffff   | Nền, chữ                                  |

**3.2. Font chữ**

*   **Font chính:** Roboto (hoặc Arial, các font sans-serif tương đương)
    *   Sử dụng cho tiêu đề, nội dung chính, các nút bấm.
*   **Font phụ:** Có thể sử dụng font serif (Times New Roman,...) cho các phần mô tả chi tiết (nếu cần).
*   **Kích thước chữ:**
    *   Tiêu đề chính: 24px - 30px
    *   Tiêu đề phụ: 18px - 22px
    *   Nội dung: 14px - 16px
    *   Chữ nhỏ: 12px

**3.3. Biểu tượng (Icon)**

*   Sử dụng bộ icon Font Awesome hoặc các bộ icon tương đương.
*   Đảm bảo icon rõ ràng, dễ hiểu, nhất quán về phong cách.

**3.4. Nút bấm (Button)**

*   **Nút chính:** Màu xanh dương (#007bff), bo tròn góc nhẹ.
*   **Nút phụ:** Màu xám (#6c757d), bo tròn góc nhẹ.
*   **Trạng thái:**
    *   Mặc định: Màu nền, chữ trắng.
    *   Hover: Đổi màu nền đậm hơn.
    *   Active: Đổi màu nền đậm hơn, có bóng đổ.
    *   Disabled: Màu xám nhạt, chữ xám đậm.

**3.5. Biểu đồ (Chart)**

*   Sử dụng thư viện Chart.js, D3.js hoặc các thư viện tương đương.
*   Đảm bảo biểu đồ rõ ràng, dễ đọc, có chú thích đầy đủ.
*   Sử dụng màu sắc nhất quán với bảng màu chung.

**3.6. Bảng (Table)**

*   Sử dụng bảng có viền mảnh, màu xám nhạt.
*   Căn chỉnh nội dung hợp lý (căn trái cho chữ, căn phải cho số).
*   Sử dụng màu nền xen kẽ giữa các dòng để dễ theo dõi.

**3.7. Khoảng cách (Spacing)**

*   Sử dụng khoảng cách hợp lý giữa các thành phần để tạo bố cục rõ ràng, dễ nhìn.
*   Khoảng cách giữa các phần chính: 20px - 30px.
*   Khoảng cách giữa các thành phần trong cùng một phần: 10px - 15px.

**3.8. Lưới (Grid)**

*   Sử dụng hệ thống lưới (grid system) để thiết kế bố cục, đảm bảo tính nhất quán và responsive.
*   Khuyến khích sử dụng Bootstrap grid hoặc các framework CSS tương đương.

**3.9. Responsive**

*   Thiết kế giao diện responsive, hiển thị tốt trên các thiết bị khác nhau (desktop, tablet, mobile).
*   Sử dụng media queries để điều chỉnh bố cục, kích thước chữ, hình ảnh cho phù hợp với từng loại thiết bị.

**3.10. Accessibility**

*   Tuân thủ các nguyên tắc về accessibility (WCAG) để đảm bảo người khuyết tật có thể sử dụng được hệ thống.
*   Sử dụng màu sắc có độ tương phản cao.
*   Cung cấp các thuộc tính ARIA cho các thành phần giao diện.

**Mô tả chi tiết các màn hình (Screens) và luồng di chuyển (Screen Flow):**

**1. Màn hình Đăng nhập (Login Screen)**

*   **URL:** `/login`
*   **Mô tả:** Màn hình cho phép người dùng đăng nhập vào hệ thống.
*   **Chi tiết:**
    *   **Tiêu đề:** "Đăng nhập"
    *   **Logo:** Logo Chính phủ (hoặc logo NQ57 nếu có).
    *   **Trường nhập liệu:**
        *   "Tên đăng nhập" (username)
        *   "Mật khẩu" (password)
    *   **Nút bấm:** "Đăng nhập" (button)
    *   **Thông báo lỗi:** Hiển thị thông báo lỗi nếu thông tin đăng nhập không chính xác (ví dụ: "Tên đăng nhập hoặc mật khẩu không đúng").
*   **Thiết kế:**
    *   Sử dụng màu sắc: Xanh dương chủ đạo (#007bff), trắng, xám.
    *   Font chữ: Roboto, Arial.
    *   Bố cục: Đơn giản, tập trung vào form đăng nhập.
*   **Luồng di chuyển:**
    *   Sau khi đăng nhập thành công, chuyển hướng đến Dashboard Tổng Quan tương ứng với nhóm người dùng.

**2. Màn hình Dashboard Tổng Quan (Dashboard Overview Screen)**

*   **URL:** `/dashboard`
*   **Mô tả:** Màn hình hiển thị tổng quan tình hình thực hiện NQ57.
*   **Chi tiết:**
    *   **Thanh Menu:**
        *   Logo, tên hệ thống.
        *   Menu: \[Dashboard Tổng Quan] \[KPI Liên Kết] \[Chất Lượng & Tuân Thủ] \[Theo Nhóm NV] \[Báo Cáo] \[Tài Khoản] (active vào Dashboard Tổng Quan)
        *   Thông tin người dùng: Tên, chức vụ.
        *   Nút "Đăng xuất".
    *   **Thẻ KPIs (KPI Cards):**
        *   Hiển thị 4 KPIs chính:
            *   **KPI 1:** "Tỷ lệ hoàn thành nhiệm vụ" - Giá trị: Lấy từ dữ liệu giả định (ví dụ: 85%). Hiển thị giá trị, đơn vị (%), mũi tên chỉ xu hướng (lên/xuống).
            *   **KPI 2:** "Tiến độ theo thời gian" - Giá trị: Dựa trên dữ liệu giả định, hiển thị dưới dạng tóm tắt (ví dụ: "Đúng tiến độ").
            *   **KPI 3:** "Tỷ lệ nhiệm vụ trễ hạn" - Giá trị: Lấy từ dữ liệu giả định (ví dụ: 5%). Hiển thị giá trị, đơn vị (%), mũi tên chỉ xu hướng (lên/xuống).
            *   **KPI 4:** "Chỉ số tổng thể NQ57" - Giá trị: Lấy từ dữ liệu giả định (ví dụ: 75 điểm).
        *   Thiết kế dạng thẻ (card), màu nền trắng, viền xám nhạt, chữ đậm, màu sắc thể hiện trạng thái (xanh lá: tốt, vàng: cảnh báo, đỏ: xấu).
    *   **Biểu đồ tròn:**
        *   Tiêu đề: "Tỷ lệ hoàn thành nhiệm vụ".
        *   Hiển thị tỷ lệ: Hoàn thành, Đang triển khai, Trễ hạn (dựa trên dữ liệu giả định).
        *   Sử dụng màu sắc: Xanh lá (hoàn thành), vàng (đang triển khai), đỏ (trễ hạn).
    *   **Biểu đồ thanh:**
        *   Tiêu đề: "Tiến độ theo nhóm nhiệm vụ".
        *   Hiển thị tiến độ của các nhóm nhiệm vụ (I, II, III, IV, V, VI, VII) (dựa trên dữ liệu giả định).
        *   Sử dụng màu sắc để phân biệt các nhóm.
    *   **Biểu đồ đường:**
        *   Tiêu đề: "Xu hướng tiến độ theo thời gian".
        *   Hiển thị xu hướng tiến độ chung theo quý (dựa trên dữ liệu giả định).
        *   Sử dụng đường nét liền, màu xanh dương.
*   **Thiết kế:**
    *   Màu sắc: Theo UI Design Guideline.
    *   Font chữ: Roboto, Arial.
    *   Bố cục: Rõ ràng, dễ nhìn, các thành phần được sắp xếp hợp lý.
*   **Luồng di chuyển:**
    *   Click vào menu "KPI Liên Kết": Chuyển đến Dashboard KPI Liên Kết.
    *   Click vào menu "Chất Lượng & Tuân Thủ": Chuyển đến Dashboard Chất lượng & Tuân thủ.
    *   Click vào menu "Theo Nhóm NV": Chuyển đến Dashboard Theo Nhóm Nhiệm vụ.
    *   Click vào nút "Đăng xuất": Chuyển đến màn hình Đăng nhập.

**3. Màn hình Dashboard KPI Liên Kết (Dashboard KPI Alignment Screen)**

*   **URL:** `/kpi`
*   **Mô tả:** Màn hình hiển thị chi tiết 12 KPIs vĩ mô và các Chỉ tiêu CP liên quan.
*   **Chi tiết:**
    *   **Thanh Menu:** (Giống Dashboard Tổng Quan, active vào KPI Liên Kết)
    *   **Danh sách KPIs vĩ mô:**
        *   Hiển thị danh sách 12 KPIs vĩ mô (dạng lưới 2 cột).
        *   Mỗi KPI hiển thị: Tên KPI, giá trị hiện tại (lấy từ dữ liệu giả định), mũi tên chỉ xu hướng (lên/xuống), mục tiêu.
        *   Có nút "Chi tiết >" để xem thông tin chi tiết của từng KPI.
    *   **Biểu đồ Radar:**
        *   Tiêu đề: "Mức độ hoàn thành các KPIs".
        *   Hiển thị mức độ hoàn thành của 12 KPIs vĩ mô trên biểu đồ radar (dựa trên dữ liệu giả định).
        *   Sử dụng màu sắc khác nhau cho các KPI, có chú thích.
    *   **Chi tiết KPI (khi click vào nút "Chi tiết >"):**
        *   Hiển thị pop-up hoặc chuyển sang trang chi tiết.
        *   Hiển thị:
            *   Tên KPI, mô tả, cách tính, đơn vị.
            *   Giá trị hiện tại, mục tiêu, % hoàn thành (lấy từ dữ liệu giả định).
            *   Biểu đồ đường: Xu hướng thay đổi của KPI theo thời gian (dữ liệu giả định).
            *   Bảng "Chỉ tiêu CP liên quan":
                *   Cột: STT, Tên Chỉ tiêu CP, Giá trị hiện tại, Mục tiêu, % Hoàn thành.
                *   Dữ liệu: Lấy từ dữ liệu giả định.
            *   Công thức tính toán KPI vĩ mô từ các Chỉ tiêu CP (nếu có).
*   **Thiết kế:**
    *   Màu sắc: Theo UI Design Guideline.
    *   Font chữ: Roboto, Arial.
    *   Bố cục: Rõ ràng, dễ nhìn.
*   **Luồng di chuyển:**
    *   Click vào menu "Dashboard Tổng Quan": Chuyển đến Dashboard Tổng Quan.
    *   Click vào menu "Chất Lượng & Tuân Thủ": Chuyển đến Dashboard Chất lượng & Tuân thủ.
    *   Click vào menu "Theo Nhóm NV": Chuyển đến Dashboard Theo Nhóm Nhiệm vụ.
    *   Click vào nút "Chi tiết >" của từng KPI: Xem thông tin chi tiết KPI.
    *   Click vào nút "Đăng xuất": Chuyển đến màn hình Đăng nhập.

**4. Màn hình Dashboard Chất lượng & Tuân thủ (Dashboard Quality & Compliance Screen)**

*   **URL:** `/quality`
*   **Mô tả:** Màn hình hiển thị thông tin về chất lượng thực hiện nhiệm vụ và mức độ tuân thủ.
*   **Chi tiết:**
    *   **Thanh Menu:** (Giống Dashboard Tổng Quan, active vào Chất lượng & Tuân thủ)
    *   **Thẻ KPIs:**
        *   "Tỷ lệ nhiệm vụ đạt chất lượng" - Giá trị: Lấy từ dữ liệu giả định (ví dụ: 88%).
        *   "Số nhiệm vụ vi phạm/không tuân thủ" - Giá trị: Lấy từ dữ liệu giả định (ví dụ: 17).
    *   **Biểu đồ thanh ngang:**
        *   Tiêu đề: "Tỷ lệ nhiệm vụ đạt chất lượng theo nhóm nhiệm vụ".
        *   Hiển thị tỷ lệ đạt chất lượng của các nhóm nhiệm vụ (I, II, III,...).
        *   Sử dụng màu sắc để phân biệt các nhóm.
    *   **Bảng "Danh sách nhiệm vụ vi phạm":**
        *   Cột: STT, Tên nhiệm vụ, Lý do vi phạm, Biện pháp xử lý.
        *   Dữ liệu: Lấy từ dữ liệu giả định.
*   **Thiết kế:**
    *   Màu sắc: Theo UI Design Guideline.
    *   Font chữ: Roboto, Arial.
    *   Bố cục: Rõ ràng, dễ nhìn.
*   **Luồng di chuyển:**
    *   Click vào menu "Dashboard Tổng Quan": Chuyển đến Dashboard Tổng Quan.
    *   Click vào menu "KPI Liên Kết": Chuyển đến Dashboard KPI Liên Kết.
    *   Click vào menu "Theo Nhóm NV": Chuyển đến Dashboard Theo Nhóm Nhiệm vụ.
    *   Click vào nút "Đăng xuất": Chuyển đến màn hình Đăng nhập.

**5. Màn hình Dashboard Theo Nhóm Nhiệm vụ (Dashboard Task Group Screen)**

*   **URL:** `/tasks`
*   **Mô tả:** Màn hình hiển thị chi tiết tiến độ thực hiện các nhiệm vụ theo nhóm.
*   **Chi tiết:**
    *   **Thanh Menu:** (Giống Dashboard Tổng Quan, active vào Theo Nhóm NV)
    *   **Dropdown chọn nhóm nhiệm vụ:** Cho phép chọn xem chi tiết từng nhóm nhiệm vụ (I, II, III, IV, V, VI, VII).
    *   **Biểu đồ Gantt:**
        *   Tiêu đề: "Tiến độ các nhiệm vụ".
        *   Hiển thị tiến độ của các nhiệm vụ trong nhóm được chọn (dựa trên dữ liệu giả định).
        *   Sử dụng màu sắc để phân biệt các nhiệm vụ, trạng thái (hoàn thành, đang triển khai, trễ hạn), đường găng (nếu có).
        *   Cho phép zoom in/out, di chuyển để xem chi tiết.
    *   **Bảng "Danh sách nhiệm vụ":**
        *   Cột: STT, Tên nhiệm vụ, Đơn vị chủ trì, Trạng thái, Tiến độ (% hoàn thành), KPIs vĩ mô liên quan.
        *   Dữ liệu: Lấy từ dữ liệu giả định.
        *   Click vào từng nhiệm vụ để xem thông tin chi tiết (pop-up hoặc trang riêng).
    *   **Chi tiết nhiệm vụ (khi click vào một nhiệm vụ):**
        *   Hiển thị pop-up hoặc chuyển sang trang chi tiết.
        *   Hiển thị: Tên nhiệm vụ, Nhóm nhiệm vụ, Đơn vị chủ trì, Đơn vị phối hợp, Trạng thái, Tiến độ, Thời hạn, KPIs vĩ mô liên quan (dữ liệu giả định).
*   **Thiết kế:**
    *   Màu sắc: Theo UI Design Guideline.
    *   Font chữ: Roboto, Arial.
    *   Bố cục: Rõ ràng, dễ nhìn.
*   **Luồng di chuyển:**
    *   Click vào menu "Dashboard Tổng Quan": Chuyển đến Dashboard Tổng Quan.
    *   Click vào menu "KPI Liên Kết": Chuyển đến Dashboard KPI Liên Kết.
    *   Click vào menu "Chất Lượng & Tuân Thủ": Chuyển đến Dashboard Chất lượng & Tuân thủ.
    *   Click vào từng nhiệm vụ trong bảng: Xem thông tin chi tiết nhiệm vụ.
    *   Click vào nút "Đăng xuất": Chuyển đến màn hình Đăng nhập.

**6. Màn hình eForm Nhập liệu (eForm Input Screen)**

*   **URL:** `/eform` (có thể là một phần của Dashboard Theo Nhóm Nhiệm vụ)
*   **Mô tả:** Màn hình cho phép người dùng nhập liệu thông tin (ví dụ: báo cáo tiến độ nhiệm vụ).
*   **Chi tiết:**
    *   **Tiêu đề:** "Báo cáo tiến độ nhiệm vụ" (hoặc tiêu đề tương ứng với loại eForm).
    *   **Thông tin chung:** Ngày báo cáo, đơn vị báo cáo, người lập báo cáo.
    *   **Bảng "Danh sách nhiệm vụ":**
        *   Cột: STT, Tên nhiệm vụ, Tiến độ (% hoàn thành), Kết quả đạt được, Khó khăn, vướng mắc, Đề xuất, kiến nghị.
        *   Cho phép nhập liệu vào các ô tương ứng.
        *   Có nút "Lưu" và "Hủy".
*   **Thiết kế:**
    *   Màu sắc: Theo UI Design Guideline.
    *   Font chữ: Roboto, Arial.
    *   Bố cục: Rõ ràng, dễ nhìn, dễ nhập liệu.
*   **Luồng di chuyển:**
     *   Có thể thiết kế thành 1 trang (url) riêng, hoặc 1 popup (modal) khi người dùng click vào 1 button trên dashboard.





[![Tải tại đây](https://img.shields.io/badge/⬇_Tải-Tại_Đây-success?style=for-the-badge)](https://chromewebstore.google.com/detail/muse-automation-auto-muse/jjcigbgkfmobiegbfipoaolediphpljp)

# 🚀 Muse Automation v1.0.0 - Tự động hóa Muse.ai AI [![English](https://img.shields.io/badge/English-blue)](README.md) [![中文](https://img.shields.io/badge/中文-red)](README_zh.md)

**Muse Automation** là công cụ năng suất tự động hóa quy trình sáng tạo của bạn trên Muse.ai. Dừng việc nhập từng prompt thủ công—tự động hóa quy trình và tạo video, ảnh ở quy mô lớn.

-----

## ✨ Các tính năng chính

* **🚀 Xử lý hàng loạt:** Xếp hàng hàng chục hoặc hàng trăm prompt và để tiện ích tự động gửi và tạo nội dung.
* **🧩 Workflow (giao diện kéo thả trực quan):** Nối prompt, ảnh và các bước tạo trên một bảng vẽ — ví dụ tạo ảnh rồi tự động dùng chính ảnh đó để tạo video. Lưu nhiều workflow, chạy từng node hoặc chạy tất cả, nhập/xuất workflow thành file.
* **🎬 Tự động Văn bản thành Video:** Tạo video từ mô tả văn bản. Hỗ trợ xử lý hàng loạt với thời gian chờ tùy chỉnh.
* **🎬 Khung hình thành Video:** Dùng ảnh khung hình bắt đầu và prompt để tạo video động.
* **🎬 Thành phần thành Video:** Kết hợp ảnh đã tải lên (nhân vật, đồ vật, giao diện) với prompt để tạo video.
* **🖼️ Tạo hàng loạt Văn bản thành Hình ảnh:** Tạo tối đa 4 ảnh mỗi prompt với tỷ lệ khung hình 16:9, 9:16, 1:1, 3:4, 4:3.
* **🖼️ Hình ảnh thành Hình ảnh:** Tạo biến thể ảnh từ ảnh nguồn và prompt.
* **⚙️ Điều khiển chuyên nghiệp:**
    * **Chạy theo khoảng:** Chỉ chạy một phần danh sách (ví dụ: prompt 5 đến 20).
    * **Chờ thông minh (Smart Delays):** Thiết lập thời gian chờ ngẫu nhiên (từ–đến giây) giữa các prompt để quản lý giới hạn tốc độ.
    * **Tự động thử lại:** Tự thử lại khi tạo lỗi (1–20 lần).
    * **Tự động tải xuống:** Tự động tải kết quả khi tạo xong.
* **🔗 Nối tiếp / Chỉnh sửa liên tục:** Nối tiếp video từ prompt trước, hoặc chỉnh sửa ảnh do prompt trước tạo ra.
* **👤 Tự động thêm ảnh nhân vật:** Ảnh được tự động gán vào prompt dựa theo tên tệp.
* **📄 Nhập Prompt:** Tải prompt từ tệp `.txt`, `.xlsx` hoặc `.csv`.
* **📊 Giám sát hàng đợi thời gian thực:** Theo dõi tiến trình với hàng đợi prompt và trạng thái từng prompt trong Side Panel.
* **📂 Quản lý tệp:** Tải xuống được sắp xếp vào thư mục theo dự án.
* **🌐 Đa ngôn ngữ:** Tiếng Anh, Tiếng Việt, Tiếng Trung, Tiếng Hàn, Tiếng Nhật, Tiếng Tây Ban Nha.

-----

## 📥 Cài đặt

### Cách 1: Cửa hàng Chrome trực tuyến (Khuyên dùng)
1. Truy cập [Cửa hàng Chrome trực tuyến](https://chromewebstore.google.com/detail/muse-automation-auto-muse/jjcigbgkfmobiegbfipoaolediphpljp) và nhấn **Thêm vào Chrome**.

---

## 📖 Hướng dẫn sử dụng

### Bắt đầu

1. **Truy cập Muse.ai**
   - Mở [muse.ai](https://muse.ai)
   - Tiện ích hoạt động trên các trang Muse.ai. Ở trang khác, Side Panel sẽ hiện nút **Đi đến Muse AI**.

2. **Mở tiện ích**
   - Nhấn biểu tượng tiện ích trên thanh công cụ Chrome. Ghim để truy cập nhanh!

3. **Cấu hình hàng loạt**
   - Trong tab **Điều khiển**, thiết lập:
     - **Prompt đồng thời:** Số prompt chạy cùng lúc.
     - **Độ trễ ngẫu nhiên:** Thời gian chờ ngẫu nhiên (từ–đến, 0–300 giây) trước khi xử lý prompt tiếp theo.

4. **Chọn chế độ**
   - Chọn: **Văn bản thành Video**, **Khung hình thành Video**, **Thành phần thành Video**, **Văn bản thành Hình ảnh**, hoặc **Hình ảnh thành Hình ảnh**.

5. **Hoặc mở Workflow**
   - Nhấn **Workflow** ở cuối tab Điều khiển để dựng quy trình nhiều bước bằng kéo thả (xem [6. Workflow](#6-workflow-giao-diện-kéo-thả-trực-quan)).

### 1. Chế độ Văn bản thành Video

1. Chọn chế độ **Văn bản thành Video**.
2. Nhập prompt vào ô (tách mỗi prompt bằng **dòng trống**).
3. Hoặc nhấn biểu tượng **Tải lên** để nhập danh sách prompt từ tệp `.txt`, `.xlsx` hoặc `.csv`. Với bảng tính, chọn trang tính và cột cần nhập.
4. (Tùy chọn) Trong **Chế độ video theo prompt**, chọn **10 giây nối tiếp** để video của prompt đó được nối tiếp với prompt kế tiếp.
5. Đặt **Lưu vào thư mục** và chọn khoảng prompt (**Bắt đầu** đến **Kết thúc**).
6. Nhấn **Chạy** để bắt đầu.

**Ví dụ Prompt:**
```
Một thành phố cyberpunk tương lai với ánh đèn neon phản chiếu trong mưa.
Camera lướt qua các con hẻm hẹp.

Một khu vườn Nhật Bản yên bình với hoa anh đào rơi xuống ao.
Camera zoom chậm vào những con cá koi đang bơi bên dưới.
```

### 2. Chế độ Khung hình thành Video

1. Chọn chế độ **Khung hình thành Video**.
2. Nhấn tải lên hoặc kéo & thả ảnh khung hình bắt đầu (PNG, JPG, GIF, tối đa 10MB mỗi ảnh).
3. Nhập prompt (tách bằng dòng trống). Ảnh được gán cho prompt theo thứ tự—tải lên mỗi prompt một ảnh.
4. Nhấn **Chạy**.

### 3. Chế độ Thành phần thành Video

1. Chọn chế độ **Thành phần thành Video**.
2. Tải lên ảnh thành phần (nhân vật, đồ vật, bối cảnh).
3. Nhập prompt (tách bằng dòng trống).
4. (Tùy chọn) Bật **Tự động thêm ảnh nhân vật** để mỗi prompt dùng ảnh có tên tệp xuất hiện trong prompt. Ví dụ: `Anna.png` sẽ được thêm vào mọi prompt có chữ "Anna".
5. Nhấn **Chạy**.

### 4. Chế độ Văn bản thành Hình ảnh

1. Chọn chế độ **Văn bản thành Hình ảnh**.
2. Nhập mô tả chi tiết cho ảnh.
3. Chọn **Đầu ra mỗi Prompt** (1–4) và cấu hình **Tỷ lệ khung hình** trong tab Cài đặt.
4. (Tùy chọn) Trong **Chế độ ảnh theo prompt**, chọn **Chỉnh sửa ảnh** để prompt kế tiếp chỉnh sửa ảnh do prompt này tạo ra.
5. Nhấn **Chạy**.

### 5. Chế độ Hình ảnh thành Hình ảnh

1. Chọn chế độ **Hình ảnh thành Hình ảnh**.
2. Tải lên ảnh nguồn.
3. Nhập prompt cho các biến thể ảnh. Bạn cũng có thể bật **Tự động thêm ảnh nhân vật**.
4. Nhấn **Chạy**.

### 6. Workflow (Giao diện kéo thả trực quan)

Workflow là giao diện kéo thả trực quan cho các quy trình nhiều bước — ví dụ: tạo vài ảnh, dùng chính các ảnh đó để tạo video, rồi nối tiếp mỗi video bằng một prompt khác. Workflow mở trong cửa sổ riêng và chạy trên tab muse.ai bạn đang mở.

#### Mở Workflow

* Nhấn **Workflow** trong tab Điều khiển (hàng nút dưới cùng).
* Đã nhập prompt hoặc tải ảnh ở side panel? Rê chuột vào **Workflow** rồi nhấn **Chuyển sang workflow**: prompt, chế độ của từng prompt và ảnh sẽ thành các node trong workflow, sẵn sàng để chạy.

#### Màn hình

| Khu vực | Gồm những gì |
| :--- | :--- |
| **Bên trái** | **Node** (bấm hoặc kéo vào bảng vẽ) và **Workflow của bạn** (danh sách workflow đã lưu) |
| **Ở giữa** | Bảng vẽ. Góc trên trái: Hoàn tác/Làm lại, **Tự sắp xếp**, vừa khung nhìn, **Ví dụ**, xoá, và nút **Chạy tất cả** |
| **Bên phải** | Tổng quan, **Tiến độ** trực tiếp, **Vấn đề** (bấm để nhảy tới node), **Kế hoạch chạy** và cài đặt đang dùng |

#### Các loại node

| Node | Chức năng |
| :--- | :--- |
| **Nhập prompt** | Một hoặc nhiều prompt, tách nhau bằng **dòng trống** |
| **Tải ảnh lên** | Ảnh của bạn (thả file vào node). Rê chuột vào ảnh: 🔍 để xem lớn, ✕ để xoá, nút kéo ở góc để đổi thứ tự. Thứ tự (hoặc menu sắp xếp) quyết định prompt nào nhận ảnh nào |
| **Tạo ảnh** | Văn bản thành Hình ảnh, hoặc Hình ảnh thành Hình ảnh khi có ảnh nối vào. Tuỳ chọn: **Chế độ ảnh theo prompt**, **Số ảnh đầu vào tối đa mỗi Prompt**, **Tự động thêm ảnh nhân vật** |
| **Tạo video** | Văn bản thành Video, hoặc khi có ảnh nối vào: **Khung hình thành Video** / **Thành phần thành Video**. Tuỳ chọn: **Chế độ video theo prompt**, số ảnh mỗi prompt (dùng chung cài đặt với side panel), **Tự động thêm ảnh nhân vật** (Thành phần thành Video) |

Node Tạo ảnh / Tạo video tự đặt tên theo prompt đầu tiên (`image_…` / `video_…`). Mỗi dòng prompt hiển thị các ảnh mà prompt đó sẽ nhận, để bạn kiểm tra trước khi chạy.

#### Nối các node

Kéo từ chấm tròn bên phải của một node và **thả vào bất kỳ chỗ nào trên node kia** — cổng phù hợp sẽ được chọn tự động. Trong lúc kéo, node nào nối được sẽ sáng viền.

| Từ | Đến | Ý nghĩa |
| :--- | :--- | :--- |
| Nhập prompt | Tạo ảnh / Tạo video | Các prompt cần tạo |
| Tải ảnh lên | Tạo ảnh / Tạo video | Ảnh tham chiếu, khung hình bắt đầu hoặc thành phần |
| Tạo ảnh | Tạo ảnh / Tạo video | **Ảnh vừa tạo** trở thành ảnh đầu vào của node đó (node đó chạy khi ảnh đã sẵn sàng) |
| Tạo video — cổng **khung cuối** | Tạo video | Video sau **nối tiếp từ khung hình cuối** của video trước |
| Tạo video — cổng **khung cuối** | Tạo ảnh | **Khung hình cuối** của mỗi video trở thành ảnh đầu vào (chạy khi video đã sẵn sàng) |
| Tạo video — cổng **video** 🎬 | Tạo video | **Video vừa tạo trở thành thành phần** của video sau (Thành phần thành Video; chạy khi video đã sẵn sàng) |

#### Chạy

* **Chạy tất cả** (góc trên trái, hoặc `Ctrl/⌘ + Enter`) chạy cả workflow theo đúng thứ tự: node nào cần ảnh được tạo sẽ tự chạy khi ảnh đã có.
* Mỗi node Tạo ảnh / Tạo video có nút **Chạy** riêng để chỉ chạy node đó. Nút bị khoá cho tới khi các node nó phụ thuộc chạy xong (rê chuột để xem lý do).
* **Dừng** huỷ những gì đang chạy.
* Khi đang chạy, các đường nối vào node đang tạo sẽ sáng lên và có dòng chảy, để bạn thấy workflow đang ở bước nào.

> ⚠️ **Chrome tạm dừng muse.ai khi tab không hiển thị** (ví dụ cửa sổ workflow che toàn màn hình). Nhấn **Bật chạy nền** (ngay dưới **Chạy tất cả** trong workflow, hoặc ở side panel), rồi chọn tab muse.ai trong hộp thoại của Chrome. Việc này chia sẻ tab muse.ai (không ghi lại hay gửi đi đâu) để muse.ai tiếp tục tạo khi bị cửa sổ khác che. Nhãn xanh **Đang chạy nền** cho biết đã bật; nhấn ✕ để tắt.

#### Kết quả

Kết quả hiện ngay trong node Tạo ảnh / Tạo video. Rê chuột vào kết quả: 🔍 để xem lớn, ✕ để xoá (nút cục tẩy xoá toàn bộ kết quả của node). Video tự phát khi rê chuột. File vẫn được tải xuống như bình thường.

#### Quản lý workflow

Trong **Workflow của bạn** (bên trái): **Tạo mới**, **Nhập**, và menu **⋯** của từng workflow — **Đổi tên** (hoặc bấm đúp vào tên), **Nhân bản**, **Xuất file**, **Xoá**. Mọi thay đổi được lưu tự động.

* **Xuất file** tải về file `.json`. Đầu file có các dòng chú thích `//` mô tả mọi node, thuộc tính và cách nối, nên bạn có thể đưa file cho trợ lý AI và nhờ AI viết workflow mới. Các dòng `//` được bỏ đi khi nhập.
* **Nhập** file bằng nút Nhập, hoặc đơn giản **kéo file `.json` thả vào bảng vẽ**.

#### Phím tắt khi chỉnh sửa

Nhấn **Phím tắt** trên thanh trên cùng (hoặc phím `?`) để xem tất cả.

| Thao tác | Phím |
| :--- | :--- |
| Hoàn tác / Làm lại | `Ctrl/⌘ + Z` / `Ctrl/⌘ + Shift + Z` |
| Sao chép / Cắt / Dán node (dán được sang workflow khác) | `Ctrl/⌘ + C / X / V` |
| Nhân bản phần đang chọn | `Ctrl/⌘ + D` |
| Chọn tất cả / Chọn thêm / Quét chọn | `Ctrl/⌘ + A` / `Ctrl/⌘ + bấm` / `Shift + kéo` |
| Tự sắp xếp | `Shift + A` |
| Xoá phần đang chọn | `Delete` |
| Chạy tất cả / Chạy nền | `Ctrl/⌘ + Enter` / `Ctrl/⌘ + Shift + Enter` |

---

## ⚙️ Cấu hình Cài đặt

Truy cập tab **Cài đặt** để tùy chỉnh:

* **Chế độ mặc định:** Chế độ mở mặc định.
* **Tỷ lệ khung hình mặc định:** 16:9, 9:16, 1:1, 3:4 hoặc 4:3.
* **Tùy chọn Video mặc định:** Chế độ video mặc định cho mỗi prompt (10 giây hoặc 10 giây nối tiếp).
* **Tùy chọn Chế độ Hình ảnh mặc định:** Chế độ ảnh mặc định cho mỗi prompt (Ảnh mới hoặc Chỉnh sửa ảnh).
* **Số lần thử lại tối đa khi lỗi:** Số lần thử lại khi tạo lỗi (1–20).
* **Chất lượng tự động tải xuống (Video / Hình ảnh):** Chọn video 1080p, ảnh 1k, hoặc **Không tải xuống**.
* **Ngôn ngữ:** English, Tiếng Việt, 中文, 한국어, 日本語, Español.
* **Cài đặt tải xuống:** Tệp được lưu vào thư mục Tải xuống của Chrome, bên trong thư mục dự án.

Nhấn **Lưu cài đặt** để áp dụng, hoặc **Đặt lại mặc định** để khôi phục giá trị mặc định.

---

## 💡 Mẹo & Thực hành tốt nhất

1. **Thời gian chờ:** Gặp giới hạn tốc độ thì tăng **Độ trễ ngẫu nhiên** trong tab Điều khiển.
2. **Chạy thử trước:** Chạy một khoảng nhỏ (ví dụ: prompt 1 đến 2) trước khi chạy cả danh sách.
3. **Viết Prompt:** Viết cụ thể. Prompt chi tiết cho kết quả tốt hơn. Tách nhiều prompt bằng dòng trống.
4. **Ảnh nhân vật:** Đặt tên tệp ảnh theo tên nhân vật (ví dụ: `Anna.png`, `Tom.jpg`) để dùng **Tự động thêm ảnh nhân vật**.
5. **Quản lý tệp:** Tải xuống tự động sắp xếp theo thư mục dự án. Bật **Tự động đổi tên tệp** để mỗi tệp bắt đầu bằng số thứ tự prompt.
6. **Workflow:** Chạy thử một node bằng nút **Chạy** riêng của nó trước khi **Chạy tất cả**. Mới dùng thì bắt đầu từ **Ví dụ**, và dùng **Xuất file** để sao lưu hoặc chia sẻ workflow.

---

## 🔧 Khắc phục sự cố

| Vấn đề | Giải pháp |
| :--- | :--- |
| **Tiện ích không hoạt động** | Đảm bảo đang ở [muse.ai](https://muse.ai). Tải lại trang nếu cần. |
| **Lỗi "Please refresh Muse AI page"** | Tải lại trang Muse.ai (Ctrl+R, F5) rồi thử lại. Nếu vẫn lỗi, cài lại tiện ích. |
| **Lỗi khi tạo** | Muse.ai có thể đang bận. Tiện ích sẽ tự thử lại theo cài đặt **Số lần thử lại tối đa**. |
| **Nút Chạy bị mờ** | Thêm prompt, và với các chế độ dùng ảnh thì tải lên đủ ảnh (mỗi prompt một ảnh). |
| **Nút Chạy hiện "Nâng cấp lên Max"** | Bạn đã dùng hết lượt miễn phí trong ngày. Nâng cấp lên Max hoặc thử lại vào ngày mai. |
| **Tải xuống không hoạt động** | Tắt "Hỏi nơi lưu từng tệp trước khi tải xuống" trong Cài đặt Chrome. |
| **Yêu cầu đăng nhập** | Đảm bảo đã đăng nhập tài khoản Muse.ai. |
| **Workflow: kết quả đứng mãi ở "Đang tạo"** | Chrome đã tạm dừng tab muse.ai bị che. Bật **Bật chạy nền** (hoặc **Chạy nền**), hoặc để tab muse.ai hiển thị. |
| **Workflow: nút Chạy của một node bị mờ** | Rê chuột vào nút: chạy node mà nó phụ thuộc trước, hoặc sửa vấn đề được báo (ví dụ chưa nối prompt). |
| **Workflow: "Không tìm thấy tab muse.ai"** | Mở [muse.ai](https://muse.ai) trong một tab (chấm xanh trên thanh trên cùng cho biết đã kết nối). |

---

## 🔒 Quyền riêng tư & Dữ liệu

* **Xử lý tại chỗ:** Logic tự động chạy cục bộ trong trình duyệt.
* **Không thu thập dữ liệu:** Chúng tôi không lưu hoặc thu thập prompt, ảnh hay dữ liệu tài khoản của bạn.
* **Lưu trữ an toàn:** Cài đặt và workflow chỉ lưu trong bộ nhớ cục bộ trình duyệt.
* **Chạy nền:** Việc chia sẻ tab muse.ai chỉ để giữ tab tiếp tục chạy. Không có gì được ghi lại, lưu hay gửi đi đâu.

---

## 📞 Hỗ trợ

- **Tác giả:** Trường Nguyễn
- **Website:** [kylenguyen.me](https://kylenguyen.me)
- **Phản hồi:** Dùng liên kết "Báo cáo lỗi cho tác giả" trong tiện ích. Sao chép nhật ký trong tab **Nhật Ký Gỡ Lỗi** và gửi kèm báo cáo.

---

## 📦 Phiên bản

Phiên bản hiện tại: **1.0.0**

---

## 📜 Bản quyền

Bản quyền © 2026 **Trường Nguyễn**. Bảo lưu mọi quyền.

Phần mềm này là tài sản riêng. Sao chép hoặc phân phối trái phép bị nghiêm cấm.

---

**Được thực hiện với ❤️ bởi Trường Nguyễn**

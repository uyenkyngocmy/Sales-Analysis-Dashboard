
# 📊 Sales Analysis Dashboard

## 📌 Giới thiệu

Dự án xây dựng **bảng điều khiển trực quan (dashboard)** giúp phân tích doanh số bán hàng theo sản phẩm, thương hiệu, giá bán và thời gian. Dashboard hỗ trợ nhà quản lý nhanh chóng nhận diện sản phẩm bán chạy, thương hiệu nổi bật và xu hướng giá, từ đó đưa ra quyết định nhập hàng, marketing và tối ưu lợi nhuận.

---

## ⚙️ Công nghệ sử dụng

* **Python (pandas, matplotlib, seaborn)**: tiền xử lý dữ liệu (chuẩn hóa, làm sạch, tạo biến).
* **Power BI**: thiết kế dashboard trực quan, biểu đồ phân tích doanh số, sản phẩm và thương hiệu.

---
## 📂 Dataset  
- Nguồn dữ liệu: Bộ dữ liệu gốc thu thập từ thông tin bán hàng sản phẩm gia vị trên thị trường Việt Nam trong 365 ngày gần nhất. Bộ dữ liệu có 200 dòng và 9 cột gồm stt, tên sản phẩm, giá bán, doanh số 365 ngày gần nhất, số sản phẩm đã bán trong 365 ngày gần nhất, tổng doanh số, số lượt bán, tổng đánh giá và Brand.
- Các bước xử lý dữ liệu:
    - Xóa dữ liệu trùng lặp: loại bỏ các dòng bị lặp lại.
    - Làm sạch brand/product name: chỉnh sửa sai chính tả, viết hoa/thường đồng nhất, gộp các biến thể về 1 tên chuẩn.
    - Chuẩn hóa giá bán: đổi về định dạng số, loại bỏ kí tự không hợp lệ. Đưa tất cả giá trị về cùng đơn vị (VND).
    - Xử lý missing values: điền thành giá trị Unknown.

---
## 📊 Dashboard Preview  
<img width="1833" height="1063" alt="image" src="https://github.com/user-attachments/assets/80009e27-a92b-472d-8f9a-a2202f6c3234" />

* KPI Cards: Tổng doanh số, số lượt bán, số loại sản phẩm, số thương hiệu.
* Top 10 sản phẩm & thương hiệu có doanh số cao nhất trong 365 ngày.
* Quan hệ giữa **giá bán và doanh số** theo thương hiệu.
* Phân phối theo giá bán sản phẩm.

---

## 🔍 Insight nổi bật

* Một số sản phẩm combo và gia vị đặc trưng chiếm tỷ trọng doanh số cao.
* Thương hiệu O’Food và THÍCH CAY dẫn đầu thị trường.
* Sản phẩm có giá bán vừa phải (<500k VND) thường đạt doanh số cao nhất.
* Thị trường vẫn tiềm năng để mở rộng sản phẩm trong phân khúc giá thấp – trung bình.


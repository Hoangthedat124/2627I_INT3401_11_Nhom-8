# Phân loại ảnh cảnh quan sử dụng mạng nơ-ron tích chập (CNN)

## 1. Hướng dẫn huấn luyện lại mô hình (Train trên Google Colab)
* **Bước 1:** Truy cập Google Colab và mở file `trainmodel.ipynb`.
* **Bước 2:** Chuyển sang sử dụng GPU bằng cách chọn: `Runtime` → `Change runtime type` → chọn **T4 GPU**.
* **Bước 3:** Tải file `dataset.zip` lên môi trường Colab và chạy tuần tự từng ô (cell) theo hướng dẫn trong notebook.
* **Bước 4:** Chờ quá trình huấn luyện hoàn tất, sau đó tải ảnh lên để kiểm thử kết quả.

---

## 2. Hướng dẫn kiểm thử mô hình có sẵn trên Google Colab
* **Bước 1:** Truy cập Google Colab và mở file `trainmodel.ipynb`.
* **Bước 2:** Tải đồng thời 3 file sau lên môi trường Colab:
  * `baseline_model.keras`
  * `baseline_history.pkl`
  * `dataset.zip`
* **Bước 3:** Chỉ chạy các cell được cho phép (bỏ qua các cell huấn luyện/bị đánh dấu cấm). *(Lưu ý: Nếu lỡ chạy nhầm cell bị cấm, vui lòng tải lại trang hoặc mở lại file notebook từ đầu).*
* **Bước 4:** Tải ảnh cần phân loại lên và đổi tên ảnh khớp với đường dẫn trong code để chạy kiểm thử.

---

## 3. Kiểm thử trực tiếp trên Web (Không cần Google Colab)
* **Bước 1:** Truy cập ứng dụng tại đường dẫn: [Hugging Face Space - CNN](https://huggingface.co/spaces/Dastsimcu/CNN)
* **Bước 2:** Nếu giao diện đang ở trạng thái ngủ (*Sleep*), hãy nhấn nút **"Restart this space"** và chờ vài phút để hệ thống khởi động lại.
* **Bước 3:** Tải lên hoặc kéo thả trực tiếp ảnh vào khung dự đoán để xem kết quả.

---
**CHÚC CÁC BẠN THÀNH CÔNG!**

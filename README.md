# Vietnamese-Deepseek-OCR

Project tập trung vào việc giải quyết bài toán OCR cho chữ viết tay tiếng Việt sử dụng mô hình DeepSeek-OCR hiện đại cùng với sự hỗ trợ từ framework của unsloth.

## Cài đặt và Sử dụng

### Yêu cầu
- Python 3.10+

### Cài đặt thư viện
```bash
pip install -r requirements.txt
```

### Cấu trúc dự án
- `notebooks/`: Chứa các Jupyter Notebook cho từng giai đoạn.
  - `00_exploration.ipynb`: Khám phá dữ liệu.
  - `01_preprocessing.ipynb`: Tiền xử lý dữ liệu.
  - `02_finetune.ipynb`: Huấn luyện mô hình với Unsloth.
  - `03_evaluation.ipynb`: Đánh giá mô hình trên tập Test.
  - `04_post_eval.ipynb`: Phân tích lỗi và trực quan hóa kết quả.
- `data/`: Chứa dữ liệu dataset (HuggingFace Arrow format).
- `report/`: Mã nguồn LaTeX cho báo cáo.

## Tài liệu tham khảo

- **UIT-HWDB Dataset:** Nguyen et al., "UIT-HWDB: A Database of Handwritten Vietnamese Words", RIVF 2022.
- **Unsloth:** Thư viện tối ưu hóa LLM fine-tuning.
- **DeepSeek-VL/Qwen-VL:** Kiến trúc mô hình nền tảng.

# Computer Vision Assignment 1
**Biểu Diễn Ảnh Màu và Lọc Tín Hiệu**

> **Môn học:** Xử lý Ảnh Số và Thị Giác Máy Tính  
> **Giảng viên:** TS. Võ Thanh Hùng  

---

## 📋 Nội dung

### Phần 1: Biểu diễn ảnh màu và ảnh xám
- Chuyển đổi RGB ↔ Grayscale (3 phương pháp: OpenCV, Average, Luminance)
- Tách và kết hợp kênh màu
- Hoán đổi kênh màu

### Phần 2: Lọc ảnh trong miền không gian
- **Low-pass:** Mean Filter, Gaussian Filter
- **High-pass:** Laplacian, Sobel Operator
- So sánh Raw vs Clean (có/không tiền xử lý)

---

## 🛠️ Công nghệ

- Python 3.8+
- OpenCV 4.x
- NumPy, Matplotlib

---

## 🚀 Chạy code

```bash
# Cài đặt
pip install opencv-python numpy matplotlib jupyter

# Chạy notebook
jupyter notebook BTL1_ComputerVision.ipynb
```

---

## 📊 Kết quả chính

**Grayscale conversion:**  
Luminance (0.299R + 0.587G + 0.114B) cho kết quả tự nhiên nhất

**Filtering:**  
- Gaussian > Mean (preserve edges tốt hơn)
- Sobel > Laplacian (ít nhạy noise hơn)
- Gaussian blur cần thiết cho high-pass filtering

---

## 📚 Tài liệu tham khảo

1. Võ Thanh Hùng, *Slide bài giảng CV*, HCMUT, 2024-2025
2. [OpenCV Documentation](https://docs.opencv.org/4.x/d2/d96/tutorial_py_table_of_contents_imgproc.html)
3. Gonzalez & Woods, *Digital Image Processing*, 4th Ed., 2018

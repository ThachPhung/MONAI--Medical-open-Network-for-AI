# MONAI--Medical-Open-Network-for-AI

**MONAI** (Medical Open Network for AI) là hệ sinh thái mã nguồn mở dựa trên **PyTorch**,  
được thiết kế chuyên biệt cho **AI trong ảnh y tế**.  

Mục tiêu: Chuẩn hoá toàn bộ pipeline từ **nghiên cứu → huấn luyện → gán nhãn → triển khai lâm sàng**,  
tạo nền tảng chung cho cộng đồng học thuật, công nghiệp và bệnh viện.

---

## 🔑 Thành phần chính

### MONAI Core
- Transform 2D/3D chuyên biệt cho ảnh y tế.  
- Hỗ trợ định dạng DICOM, NIfTI.  
- Networks, losses, metrics, sliding-window inference.  

### MONAI Label
- Nền tảng gán nhãn thông minh.  
- Tích hợp với **3D Slicer**, **OHIF**, **CVAT**.  
- Hỗ trợ **active learning** để tăng tốc tạo dữ liệu.  

### MONAI Deploy App SDK
- Bộ SDK đóng gói ứng dụng AI thành **MAP (MONAI Application Package)**.  
- Dễ triển khai trong môi trường lâm sàng.  

### Model Zoo & Bundles
- Tập hợp các mô hình **state-of-the-art**.  
- Cấu hình train/infer đầy đủ, dễ tuỳ biến.  

### Generative Models
- Hỗ trợ **Diffusion Models, GANs, anomaly detection, MRI reconstruction**.  

---

## 🚀 Lý do chọn MONAI
- Tối ưu cho **ảnh y tế đa chiều (2D/3D/4D, DICOM/NIfTI)**.  
- Chuẩn hoá vòng đời mô hình nhờ **Bundles / Model Zoo**.  
- Đầy đủ pipeline: **Label → Train → Deploy**.  

---

## ⚡ Cài đặt nhanh

```bash
# Cài đặt MONAI Core
pip install "monai[pillow,tqdm]"

# (Tuỳ chọn) Cài đặt Generative Models
pip install monai-generative


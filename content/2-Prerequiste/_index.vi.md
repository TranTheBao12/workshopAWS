---
title : "Preparation"
date : "2025-05-28"
weight : 2
chapter : false
pre : " <b> 2. </b> "
---

{{% notice info %}}
Trước khi bắt đầu bài thực hành, bạn cần hoàn thành các bước chuẩn bị môi trường và công cụ cần thiết bên dưới.
{{% /notice %}}

### Nội dung chuẩn bị:

1. **Cài đặt công cụ:**  
   - Cài đặt **.NET SDK** (ASP.NET Core).  
   - Cài đặt **FFmpeg** để tạo video.  
   - Cài đặt **Tesseract OCR** để trích xuất văn bản từ ảnh.  
   - Cài đặt **Google Cloud SDK** nếu sử dụng dịch vụ TTS và Translate từ Google.  

2. **Cấu hình AWS CLI:**  
   - Cài đặt AWS CLI phù hợp với hệ điều hành.  
   - Cấu hình AWS CLI với lệnh:  
     ```bash
     aws configure
     ```  
     Nhập Access Key, Secret Key, vùng (region) và định dạng đầu ra (output format).

3. **Chuẩn bị mã nguồn:**  
   - Clone hoặc tải dự án **ImageToVideoWeb**.  
   - Kiểm tra các thư mục như `uploads/`, `temp/`, `outputs/` đã tồn tại hoặc tạo mới.  
   - Cấu hình thông tin bucket S3 và các khóa API (Google API Key, AWS S3 config, v.v.) trong `appsettings.json`.

4. **Kiểm tra cục bộ:**  
   - Chạy ứng dụng ở môi trường local:  
   

### Liên kết tham khảo:
- [Tài liệu .NET](https://learn.microsoft.com/en-us/dotnet/core/install/)  
- [Tài liệu AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)  
- [Tài liệu Google Cloud SDK](https://cloud.google.com/sdk/docs/install)  

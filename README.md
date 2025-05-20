# Chuyển đổi tín hiệu PPG sang CO₂ bằng Corr-Encoder

## Tổng quan

Dự án này xây dựng mô hình **Corr-Encoder** nhằm chuyển đổi tín hiệu sinh lý từ **PPG (Photoplethysmogram)** sang tín hiệu **CO₂ (Carbon Dioxide)**.

Mô hình học cách khai thác mối tương quan giữa tín hiệu PPG và CO₂ để dự đoán chính xác tín hiệu CO₂ từ đầu vào PPG.

## Dữ liệu

Dữ liệu sử dụng là bộ **CapnoBase**, một bộ dữ liệu nổi tiếng chứa các tín hiệu PPG và CO₂ được ghi đồng bộ cùng các tín hiệu sinh lý khác.

- Link tải dữ liệu: [CapnoBase trên PhysioNet](https://physionet.org/content/capnobase/1.0.0/)
- Dữ liệu được tiền xử lý để căn chỉnh tín hiệu PPG và CO₂ phù hợp cho việc huấn luyện mô hình.

## Mô hình

- **Corr-Encoder**: Mô hình mạng nơ-ron học biểu diễn mối quan hệ tương quan giữa PPG và CO₂ để thực hiện chuyển đổi tín hiệu.
![image](https://github.com/user-attachments/assets/06793f4c-2de0-4020-be6c-adcfcab303c9)



![image](https://github.com/user-attachments/assets/123f4197-a25d-43d8-b197-9674fac0e296)

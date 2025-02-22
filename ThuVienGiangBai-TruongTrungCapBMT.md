# Creating the markdown content based on the Kiến Thức Lái Xe section
md_content_kien_thuc_lai_xe = """
# Kiến Thức Lái Xe - Trường Trung Cấp Buôn Ma Thuột

Trang Kiến Thức Lái Xe cung cấp các bài viết và thông tin hữu ích về việc thi và học lái xe.

## Liên kết
- [Kiến Thức Lái Xe tại BMTC](https://bmtc.edu.vn/category/kien-thuc-lai-xe/)

## Các bài viết nổi bật
- **Kiến thức tối thiểu**: Các lưu ý khi chuẩn bị hồ sơ thi bằng lái xe B2.
- **Thông báo tuyển dụng**: Trường Trung cấp Buôn Ma Thuột thông báo tuyển dụng giáo viên và nhân viên kế toán.
- **Thông báo tuyển sinh**: Thông báo tuyển sinh hệ sơ cấp và học viên lái xe hạng B.

## Liên hệ
- Địa chỉ: 131 Phan Huy Chú, Phường Khánh Xuân, TP Buôn Ma Thuột, Đắk Lắk.
- Điện thoại: 0262 368 5533.
- Email: [info@bmtc.edu.vn](mailto:info@bmtc.edu.vn)
"""

# Saving the content to a .md file
file_path_kien_thuc_lai_xe = "/mnt/data/Kien_Thuc_Lai_Xe_BMTC.md"
with open(file_path_kien_thuc_lai_xe, "w", encoding="utf-8") as file:
    file.write(md_content_kien_thuc_lai_xe)

file_path_kien_thuc_lai_xe  # Returning the file path for download

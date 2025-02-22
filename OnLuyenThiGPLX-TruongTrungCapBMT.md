# Creating the markdown content based on the information from the page
md_content = """
# Ôn Luyện Thi GPLX - Trường Trung Cấp Buôn Ma Thuột

Trang ôn luyện thi GPLX của Trường Trung Cấp Buôn Ma Thuột. Cung cấp các khóa học ôn luyện để thi lấy giấy phép lái xe hạng B.

## Liên kết
- [Ôn luyện thi GPLX tại BMTC](https://bmtc.edu.vn/on-luyen-thi-gplx/)

## Thông tin về khóa học
- Khóa học lái xe hạng B.
- Khai giảng thường xuyên.

## Liên hệ
- Địa chỉ: 131 Phan Huy Chú, Phường Khánh Xuân, TP Buôn Ma Thuột, Đắk Lắk.
- Điện thoại: 0262 368 5533.
- Email: [info@bmtc.edu.vn](mailto:info@bmtc.edu.vn)
"""

# Saving the content to a .md file
file_path = "/mnt/data/On_Luyen_Thi_GPLX_BMTC.md"
with open(file_path, "w", encoding="utf-8") as file:
    file.write(md_content)

file_path  # Returning the file path for download

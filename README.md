# 22005287nguyenngochoangan
Họ và Tên: Nguyễn Ngọc Hoàng An
MSSV: 22005287
Lớp: 22C2B-LTM1
Đề tài: PHẦN MỀM QUẢN LÝ SẢN PHẨM


Tải code về giải nén chạy file

MỞ NetBean -> Open Project 
TRƯỚC KHI CHẠY BÀI HÃY NHẤN VÀO THƯ MỤC  data -> dsConnectDatabase *ĐỂ ĐỔI CẤU HÌNH KẾT NỐI VÀO DATABASE SQL
HƯỚNG DẴN :
public class clsConnectDB {
    String connectionString = "jdbc:sqlserver://Admin:1433;" 
            + "databaseName=quanlysanpham;user=sa;password=1234;";

Ở ĐÂY Admin:1433 LÀ TÊN CỦA PC CÓ 2 CÁCH ĐỂ BIẾT 
1. LÀ SERVER NAME KHI VÀO SQL SERVER SẼ THẤY BẢNG CHỌN HIỆN RA ĐẦU TIÊN * SẼ LÀ THAY THẾ CHO PHẦN ADMIN
2. LÀ VÀO SETTING HỆ THỐNG MÁY TÍNH TÊN THIẾT BỊ * SẼ LÀ THAY THẾ CHO PHẦN ADMIN 
3. 1433 LÀ TCP/IP CỦA SQL 
4. databaseName=quanlysanpham LÀ TÊN FILE CHẠY TRONG SQL CỦA BÀI 
5. user=sa;password=1234 LÀ TÀI KHOẢN VÀ MẬT KHẨU ĐĂNG NHẬP VÀO SQL SERVER , MỖI MÁY CÓ TÀI KHOẢN HOẶC MẬT KHẨU KHÁC NHAU DO MỖI NGƯỜI TỰ TẠO
6. Khi mở bài chạy hiện thư mục báo lỗi thì thoát và click chuột phải vào phần Libraries -> Add JAR/Folder... -> Tìm thư mục lib trong file bài làm add vào là xong

VÀO THƯ MỤC DATABASE SẼ THẤY FILE SQL QLSanPham NHẤN ĐÚP VÀO 
1. KHI Mở FILE CÓ ĐUÔI SQL bỏ file vào bôi đen tất cả đoạn code và chạy , hoặc tạo Database -> New Database trước khi * LƯU Ý : PHẢI ĐẶT TÊN FILE TRÙNG 
2. CÁCH KHÁC LẤY 2 FILE QLSanPham LẦN LƯỢT CÓ ĐUÔI .LDP VÀ .MDF, TIẾP THEO TÌM THƯ MỤC C:\Program Files\Microsoft SQL Server
3. TÌM ĐẾN FILE MSSQL13.MSSQLSERVER\MSSQL\DATA RỒI DÁN 2 FILE VÀO ĐÓ 
4. VÀO SQL SERVER NHẤP CHUỘT TRÁI VÀO MỤC Databases => Attach... => NHẤN ADD RỒI TÌM  ĐẾN VÀ MỞ THƯ MỤC MSSQL13.MSSQLSERVER\MSSQL\DATA BẤM FILE QLSanPham.MDF => OK
* CHÚ Ý: MỖI MÁY SẼ CÓ THƯ MỤC MSSQL13.MSSQLSERVER KHÁC NHAU DO PHIÊN BẢN CÀI CHỈ CẦN TÌM TÊN MSSQL  .MSSQL KHI BẤM VÀO THƯ MỤC MSSQL HIỆN THƯ MỤC DATA LÀ ĐÚNG


Mật Khẩu và Tài Khoản Đăng Nhập
PHẦN ADMIN:
TenDangNhap: admin Pasword: admin
TenDangNhap: danhtp Pasword: 123456
PHẦN DÀNH CHO BỘ PHẬN IT:
TenDangNhap: tuannc Pasword: 123123
PHẦN NHÂN VIÊN:
TenDangNhap: taolhpk TenDangNhap: 123123
TenDangNhap:tuan1994  TenDangNhap:123456






# Đồ án: Quản Lý Quán Cafe
## Sinh viên thực hiện: Nguyễn Văn Hoan 
## Giáo viên Hướng dẫn: Đỗ Duy Cốp
   ## Dàn ý: chi tiết Quản lý quán cafe
 
  ### 1. Đối tượng sử dụng hệ thống
          -Chủ quán (Admin): Quản lý toàn bộ hoạt động, doanh thu, nhân sự.
          
          -Nhân viên phục vụ: Nhận đơn, phục vụ khách hàng.
          
          -Nhân viên pha chế: Nhận đơn pha chế đồ uống.
          
          -Nhân viên thu ngân: Xử lý thanh toán, in hóa đơn.
          
          -Khách hàng: Đặt món, đặt bàn, đánh giá dịch vụ.

  ### 2.A: Chức năng hệ thống theo từng đối tượng
  2.1 Quản lý thực đơn
      Đối tượng sử dụng: Admin
      Mô tả:
      
            -Thêm, chỉnh sửa, xóa món.
            
            -Cập nhật giá, hình ảnh, mô tả.
            
            -Phân loại món theo danh mục.

 2.2 Quản lý kho nguyên liệu
     Đối tượng sử dụng: Admin, nhân viên pha chế
     Mô tả:
     
          -Theo dõi số lượng nguyên liệu tồn kho.
          
          -Nhập hàng, xuất hàng, cảnh báo nguyên liệu sắp hết.
          
          _Quản lý lịch sử nhập – xuất nguyên liệu.

 2.3 Quản lý nhân viên
     Đối tượng sử dụng: Admin
    Mô tả:
    
          -Thêm, sửa, xóa nhân viên.
          
          -Phân quyền cho nhân viên (thu ngân, phục vụ, pha chế).
          
          -Theo dõi hiệu suất làm việc (số đơn phục vụ, doanh thu đóng góp).

2.4 Quản lý doanh thu & báo cáo
    Đối tượng sử dụng: Admin
    Mô tả:
    
         -Thống kê doanh thu theo ngày, tuần, tháng.

        -Báo cáo món bán chạy, lợi nhuận theo sản phẩm.

        -Xuất báo cáo dưới dạng file Excel, PDF.

2.5 Quản lý chương trình khuyến mãi & khách hàng thân thiết
     Đối tượng sử dụng: Admin
     Mô tả:

           -Tạo mã giảm giá, chương trình khuyến mãi.

           -Quản lý khách hàng thành viên, tích điểm.

           

## 2.B: Chức năng dành cho Nhân viên phục vụ
    2.1. Nhận đơn từ khách hàng
        Đối tượng sử dụng: Nhân viên phục vụ
        Mô tả:

              -Nhận đơn từ khách (tablet, điện thoại).

              -Gửi đơn đến quầy pha chế và bếp.

    2.2 Quản lý bàn & tình trạng đặt chỗ
        Đối tượng sử dụng: Nhân viên phục vụ
        Mô tả:

              -Cập nhật tình trạng bàn (trống/đang sử dụng).

              -Đặt bàn trước cho khách nếu cần.

    2.3. Xử lý yêu cầu của khách hàng
         Đối tượng sử dụng: Nhân viên phục vụ
         Mô tả:

                -Thêm món, hủy món theo yêu cầu khách.

                -Gửi thông báo cập nhật đơn hàng.

## 2.C. Chức năng dành cho Nhân viên pha chế
     2.1. Nhận đơn pha chế
     Đối tượng sử dụng: Nhân viên pha chế
     Mô tả:

           -Nhận thông tin đơn hàng từ hệ thống.
 
           -Hiển thị danh sách món cần làm.

     2.2. Cập nhật trạng thái món
     Đối tượng sử dụng: Nhân viên pha chế
     Mô tả:

           -Xác nhận khi món đã pha chế xong.
           
           -Gửi thông báo đến phục vụ để giao món.

     2.3. Quản lý nguyên liệu tiêu hao
      Đối tượng sử dụng: Nhân viên pha chế, Admin
      Mô tả:

            -Cập nhật lượng nguyên liệu sử dụng hàng ngày.
            
           -Đề xuất nhập hàng nếu nguyên liệu sắp hết.

## 2.D. Chức năng dành cho Nhân viên thu ngân
   2.1. Xử lý thanh toán
   Đối tượng sử dụng: Nhân viên thu ngân
   Mô tả:

         -Thanh toán bằng tiền mặt, thẻ, ví điện tử.

         -Kiểm tra mã giảm giá, tích điểm khách hàng.

    2.2. In hóa đơn
     Đối tượng sử dụng: Nhân viên thu ngân
     Mô tả:

           -In hóa đơn sau khi thanh toán.

           -Lưu lịch sử giao dịch.

## 3. Xử lý hoàn tiền, hủy giao dịch
Đối tượng sử dụng: Nhân viên thu ngân, Admin

Mô tả:

Hủy đơn nếu khách hàng đổi ý.

Xử lý hoàn tiền theo chính sách quán.

E. Chức năng dành cho Khách hàng
1. Đặt bàn online
Đối tượng sử dụng: Khách hàng

Mô tả:

Đặt bàn trước qua ứng dụng/web.

Xem tình trạng bàn trống.

2. Đặt món từ xa
Đối tượng sử dụng: Khách hàng

Mô tả:

Đặt món để mang đi hoặc giao hàng.

Theo dõi trạng thái đơn hàng.

3. Xem thực đơn & giá cả
Đối tượng sử dụng: Khách hàng

Mô tả:

Xem hình ảnh, giá, mô tả món.

Đọc đánh giá từ khách hàng khác.

4. Đánh giá, phản hồi chất lượng dịch vụ
Đối tượng sử dụng: Khách hàng

Mô tả:

Đánh giá món ăn, dịch vụ.

Gửi phản hồi trực tiếp cho quán.

5. Sử dụng chương trình khách hàng thân thiết
Đối tượng sử dụng: Khách hàng

Mô tả:

Tích điểm khi mua hàng.

Sử dụng mã giảm giá.

3. Công nghệ áp dụng
Phần mềm web/app: Quản lý toàn bộ hệ thống.

Máy POS: Hỗ trợ thanh toán nhanh chóng.

Màn hình bếp/pha chế: Hiển thị đơn hàng tự động.

Máy in hóa đơn: Xuất hóa đơn nhanh.

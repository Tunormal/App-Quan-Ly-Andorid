# App-Qu-n-L-Android
App Quản lý Chi tiêu, thu nhập, lịch/lịch Phật giáo hỗ trợ tu tập được code bởi kotlin
# Tú normal - Lịch Thập trai & Chi tiêu

Tú normal là app Android giúp bạn theo dõi lịch âm, ngày Thập trai, sự kiện cá nhân hằng năm, ghi chú có hạn và quản lý thu chi hằng ngày trong cùng một nơi.

Tên gọi phù hợp cho phần lịch là **Lịch Thập trai & Phật pháp**. App đang đánh dấu 10 ngày trai theo lịch âm trong mỗi tháng, nên gọi là "ngày Thập trai" sẽ rõ hơn. Bát Quan Trai Giới là phần thực hành giữ giới có thể gắn với những ngày này.

## App dùng để làm gì?

- Xem lịch dương và lịch âm.
- Nhận biết các ngày Thập trai trong tháng âm.
- Xem các ngày vía, lễ Phật giáo nếu bật chế độ Phật pháp.
- Thêm sự kiện cá nhân lặp lại hằng năm như sinh nhật, ngày giỗ, ngày kỷ niệm.
- Nhận thông báo sự kiện theo đúng ngày và giờ đã đặt.
- Nhận thông báo tổng hợp lúc 6:00 sáng.
- Ghi chú việc cần làm có ngày và giờ hết hạn.
- Quản lý nguồn tiền, mục tiêu thu nhập, mục tiêu chi tiêu và giao dịch.
- Xem biểu đồ chi tiêu theo tuần, tháng và so sánh với kỳ trước.
- Sao lưu và khôi phục dữ liệu bằng file JSON.

## Màn hình Trang chủ

Trang chủ hiển thị nhanh các thông tin quan trọng trong ngày:

- Ngày dương hôm nay.
- Ngày âm hôm nay.
- Nhãn ngày Thập trai hoặc ngày vía nếu có.
- Tổng số dư hiện có.
- Thu nhập và chi tiêu trong tháng.
- Mục tiêu đang sắp hết hạn hoặc vượt hạn mức.
- Ghi chú sắp đến hạn.

Từ Trang chủ, bạn có thể mở nhanh lịch, thêm giao dịch mới hoặc tạo mục tiêu mới.

## Màn hình Lịch Thập trai & Phật pháp

Màn hình lịch giúp bạn xem lịch theo tháng:

- Mỗi ô ngày có cả ngày dương và ngày âm.
- Ngày hôm nay được làm nổi bật.
- Ngày Thập trai có dấu và màu riêng.
- Ngày vía, lễ Phật giáo được đánh dấu khi bật chế độ Phật pháp.
- Có thể chuyển tháng, chọn nhanh tháng/năm và quay về hôm nay.

Bạn cũng có thể thêm **sự kiện hằng năm**. Ví dụ:

- Sinh nhật.
- Ngày giỗ.
- Kỷ niệm.
- Ngày cần nhắc riêng.

Khi thêm sự kiện, bạn nhập tiêu đề, nội dung, ngày và giờ thông báo. Sự kiện sẽ được nhắc lại mỗi năm, không tự xóa sau khi qua ngày.

## Màn hình Chi Tiêu

Màn hình Chi Tiêu dùng để quản lý tiền cá nhân:

- Tạo nhiều nguồn tiền như tiền mặt, ngân hàng, ví điện tử, tiết kiệm.
- Ghi nhận thu nhập, chi tiêu và chuyển khoản.
- Chọn ngày giao dịch khi nhập giao dịch mới.
- Giờ phút giao dịch được hệ thống tự lưu để lịch sử gần đây hiển thị đúng thời điểm, người dùng không cần chỉnh thủ công.
- Tạo mục tiêu chi tiêu hoặc mục tiêu thu nhập.
- Theo dõi số tiền đã dùng so với hạn mức.
- Cảnh báo mục tiêu sắp hết hạn hoặc vượt hạn mức.
- Mục tiêu quá hạn đủ 3 ngày sẽ được tự dọn khỏi app.

Phần biểu đồ hỗ trợ:

- Chi tiêu tuần này.
- So sánh tuần này với tuần trước.
- Chi tiêu tháng này.
- Thống kê tháng trước.
- So sánh tháng này với tháng trước.
- Phân bổ chi tiêu theo danh mục.

Lịch sử giao dịch có phân trang kiểu web để dễ xem khi dữ liệu nhiều.

## Màn hình Ghi chú

Ghi chú dùng cho các việc cần nhắc theo hạn:

- Mỗi ghi chú có tiêu đề, nội dung, ngày hết hạn và giờ hết hạn.
- Giờ hết hạn mặc định là 00:00, bạn có thể chỉnh lại theo nhu cầu.
- Ghi chú quá hạn không tự xóa ngay, để bạn tự xem và xác nhận.
- Khi bấm hoàn thành, ghi chú vẫn còn trong ngày đó và tự xóa sau 0h ngày hôm sau.
- Nếu bật nhắc trước hạn, app sẽ thông báo trước khi ghi chú hết hạn theo mốc bạn chọn.

## Màn hình Cài đặt

Trong Cài đặt, bạn có thể:

- Quản lý nguồn tiền.
- Thêm trường giao diện linh động cho nguồn tiền, mục tiêu hoặc danh mục.
- Bật/tắt nhắc ghi chú sắp hết hạn.
- Chọn mốc nhắc trước: 15 phút, 30 phút hoặc 1 tiếng.
- Chọn giao diện Light, Dark hoặc theo hệ thống.
- Chọn giao diện theo mùa.
- Chọn đơn vị tiền tệ VND hoặc USD.
- Bật/tắt Lịch Thập trai & Phật pháp.
- Test thông báo.
- Xuất dữ liệu JSON.
- Nhập dữ liệu JSON từ file trên máy hoặc từ nội dung dán vào.
- Xóa toàn bộ dữ liệu nếu muốn làm lại từ đầu.

## Sao lưu và khôi phục dữ liệu

App có nút **Xuất file JSON** để tạo file sao lưu.

- Trên Android 10 trở lên, file được lưu vào thư mục Downloads của máy, trong thư mục `Tu normal`.
- Trên Android cũ hơn, file được lưu vào thư mục dữ liệu của app.
- File sao lưu chứa nguồn tiền, mục tiêu, giao dịch, ghi chú, sự kiện lịch hằng năm, trường tùy chỉnh và thống kê tháng.

Khi cần khôi phục, bạn dùng nút **Nhập dữ liệu JSON**, chọn file trên máy hoặc dán nội dung JSON vào app.

## Thông báo

App có các loại thông báo chính:

- Thông báo 6:00 sáng với ngày âm, ngày Thập trai, sự kiện hôm nay, ghi chú sắp hết hạn và cảnh báo tài chính.
- Thông báo ghi chú trước giờ hết hạn.
- Thông báo sự kiện lịch đúng ngày và giờ đã đặt.

Sự kiện hằng năm sẽ tự đặt lại thông báo cho năm tiếp theo.

## Dữ liệu và quyền riêng tư

App ưu tiên dùng offline. Dữ liệu được lưu trong máy của bạn, không yêu cầu mạng cho các chức năng chính.

Bạn nên xuất file JSON định kỳ nếu muốn giữ bản sao lưu trước khi đổi máy hoặc xóa dữ liệu.

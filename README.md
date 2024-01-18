# Book-Recommention-System

# Thông tin nhóm : 

| STT | Họ và tên | MSSV |
|-------|-------|-------|
| 1 | Huỳnh Bảo Khang | 20280050 |
| 2 | Võ Thái Bình | 20280007 |
| 3 | Đặng Yến Linh  | 20280058 |
| 4 | Phạm Bảo Cương | 20280010 |

# Mô tả đồ án :
- Đồ án cuối kì môn Python cho Khoa học dữ liệu ( Đại học Khoa học tự nhiên - DDHQG HCM)
- Chủ đề :  Book-Recommention-System. 
- Báo cáo chi tiết được viết trong file pdf, các thành viên sẽ thay nhau thuyết trình bằng file colab. 

# Mục lục: 
1. Lời nói đầu.
2. Loading library and dataset - Đọc thư viện và bộ dữ liệu
3. Exploratory Data Analysis - Phân tích dữ liệu tổng quan
4. Data Visualization - Trực quan hóa dữ liệu
5. Data Pre-processing - Tiền xử lý dữ liệu
6. System Building - Xây dựng hệ thống
7. Tổng kết .

# Tổng quan:
Sách không chỉ là những trang giấy có chữ in. Xuyên suốt lịch sử, sách là nơi ghi chép các sự kiện
và là kho lưu trữ kiến thức chung của nhân loại. Nếu không có văn bản hoặc văn bản in, nền văn
minh nhân loại sẽ không như ngày nay. Những nhà tư tưởng, nhà văn và những người có ảnh hưởng
vĩ đại luôn là những người đọc sách. Họ dành phần lớn thời gian đọc sách để thu thập kiến thức mà
sau này sẽ giúp họ thay đổi thế giới.

Sách có rất nhiều thể loại, và mọi người đều đọc sách với sở thích , nhu cầu, mục đích không giống
nhau. Do đó, hệ thống đề xuất là công cụ lọc thông tin mạnh mẽ có thể giúp chúng ta tận dụng nguồn
dữ liệu dồi dào hiện có để giúp cho việc đưa ra lựa chọn những cuốn sách phù hợp với nhu cầu, sở
thích của mỗi cá nhân một cách dễ dàng hơn. Có hai lợi ích của việc sử dụng hệ thống đề xuất: Một
mặt, nó có thể giảm lượng lớn công sức tìm kiếm sản phẩm của người dùng và giảm thiểu vấn đề quá
tải thông tin. Mặt khác, nó có thể tăng giá trị kinh doanh cho các nhà cung cấp dịch vụ trực tuyến
và trở thành nguồn doanh thu quan trọng.

# Lời kết: 
Hệ thống đề xuất là một công nghệ mới mạnh mẽ để trích xuất giá trị bổ sung cho doanh nghiệp
từ cơ sở dữ liệu người dùng của nó. Hệ thống mang lại lợi ích cho người dùng bằng cách cho phép họ
tìm thấy các nhiều cuốn sách mà họ thích một cách dễ dàng hơn. Ngược lại, họ giúp doanh nghiệp
bằng cách tạo ra nhiều doanh thu hơn.

Về phần báo cáo mà nhóm em đã thực hiện. Từ một bộ dữ liệu chứa thông tin về của hơn 271000
cuốn sách, và các người dùng đã đánh giá nó, nhóm đã trực quan hóa dữ liệu, xử lý các dữ liệu bất
hợp lý, cũng như đưa ra các đề xuất cho người dùng theo nhiều cách khác nhau. Ở đây, nếu người
dùng của chúng ta là người dùng mới, chúng ta sẽ đề xuất cho người dùng dựa trên top 10 các cuốn
sách nổi tiếng nhất. Nếu là người dùng đã từng sử dụng nền tảng trực tuyến của chúng ta, khi họ
nhập vào ID mình thì có thể thấy được top 5 cuốn sách yêu thích nhất của bản thân, bên cạnh đó hệ
thống cũng sẽ đề xuất cho họ những cuốn sách mà họ có thể thích. Ngoài ra, người dùng cũng có thể
tìm kiếm sự đề xuất bằng cách nhập vào tên của cuốn sách , hệ thống sẽ tiến hành đề xuất dựa trên
nội dung, hay dựa trên sự tương đồng của sản phẩm. Bằng các cách lọc này hệ thống sẽ đưa ra cho
người dùng các cuốn sách tương tự cuốn sách mà họ tìm kiếm - nếu cuốn sách mà họ tìm kiếm nằm
trong bộ dữ liệu và có một độ phổ biến nhất định, ngược lại những cuốn sách chưa phổ biến thì sẽ
không có sự đề xuất nào cả.

Nhìn chung về bài làm mà nhóm đã thực hiện code vẫn chưa thật sự tối ưu. Hơn nữa, hệ thống
của chúng ta vẫn còn nhiều thiếu sót, chẳng hạn khi ta có một cuốn sách mới và cuốn sách này chưa
phổ biến nhưng có đánh giá khá tốt, nghĩa là cuốn sách này sẽ có xu hướng có thể nổi tiếng trong
thời gian tới, đối với cách làm mà nhóm thực hiện vẫn chưa cải thiện được trường hợp này. Nhóm em
sẽ cố gắng cải thiện trong thời gian tới để hệ thống được hoàn thiện hơn.

Cuối cùng, đọc sách không chỉ cung cấp tri thức cho chúng ta, mà còn mang lại nhiều lợi ích hơn
thế .Đọc sách giúp ta cải thiện sự tập trung và tăng cường khả năng tư duy, phân tích ; vốn từ của
chúng ta cũng sẽ được mở rộng thông qua việc đọc sách.Đọc sách còn là một hình thức giải trí , giảm
căng thẳng . . . Mọi người nên khắc sâu thói quen đọc sách để cải thiện khả năng đọc, từ vựng và
nhận thức về các chủ đề khác nhau.

Hy vọng bằng cách sử dụng hệ thống đề xuất sách, chúng ta có thể tìm kiếm những cuốn sách phù
hợp với sở thích , nhu cầu dễ dàng hơn, từ đó mà chúng ta có thể nuôi dưỡng thói quen đọc sách

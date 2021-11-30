Trong ví dụ này, chúng ta có 3 “trang” do bộ định tuyến xử lý: trang chủ(Home), trang giới thiệu(About) và trang người dùng(Topics).
Khi bạn nhấp xung quanh vào các <Link> khác nhau, bộ định tuyến sẽ hiển thị <Route> phù hợp.

Ví dụ này cho thấy cách hoạt động của định tuyến lồng nhau. 
Route /topics tải thành phần Topics, thành phần này hiển thị bất kỳ thành phần nào khác của <Route> theo điều kiện trên giá trị path :id.

Trang Topics có <Switch> riêng với nhiều tuyến đường hơn
xây dựng trên đường dẫn URL / chủ đề. Bạn có thể nghĩ về
<Route> thứ 2 ở đây dưới dạng trang "index" cho tất cả topics, hoặc
trang được hiển thị khi không có chủ đề nào được chọn
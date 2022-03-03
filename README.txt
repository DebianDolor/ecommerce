1, flex-wrap: cho phép các items tự đỘng xuống dòng hoặc vẫn luôn nằm trên 1 hàng khi kích thước container thay đổi
2, flex-direction: xác định hướng của main-axis để container sắp xếp các items
3, overflow-x: điều khiển nội dung bị tràn theo chiều ngang (visible, hidden, auto, scroll)
4, opacity: thiết lập độ mờ của phần tử
5, transition: tạo hiệu ứng chuyển đổi
6, z-index: xác định thứ tự xếp chồng nhau của 1 thành phần vị trí
7, cubic-bezier: làm slider
8, font-weight: xác định độ đậm của chữ
9, :hover: dùng để chọn phần tử đang bị di chuột vào

10, querySelector(): trả về phần tử đầu tiên là phần tử con của phần tử mà nó được gọi ra khớp với nhóm bộ chọn được chỉ định.
VD: 
Lấy phần tử <p> đầu tiên trong tài liệu:                    var el = document.querySelector("p");
Thay đổi văn bản của phần tử có id="demo":                  document.querySelector("#demo").innerHTML = "Hello World!";
Lấy phần tử <p> đầu tiên là con của một phần tử <div>:      var el = document.querySelector("div > p");
Tìm phần tử đầu tiên khớp với một lớp:                      var el = document.querySelector(".myclass");
Một bộ chọn phức tạp hơn:                                   var el = document.querySelector("div.user-panel.main input[name='login']");

11, insertAdjacentHTML(position, text): 
        phân tích giao diện của file dưới dạng xml hoặc html, và chèn node vào các vị trí đưỢc chỉ định bởi tham số của hàm
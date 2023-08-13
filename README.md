🥞 CÁC THẺ THÔNG DỤNG TRONG HTML 📑

- ⚙ In đậm chữ: `<b> </b>`
</br> ❗ Lưu ý: có một số thẻ trong HTMl đã có sẵn thuộc tính in đậm như các thẻ từ H1 đến H6.
- ⚙ In nghiêng: `<i> </i>`
- ⚙ Gạch chân: `<u> </u>`
- ⚙ Văn bản: `<p> </p>`
- ⚙ Tiêu đề: `<h1> </h1>` hoặc có thể là h1,h2,h3,..,h6


📄 Thẻ phân trang: `<hr> </hr> `
</br> ❗ Lưu ý: ta cũng có thể sử dụng đúng một thẻ mở vẫn dược `<hr>`.

📸 Thẻ chèn video: `<video src=""></video>`
</br> ❗ Lưu ý: bên trong ***src*** ta sẽ chèn một file video chứ không được chèn link video.

📷 Thẻ chèn ảnh: `<img src="" alt="">`
</br> ❗ Lưu ý: bên trong ***src*** ta có thể chèn một file ảnh được tải về máy hoặc một đường link ảnh online.

🔗 Thẻ liên kết: `<a href=""></a>`
</br> ❗ Lưu ý: bên trong ***href*** ta chỉ có thể chèn link website hoặc một liên kết nào đó.

-------------------------
📔 CÁC THUỘC TÍNH TRONG CSS 🌳

- 🔗 Cách liên kết file HTML và CSS lại với nhau
    + Ở trong file HTML, tại trong cặp thẻ `<head> </head>`, ta sẽ chèn một thẻ như sau `<link rel="stylesheet" href="style.css">`. Trong đó tại ***href*** ta sẽ chèn tên file CSS kèm theo đuôi ***.css***. Ví dụ: style.css

- 🌵 Các cách gọi ra các thẻ bên HTML trong CSS
    + Cách 1:
        + Bên HTML trong thẻ mở HTML ta sẽ chèn thêm một trường `class=""`. Ví dụ: `<h1 class="<tên thay thế>">...</h1>`. Bên trong ***class=""*** ta sẽ đặt một tên thay thế cho nó ***(nickname)*** để gọi từ HTML qua bên CSS
        + Các cách gọi như sau: `.<tên thay thế>`. ❗ Lưu ý là có dấu chấm ở trước
        + Format code như sau chung: 
            + `.<tên thay thế> { <bên trong là các thuộc tính }`
    + Cách 2:
        + Chỉ cần gọi ra tên các thẻ thuộc HTML
        + Ví dụ: `h1 { <các thuộc tính> }`, `p { <các thuộc tính> }`
        + Format code như sau chung: 
            + `.<thẻ HTML> { <bên trong là các thuộc tính }`
        + ❗ Lưu ý: cách 2 là sẽ style (chèn thuộc tính CSS) cho tất cả những thẻ HTMl mà mình đã style cho nó.

- 🧊 Những thuộc tính CSS thông dụng 🥃
    + Sau đây là format code chung khi chúng ta viết
        + ***font-size: <kích cỡ chữ đơn vị px>;*** ***<-- Thuộc tính này sẽ chỉnh kích cỡ của chữ theo đơn vị pixel -->***
        </br> 🧊 Ví dụ: font-size: 18;
        </br> ❗ Lưu ý là có dấu ***";"*** (dấu phẩy) cuối đoạn code, và áp dụng cho các thuộc tính còn lại.

        + ***font-weight: <giá trị cho độ đậm hoặc nhạt của chữ: từ 100, 200, 300, ...900>;*** ***<-- Thuộc tính này sẽ chỉnh độ đậm hoặc nhạt của chữ -->***
        </br> 🧊 Ví dụ: font-weight: 500;

        + ***color: <tên màu theo tiếng anh hoặc mã màu hex>;*** ***<-- Thuộc tính này sẽ chỉnh màu của chữ -->***
        </br> 🧊 Ví dụ: color: white; hoặc color: #fff; 
        </br> (Trong đó #fff là mã màu hex, đại diện cho màu trắng)

        + ***text-align: <các kiểu căn chữ như: left, right, center>;*** ***<-- Thuộc tính này sẽ căn chữ theo định dạng-->***
        </br> 🧊 Ví dụ: text-align: center;
        </br> (Lúc này nó sẽ căn chỉnh nội dung đang được style ra giữa, có thể áp dụng cho chữ, video, hình ảnh, ...)

        + ***font-style: <thuộc tính style cho chữ>;*** ***<-- Thuộc tính này chỉnh style cho chữ in nghiên hoặc những thứ khác -->***
        </br> 🧊 Ví dụ: font-style: italic;
        </br> (Lúc này nó chỉnh chữ sang in nghiêng)

        + ***background: url("<link ảnh hoặc file ảnh được tải về máy>");*** ***<-- Thuộc tính này sẽ chèn background cho website của mình -->***
        </br> 🧊 Ví dụ: background: url("https://wallpaperaccess.com/full/31190.jpg");
        </br> Nếu muốn hiển thị background triệt để hơn không bị lỗi vặt thì ta sẽ sử dụng thêm một số thuộc tính đi kèm như sau: 
            + background-repeat: no-repeat; ***<-- Thuộc tính này sẽ giúp cho ảnh không bị lặp lại hoặc phân đôi ra để chèn vào những chỗ ảnh không hiển thị hết được website (hầu như là do kích thước ảnh nhỏ không bao phủ được hết website nên nó sẽ phân ra nhiều ảnh để chèn hết) -->***
            + background-size: cover; ***<-- Thuộc tính này sẽ chèn background rộng toàn bộ màn hình giúp cho website trở nên toàn diện hơn -->***

        
        




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
        + Bên HTML trong thẻ mở HTML ta sẽ chèn thêm một trường `class=""`. Ví dụ: `<h1 class="<tên thay thế>"> ... </h1>`. Bên trong ***class** ta sẽ đặt một tên thay thế cho nó (nickname) để gọi nó bên CSS
        + Các gọi như sau: `.<tên thay thế>`. Lưu ý là có dấu chấm ở trước
        + Format chung: 
            + `.<tên thay thế> {}`

Các thuộc tính phổ biến trong CSS
color: <tên màu hoặc mã màu>;
font-size: <cỡ chữ đơn vị px>;
font-weight: <độ đậm hoặc mảnh của chữ>;





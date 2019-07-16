# Chương trình JavaScript đầu tiên

Có hai môi trường chủ yếu để chạy JavaScript là trình duyệt và máy chủ (Node.js). Nhằm thuận tiện cho việc học và chạy thử môi trường trình duyệt là sự lựa chọn tốt hơn. Sau khi đã nắm được các kiến thức về JavaScript bạn có thể dễ dàng học Node.js nếu cần.

Trong bài học đầu tiên, chúng ta cùng tạo ra một chương trình in ra thông báo quen thuộc "Hello World!".

Bởi ta chọn chạy trên trình duyệt nên trước tiên cần tìm hiểu cách đưa mã JavaScript vào trong một trang HTML.

## Thẻ "script"

Có thể chèn các chương trình JavaScript vào bất cứ đâu trong một tài liệu HTML bằng cách sử dụng thẻ “script”.

Ví dụ:

```html
<!DOCTYPE html>
<html>

<body>
    <p>Trước thẻ script...</p>
    <script>
        alert(“Hello World!”);
    </script>
    <p>...Sau thẻ script.</p>
</body>
</html>
```

Khi trình duyệt đọc đến thẻ "script" thì mã JavaScript bên trong được chạy. Chương trình JavaScript được đặt bên trong thẻ "script" của chúng ta chỉ gồm một lệnh duy nhất:

```javascript
alert("Hello World!");
```

Lệnh `alert("Hello World!")` có chức năng tạo ra một cửa sổ nhỏ trong đó có thông báo `"Hello World!"` cùng với nút **OK**.

Cách này chỉ thích hợp khi chương trình của chúng ta gồm ít lệnh. Khi chương trình trở nên phức tạp và có nhiều lệnh hơn, ta nên viết mã trong một tệp riêng có phần mở rộng là `.js`. Ta có thể đưa toàn bộ tệp `.js` này vào trong HTML bằng cách sử dụng thuộc tính `src` của thẻ "script" như sau:

```html
<script src="/path/to/script.js"></script>
```

Ở đây `/path/to/script.js` là đường dẫn tuyệt đối tới tệp `script.js` (tính từ thư mục gốc của trang web `/`).


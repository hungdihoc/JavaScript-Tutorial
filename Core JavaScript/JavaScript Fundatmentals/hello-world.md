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


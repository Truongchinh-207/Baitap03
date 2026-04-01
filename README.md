<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Bài 3 Javascript</title>

    <style>
        body {
            margin: 0;
            font-family: Arial;
            background: black;
            color: white;
        }

        h1 {
            text-align: center;
            padding: 10px;
        }

        .nav {
            text-align: center;
            margin: 20px;
        }

        .btn {
            background: gray;
            color: white;
            padding: 10px 20px;
            border: none;
            margin: 5px;
            cursor: pointer;
        }

        .content {
            background: #eee;
            color: black;
            margin: 20px;
            padding: 20px;
            border-left: 5px solid green;
        }

        .content h2 {
            margin-top: 0;
        }

        .content a {
            color: blue;
            text-decoration: none;
        }

        .top-btn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: pink;
            border: none;
            padding: 10px;
            cursor: pointer;
        }
    </style>
</head>

<body>

    <h1>Bài 3: Lập trình Javascript</h1>

    <div class="nav">
        <button class="btn">Bài trước</button>
        <button class="btn">Bài tiếp theo</button>
    </div>

    <div class="content">
        <h2>Nội dung bài học</h2>

        <ol>
            <li>
                <a href="#">Tổng quan về Javascript</a>
                <ul>
                    <li>Giới thiệu chung</li>
                    <li>Vị trí đặt mã Javascript trong HTML</li>
                    <li>Liên kết đến tập tin JavaScript</li>
                    <li>HTML DOM</li>
                </ul>
            </li>

            <li>
                Javascript cơ bản
                <ul>
                    <li>Câu lệnh, khối lệnh</li>
                    <li>Kiểu dữ liệu</li>
                    <li>Các toán tử</li>
                    <li>Biến</li>
                    <li>Cấu trúc điều khiển</li>
                </ul>
            </li>

            <li>
                Hàm Javascript
                <ul>
                    <li>Giới thiệu chung</li>
                    <li>Định nghĩa hàm</li>
                    <li>Gọi hàm</li>
                </ul>
            </li>

            <li>Các chủ đề khác</li>
            <li>Unit testing</li>
        </ol>
    </div>

    <!-- Nút lên đầu -->
    <button class="top-btn" onclick="scrollToTop()">Lên đầu trang</button>

    <script>
        function scrollToTop() {
            window.scrollTo({
                top: 0,
                behavior: "smooth"
            });
        }
    </script>

</body>
</html>

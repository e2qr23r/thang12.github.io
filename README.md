<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Giới thiệu bản thân</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(-45deg, #74ebd5, #9face6, #fbc2eb, #a6c1ee);
            background-size: 400% 400%;
            animation: gradientBG 10s ease infinite;
            margin: 0;
        }

        @keyframes gradientBG {
            0% {background-position: 0% 50%;}
            50% {background-position: 100% 50%;}
            100% {background-position: 0% 50%;}
        }

        .card {
            max-width: 600px;
            background: white;
            margin: 60px auto;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 15px 40px rgba(0,0,0,0.2);
            text-align: center;
            animation: fadeIn 1.5s ease;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        h1 {
            color: #333;
        }

        .typing {
            border-right: 3px solid;
            white-space: nowrap;
            overflow: hidden;
            width: 0;
            animation: typing 3s steps(30, end) forwards, blink 0.7s infinite;
        }

        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }

        @keyframes blink {
            50% { border-color: transparent }
        }

        p {
            font-size: 16px;
            color: #555;
            margin: 10px 0;
            transition: 0.3s;
        }

        p:hover {
            transform: scale(1.05);
            color: #007bff;
        }

        .highlight {
            font-weight: bold;
        }

        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 25px;
            background: linear-gradient(45deg, #007bff, #00c6ff);
            color: white;
            border-radius: 10px;
            text-decoration: none;
            transition: 0.3s;
        }

        .btn:hover {
            transform: scale(1.1);
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }

        .avatar {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin-bottom: 15px;
            animation: zoomIn 1.5s ease;
        }

        @keyframes zoomIn {
            from {
                transform: scale(0);
                opacity: 0;
            }
            to {
                transform: scale(1);
                opacity: 1;
            }
        }

        .footer {
            margin-top: 20px;
            font-size: 14px;
            color: #888;
        }
    </style>
</head>
<body>

<div class="card">
    
    <!-- Avatar -->
    <img src="https://i.imgur.com/4M34hi2.png" class="avatar">

    <!-- Typing effect -->
    <h1 class="typing">👋 Xin chào! Tôi là Thắng</h1>

    <p><span class="highlight">Họ tên:</span> Trần Danh Thắng</p>
    <p><span class="highlight">Năm sinh:</span> 2007</p>
    <p><span class="highlight">Trường:</span> Đại học Duy Tân</p>
    <p><span class="highlight">Học vấn:</span> Sinh viên đại học</p>

    <p><span class="highlight">Sở thích:</span> Lướt web, khám phá công nghệ, tìm hiểu lập trình</p>

    <p><span class="highlight">Kỹ năng:</span> HTML, CSS cơ bản, đang học JavaScript</p>

    <p><span class="highlight">Mục tiêu:</span> Trở thành lập trình viên chuyên nghiệp</p>

    <p><span class="highlight">Liên hệ:</span> 0000000000</p>

    <a href="#" class="btn">Kết nối với tôi</a>

    <div class="footer">
        © 2026 - Trang cá nhân của Thắng
    </div>

</div>

</body>
</html>

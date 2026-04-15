<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>세하치과 로그인</title>
    <style>
        /* 기본 설정 */
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            width: 100%;
            font-family: 'Pretendard', sans-serif;
        }

        /* 배경 이미지 설정 */
        .background {
            background-image: url('배경.jpg'); /* 이미지 파일 경로 */
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            height: 100vh;
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        /* 중앙 흰색 박스 */
        .login-box {
            background-color: rgba(255, 255, 255, 0.95); /* 살짝 투명한 흰색 */
            padding: 40px;
            border-radius: 20px; /* 모서리 둥글게 */
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            text-align: center;
            width: 320px;
        }

        .login-box h2 {
            margin-top: 0;
            color: #333;
            font-size: 1.2rem;
            margin-bottom: 20px;
        }

        /* 비밀번호 입력창 */
        input[type="password"] {
            width: 100%;
            padding: 12px;
            margin-bottom: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-sizing: border-box; /* 패딩 포함 크기 조절 */
            font-size: 1rem;
            outline: none;
        }

        /* 확인 버튼 */
        button {
            width: 100%;
            padding: 12px;
            background-color: #555;
            color: white;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1rem;
            transition: background 0.3s;
        }

        button:hover {
            background-color: #333;
        }
    </style>
</head>
<body>

    <div class="background">
        <div class="login-box">
            <h2>비밀번호 입력</h2>
            <form>
                <input type="password" placeholder="Password" required>
                <button type="submit">확인</button>
            </form>
        </div>
    </div>

</body>
</html>

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>세하치과</title>
    <style>
        /* 기본 여백 제거 */
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            width: 100%;
            font-family: 'Pretendard', sans-serif;
        }

        /* 배경 이미지 설정 (배경.png로 수정 완료) */
        .background {
            background-image: url('배경.png'); 
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
            background-color: rgba(255, 255, 255, 0.9);
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            text-align: center;
            width: 320px;
        }

        h2 {
            margin: 0 0 20px 0;
            font-size: 1.2rem;
            color: #333;
        }

        input[type="password"] {
            width: 100%;
            padding: 12px;
            margin-bottom: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-sizing: border-box;
            outline: none;
        }

        button {
            width: 100%;
            padding: 12px;
            background-color: #555;
            color: white;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1rem;
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

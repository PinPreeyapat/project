<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ข้อมูลส่วนตัว - Profile</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .card {
            background-color: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            text-align: center;
            max-width: 400px;
            width: 90%;
        }
        .avatar {
            width: 100px;
            height: 100px;
            background-color: #764ba2;
            color: white;
            font-size: 40px;
            font-weight: bold;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0 auto 20px;
        }
        h1 {
            color: #333;
            margin-bottom: 5px;
            font-size: 24px;
        }
        .role {
            color: #764ba2;
            font-weight: bold;
            margin-bottom: 20px;
        }
        .info {
            text-align: left;
            background-color: #f8f9fa;
            padding: 15px 20px;
            border-radius: 10px;
            color: #555;
            line-height: 1.8;
        }
    </style>
</head>
<body>

    <div class="card">
        <div class="avatar">P</div>
        <h1>ชื่อ-นามสกุล ของคุณ</h1>
        <div class="role">นักศึกษาสาขาเทคโนโลยีสารสนเทศ</div>
        
        <div class="info">
            <p><strong>รหัสนักศึกษา:</strong> 66xxxxxxx</p>
            <p><strong>ชื่อเล่น:</strong> พิณ</p>
            <p><strong>งานอดิเรก:</strong> เขียนโค้ด, ฟังเพลง, ดูหนัง</p>
            <p><strong>อีเมล:</strong> your.email@example.com</p>
        </div>
    </div>

</body>
</html>

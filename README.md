<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>1번문제</title>
</head>
<body>
    <form action="" method>
        <fieldset>
            <legend>납품자 정보</legend>
            <label for="name">1. 납품자명 : </label>
            <input type="text" id="name" name="name"><br>
            <label for="email">2. email : </label>
            <input type="email" placeholder="answer@naver.com" id="email" name="email"><br>
            <label for="homepage">3. 홈페이지 : </label>
            <input type="url" value="http://" id="homepage" name="hompage"><br>
            <label for="region">4. 지역 : </label>
            <select name="region" id="region" name="region">
                <option value="seoul">서울</option>
                <option value="busan" selected>부산</option>
                <option value="jeju">제주</option>
                <option value="ect">기타</option>
            </select>
        </fieldset>
        <fieldset>
            <legend>납품정보</legend>
            <ul>
                <li>상품명 : </li><input type="text" name="item"><br>
                <li>납품수량 : </li><input type="number"  min="100" placeholder="최소 100" name="quantity"><br>
                <li>납품등급 : </li><input type="range" name="quality"><br>
                <li>기타사항 : </li><textarea name="etc" rows="5" id="" name="etc"></textarea>
            </ul>
        </fieldset>
        <input type="submit" value="send message">
    </form>
</body>
</html>

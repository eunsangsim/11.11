<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>함수 만들기</title>
<script>
function gugudan(n) { // 함수 작성
    let m = parseInt(n); // 문자열 n을 숫자로 바꿈
    if(isNaN(m) || m < 1 || m > 9) {
        alert("잘못입력하셨습니다.");
        return;
    }
    for(let i=1; i<=12; i++) { // i는 1~12까지 반복
        document.write(m + "x" + i + "=" + m*i + "<br>");
    }
}
</script>
</head>
<body>
<h3>구구단 출력 함수 만들기</h3>
<hr>
<script>
    let n = prompt("구구단 몇 단을 원하세요", ""); // n은 문자열
    gugudan(n); // 함수 호출
</script>
</body>
</html>
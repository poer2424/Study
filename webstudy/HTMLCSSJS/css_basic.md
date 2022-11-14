## 기본 선택자

1. ```* { margin:0; }``` 문서의 모든 요소에 스타일 적용
2. ```p { font-style: italic; }``` 특정 태그를 사용한 모든 요소에 스타일 적용
3. ```.bg { background-color: #ddd; }``` 클래스 선택자, 특정 부분만 선택해서 문서 안에 여러번 적용. 

    ```<h1 class="bg">레드향</h1>``` 이런식으로다가 
4. ```#container { width: 500px; }``` id 선택자, 특정 부분만 선택해서 문서 안에 한번만 적용.

    ```<div id="container">내용</div>``` 이런식으로다가

## link로 css관련 코드 .css에 저장하기

```<style>..코드..</style> 내용을 복사후 다른곳에 .css파일만들어서 <style></style>빼고 복붙. 그렇게하고 원래 있던 <style>..코드..</style> 내용 지우고 <link rel="stylesheet" href="000/000.css>```
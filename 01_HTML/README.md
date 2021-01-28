# HTML 기본 학습 

## 웹 페이지 기본 구조와 작성방법 
태그, 요소, 속성의 이해 및 HTML, CSS, JS 작성방법 따라하기 

## 1. HTML5 기본 태그

### head 태그 : 형식 지정
```
<title> : 웹 페이지 제목 설정
<link> : 링크 태그 (외부 css 파일 사용) 속성 [rel="", href="style.css"]
<meta charset='utf-8'> : 문자 인코딩 방식 (utf-8) 
<style> : 스타일 태그 
  사용 예시) h1 { 
              color:white;
              background-color:black;
            }
<script> : 자바스크립트 작성 태그 
  alert("내용") : 경고창 생성
  src="sample.js" 속성으로 외부 자바스크립트 참조 가능  
```

### body 태그 : 내용 작성
```
<h1> ~ <h6> : 제목 글자 태그 1~6
<p> : 문단(paragraph)
<br> : 개행 태그 
<b> : 진하게 (bold)
<i> : 기울어진 (italic)
<ins> : 밑줄 
<del> : 취소선 

<small> : 작은 글씨  
<sup> : 윗첨자
<sub> : 아래첨자
  
<a> : 닻(anchor) 태그, 하이퍼링크 생성  
  속성 [href="URL 주소", target="_self" "_blank" "_parent"]

<ol> : 순서 있는 리스트 (ordered list) 
<ul> : 순서 없는 리스트 (unordered list)
<li> : 리스트 생성 태그 

<table> : 테이블 생성 태그     / 속성 [border="1"] : 테이블 테두리 설정
  <th> : 테이블 제목 행 생성 (table head)
  <tr> : 테이블 행 생성 (table row)
  <td> : 테이블 셀 생성 (table data) 
  속성 [rowspan="2" / colspan="2"] : 테이블 셀 병합 

<image> : 이미지 태그 / 속성 [src="URL" / alt="이미지 대체"]
<audio> : 음악 파일 삽입 태그 / 속성 [src="URL" / controls="controls"]
<video> : 동영상 파일 삽입 태그 / 속성 [src="URL" / controls="controls"]
```

## 2. HTML5 입력 태그 (form 태그 내부에서 동작) 
```
<input type="text" name="userID" value="ID">
[input type]
  text : 텍스트 상자 
  password : 텍스트 상자 (내용 가려짐) 
  file : 파일 업로드 
  checkbox : 다중 항목 선택
  radio : 단일 항목 선택 
  button : 버튼 
  reset : 리셋 버튼
  submit : 제출 버튼(확인)
  
<select>   : 선택컨트롤 (콤보박스)
  <option value=""></option> 
  <option value=""></option> 
  <option value=""></option> 
</select>  
```  
  
  

[이전](https://github.com/BlancBunny/StudyHtml)


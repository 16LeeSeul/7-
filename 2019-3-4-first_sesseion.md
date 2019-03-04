# 웹 개론
***
![1](https://user-images.githubusercontent.com/37537330/53728445-252a2600-3eb6-11e9-91ec-3b101c0e68ef.png)
![2](https://user-images.githubusercontent.com/37537330/53728455-28bdad00-3eb6-11e9-9694-4593143ca34c.png)
![3](https://user-images.githubusercontent.com/37537330/53728457-29eeda00-3eb6-11e9-8628-1a39f9e818d5.png)
![4](https://user-images.githubusercontent.com/37537330/53728460-2c513400-3eb6-11e9-893d-11373bcdc10f.png)
![5](https://user-images.githubusercontent.com/37537330/53728464-2e1af780-3eb6-11e9-92bd-d6b490d133ad.png)
![6](https://user-images.githubusercontent.com/37537330/53728468-2fe4bb00-3eb6-11e9-8e81-f5c70207c8ee.png)
![7](https://user-images.githubusercontent.com/37537330/53728469-3115e800-3eb6-11e9-8e0a-f5b3783fd425.png)
![8](https://user-images.githubusercontent.com/37537330/53728473-32dfab80-3eb6-11e9-8d18-e27820ade1db.png)
![9](https://user-images.githubusercontent.com/37537330/53728479-3410d880-3eb6-11e9-880d-c874a6b5a7d7.png)
![10](https://user-images.githubusercontent.com/37537330/53728483-35420580-3eb6-11e9-82b6-dd0f4e1d59b0.png)
![11](https://user-images.githubusercontent.com/37537330/53728486-36733280-3eb6-11e9-8bd5-9923d9077ce1.png)
![12](https://user-images.githubusercontent.com/37537330/53728489-383cf600-3eb6-11e9-817c-81a39f8c02bd.png)
![13](https://user-images.githubusercontent.com/37537330/53728490-396e2300-3eb6-11e9-8afc-b14343ee2433.png)
![14](https://user-images.githubusercontent.com/37537330/53728493-3b37e680-3eb6-11e9-98d0-60904dafa161.png)
![15](https://user-images.githubusercontent.com/37537330/53728496-3c691380-3eb6-11e9-97cb-368f3a77ee0d.png)
  
  
# html 실습
***
![19](https://user-images.githubusercontent.com/37537330/53730667-f57e1c80-3ebb-11e9-806a-94db96bf5e5b.png)
***
  
## 프로젝트를 만들 폴더 생성하기
    mkdir basic

## index.html 파일 만들기
***
## html로 작성되 문서입니다! 라고 알려주는 태그
    <!DOCTYPE html>
    <html lang="ko"> 
  
  
    </html>
-> "ko" 는 한글로 되어 있다고 알려줌!  

## 화면에 직접 드러나지 않지만 문서를 설명해주는 태그
    <head>
      <meta charset="utf-8">  
      <title> html이 뭘까?</title> 
    </head>
-> html 태그 안에 적어줍니다.  
-> "utf-8"은 인코딩 방식을 알려줍니다.  
-> title 태그는 문서에 드러나지 않지만 한마디로 페이지를 설명해주는 태그입니다!  
어떻게 설명해주는 지 코드를 실행했을 때를 살펴보세요!  

![18](https://user-images.githubusercontent.com/37537330/53730102-468d1100-3eba-11e9-885e-911a6fdf06fd.png)  

## 화면에 직접적으로 등장하는 태그
    <body>
    이게 보일까요?!
    </body>
-> a, img, h1, li 등등 여러가지 태그들이 있습니다.  
-> html은 정형화된 문법으로 반복적으로 사용되기 때문에 태그들을 익혀두면 사용하기 쉽습니다.  

## 기본 틀을 만들어주는 단축키
    !+tab
-> 기본적인 틀을 만들어주는 단축키  
***
## 이 body 태그 안 부분을 여러 태그들로 한 번 꾸며볼까요?
## h1 태그 - 중요 제목을 나타내는 태그
    <h1> 안녕하세요 </h1>
    <h2> 멋쟁이 사자가 되고 싶어요! </h2>
    <p> 저는 한국외국어대학교 바이오메디컬공학부 이슬입니다.
    띄어쓰기가 언제 될까요?<br>
    이제 될까요?! </p>
-> h1 ~ h6 까지 있으며, 숫자가 작은 순서대로 더 중요한 제목을 나타냅니다.  
-> 일반 단락을 나타내는 태그는 p 태그입니다.  
-> br 은 단락 바꿈을 해주는 태그입니다.  
  
## form 태그 - 입력값을 받아들이는 태그
    <form action ="전송받을 대상"> 
        아이디 : <input type="text" name="id">
        비밀번호 : <input type="password" name="pw">
        <input type="submit">
    </form>
-> 사용자들로부터 입력받은 태그들을 전송받을 대상에게 action으로 전송합니다.  
  
![20](https://user-images.githubusercontent.com/37537330/53731086-0a0ee480-3ebd-11e9-93b1-73cd63117ba3.png)

## img 태그 - 이미지를 첨부하는 태그
    <img src=".jpg" width=100>
-> 이미지를 첨부하는 태그로 높이나 너비를 조절할 수 있습니다.

## ol 태그 - 순서가 있는 리스트를 만들어주는 태그
    <ol>
      <li>1학년</li>
      <li>2학년</li>
      <li>3학년</li>
      <li>4학년</li>
     </ol>
-> ordered list 태그 : 순서가 있는 리스트들을 만들어 줍니다.  
-> li 태그 : 리스트 항목들을 적어줍니다.  
-> 단축키 : ol>li*개수 + tab  

## ul 태그 - 순서가 없는 리스트를 만들어주는 태그
    <ul>
      <li>여름 계절학기</li>
      <li>겨울 계절학기</li>
    </ul>
-> unordered list 태그 : 순서가 없는 리스트들을 만들어 줍니다.  
-> li 태그 : 리스트 항목들을 적어줍니다.  
-> 단축키 : ul>li*개수 + tab  

## a 태그 - 링크를 걸어주는 태그
    <a href="1.html">1학년</a>
-> 링크를 걸어주는 태그입니다.  
  
  

# css
***
![17](https://user-images.githubusercontent.com/37537330/53728501-3f640400-3eb6-11e9-80d6-5bf5f304dcb1.png)

## css inline style sheet
    <h2 style = "color:blue">멋쟁이 사자가 되고 싶어요! </h2>
-> 직접 html 태그의 style 속성에 CSS 코드를 넣어 적용시키는 방법입니다.  
처음 적용시킬 때는 편하지만, 후에 복잡한 프로젝트를 할 때 꾸미는 데에 한계가 있으며 재사용이 불가능합니다.

## css internal style sheet
    <style>
      h1 {
        color: red;
      }
    </style>
-> html 문서 안에 스타일 코드를 넣는 방법입니다.  
<style>과 </style> 안에 CSS 코드를 넣습니다.  보통 head 태그 안에 넣으나 어디에 넣어도 잘 적용이 됩니다.  
하지만, 서로 다른 html 문서에 적용할 수 없다는 단점이 있습니다.

## css linking style sheet
    p {
    color: yellow;
    }

    <link rel="stylesheet" href="style.css">
  
-> 별도의 CSS 파일을 만들고 html 문서와 연결하는 방법입니다.  
style.css를 적용시키고 싶은 html 문서에 링크만 걸어주면 되기 때문에 여러 html 문서에 적용시킬 수 있다는 장점이 있습니다.

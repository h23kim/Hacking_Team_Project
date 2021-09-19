기획
===========
### :bulb: 김지선(Prcnsi) 
<br>
우선 해킹을 직간접적으로 보안을 맛보는 것을 목표로
먼저 보안 취약점에 대해 알아보는 시간을 가졌다.

다음으로는 해킹 공방전을 진행하기 위해
팀별로 서버와 DB를 구축해 오라고 과제를 냈다.  
그리고 두 번의 실습을 통해 웹 해킹이 어떻게
이루어지는지 이론을 통해서가 아닌 실습을 통해
해보면서 배울 수 있었다.    
<br>

계기
=====================
필자 보안에 관심이 있어서 학기 초에 교내 정보 보안 동아리(Colony)에 해킹 팀에 들어갔다.

여름 방학이 다가올 무렵,
해킹 팀 인원 중 동아리원을 대상으로
스터디를 진행할 기회가 주어졌다.

그래서 웹 해킹 스터디원을
구글폼으로 받아서
해킹 프로젝트를 진행했다.    

<br>

작업환경
===
  에디터: :cloud:구름 IDE<br>
  백엔드: PHP<br>
  프론트엔드: HTML5,JS,CSS<br>
  데이터베이스: MySQL<br>
  모임: 디스코드

<br>

진행 일지
===========
:bulb: 2021년 7월 7일~8월 12일
<br><br>
| 날짜 | 한 것 |
|:--------|:--------:|
| 7/7 | 브루트 포스 취약점 소개 및 실습 | 
| 7/14 | 7/14까지 서버 구축에 필요한 공부후 정리해서 내 메일로 제출하는 과제 냄 | 
| 7/22 | 팀별로 보안 취약점 주제 맡아서 발표 | 
| 7/22 ~ 8/5 | 팀별로 서버 구축 | 
| 8/5 | PM 8:30 ~ 10:30까지 디스코드에서 서버 켜놓고 1회차 실습 | 
| 8/5 ~ 8/12 | 2회차 공격 준비 (실전적인 공격 방법 및 보안 코드에 대한 공부) |
| 8/12 | PM 8:30 ~ 9:30 디스코드에서 서버 켜놓고 2회차 실습 |

<br>

진행 방식 
=========
이론 다음 실습을 진행하기위해 우선
보안 취약점에 대해 먼저 알아봤다.

다음으로는 서버 구축에 필요한 
공부 웹 언어 문법 데이터베이스 등을 
간략하게 활용법 위주로 정리해서 본인 메일로
제출하는 과제를 냈다. 

그리고 2주를 주고 팀별로 서버를 완성해
오라는 과제를 냈다.

마지막으로 주 1회씩 2번의 실습을 끝으로
실전적 보안을 맛보는 시간을 가졌다.

<br>

결과 화면
================
## :bulb: 5조 웹 완성 화면(Team_5)
![image](https://user-images.githubusercontent.com/86015194/130646281-eb382ebe-fa29-4d75-9095-a403ee8e083f.png)<br>
![image](https://user-images.githubusercontent.com/86015194/130646450-f7fdf927-bde7-4905-b71c-5cad9bae74bf.png)<br>
![image](https://user-images.githubusercontent.com/86015194/130646537-f47d3913-80ee-42ff-816a-9edc45800a1c.png)<br>
![image](https://user-images.githubusercontent.com/86015194/130646619-3a1bedd7-60e4-4226-bb32-e1ab96636e23.png)<br>

![image](https://user-images.githubusercontent.com/86015194/130646756-79ff5d3b-8309-4cd3-a524-efb76eab3cad.png)

<br><br><br>

## :bulb: DB 구축
<img src="https://user-images.githubusercontent.com/86015194/130646957-83355778-3bcf-4cc7-998a-94c64ade0a51.png" width="400" height="200"><img src="https://user-images.githubusercontent.com/86015194/130647180-3f8534e6-827d-4c33-85d5-1d4f313ac04b.png" width="400" height="200">
<img src="https://user-images.githubusercontent.com/86015194/130647286-76228127-e2c4-4d69-a83d-67834d33dae0.png" width="800" height="400">

<img src="https://user-images.githubusercontent.com/86015194/130647120-901366a5-95b2-4c09-916d-b2956ebf650a.png" width="400" height="200"><img src="https://user-images.githubusercontent.com/86015194/130647047-b2ca27b1-892a-480c-9b2b-e3e55610b561.png" width="400" height="200">



<br><br><br>

## :bulb: 실습 화면

<img src="https://user-images.githubusercontent.com/86015194/130647792-a24f9b79-efd4-4638-b43f-a6afe80bde56.png" width="400" height="200"><img src="https://user-images.githubusercontent.com/86015194/130647841-5f57bf61-fec4-4810-871b-be5009feee2e.png" width="400" height="200">

!


<br><br>

:bulb: 5조 팀원
============
* 17학번 박준영<br>
* 20학번 김채은<br>
* 21학번 김지선<br><br>




Error
==============
## 1st Error

처음 회원가입이 되어야 로그인도 되고 로그인이 되어야 글 작성도 할 수 있는데 회원가입하는 부분
sign_up.php에서 회원가입을 해도 DB에 저장이
안 되어서 2,3일 하루종일 
이것만 고민했던 기억이 난다. <br><br>

알고보니 DB와 웹을 연동하는데 기초지식이
부족해서 생긴 문제였다.

이는 DB의 비밀번호를 설정해주지 않고 HTML안에
<form>태그 안의 input 태그의 name 속성에서
대소문자가 안 맞아서 저장이 안 되었던 것이었다.

별 게 아니여서 허무했지만 이 과정을 통해
앞으로 웹과 데이터베이스 연동은 쉽게
할 수 있을 것 같다.<br><br>

이 에러를 해결한 뒤로는 약간 모든 코드에 적용되는 내용이여서 그리고 로그인이든 글 작성이든 삭제든 수정이든 기본 개념이 비슷해서 어렵지 않게 할 수 있었다.
<br><br>

## 2nd Error
다음으로는 뼈대를 완성하고 CSS를 적용할 때 있었다.
CSS는 오픈소스를 가져다 썼다.<br>
그런데 가져오는 것 까진 하겠는데
이게 적용이 안 되는 에러가 있었다.

## <CSS 적용 전>
![image](https://user-images.githubusercontent.com/86015194/130645341-06efc8be-9f02-4a8a-add0-609bf4eb1ee1.png)
  
## <CSS 적용 후>
 ![image](https://user-images.githubusercontent.com/86015194/130645502-ce972d11-5a35-4074-9cdf-7b8e9c222eb9.png)

이는 여러 번 수정하다 보니 해결됐다. 알고보니 css는 include로 부르면 안 되고 
<link>태그의 href 속성으로 불러와야 했다.
물론 <link>태그는 <head> 안의 영역에 
존재해야한다.

별거 아니지만 각각 위치에 대해 엄격하게
문법적으로 맞추지 않으면 작동하지 않는 것을 보고<br>
기초를 더욱 충실히 해야겠다고 느꼈다.

<br>
  
  
  
  
 ## 소스코드 구조 !!
  (추가 예정)

느낀점
=====================
  -구름 IDE가 신기했고 바로 다른 사람이 코드 작성하         는게 보이는게 재밌었다.
  
  -일부러 보안에 취약한 언어 PHP를 사용했으나 (보통 워게임의 언어가 PHP) 실제로 현업에 사용되는 
리액트 Vue.js와 같은 라이브러리리나 프레임워크 기반 서버를 구축했다면 좀 더 실질적으로 보안을 맛볼 수 있지 않았을까 하는 아쉬움이 있다. 이는 다음 프로젝트 기획시 참고해야겠다.

  ps. 프로젝트 진행에 많은 도움을 주신 연구실 선배님들 
보실진 모르겠지만 감사했습니다!


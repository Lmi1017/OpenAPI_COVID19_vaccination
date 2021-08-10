# 대한민국 COVID-19 예방접종센터
## 📂 폴더
  - covid19_status_info : toy project <b>(main)</b>
  - img : 사진 폴더함
  - test_f : 오류 및 에러 찾기, 기존 파일 비교, 연습 및 실슬 폴더
  - center_map : 미니지도 페이지 폴더

<br>

## 👩‍💻 목적
- Ajax를 이용한 OpenAPI 활용 기초 연습
- Kakao 지도 api 활용
- JQuery와 Javascript 활용 
- Bootstrap 활용

<br>

## 🛠사용기술🛠 
<p>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/></a> &nbsp
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/></a> &nbsp
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/></a> &nbsp
<img src="https://img.shields.io/badge/JQuery-0D47A1?style=flat-square&logo=JQuery&logoColor=white"/></a> &nbsp
<img src="https://img.shields.io/badge/Bootstrap-673AB7?style=flat-square&logo=Bootstrap&logoColor=white"/></a> &nbsp
</p>

<br>

## 🔏 해결 및 추가 : 기록
### 👩‍💻 오류 
- 2021.08.06 
  1. > Failed to load resource: the server responded with a status of 404 (Not Found) ▶ 해결
  2. > Failed to find a valid digest in the 'integrity' attribute for resource 'https://code.jquery.com/jquery-3.2.1.min.js' with computed SHA-256 integrity 'hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4='. The resource has been blocked. ▶ 해결
  3. > Found 2 elements with non-unique id #validationServer04: ▶ 해결
- 2021.08.07
  1. > Failed to load resource: the server responded with a status of 401 (Unauthorized) ▶ 해결
  2. > Uncaught ReferenceError: kakao is not defined 
      at maptest.html:13 ▶ 해결


<br>

### 📃 추가 및 기록
- 2021.08.06
  1. `appointment.html` 대리 예약 추가 <b>▶ ⚒완료🛠</b>
  2. `index.html` 디자인 수정중
- 2021.08.07
  1. `index.html` 디자인 수정 <b>▶ ⚒완료🛠</b>
  2. `maptest.html` kakao 지도api 연습 <b>▶ ⚒완료🛠</b>
  3. `center_map` 폴더 및 지도 추가 & `appointment.html` 하이퍼링크를 이용한 미니(지도)창 추가 <b>▶ ⚒완료🛠</b>
  3. 주석정리
- 2021.08.10
  1. `center.html` ajax(통신)호출시 로딩화면 출력 <b>▶ ⚒완료🛠</b>

<br>

### 📚 ajax : 간단 요약
- api 정보 불러오기  
```javascript
type: "GET",
 url: "https://api.odcloud.kr/api/15077586/v1/centers?page=key입력",
data: {},
```
- table과 a 태그 생성 & 정보 삽입
```javascript
let temp_html = `<tr>
                    <td>${id}</td>
                    <td>${facilityName}</td>
                    <td>${centerName}</td>
                    <td><a href="/center_map/center${num}.html" onclick="window.open(this.href, '_blank', 'width=900, height=700'); return false;">${address}</a></td>
                    <td>${phoneNumber}</td>
                </tr>`;

```
<br>

### 🎫 이미지 출처
- 질병관리청 : http://www.kdca.go.kr/index.es?sid=a2  

<br>

## 💻 시연
### 🔊 사진
![](https://images.velog.io/images/daymoon_/post/da97fd28-40ad-4600-a5c0-b009d6dc165b/image.png)  

![](https://images.velog.io/images/daymoon_/post/477e57ed-8030-486b-bd27-b04c228ae2f9/image.png)  

![](https://images.velog.io/images/daymoon_/post/f1479cc6-7b9f-45fa-a78f-2250530f28c4/image.png)

![](https://images.velog.io/images/daymoon_/post/7471a569-6875-4408-9ab7-9e275ce860b6/image.png)  

<br>

### 🔊 영상(gif)
<img width="80%" src="https://user-images.githubusercontent.com/83294927/128598754-b1c8b552-d28c-42e1-83c2-a31c657bb6f4.gif"/>  

<img width="80%" src="https://user-images.githubusercontent.com/83294927/128598755-3f189a89-6da1-4a32-a084-412ee88fa5f2.gif"/>  

<img width="80%" src="https://user-images.githubusercontent.com/83294927/128598901-fbb9ba77-2f13-42c5-a9e6-7405ffea8a97.gif"/>
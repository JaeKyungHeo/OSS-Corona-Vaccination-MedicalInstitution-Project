[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🔍 About the Project
> 현재 코로나19로 인해 얼마전부터 위탁의료기관을 통한 신종 코로나바이러스 감염증(코로나19) 접종이 본격 시작되었습니다. 
이에 따라, 원하는 지역의 예방접종 위탁의료기관을 간편하게 조회할 수 있는 웹서비스를 개발하였습니다. 
이 프로젝트는 매 정각 1번씩 갱신되고 있는 위탁의료기관의 데이터(점심시간,진료시간,휴무여부,주소,연락처 등)를 카카오맵을 활용하여 제공합니다.

## ✅ Open API
- [카카오맵 API](https://apis.map.kakao.com/web/)
- [공공데이터 포털에서 제공하는 코로나19 예방접종 위탁의료기관 정보 API](https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15081240)

## 💻 User Interface 
<img src="https://user-images.githubusercontent.com/84301776/127002637-50025e8f-9f98-4c4f-a94b-13c46b49eb46.png"  width="1000" height="500">
<img src="https://user-images.githubusercontent.com/84301776/127003107-9fd049e3-dd76-4b0a-b606-6939d28c5c4a.png"  width="1000" height="500">
   
## 📋 기술 스택
- Nodejs
- Html(-> ejs(Embedded JavaScript))
- Css
- JavaScript
- Express
- AWS EC2
 

## ✏️ 프로젝트 사용 방법
1. cloning
```
http://khuhub.khu.ac.kr/2018103585/Corona_Vaccination_Medical_Institution.git
```

2. install npm packages
```
cd Corona_Vaccination_Medical_Institution
npm install
```
3. add API key
> Fill {} with API Key
```
const $key = '{Corona Vaccination Medical Institution API key}' //(app.js)
```
```
<script type="text/javascript" src="https://dapi.kakao.com/v2/maps/sdk.js?appkey={Kakao map API Key}&libraries=services"></script> //(index.ejs)
```
4. Execute 
```
node app.js
```

## 💻 Project Architecture
<img src="https://user-images.githubusercontent.com/84301776/127003221-e4201c23-ef5e-41c4-b874-937e9d402bdb.png"  width="1000" height="600">

  
   
## ✨ Contributors 

| 김서연 | 허재경 |
| :----: | :----: |
| [@ksy991018](https://github.com/ksy991018) | [@JaeKyungHeo](https://github.com/JaeKyungHeo) |
 

# Withinstar.com
<p align="center">
  <img src="./images/image06.png">
</p>

## 소개
<p align="center">
  <img src="./images/image02.png" width="48%">
  <img src="./images/image01.png" width="48%">
  <br>
  <img src="./images/image03.png" width="48%">
  <img src="./images/image04.png" width="48%">
</p>

[**Withinstar.com**](www.withinstar.com)은 사용자들이 **Instagram**을 통해 비밀스럽게 관심을 표현하고 매칭을 이루도록 돕는 웹 애플리케이션입니다.
Flask를 기반으로 개발되었으며, **MongoDB**를 활용한 데이터 관리와 **암호화 시스템**으로 사용자 정보를 안전하게 보호합니다.

---

## 주요 기능
1. **Instagram ID 매칭 시스템**
   - 사용자는 자신의 Instagram ID와 관심 있는 상대방의 ID를 입력합니다.
   - 입력된 정보는 암호화되어 저장되며, 매칭이 이루어질 경우에만 두 사용자에게 알림이 전송됩니다.

2. **매칭 알림 및 후속 기능**
   - 매칭 성공 시, Instagram DM을 통해 알림을 제공합니다.
   - 추가 지목을 원하는 경우, 결제를 통해 다른 사용자를 선택할 수 있습니다.

3. **사용자 친화적인 인터페이스**
   - 후킹 멘트와 직관적인 디자인으로 서비스를 쉽게 이용할 수 있습니다.
   - 광고 배너와 팝업 메시지로 시각적 완성도를 높였습니다.

4. **데이터 보안**
   - 환경 변수로 MongoDB URI와 암호화 키를 관리하여 보안을 강화했습니다.
   - 데이터를 암호화/복호화하는 Fernet 라이브러리를 사용하여 민감한 정보를 안전하게 처리합니다.

5. **Google AdSense 통합**
   - 사이트에 광고를 배치하여 수익 창출 가능성을 확장했습니다.

---

## 기술 스택
- **Backend**: Flask, Flask-PyMongo
- **Frontend**: HTML, CSS, Jinja2 Template
- **Database**: MongoDB
- **Security**: Python Cryptography Fernet
- **Other Integrations**: Google Analytics, Google AdSense, Gmail SMTP

  ![image05](./images/image05.png)

---

## 관련 자료
![1](./images/1.png)
![2](./images/2.png)
![3](./images/3.png)
![4](./images/4.png)
![5](./images/5.png)
![6](./images/6.png)
![7](./images/7.png)
![8](./images/8.png)
![9](./images/9.png)
![10](./images/10.png)
![11](./images/11.png)
![12](./images/12.png)
---

## 프로젝트 구조
```plaintext
Withinstar/
│
├── templates/             # HTML 템플릿 파일
│   ├── base.html
│   ├── index.html
│   ├── success.html
│   ├── error.html
│
├── static/                # 정적 파일
│   ├── css/
│   │   └── style.css
│   ├── images/
│   │   └── logo1.png
│   │   └── instagram.png
│   │   └── loading.gif
│   ├── js/
│   │   └── language-toggle.js
│
├── app.py                 # Flask 메인 애플리케이션
├── requirements.txt       # Python 의존성 패키지
├── .gitignore             # 제외 목록
├── .env                   # 환경 변수 파일
└── README.md              # 프로젝트 설명 파일

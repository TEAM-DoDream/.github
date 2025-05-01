<div align="center">
  <img src="https://github.com/user-attachments/assets/c9ab5923-9a59-4b10-ad1c-3b636ac467a3">
</div>

## 👥 Team Members

<table align="center">
  <tr>
   <td align="center">
      <a href="https://github.com/cywin1018">
        <img src="https://github.com/cywin1018.png" width="100px;" alt="최용원"/><br />
        <sub><b>최용원</b></sub>
      </a><br />
      <sub>Frontend</sub>
    </td>   
    <td align="center">
      <a href="https://github.com/Chasyuss">
        <img src="https://github.com/Chasyuss.png" width="100px;" alt="박채수"/><br />
        <sub><b>박채수</b></sub>
      </a><br />
      <sub>Frontend</sub>
    </td>
    <td align="center">
      <a href="https://github.com/chyun7114">
        <img src="https://github.com/chyun7114.png" width="100px;" alt="윤창현"/><br />
        <sub><b>윤창현</b></sub>
      </a><br />
      <sub>Backend</sub>
    </td>
    <td align="center">
      <a href="https://github.com/sseongeun">
        <img src="https://github.com/sseongeun.png" width="100px;" alt="조성은"/><br />
        <sub><b>조성은</b></sub>
      </a><br />
      <sub>Backend</sub>
    </td>
  </tr>
</table>

## 두드림 소개

## ✔️ ERD

## ✔️ System Architecture
![image](https://github.com/user-attachments/assets/ecaede0f-6962-4763-86c7-014e37fe23ff)
## 멘토님 질문 3가지

### Front-End

### Back-End
1. 저희는 CLOVA Studio의 chat-completion API를 이용해 맞춤 직업 추천 시스템을 구현하고 있습니다. 
프롬프트 내부에 직업 목록, 설명, 사용자의 온보딩 질문에 대한 답을 함께 전달하는 구조라 사용되는 토큰 수가 많은데요, 프롬프트 구조 내에서 불필요한 토큰을 줄이거나 토큰 효율을 높이는 팁이나 전략이 있을까요?

2. 현재, training과 recruit 패키지 내에서 고용노동부 API 및 사람인 API를 통해 훈련과 채용 정보를 가져오고 있습니다. 
변동이 적은 데이터를 대상으로 Redis 기반 캐싱 + 분산락으로 중복 호출을 방지하고 있는데, 
이 전략이 적절한지 궁금하고, 추가로 2계층 캐싱(DB + Redis)을 적용하는 게 좋은 방법인지 알려주실 수 있으신가요?

3.

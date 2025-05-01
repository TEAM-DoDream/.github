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
1. 저희 팀은 CLOVA Studio의 chat-completion API를 활용해 맞춤 직업 추천 시스템을 구현하고 있습니다. 
현재 프롬프트 내에서 직업 목록과 설명을 함꼐 전달하고 있어서 사용되는 토큰 수가 꽤 많은데, 이런 프롬프트 구조 내에서 불필요한 토큰 사용을 줄이거나 토큰 효율을 높일 수 있는 팁이나 전략이 있을까요?
<br>
2. 현재 training과 recruit 패키지 내에서 외부 API(고용 24, 사람인 채용정보 API)를 통해서 데이터를 받아오는 중입니다.
각각 공공기관에서 주최하는 훈련과정과, 여러 기업의 채용정보를 받아오는데 외부 API를 쓰는 중인데, 이 때 DB에 데이터를 직접 저장하지 않기 위해 레디스를 사용하여 캐싱을 통해 저장하는 방식으로 개발했습니다.
여기서 쓰인 캐싱 전략이 올바른지 궁금하고, 또한 더 나아가 2계층 캐시를 적용하여 일부 데이터를 DB에 저장하여 사용하는 것까지 적용해야하는지 궁금합니다.
(현재 API 중복 호출을 막기 위한 분산락을 적용한 캐싱을 사용하고 있고, 각 API로 불러오는 정보는 1일 정도의 시간 안에서는 불변하는 데이터입니다.
<br>
3.

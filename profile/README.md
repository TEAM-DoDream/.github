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

## Swagger-URL
[두드림 API 명세서](https://dodream.p-e.kr/swagger-ui/index.html#/)

## ✔️ ERD
<img width="1011" alt="스크린샷 2025-05-01 오후 4 27 53" src="https://github.com/user-attachments/assets/d9b153fb-3b60-44f8-bbf9-03e924426b5c" />


## ✔️ System Architecture
![image](https://github.com/user-attachments/assets/72def8a0-6f4c-4ff6-8c10-d1e3205a2bde)

## 멘토님 질문 3가지

### Front-End
1. Lighthouse 점수를 올리기 위한 최적화 작업은 어떤 우선순위로 접근하는 게 좋을까요? 혹시 실무에서 효과적이었던 팁이 있으실까요?

2. 전역 상태 관리는 편리하지만 리렌더링 측면에서 오버헤드가 있어서 요즘에는 지역 상태로 바꾸는 경우가 많다고 들었습니다. 이런 상황에서는 상태를 어떤 기준으로 전역과 지역으로 나눠서 관리하는 게 좋을까요?

3. 코드가 구조적으로 잘 구성되어 있는지, 특히 일관성과 재사용성 측면에서 어떤 부분을 체크해보면 좋을지 조언 부탁드립니다!
### Back-End
1. 저희는 CLOVA Studio의 chat-completion API를 이용해 맞춤 직업 추천 시스템을 구현하고 있습니다. 
프롬프트 내부에 직업 목록, 설명, 사용자의 온보딩 질문에 대한 답을 함께 전달하는 구조라 사용되는 토큰 수가 많은데요, 프롬프트 구조 내에서 불필요한 토큰을 줄이거나 토큰 효율을 높이는 팁이나 전략이 있을까요?

2. 현재, training과 recruit 패키지 내에서 고용노동부 API 및 사람인 API를 통해 훈련과 채용 정보를 가져오고 있습니다. 
변동이 적은 데이터를 대상으로 Redis 기반 캐싱 + 분산락으로 중복 호출을 방지하고 있는데, 
이 전략이 적절한지 궁금하고, 추가로 2계층 캐싱(DB + Redis)을 적용하는 게 좋은 방법인지 알려주실 수 있으신가요?

3. 현재 저희는 NCP 서버에 Redis와 MySQL을 각각 Docker 컨테이너로 실행하고 있습니다. 별도의 클라우드 서비스를 사용하지 않기에 비용을 줄일 수 있고, 구축 방법이 간단하여 해당 방법을 사용했습니다.
다만 성능, 장애 대응 등 여러 측면에서 볼 때, 클라우드 서비스와 현재 방식 중 어떤 것을 더 적합한지 궁금합니다!

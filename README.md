![image](/docs/main.jpg)
# ❤ MEET:Z 소개
> "팬과 스타의 MEET을 이뤄주는 영통팬싸 플랫폼"

## 📅 개발 기간
**24.07.08 ~ 24.08.16** (7주)

(SSAFY 공통 프로젝트 - 웹 기술 트랙)

## 👨‍💻 팀원

| 손다인 | 이승원 | 김태연 |
| -------- | -------- | -------- | 
| 팀장 | 팀원 | 팀원 |
| BE | BE | BE | FE | FE | FE |
| - 유저관리<br>- 미팅일정<br>- 웹소켓 채팅<br> | - Infra<br>- 미팅 자동화 시스템   | - 비속어 필터링<br>- 팬 경고, 신고 기능 |

| 강창우 | 신민경 | 서민수 |
| -------- | -------- | -------- |
| 팀원 | 팀원 | 팀원 |
|  FE | FE | FE |
|- 유저관리<br>- 미팅일정<br>- 웹소켓 채팅<br>- 팬 경고/신고<br> |- Infra<br> - UI/UX디자인<br> - 미팅 자동화 시스템<br>  | - UI/UX 디자인<br>- 퍼블리싱<br>- 블랙리스트 |

# 2. 🔍 개발 환경

## 2-1. 환경 설정

  ### 👨‍💻 **Frontend**
  
    - Vite
    - React
    - TypeScript
    - Zustand (상태 관리)
    - Tailwind CSS
    - React Router Dom
    - Stomp JS (웹소켓 통신)

  ### 👨‍💻 **Backend**

    - Spring Boot
    - Spring Security

  ### 👨‍💻 **DB**

    - MySQL
    - MariaDB
    - Redis
    - Naver Cloud

  ### 👨‍💻 **CI/CD**
  
    - AWS EC2
    - Jenkins
    - Docker
    - nginx
    
  ### 👨‍💻 **Web RTC**

    - openvidu 2.25

  ### 👨‍💻 **협업 툴**

    - Git Lab
    - Jira
    - Mattermost
    - Discord

## 2-2. 개발문서
  ### **아키텍처**
  ![image](/meetz-back/meetz/src/main/resources/Architecture.png)

  ### **ERD**
  ![D110_까까_ERD](/meetz-back/meetz/src/main/resources/ERD-image.png)


# 3. 💗 주요 기능

## 주요 기능
### **💞 매니저**
![image](/docs/manager_1.gif)
![image](/docs/manager_2.gif)
![image](/docs/manager_3.gif)
### **💞 팬**
![image](/docs/fan_1.gif)
![image](/docs/fan_2.gif)
![image](/docs/fan_3.gif)
### **💞 가수**
![image](/docs/star_1.gif)
# 4. 🛠 구현 방안
## 4-1. 스케줄링 알고리즘
![image](/docs/algorithm.gif)

# 5. ⚙ Git Flow
## 🖱 과정 요약

    1. 깃랩에서 이슈 생성
    2. 로컬 develop 브랜치에서 `git pull origin develop` 하기
    3. `git checkout -b feature/기능-#이슈번호`
    4. 새로 만든 브랜치에서 열심히 작업한다.
    5. `git add “파일”` → 파일을 개별로  add 
    6. `git commit -m “커밋메시지”`
    7. git add → git commit 반복
    8. [`git push origin feature/기능-#이슈번호`]
    9. create merge request
    10. git merge

## 🗨 Commit Convention

    📌 feat: 새로운 기능 추가, 기능 수정, 삭제
    
    📌 fix: 오류, 버그 수정
    
    📌 docs: README나 WIKI 같은 문서 개정
    
    📌 style: 코드 스타일 혹은 포맷 등에 관한 커밋
    📌 refactor:  코드 리팩토링에 대한 커밋 (쓸모없는 코드 삭제 등)
    📌 test : 테스트 코드 수정에 대한 커밋
    
    📌 config : 모듈 설치, 설정 파일 추가, 라이브러리 추가, 패키지 구조 수정 등
    
    📌 chore: 간단한 코드 수정(오탈자 등), 내부 파일 수정 등 기타 변경 사항
    
    📌 rename: 파일 이름 변경이 있을 때 사용
    
    📌 remove : 파일 삭제
# 6. 💕 기대효과
  ### **👩‍💼 엔터 3사 재직자**
    일일이 시간을 고지하고 시간에 맞춰 
    전화를 걸고 끊는 등의 번거로움을 덜 수 있어 
    소속사 팬 마케팅팀 영통 팬싸 운영 업무의 
    리소스를 크게 절감 할 수 있을 것 같습니다. 
  ### **👩‍💼 엠넷 서바이벌 프로그램 출신 아이돌 팬매니저**
    지금까지는 실시간 모니터링을 위해서
    스피커폰으로 연결하거나, 옆에서 이어폰을 꼽고 
    같이 들어야 했기 때문에 불편한 점이 컸어요.
    또 팬분들에게 대기순서에 관한 문의가 많이 들어오는데,
    대기시간과 진행순서를 확인시켜줄수 있다니 정말 편리할 것 같아요
  ### **👩‍💼 CJ ENM IP커머스 사업팀**
    영통 팬싸 화면 캡쳐를 통한 
    굿즈 판매로 부가 수익을 기대해볼 수 있는 점이 좋은 것 같습니다. 
    영통 팬싸는 음반판매를 촉진하기 위한 이벤트인데
    이 기능을 통해서 영통팬싸 자체도 엔터사의 새로운 BM이 될 수 있을 것 같아요.
    플랫폼의 기능적 측면 외에도, 아티스트 IP 기반 BM 다각화를 꾀할 수 있다는 점에서 
    굉장히 매력적인 프로덕트라고 생각합니다. 
 ### **👩‍💼 엠넷 관계자**
     예상치 못한 기술적인 이슈로
     CS가 안 생길 수 없고 운영상 어려움이 있어 부담이 되었는데, 
     운영상에 있어서 효율적이고 부담이 적어질 것 같습니다. 
     그리고 제공해주는 기능들이 팬 친화적이라서 
     팬 선호도가 높을 것으로 보입니다. 

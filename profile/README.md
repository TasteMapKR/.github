<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=D8BFD8&height=250&section=header&text=🚩TasteMap&fontSize=80&fontAlign=70&fontAlignY=40&fontColor=2F4F4F&animation=fadeIn" style="width: 100%; height: auto;" />
</p>

# 📌나만의 먹거리루트 : TasteMap (개인 프로젝트)
**✏내가 만들고 싶은거 만들기 프로젝트✏**
<br>
2024/08/01 ~ 2024/08/21(3주)
## 📖아이디어 
- 자신만의 먹거리 코스를 주소 기준으로 적어 루트를 생성
- 코스의 루트별로 지도에 표시하여 정해진 루트를 표시
- 사용자가 그걸보고 평가를 내릴 수 있음
  
<br>

## 아쉬운점
- CSS 생성형 AI 도움
- 유효성 검사의 미흡
- JWT 토큰 관리를 위한 Redis 구현
<br>

## 배운점
**소셜 로그인 REST API 서버 구현**:
- 소셜 로그인 기능을 REST API 기반으로 설계 및 구현하여 사용자 인증 간소화.
- JWT를 사용하여 사용자 세션을 관리 및 민감한 정보를 암호화하여 저장.

**JWT 기반 보안 관리**:
- 사용자 인증과 권한 관리를 위한 JWT 발급 및 검증 시스템 설계.
- 민감한 정보는 데이터베이스에 암호화하여 저장하며, 토큰은 HTTP-only 쿠키로 저장하여 보안성 강화.
- REFRESH 토큰의 보안을 강화하기 위해 데이터베이스를 이용한 검증 및 관리 구현.

**QueryDSL을 활용한 조회 최적화**:
- QueryDSL을 사용하여 복잡한 쿼리를 효율적으로 처리하고, 데이터 조회 성능을 최적화.

**Amazon S3와 엔티티 PK를 활용한 이미지 관리**:
- Amazon S3에 이미지 파일을 업로드하고, 엔티티의 PK를 이용해 파일을 구조화하여 손쉽게 이미지 접근이 가능하도록 구현.
- EC2와 Docker compose를 이용한 배포 과정 자동화

**GitHub Actions 및 Docker를 활용한 CI/CD 자동화**:
- GitHub Actions와 Docker를 활용하여 빌드 및 배포 자동화 파이프라인을 구축.
- Docker Hub에 이미지 빌드 및 푸시, 테스트 자동화.

**EC2와 Docker Compose를 이용한 배포 자동화**:
- AWS EC2와 Docker Compose를 사용해 애플리케이션의 무중단 배포 자동화.
- Docker Compose를 활용해 여러 컨테이너 기반의 애플리케이션을 효율적으로 관리.


  <br>
  
## 기능 소개

| 페이지          | 설명                                                                                     |
|-----------------|------------------------------------------------------------------------------------------|
| 메인            | 주요 기능이나 홈 화면을 표시하는 페이지로, 애플리케이션의 중심적인 역할을 합니다. |
| 로그인          | 사용자 인증 기능으로 OAuth2.0을 이용한 소셜 로그인 네이버, 구글을 지원합니다. |
| 코스            | 사용자가 만든 코스와 루트를 확인할 수 있는 페이지입니다. |
| 생성            | 코스와 루트를 만드는 페이지로 모든 값이 필수 값입니다. |
| 평가            | 사용자가 해당 코스에 대해 평가하는 페이지로, 통계를 통한 확인도 가능합니다. |

| 기능   | 이미지                                      |
|--------|---------------------------------------------|
| 메인   | ![Main](../img/Main.jpeg)                  |
| 로그인 | ![Login](../img/Login.jpeg)                |
| 코스   | ![Course](../img/Course.jpeg)              |
| 생성   | ![Create](../img/Create.jpeg)              |
| 평가   | ![Feedback](../img/Feedback.jpeg)          |

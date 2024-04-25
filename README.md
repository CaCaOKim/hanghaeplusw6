# 항해플러스 백앤드 4기 W6: e-Commerce for CI/CD

### 브랜치 전략
- 서버 환경
  - dev: 개발한 기능들을 테스트하는 서버
  - staging: 실제로 운영되는 서버와 같은 환경에서 테스트하는 서버
  - prod: 실제 운영되는 서버
- 브랜치
  - feature: 기능별로 하나씩 생성되는 브랜치. 개발자가 개발한 파일들을 수시로 Push하여 저장해놓는다.
  - develope: feature브랜치들을 merge하여 dev서버에 배포하여 테스트하는 브랜치.
  - staging: dev서버에서 테스트를 끝낸 코드들을 merge하여 main브랜치에 merge하기 전 최종으로 staging서버에 배포하여 테스트 하는 브랜치.
  - main: prod서버에 배포되어 실제로 운영되는 코드들을 담은 브랜치.


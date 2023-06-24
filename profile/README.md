# 발료 마루
발표 마루는 음성 분석을 통해 발표 능력을 향상시키도록 도와주는 웹 어플리케이션입니다.

## 요구사항 명세서
https://ionized-philosophy-330.notion.site/dc4ffffb452b4eda8b3d4ff4085c6ef3

## 상세 설계서
https://ionized-philosophy-330.notion.site/d116260279ed433fbf7493989bf74c90

## 최종 보고서
https://ionized-philosophy-330.notion.site/f7713eae182c494baba5e68ee137f9a3?pvs=4

## GitHub flow branch 전략
- Main(master) branch, feature branch 두 개의 branch로 운영
- Feature branch에서 작업 후 main branch에 merge한다.(pull request)

### 사용 이유
- 다른 branch 전략에 비해 간단하다.
- 소규모 작업이기에 복잡한 브랜치 전략이 필요하지 않다.

### Branch convention
- Branch 이름은 kebab-case를 사용한다.
- 역할을 쉽게 알아볼 수 있도록 feat-login, fix-split-voice 처럼 기능을 구분하도록 맨 앞에 단어를 다음과 같은 단어를 사용한다. 
  - feat, fix, setting, chore, refactor, …
- 작업하기 전에 issue를 먼저 작성한다.

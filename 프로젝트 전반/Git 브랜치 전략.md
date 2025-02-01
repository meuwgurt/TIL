# Git 브랜치 전략

### Git 브랜치 전략
<hr>

브랜치 전략이란 여러 개발자가 하나의 저장소를 사용하는 환경에서 저장소를 효과적으로 사용하기 위한 work-flow 이다.<br>
브랜치의 생성 / 삭제 / 병합 등 git 의 유연한 구조를 활용하여 각 개발자들의 혼란을 최대한 줄이며 다양한 방식으로 소스를
관리하는 역할을 한다.

즉, 브랜치 생성에 규칙을 만들어서 협업을 유연하게 하는 방법론을 말한다.

(1) git - flow<br>
(2) github - flow

### 1️⃣ Git - Flow 전략
<hr>

기본적인 가지의 이름은 아래의 5가지로 구분
`feature` / `develop` / `release` / `hotfix` / `master`

5가지 중 `항상 유지되는 메인 브랜치` (master) (develop) 2가지와 `Merge되면 사라지는 보조 브랜치` (feature)
(release) (hofix) 3가지로 구성된다.
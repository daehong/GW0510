Instruction
===========

아래와 같은 미션을 팀원들끼리 수행하시면 됩니다. 총 두 개의 세션으로 진행합니다.

Session 1
=========

요구사항:

* 각 팀원의 이름으로 브랜치를 만들어서 원래 있는 파일을 총 다섯개 이상 고쳐서 커밋을 세 개 만들고 만들어진 브랜치를 GW0510 리모트에 push 하기 (팀원간 GW0510 리모트에서 pull 해서 잘 만들어졌는지 서로 코칭해주기, github에서도 보이는지 확인)
* 팀에서 두명씩 편을 짜서 두 명의 브랜치 머지해서 GW0510 리모트에 push
* 팀에서 인티그레이터를 뽑아 전체 팀원들의 작업을 하나의 브랜치로 머지하고 GW0510 리모트에 push

위 작업을 할 때 아래의 조건을 충족시키기

* FF merge (fast-forward merge) 해보기 (팀원끼리 증명하기)
* Recursive merge 해보기 (어떻게 증명을 하죠?)
* Merge conflict 만들어서 merge 해보기 (conflict 조건)

잘 진행되었는지 회고

Session 2
=========

요구사항: Session 1 에서 만들어진 작업을 기반으로

* 로컬의 repo 를 지우고 다시 받아보기
* 필요 없는 브랜치 다듬어내기 (예. 팀원 이름으로 올린 브랜치 필요한가?), 그리고 왜 그렇게 다듬어냈는지 설명하기
* 최종 작업한 내용을 release_[우리팀] 이름으로 브랜치를 만들어 remote 로 올리기 (예.1팀의 최종 작업 브랜치 이름은 release_team1 이다)
* 해당 릴리즈 브랜치에는 [우리팀]_v1.0 태그 만들어서 GW0510 remote 에 올리기 (예. 1팀은 team1_v1.0 태그 만들어서 GW0510)

옆 팀과 협업하기

* 1팀은 2팀과(A팀), 3팀은 4팀 5팀(B팀)과 작업한 내용을 합치고 GW0510 리모트에 push
* A팀과 B팀은 서로의 내용을 합쳐서 master 브랜치로 머지하고 GW0510 리모트에 push

Etc
===

* 체크인을 재미있게 했습니다.
* 체크인에서 세 가지 이야기를 했습니다.

Week 2
=============

* Fork
 * Fork란 다른 사용자의 Repository를 자신의 계정으로 복사하여 독립적으로 수정하고 관리할 수 있게 해주는 기능이다.
   이때, Original Repository에 어떤 변화가 생기면 Forked된 Repository에 반영할 수 있다.(fetch, rebase를 통해 가능하다고 한다.)
   반대로 내가 수정한 코드를 Original Repository에 반영하고 싶으면 Pull Request를 Original Repository에 요청하고
   관리자가 승인하면 commit, merge되어 Original Repository에 반영된다.

=============

* Star
 * 관심 있는 Repository나 프로젝트에 star를 달아 “북마크”와 같이 관리

=============

* Issue
 * Repository에서 작업 계획, 토론 및 추적을 위해 활용
 * Github사이트에서 Issue 탭에서 생성가능
 * Title과 Description 추가 필요

===============

* Branch
 * 기존 브랜치에서 분기되어 생성되는 별도의 작업 공간
 * Merge를 통해 main branch와 병합가능
 * merge전 Pull Request를 통해 새로운 변경을 제안하고 병합시 발생하는 충돌을 해결하는 과정이 필요하다.(ex. 코드리뷰)
 * Merge의 3가지 옵션
  1. Merge Commit
  - 두 브랜치를 공통 부모로 하는 새로운 commit ‘E’를 만듦
  - A, B, C의 커밋이 그대로 main 브랜치로 병합
  2. Squash and Merge
  - Squash : 여러개의 commit을 하나의 commit으로 합치는 것을 뜻함
  - Squash Merge는 병합할 branch의 모든 commit을 하나의 commit으로 Squash한 새로운 commit을 mian branch에 추가하는 방식으로 병합하는 것을 의미한다.
  - Squash를 하게 되면 모든 commit 이력이 하나의 commit으로 합쳐지며 사라진다는 점을 주의
  3. Rebase and Merge
  - main branch의 최신 commit으로 base를 변경
  - commit들이새로운 commit으로 변경되면서 commit hash가 변경되기에 주의 필요(무수한 충돌이 발생할 수 있음)



=================
<https://github.com/swoon427/2024-1-Beginner-Study/pull/2>
Week 3
=============

# git log
 * commit 기록을 최신 순으로 확인
 * --oneline 옵션을 사용하면 각 커밋을 한 줄에 요약

# Commit id
 * commit의 식별을 위해 사용하는 40자 길이의 16진수
 * 중복 확률은 2의 80제곱 분의 1
 * SHA-1 해시 함수를 이용

# HEAD
 * HEAD는 현재 작업 중인 위치를 가리킨다
 * 현재 작업중인 브랜치의 가장 최근 commit
 * 다음 commit의 base가 되는 commit
 * 새로운 commit이 생기면 HEAD도 변경

# commit --amend
 * 마지막 commit의 내용에 변경이 있을 때 사용
 * 완전히 새로운 commit으로 대체
      * commit id가 바뀜
 * vim으로 진입하여 commit 메세지를 수정하게 됨
 * ‘--no-edit’ option으로 commit 메시지 수정 없이 commit 수정 가능
 * ! 다른사람이 작업 기반으로 삼고있는 commit은 amend하지 않도록 주의 !

# reset
 * commit을 제거하는데 사용
 * git log를 통해서 나오는 commit id를 통해 commit 지정 가능
 * 세가지 옵션이 존재함
      --soft : 바로 commit 가능한 부분으로 돌아감
      --mixed : add 부터 시작해야함
      --hard : commit 삭제

# revert
 * commit을 제거하지 않고 되돌림
 * 되돌리기 위한 새로운 commit 생성됨
 * reset은 commit을 삭제하기 때문에 revert가 더 안전함
Week 4
=============

# 브랜치 관리의 중요
 * 서로의 작업에 영향을 주지 않기 위해 브랜치의 분리 필요
 * 각 브랜치가 어떤 작업을 위해 존재하는지 구분 필요
 * main 브랜치의 안전한 관리 필요

# 브랜치 보호 규칙
 * 승인 없이 Pull equest를 병합할 수 없도록 제한 가능
 * 특정 브랜치에 Push 가능자를 제한 가능
 * 브랜치 보호 규칙을 이용해 브랜치를 안전하게 관리 가능

# Git Flow vs GitHub Flow
 * 브랜치 전략의 방법들로 현재 GitHub Flow를 많이 사용함

# Git Flow
 * Main Branches
 1. main(master)
 2. develop
 * Supporting branches
 1. feature
 2. release
 3. hotfix

# Git Flow - main
 * 프로젝트 생성 시 기본으로 생성되는 브랜치
 * 영원히 존재하는 첫 번째 브랜치
 * 병합될 때마다 제품의 새로운 버전이 탄생
 * main1라는 1름 대신 master를 사용하기도 함

# Git Flow - develop
 * feature 브랜치의 기반이 됨

# Git Flow - feature
 * develop 브랜치에서 분기하여 작업
 * 기능 개발 완료 후 다시 develop으로 병합

# Git Flow - release
 * 배포 준비를 위한 브랜치
 * 자잘한 버그를 수정하고 QA작업을 함
 * develop 브랜치에서 분기하여 main 브랜치로 병합

# GitHub Flow
 * 수시로 배포되는 상황이 Git Flow와 안 어울리는 것을 개선하기 위해 고안한 방법
 * Main과 Feature 브랜치만을 이용

# GitHub Flow - main
 * 항상 배포 가능 상태로 유지
 * main으로 병합 전에 충분한 test 필요

# GitHub Flow - feature
 * Git Flow와 달리 이외 브랜치들을 구분하지 않음
 * main에서 분기하여 작업 후 다시 main으로 병합
 * 브랜치의 목적을 이름에 잘 담아야 함





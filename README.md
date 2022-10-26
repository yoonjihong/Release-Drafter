# Release-Drafter
Release Drafter를 사용한 프로젝트 릴리즈 버전 관리 자동화 workflow 샘플


Github Action - Release Drafter    
https://github.com/marketplace/actions/release-drafter



# Version 설명
PR시 설정된 label에 따라 자동 버전 변경
  - major : 첫번째 버전업 v1.0.0
  - minor : 두번째 버전업 v0.1.0
  - patch : 세번째 버전업 v0.0.1
  
# Release 노트
Merge된 PR의 각 내용들을 아래 카테고리에 설정된 레이블별로 자동으로 분류

  - title: '🚀 Features'    
    labels: 'feature'
  - title: '🐛 Bug Fixes'    
    labels: 'bugFix'
  - title: '🧰 Maintenance'     
    label: 'chore'

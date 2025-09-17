HelloWorld

git init : local repository 시작

git config --global [user.email / user.name] "email or name"
: 이 프로젝트 저자 설명

git add 파일경로
: 업로드할 버전에 파일 추가하기

git commit -m "설명"

git log
: 해당 프로젝트 버전 로그 출력

git checkout [commit id(최소 7자리)]
: 해당 버전 덮어씌움
: commit id 부분에 - 들어가면 가장 최신버전

git remote add origin [주소]
: github 프로젝트와 연결

git branch -M [이름]
: branch : 프로젝트 버전 가지치기 (개별 파일 수정 & 통합 위해)
: 가지 매인은 main이라고 함 (기둥)


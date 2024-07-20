# practice

## main 브랜치 파일을 작업 후 prac 브랜치로 푸시 하는 방법
### 1. 로컬 레포지 토리 클론
git clone \<your-repository-url>    
cd \<your-repository-directory>

### 2. 브랜치 확인 및 main 브랜치로 전환
git checkout main

### 3. 최신 상태로 업데이트
git pull origin main

### 4. 작업 진행

### 5. 변경 사항 커밋
git add .
git commit -m "작업 내용에 대한 설명"

### 6. prac 브랜치로 전환
git checkout prac

### 7. 변경사항 푸시
git push origin prac

## GitHub에서 main 브랜치에 있는 파일을 prac 브랜치로 가져오는 방법
### 1. 로컬 레포지토리 클론
git clone \<your-repository-url>    
cd \<your-repository-directory>

### 2. prac 브랜치로 전환
git checkout prac

### 3. main 브랜치의 변경 사항을 prac 브랜치로 병합
git pull origin main
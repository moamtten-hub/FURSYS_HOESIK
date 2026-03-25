[README.md](https://github.com/user-attachments/files/26230783/README.md)
# 송파 회식 장소 추천 사이트

GitHub Pages에 바로 업로드할 수 있는 정적 사이트 구조입니다.

## 파일 구성
- `index.html`: 메인 사이트 파일

## GitHub Pages 업로드 방법

### 1) GitHub에서 새 저장소 만들기
- GitHub 로그인
- 오른쪽 상단 `+` 클릭
- `New repository` 선택
- 저장소 이름 입력
  - 예: `songpa-hoesik`
- `Public` 선택
- `Create repository` 클릭

### 2) 이 폴더의 파일 업로드
- 방금 만든 저장소로 이동
- `Add file` → `Upload files`
- 이 폴더 안의 `index.html` 파일을 드래그해서 업로드
- 아래 커밋 메시지 입력
  - 예: `first deploy`
- `Commit changes` 클릭

### 3) GitHub Pages 켜기
- 저장소 상단 `Settings` 클릭
- 왼쪽 메뉴에서 `Pages` 클릭
- `Build and deployment` 섹션에서
  - `Source`: `Deploy from a branch`
  - `Branch`: `main`
  - 폴더: `/ (root)`
- `Save` 클릭

### 4) 배포 주소 확인
- 잠시 후 Pages 주소가 생성됩니다.
- 주소 형태 예시:
  - `https://github아이디.github.io/songpa-hoesik/`

### 5) 수정 반영
- `index.html`을 다시 업로드해서 덮어쓰기 후 커밋하면 사이트가 자동 갱신됩니다.

## 커스텀 포인트
- 식당 데이터 수정: `index.html` 안의 `RESTAURANTS` 배열 수정
- 기본 역 변경: `selectedStation = "오금역"` 부분 수정
- 제목/설명 변경: 상단 hero 영역 문구 수정

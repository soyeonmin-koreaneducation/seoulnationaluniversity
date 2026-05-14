# Soyeon Min — CV Site

GitHub Pages로 자동 배포되는 CV 사이트입니다.

## 배포 방법

### 1단계: GitHub 저장소 생성
1. [github.com](https://github.com) 로그인
2. 우측 상단 `+` → **New repository**
3. Repository name: `cv` (또는 원하는 이름)
4. **Public** 선택 (GitHub Pages 무료 사용 조건)
5. **Create repository** 클릭

### 2단계: 파일 업로드
1. 저장소 페이지에서 **"uploading an existing file"** 클릭
2. `index.html` 파일 드래그 앤 드롭
3. **Commit changes** 클릭

### 3단계: GitHub Pages 활성화
1. 저장소 상단 **Settings** 탭
2. 왼쪽 메뉴 **Pages** 클릭
3. Source: **Deploy from a branch**
4. Branch: **main** / `/ (root)` 선택
5. **Save** 클릭

### 4단계: 사이트 확인
약 1~2분 후 아래 주소로 접속:
```
https://{GitHub username}.github.io/{repository name}/
```
예시: `https://soyeonmin.github.io/cv/`

---

## CV 내용 수정 방법

1. GitHub 저장소에서 `index.html` 클릭
2. 우측 상단 연필 아이콘(✏️) 클릭 → 직접 편집
3. **Commit changes** 클릭
4. 약 1분 후 사이트에 자동 반영

---

## 파일 구조

```
/
└── index.html   ← CV 전체 (사진 포함, 단일 파일)
```

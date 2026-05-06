# Jaeyu Kim — Website

## 폴더 구조
```
├── index.html                  ← 홈페이지 (CSS+JS 모두 포함)
├── css/style.css               ← 디자인
├── js/
│   ├── about.js                ← ✏️ About 수정
│   └── projects/               ← ✏️ 프로젝트마다 파일 하나
│       ├── basics-office.js
│       └── ...
└── images/
    ├── architecture/
    │   ├── basics-office/      photo-1.jpg ~ photo-5.jpg / draw-1.jpg ~ draw-5.jpg
    │   └── memorial-park/
    ├── interior/
    ├── design/
    ├── research/
    ├── furniture/
    └── drawing/
```

## 프로젝트 추가
1. `images/[카테고리]/[이름]/` 폴더 만들고 이미지 넣기
2. `js/projects/[이름].js` 파일 추가 (기존 파일 복사해서 수정)
3. `index.html` 에서 `const PROJECTS = [];` 바로 아래에 해당 js 파일 내용 붙여넣기

## 이미지 교체
`images/[카테고리]/[프로젝트]/` 폴더에 `photo-1.jpg`, `draw-1.jpg` 형식으로 교체
개수 변경시 `js/projects/[이름].js` 의 `photos`, `draws` 숫자도 수정

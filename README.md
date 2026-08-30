# 꼬꼬마어린이집 홈페이지

## 📸 사진 업데이트 방법 (핵심!)

이제부터는 **파일명을 그대로 유지한 채, 같은 이름의 새 사진으로 덮어쓰기만 하면** 자동으로 홈페이지에 반영됩니다.
(예전처럼 파일명에 날짜를 넣고 index.html을 같이 고칠 필요가 없어졌습니다.)

`/images` 폴더 안에 있는 아래 파일명 그대로, 새 사진 파일로 교체해서 GitHub에 업로드(커밋)하면
Netlify가 자동으로 감지해서 1~2분 안에 사이트에 반영합니다.

| 파일명 | 위치 |
|---|---|
| main-photo.webp | 메인 상단 대표 사진 |
| activity-01.webp ~ activity-17.webp | "꼬꼬마의 하루" 활동 사진 17장 |
| program-music.webp | 코앤코 음악놀이 |
| program-physical.webp | 트니트니 체육놀이 |
| program-english.webp | 뮤엠영어 |
| teacher-interaction.webp | 교사-영아 상호작용 사진 |
| meal-record.webp | 급식 기록 사진 |
| teacher-learning-community.webp | 교직원 학습공동체 사진 |
| safety-experience.webp | 소방안전체험 사진 |
| director.webp | 원장 사진 |
| map-guide.webp | 오시는 길 지도 이미지 |
| kkomakids-logo-header.webp | 상단 로고 |
| kkomakids-logo-full.webp | 하단 로고 |

> ⚠️ 새 사진 파일도 **같은 파일 형식(.webp)과 같은 파일명**으로 저장해서 올려주세요.
> 파일명이 다르면 자동으로 반영되지 않습니다.

## 🔄 자동 배포가 되려면 (최초 1회 설정 필요)

이 저장소가 Netlify와 "Git 연동"되어 있어야 파일을 바꿔서 올렸을 때 자동으로 배포됩니다.
아직 연동 전이라면 아래 순서로 진행해주세요.

1. 이 폴더(GitHub 저장소)를 GitHub에 업로드
2. Netlify 관리자 화면 → 기존 kkomakids 사이트 → **Site configuration → Build & deploy → Link repository**
   (또는 "Import from Git"으로 새로 연결한 뒤, 기존 도메인을 그대로 이전)
3. 연결 후에는 GitHub에서 파일만 바꿔 커밋하면 Netlify가 자동으로 재배포합니다.

## 📱 스마트폰에서 사진 교체하는 방법

1. GitHub 앱(또는 모바일 웹) 접속 → 이 저장소 → `images` 폴더로 이동
2. 교체할 파일 탭 → 우측 상단 편집(연필) 아이콘 → "Upload files"로 같은 이름의 새 사진 업로드
3. 커밋(Commit changes)하면 자동으로 사이트에 반영됩니다.

## 📂 현재 필요한 작업

이번 정리에서 사진 원본 파일 자체는 포함되어 있지 않습니다 (코드/텍스트 파일만 전달받음).
`/images` 폴더에 원본 사진들을 위 표의 파일명 그대로 넣어주셔야 사이트가 정상적으로 뜹니다.
(기존에 갖고 계신 원본 사진 파일이 있다면 그 파일들을 이 이름으로 저장해서 넣어주시면 됩니다.)

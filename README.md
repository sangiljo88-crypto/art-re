# NWG Art-Re | 수입차 복원의 예술, 아트리

## 프로젝트 개요
수입차 복원 전문업체 **아트리(Art-Re)**의 랜딩페이지입니다.
Art + Restore = Art-Re. 47년간 16만대 복원. 센터에서 실패한 차량이 마지막으로 오는 곳.

## 완성된 기능

### 페이지 구조 (14개 섹션)
1. **Navigation** — 고정 네비게이션 바 (로고, 전화, CTA)
2. **Hero** — 브랜드 소개, 카운터(162,537대+), 메인 CTA
3. **Philosophy** — 기술 철학 인용문
4. **Founder** — 대표 엄준식 47년 경력 소개
5. **History** — 1977~현재 타임라인
6. **Villain** — 경쟁 대안 비교 (센터/동네업체/저가업체 vs Art-Re)
7. **Difference** — 4가지 핵심 차별점
8. **Services** — 4가지 복원 서비스
9. **✨ Before/After Gallery (NEW)** — 인터랙티브 드래그 슬라이더 비포/애프터 갤러리
10. **Testimonials** — 3개 고객 후기
11. **CTA** — 전환 유도 섹션
12. **FAQ** — 5개 자주 묻는 질문 (아코디언)
13. **Contact** — 위치/운영시간/연락처
14. **Footer** — 사업자 정보

### Before/After 갤러리 (신규 추가)
- **인터랙티브 드래그 슬라이더**: 마우스/터치로 좌우 드래그하여 비포/애프터 비교
- **3개 복원 사례**:
  - BMW 화이트 — 프론트 펜더 긁힘/페인트 박리 복원
  - BMW 블루 — 리어 범퍼 광범위 긁힘/손상 복원
  - Bentley 그린 — 프론트 범퍼 찍힘/크랙 복원
- **탭 네비게이션**: 차종별 탭으로 사례 전환
- **복원 통계 표시**: 작업 기간, 컬러매칭, 이색 클레임

### 기술 기능
- GSAP 애니메이션 + ScrollTrigger
- 골드 파티클 애니메이션
- 복원 카운터 (localStorage 기반, 일 3~12대 증가)
- FAQ 아코디언
- 반응형 디자인 (모바일/태블릿/데스크톱)
- Tally.so 폼 팝업 연동

## 파일 구조
```
index.html              (메인 페이지 - 모든 CSS/JS 인라인)
images/
  ├── bmw-white-before.jpg    (BMW 화이트 복원 전)
  ├── bmw-white-after.jpg     (BMW 화이트 복원 후)
  ├── bmw-blue-before.jpg     (BMW 블루 복원 전)
  ├── bmw-blue-after.jpg      (BMW 블루 복원 후)
  ├── bentley-front.jpg       (벤틀리 전면 사진)
  ├── bentley-before1.jpg     (벤틀리 복원 전 1)
  ├── bentley-before2.jpg     (벤틀리 복원 전 2)
  └── bentley-after.jpg       (벤틀리 복원 후)
README.md
```

## 진입 URI
- `/` 또는 `/index.html` — 메인 랜딩페이지
- `#gallery` — Before/After 갤러리 섹션 바로가기

## 외부 서비스
- **Google Fonts**: Playfair Display, Noto Serif KR, Noto Sans KR
- **Font Awesome 6.4**: 아이콘
- **GSAP 3.12 + ScrollTrigger**: 애니메이션
- **Tally.so**: 상담 신청 폼 (ID: LZPqzj)

## 향후 개선 사항
- [ ] 추가 복원 사례 사진 (포르쉐, 벤츠 등)
- [ ] 복원 과정 영상 섹션
- [ ] 카카오톡 채팅 연동
- [ ] 네이버 지도 임베드
- [ ] SEO 최적화 (구조화 데이터, OG 태그)
- [ ] Google Analytics 연동

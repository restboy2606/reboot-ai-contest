# 안심체크 제안서 웹

2026 리부트 AI 활용대회용 **심사 설명 페이지**입니다.  
본진 서비스 코드와 분리된 restboy 계정 제출 패키지입니다.

## 링크

- 웹 제안서(이 레포): GitHub Pages 배포 후 공개
- 라이브 서비스: https://anshim-check.vercel.app
- 서비스 코드: https://github.com/restboy2606/anshim-check

## 역할 분리

| 레포 | 역할 |
|---|---|
| `restboy2606/anshim-check` | 실제 서비스 본진 |
| `restboy2606/reboot-ai-contest` | 대회 제안서/설명 페이지 |

## 구성

```text
reboot-ai-contest/
├─ index.html
├─ styles.css
├─ assets/
│  ├─ hero-app.svg
│  ├─ hero-flow.svg
│  └─ hero-arch.svg
└─ README.md
```

## 디자인 메모

Behance 인기 헬스/시니어/SaaS 케이스에서 공통으로 보인 방향:

- 밝은 배경 + 강한 블루 액센트
- 큰 타이포 / 넉넉한 여백
- 카드형 섹션 구성
- 과한 장식보다 신뢰감과 가독성 우선

안심체크 브랜드 블루(`#2F6BFF` 계열)에 맞춰 재해석했습니다.

## 로컬 확인

```bash
# 정적 파일이므로 아무 서버나 가능
npx --yes serve .
```

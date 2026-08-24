# 📦 Public Assets & Media CDN

이 저장소는 웹사이트, 블로그, Google Apps Script(GAS), 이메일 템플릿 등에 사용되는 **공개 이미지 및 정적 문서(에셋)**를 호스팅하기 위한 전용 저장소입니다.

---

## 📂 폴더 구조

```text
assets/
├── images/           # 이미지 파일 (JPG, PNG, SVG, WebP 등)
│   ├── kfta-therapy.jpg
│   └── 한국패션테라피협회.jpg
└── docs/             # 공개 문서 및 템플릿 파일 (PDF, TXT, JSON 등)
```

---

## 🔗 CDN URL 사용법 (jsDelivr)

GitHub에 푸시된 파일은 jsDelivr CDN을 통해 초고속 캐싱되어 무료로 제공됩니다.

### 1. 이미지 URL 규칙
- **기본 포맷:** `https://cdn.jsdelivr.net/gh/<USERNAME>/<REPO_NAME>@main/images/<FILE_NAME>`
- **예시 (KFTA 이미지):**  
  `https://cdn.jsdelivr.net/gh/lumiere-nam/assets@main/images/kfta-therapy.jpg`

### 2. 문서 URL 규칙
- **예시:**  
  `https://cdn.jsdelivr.net/gh/lumiere-nam/assets@main/docs/<FILE_NAME>`

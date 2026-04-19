# vrc-texture-generator

VRChat에서 활용할 텍스처를 생성하거나 가공하기 위한 웹 도구 프로젝트입니다. 현재 저장소 구조상 Nuxt 기반 프런트엔드 프로젝트가 `nuxt/` 디렉터리에 들어 있으며, 생성형 텍스처 또는 편집형 텍스처 워크플로를 위한 초기 형태로 보입니다.

## 현재 상태

루트 README에는 설명이 거의 없지만, 실제 구현은 `nuxt/` 하위 프로젝트에 포함되어 있습니다.

## 기술 스택

- Nuxt 2
- Vue 기반 UI
- Element UI
- Axios
- CodeFlask
- Sass

## 프로젝트 구조

```text
nuxt/
├─ nuxt.config.js
├─ package.json
├─ .eslintrc.js
├─ stylelint.config.js
└─ ...
```

## 주요 스크립트

`nuxt/package.json` 기준:

```bash
yarn dev
yarn build
yarn start
yarn generate
yarn lint
```

## 배포

정적 생성 후 `gh-pages` 브랜치로 배포하는 스크립트가 포함되어 있습니다.

```bash
yarn deploy
```

## 예상 활용 시나리오

- VRChat용 텍스처 생성/편집 실험
- 웹 기반 텍스처 제작 툴 프로토타이핑
- 코드 편집 UI를 포함한 시각적 도구 개발

## 보완이 필요한 부분

- 루트 README에 실제 기능 설명 보강
- `nuxt/` 내부 페이지 구조와 사용 예시 문서화
- 입력/출력 포맷, 생성 결과물 예시 추가

## 라이선스

이 저장소는 `LICENSE` 파일을 포함하고 있습니다. 자세한 내용은 해당 파일을 확인하세요.

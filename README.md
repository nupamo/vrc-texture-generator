# vrc-texture-generator

VRChat에서 활용할 텍스처를 생성하거나 가공하기 위한 웹 도구 프로젝트입니다. 현재 저장소 구조상 Nuxt 기반 프런트엔드 프로젝트가 `nuxt/` 디렉터리에 들어 있으며, 생성형 텍스처 또는 편집형 텍스처 워크플로를 위한 초기 형태로 보입니다.

## 현재 상태

루트 README에는 설명이 거의 없지만, 실제 구현은 `nuxt/` 하위 프로젝트에 포함되어 있습니다. 현재 기준으로는 완성된 제품보다는 오래된 프로토타입 성격이 더 강합니다.

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

## 현재 기준의 한계

- Nuxt 2 기반이라 스택이 다소 오래됨
- 루트 README만 봐서는 실제 기능이 잘 드러나지 않음
- 입력/출력 예시, 스크린샷, 사용 흐름 설명이 부족함

## 다시 살릴 때 추천 방향

이 프로젝트를 계속 발전시킬 생각이라면 아래 중 하나를 선택하는 게 좋습니다.

1. 현재 구조 유지, README와 예시만 보강
2. 최신 프런트엔드 스택으로 재구성
3. 핵심 기능만 분리해 더 작은 도구로 재출발

## 보완이 필요한 부분

- 루트 README에 실제 기능 설명 보강
- `nuxt/` 내부 페이지 구조와 사용 예시 문서화
- 입력/출력 포맷, 생성 결과물 예시 추가

## 라이선스

이 저장소는 `LICENSE` 파일을 포함하고 있습니다. 자세한 내용은 해당 파일을 확인하세요.

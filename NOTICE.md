# 서드파티 고지 (Third-party notices)

이 프로젝트에 포함되어 함께 배포되는 외부 에셋과 라이브러리입니다. 앱 안의 "크레딧 · 라이선스" 화면과 같은 내용이며, 새 에셋을 넣을 때는 `src/lib/credits.ts`에도 항목을 추가하세요.

## 에셋
- **Microsoft Rocketbox — Female_Adult_03** (`public/models/rocketbox_female_03.glb`)
  MIT License, Copyright (c) 2020 Microsoft. 출처: https://github.com/microsoft/Microsoft-Rocketbox
  변환·수정: FBX→GLB, 텍스처 축소, 스페큘러 맵→거칠기 맵. 라이선스 원문: `public/models/LICENSE-Rocketbox.md`

## 라이브러리
three.js, React, @react-three/fiber, @react-three/drei, zustand (MIT), Draco 디코더 `public/draco` (Apache-2.0, Google).

## 상표
이 앱에서 언급하는 제품명·상표는 각 소유자의 것이며, 이 프로젝트는 그들과 제휴·보증 관계가 없습니다. 물리적 정확성을 보장하지 않는 근사 시뮬레이터입니다.

## 데이터
- **조명 모디파이어·어태치먼트 제품 카탈로그(339종)** (`src/data/modifierCatalog.json`): 프로젝트 소유자가 제공한 제품명·분류 목록입니다. 제품 이미지·제조사 측정값은 포함하지 않으며, 앱에서는 이름에서 읽은 크기·각도로 만든 추정 프리셋으로만 사용합니다.

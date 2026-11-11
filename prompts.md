# 테스트에 쓴 프롬프트 모음

- 생성 모델: stable-diffusion-v1-5/stable-diffusion-v1-5 + ControlNet v1.1 OpenPose
- 공통 설정: seed 1234, steps 20, guidance 7.5, 크기 512x768
- 네거티브 프롬프트: blurry, low quality, deformed

| 결과 파일 | 포즈 | 포즈 강도 | 프롬프트 |
|---|---|---|---|
| output_01.png | pose_01 | 1.0 | A factory worker in a white safety helmet and navy work uniform, full body, inside a bright manufacturing plant. Soft morning light from tall windows on the left. Photorealistic documentary photography, muted industrial color palette. |
| expA_prompt2.png | pose_01 | 1.0 | An astronaut in a white space suit, full body, on the gray surface of the moon with the Earth in the black sky. Hard sunlight from the right. Photorealistic cinematic still. |
| expA_prompt3.png | pose_01 | 1.0 | A chef in a white uniform and a tall chef hat, full body, in a cozy restaurant kitchen. Warm light from above. Watercolor illustration, soft pastel colors. |
| output_02.png | pose_02 | 1.0 | A factory worker in a white safety helmet and navy work uniform, full body, inside a bright manufacturing plant. Soft morning light from tall windows on the left. Photorealistic documentary photography, muted industrial color palette. |
| output_03.png | pose_03 | 1.0 | A factory worker in a white safety helmet and navy work uniform, full body, inside a bright manufacturing plant. Soft morning light from tall windows on the left. Photorealistic documentary photography, muted industrial color palette. |
| expC_scale_0.3.png | pose_02 | 0.3 | A factory worker in a white safety helmet and navy work uniform, full body, inside a bright manufacturing plant. Soft morning light from tall windows on the left. Photorealistic documentary photography, muted industrial color palette. |
| expC_scale_1.0.png | pose_02 | 1.0 | A factory worker in a white safety helmet and navy work uniform, full body, inside a bright manufacturing plant. Soft morning light from tall windows on the left. Photorealistic documentary photography, muted industrial color palette. |
| expC_scale_1.6.png | pose_02 | 1.6 | A factory worker in a white safety helmet and navy work uniform, full body, inside a bright manufacturing plant. Soft morning light from tall windows on the left. Photorealistic documentary photography, muted industrial color palette. |

## 참조 사진

- ref_01.png : 서서 한 손을 머리 옆으로 든 자세
- ref_02.png : 의자에 앉아 신문을 읽는 자세
- ref_03.png : 걷는 자세

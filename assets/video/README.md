# AI Generated Video Sources

본 폴더는 CANIDAY 광고 영상 제작에 사용되는 AI 생성 영상 소스를 보관하는 폴더입니다.

`assets/images/`에 생성한 씬별 키비주얼 이미지를 기반으로, 이미지-투-비디오 AI 도구를 사용하여 짧은 모션 영상을 제작합니다.

---

## 공통 영상 규격

| 항목 | 내용 |
|---|---|
| 화면 비율 | 9:16 |
| 권장 해상도 | 1080 x 1920 |
| 프레임레이트 | 24~30fps |
| 영상 길이 | 씬별 5~8초 |
| 스타일 | 따뜻한 2D 일러스트 기반 모바일 앱 광고 |
| 움직임 | 과하지 않은 카메라 모션, 부드러운 빛 변화, 작은 UI 움직임 |
| 텍스트 | AI 영상 안에는 직접 생성하지 않음 |
| 최종 자막 | CapCut 편집 단계에서 삽입 |

---

## 사용 도구

| 영역 | 도구 | 사용 목적 |
|---|---|---|
| 이미지-투-비디오 | Pippit 또는 Runway | 정지 이미지를 짧은 광고용 모션 컷으로 변환 |
| 대체 도구 | Pika 또는 Kling | 대기열, 크레딧 부족, 결과 불안정 시 대체 사용 |
| 통합 편집 | CapCut | 컷 편집, 자막, 오디오 레벨 조정 |

---

## 공통 모션 지시사항

모든 씬에 아래 조건을 공통 적용합니다.

```txt
Create a short vertical 9:16 video from the provided image. Preserve the original composition, character design, colors, and illustration style. Add only subtle motion: gentle camera push-in, soft light movement, slight parallax, natural breathing-like stillness, and minimal UI glow. Do not add new characters, do not change the character design, do not add text, do not create speech bubbles, do not distort the smartphone screen, do not change the scene into 3D or photorealistic style.
```

---

## Negative Motion Prompt

```txt
no new text, no subtitles, no logo distortion, no extra character, no character redesign, no mouth on CANI, no shiny eye highlights, no exaggerated movement, no camera shake, no fast zoom, no 3D render, no photorealistic conversion, no fantasy portal, no terrarium, no comic panel, no glitch, no warped hands, no distorted phone screen
```

---

# Scene 01 Motion Prompt

## 입력 이미지

```txt
assets/images/scene01_tired_user_keyvisual.png
```

## 출력 파일명

```txt
scene01_tired_user_motion.mp4
```

## 길이

5초

## 모션 목적

사용자가 하루를 시작하지 못하는 정적인 무기력감을 보여준다.

## 비디오 생성 프롬프트

```txt
Create a 5-second vertical 9:16 video from the provided image. Keep the young person lying on the bed still and tired. Add very subtle morning light movement through the curtains, a slow gentle camera push-in, and slight fabric parallax on the bed. The mood should feel calm, relatable, and slightly stuck, not dramatic. Do not add text, do not change the person, do not add CANI in this scene.
```

## 출력 결과 요약

무기력한 아침 분위기를 유지하면서 광고의 공감 훅으로 사용할 수 있는 도입 영상 컷을 만든다.

---

# Scene 02 Motion Prompt

## 입력 이미지

```txt
assets/images/scene02_caniday_notification_keyvisual.png
```

## 출력 파일명

```txt
scene02_caniday_notification_motion.mp4
```

## 길이

6초

## 모션 목적

CANIDAY 앱 알림이 사용자의 하루에 작은 전환점을 만드는 순간을 보여준다.

## 비디오 생성 프롬프트

```txt
Create a 6-second vertical 9:16 video from the provided image. Keep the smartphone and objects in the same composition. Add a soft notification glow on the phone screen, a very slight camera push-in, and gentle sunlight movement across the bed or desk. CANI should remain inside the app screen only. Do not add readable text. Do not change the phone UI layout. Do not add new objects.
```

## 출력 결과 요약

휴대폰 화면의 은은한 알림 효과를 통해 CANIDAY 앱이 등장하는 장면을 만든다.

---

# Scene 03 Motion Prompt

## 입력 이미지

```txt
assets/images/scene03_cani_action_card_keyvisual.png
```

## 출력 파일명

```txt
scene03_cani_action_card_motion.mp4
```

## 길이

7초

## 모션 목적

앱 속 CANI가 작은 행동 카드를 제안하는 핵심 서비스 장면을 보여준다.

## 비디오 생성 프롬프트

```txt
Create a 7-second vertical 9:16 video from the provided image. Keep the smartphone centered. CANI must stay inside the app interface and act as a friendly service guide. Add a subtle UI card lift animation, soft warm glow from the phone screen, and a slow camera push-in. CANI may have a tiny gentle bounce, but do not change its shape, face, eyes, color, or tail. Do not add mouth, text, speech bubble, portal, or fantasy elements.
```

## 출력 결과 요약

CANIDAY 앱 속 캐릭터가 1분 행동을 제안하는 브랜드 핵심 컷을 만든다.

---

# Scene 04 Motion Prompt

## 입력 이미지

```txt
assets/images/scene04_small_action_keyvisual.png
```

## 출력 파일명

```txt
scene04_small_action_motion.mp4
```

## 길이

7초

## 모션 목적

사용자가 물 한 잔 마시기 또는 10초 호흡처럼 작은 행동을 실행하는 장면을 보여준다.

## 비디오 생성 프롬프트

```txt
Create a 7-second vertical 9:16 video from the provided image. Keep the person sitting near the bed or desk and performing a small self-care action. Add a subtle drinking motion or calm breathing motion if possible, but keep it natural and minimal. Add soft morning light movement and slight camera push-in. The smartphone should remain nearby with the CANIDAY app visible. CANI should stay only inside the smartphone screen. Do not add text or exaggerated emotional change.
```

## 출력 결과 요약

사용자가 부담 없는 작은 행동을 실제로 실행하는 장면을 만든다.

---

# Scene 05 Motion Prompt

## 입력 이미지

```txt
assets/images/scene05_success_feedback_keyvisual.png
```

## 출력 파일명

```txt
scene05_success_feedback_motion.mp4
```

## 길이

8초

## 모션 목적

작은 행동 완료 후 CANIDAY 앱이 성취감을 제공하는 순간을 보여준다.

## 비디오 생성 프롬프트

```txt
Create an 8-second vertical 9:16 video from the provided image. Keep the smartphone screen as the main focus. Add a soft completion glow around the check mark or success card. CANI should gently celebrate inside the app screen with a tiny bounce or hand movement, but keep the motion calm and supportive. Add subtle sparkles only if they match the original style. Do not add readable text. Do not redesign CANI. Do not make the celebration loud or exaggerated.
```

## 출력 결과 요약

작은 행동 완료 후 따뜻한 피드백을 받는 장면을 만든다.

---

# Scene 06 Motion Prompt

## 입력 이미지

```txt
assets/images/scene06_brand_ending_keyvisual.png
```

## 출력 파일명

```txt
scene06_brand_ending_motion.mp4
```

## 길이

5초

## 모션 목적

브랜드명, 슬로건, CTA를 삽입할 수 있는 엔딩 광고 컷을 만든다.

## 비디오 생성 프롬프트

```txt
Create a 5-second vertical 9:16 video from the provided image. Keep the smartphone mockup centered and leave empty space for title and CTA to be added later in editing. Add a slow gentle camera push-in, soft background light movement, and a subtle app screen glow. CANI should remain inside the app screen or as shown in the original image. Do not add text, fake app store badges, watermark, or new logo. Keep the scene clean and polished like a mobile app launch advertisement.
```

## 출력 결과 요약

최종 브랜드명, 슬로건, CTA를 편집 단계에서 넣을 수 있는 엔딩 모션 컷을 만든다.

---

# 생성 후 저장할 영상 목록

| 씬 | 입력 이미지 | 출력 영상 | 길이 | 상태 |
|---|---|---|---:|---|
| Scene 01 | `scene01_tired_user_keyvisual.png` | `scene01_tired_user_motion.mp4` | 5초 | 생성 예정 |
| Scene 02 | `scene02_caniday_notification_keyvisual.png` | `scene02_caniday_notification_motion.mp4` | 6초 | 생성 예정 |
| Scene 03 | `scene03_cani_action_card_keyvisual.png` | `scene03_cani_action_card_motion.mp4` | 7초 | 생성 예정 |
| Scene 04 | `scene04_small_action_keyvisual.png` | `scene04_small_action_motion.mp4` | 7초 | 생성 예정 |
| Scene 05 | `scene05_success_feedback_keyvisual.png` | `scene05_success_feedback_motion.mp4` | 8초 | 생성 예정 |
| Scene 06 | `scene06_brand_ending_keyvisual.png` | `scene06_brand_ending_motion.mp4` | 5초 | 생성 예정 |

총 예상 길이: 38초

---

# 영상 생성 시 주의사항

1. 이미지 원본의 구도와 색감을 유지한다.
2. CANI 캐릭터의 얼굴, 색상, 꼬리, 눈 형태를 변경하지 않는다.
3. AI 영상 안에서 텍스트를 생성하지 않는다.
4. 브랜드명, 슬로건, CTA는 CapCut 편집 단계에서 자막으로 넣는다.
5. 앱 서비스 홍보 영상이므로 테라리움, 포털, 평행세계 설정은 사용하지 않는다.
6. 카메라 모션은 느린 push-in 또는 약한 parallax 정도로 제한한다.
7. 사용자의 감정 변화는 과장하지 않고, “조금 나아지는 느낌”으로 표현한다.
8. 최종 편집 시 모든 영상 컷을 9:16 비율로 통일한다.

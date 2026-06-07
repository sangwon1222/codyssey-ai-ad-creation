# AI Generated Image Sources

본 폴더는 CANIDAY 광고 영상 제작에 사용되는 AI 생성 이미지 소스를 보관하는 폴더입니다.

최종 광고 영상은 9:16 세로형 숏폼 광고를 기준으로 제작하므로, 모든 이미지는 다음 규격을 기준으로 생성합니다.

## 공통 이미지 규격

| 항목 | 내용 |
|---|---|
| 화면 비율 | 9:16 |
| 권장 해상도 | 1080 x 1920 |
| 스타일 | 따뜻한 2D 일러스트, 모바일 앱 광고 스타일 |
| 색감 | 부드러운 파스텔톤, 차분한 오렌지 포인트 |
| 텍스트 | AI 이미지 안에는 최소화하고, 주요 카피는 편집 단계에서 자막으로 삽입 |
| 캐릭터 | CANIDAY 앱 속 캐릭터 CANI |

---

## 공통 스타일 프롬프트

아래 스타일 문구는 모든 씬 프롬프트에 공통으로 적용합니다.

```txt
warm 2D digital illustration, vertical 9:16 mobile advertisement composition, soft pastel colors, cozy lighting, clean modern mobile app visual style, gentle orange accent color, emotional but not depressing mood, trendy Gen Z short-form ad aesthetic, simple background, clear focal point, high quality, no text, no watermark
```

---

## CANI 캐릭터 고정 설명

CANI는 CANIDAY 앱 속에서 사용자의 작은 행동을 도와주는 브랜드 캐릭터입니다.  
이미지 생성 시 캐릭터가 변형되지 않도록 아래 설명을 반복적으로 사용합니다.

```txt
CANI character: a small cute orange fox-like chibi character, round body, orange fur color #E98A3C, white face and white belly, simple black circular eyes with no highlights, no mouth, rounded tail with white tail tip, simple sticker-like shape, clean thick outline, very minimal facial details, cute but calm expression, do not redesign the character
```

---

## Negative Prompt

모든 이미지 생성 시 아래 요소는 제외합니다.

```txt
photorealistic, 3D render, realistic human face, horror mood, dark depression, messy typography, unreadable text, distorted hands, extra fingers, extra limbs, strange eyes, mouth on CANI, shiny eye highlights, different fox design, terrarium, fantasy portal, comic panel layout, speech bubble, watermark, logo distortion
```

---

# Scene 01 Image Prompt

## 파일명

```txt
scene01_tired_user_keyvisual.png
```

## 씬 목적

사용자가 하루를 시작하지 못하고 “오늘도 망했다”고 느끼는 공감 상황을 보여준다.

## 이미지 생성 프롬프트

```txt
A vertical 9:16 warm 2D digital illustration for a mobile app advertisement. A young person in their late teens or twenties is lying on a bed in a small modern Korean room, looking tired but not extremely sad. Morning light comes softly through the curtains. A smartphone is lying near the pillow but the screen is not clearly visible yet. The room has realistic details: a desk, a water cup, a notebook, and slightly messy clothes. The mood should feel relatable, calm, and slightly stuck, not dramatic. Use soft pastel colors and cozy lighting. No text in the image.

CANI character is not visible in this scene.

Style: warm 2D digital illustration, vertical 9:16 mobile advertisement composition, soft pastel colors, cozy lighting, clean modern mobile app visual style, gentle orange accent color, emotional but not depressing mood, trendy Gen Z short-form ad aesthetic, simple background, clear focal point, high quality, no text, no watermark.
```

## 출력 결과 요약

무기력하지만 과장되지 않은 10~20대 사용자의 아침 장면을 확보한다.

---

# Scene 02 Image Prompt

## 파일명

```txt
scene02_caniday_notification_keyvisual.png
```

## 씬 목적

CANIDAY 앱 알림이 등장하며 사용자의 하루에 작은 전환점이 생기는 순간을 보여준다.

## 이미지 생성 프롬프트

```txt
A vertical 9:16 warm 2D digital illustration for a mobile app advertisement. Close-up view of a smartphone on a bed or desk. The phone screen shows a clean fictional self-care app notification from CANIDAY. The notification design should be simple and modern, with a soft orange accent color. The screen may show a small app card with a cute orange fox-like character icon, but avoid readable detailed text because text will be added later in editing. Around the phone, there are small everyday objects: a water cup, a notebook, and soft morning light. The mood is calm and gently hopeful. No large text in the image.

Include CANI as a tiny app icon or small character inside the phone screen only.

CANI character: a small cute orange fox-like chibi character, round body, orange fur color #E98A3C, white face and white belly, simple black circular eyes with no highlights, no mouth, rounded tail with white tail tip, simple sticker-like shape, clean thick outline, very minimal facial details, cute but calm expression, do not redesign the character.

Style: warm 2D digital illustration, vertical 9:16 mobile advertisement composition, soft pastel colors, cozy lighting, clean modern mobile app visual style, gentle orange accent color, emotional but not depressing mood, trendy Gen Z short-form ad aesthetic, simple background, clear focal point, high quality, no text, no watermark.
```

## 출력 결과 요약

CANIDAY 앱 알림이 사용자의 하루에 작은 시작점을 만드는 장면을 확보한다.

---

# Scene 03 Image Prompt

## 파일명

```txt
scene03_cani_action_card_keyvisual.png
```

## 씬 목적

앱 속 CANI가 “1분 행동 카드”를 꺼내주는 서비스적 개입을 보여준다.

## 이미지 생성 프롬프트

```txt
A vertical 9:16 warm 2D digital illustration for a mobile app advertisement. A smartphone screen fills the center of the composition. Inside the phone screen, the CANIDAY app interface is visible as a clean and simple self-care app. CANI, a small cute orange fox-like chibi character, appears inside the app and is holding or presenting a small action card. The action card should look like a simple UI card, but do not include readable text because text will be added later in editing. The card represents a tiny one-minute self-care action. The phone screen emits a soft warm glow. The background is a cozy desk or bed environment, softly blurred.

CANI should look like a service guide character inside the mobile app, not a fantasy creature. Do not include terrarium, portal, magical world, or comic panel elements.

CANI character: a small cute orange fox-like chibi character, round body, orange fur color #E98A3C, white face and white belly, simple black circular eyes with no highlights, no mouth, rounded tail with white tail tip, simple sticker-like shape, clean thick outline, very minimal facial details, cute but calm expression, do not redesign the character.

Style: warm 2D digital illustration, vertical 9:16 mobile advertisement composition, soft pastel colors, cozy lighting, clean modern mobile app visual style, gentle orange accent color, emotional but not depressing mood, trendy Gen Z short-form ad aesthetic, simple background, clear focal point, high quality, no text, no watermark.
```

## 출력 결과 요약

CANI가 앱 안에서 작은 행동을 안내하는 핵심 브랜드 장면을 확보한다.

---

# Scene 04 Image Prompt

## 파일명

```txt
scene04_small_action_keyvisual.png
```

## 씬 목적

사용자가 물 한 잔 마시기 또는 10초 호흡처럼 작은 행동을 실행하는 장면을 보여준다.

## 이미지 생성 프롬프트

```txt
A vertical 9:16 warm 2D digital illustration for a mobile app advertisement. A young person in their late teens or twenties is sitting up near a bed or desk and taking a small self-care action. The person is drinking a glass of water or taking a calm breath while holding a smartphone nearby. The room still looks realistic and slightly messy, but the mood is becoming lighter. The action should feel small and achievable, not dramatic. The smartphone screen shows a simple warm CANIDAY app interface with a small orange character icon, but no readable text. Soft morning light, gentle warm color palette, calm atmosphere.

CANI may appear as a small guide character on the smartphone screen only.

CANI character: a small cute orange fox-like chibi character, round body, orange fur color #E98A3C, white face and white belly, simple black circular eyes with no highlights, no mouth, rounded tail with white tail tip, simple sticker-like shape, clean thick outline, very minimal facial details, cute but calm expression, do not redesign the character.

Style: warm 2D digital illustration, vertical 9:16 mobile advertisement composition, soft pastel colors, cozy lighting, clean modern mobile app visual style, gentle orange accent color, emotional but not depressing mood, trendy Gen Z short-form ad aesthetic, simple background, clear focal point, high quality, no text, no watermark.
```

## 출력 결과 요약

사용자가 부담 없는 작은 행동을 실제로 실행하는 장면을 확보한다.

---

# Scene 05 Image Prompt

## 파일명

```txt
scene05_success_feedback_keyvisual.png
```

## 씬 목적

작은 행동 완료 후 CANIDAY 앱이 작은 성공 피드백을 제공하는 장면을 보여준다.

## 이미지 생성 프롬프트

```txt
A vertical 9:16 warm 2D digital illustration for a mobile app advertisement. Close-up view of a smartphone held in one hand. The CANIDAY app screen shows a clean success feedback UI with a soft orange check mark or simple completion card. CANI, the small cute orange fox-like character, is gently celebrating inside the app screen with a calm and supportive pose. The celebration should be subtle and warm, not loud or exaggerated. The background shows a slightly brighter room with a water cup and notebook on the desk. No readable text in the image because text will be added later in editing.

CANI should stay inside the app interface and act as a friendly service character.

CANI character: a small cute orange fox-like chibi character, round body, orange fur color #E98A3C, white face and white belly, simple black circular eyes with no highlights, no mouth, rounded tail with white tail tip, simple sticker-like shape, clean thick outline, very minimal facial details, cute but calm expression, do not redesign the character.

Style: warm 2D digital illustration, vertical 9:16 mobile advertisement composition, soft pastel colors, cozy lighting, clean modern mobile app visual style, gentle orange accent color, emotional but not depressing mood, trendy Gen Z short-form ad aesthetic, simple background, clear focal point, high quality, no text, no watermark.
```

## 출력 결과 요약

CANIDAY가 작은 행동을 완료한 사용자에게 부담 없는 성취감을 제공하는 장면을 확보한다.

---

# Scene 06 Image Prompt

## 파일명

```txt
scene06_brand_ending_keyvisual.png
```

## 씬 목적

마지막 3~5초 구간에서 브랜드명, 슬로건, CTA를 명확하게 노출할 수 있는 엔딩 화면을 만든다.

## 이미지 생성 프롬프트

```txt
A vertical 9:16 warm 2D digital illustration for a mobile app advertisement ending scene. A clean smartphone mockup is centered on a soft pastel background. The phone screen shows the CANIDAY app home screen concept with simple self-care cards and the small CANI character inside the app. Leave enough empty space at the top or center for brand title and slogan to be added later in editing. The composition should feel like a polished mobile app launch advertisement. Use warm orange accent color, clean UI, soft shadows, and a calm hopeful mood. No readable text in the image, no fake app store badges, no watermark.

CANI character: a small cute orange fox-like chibi character, round body, orange fur color #E98A3C, white face and white belly, simple black circular eyes with no highlights, no mouth, rounded tail with white tail tip, simple sticker-like shape, clean thick outline, very minimal facial details, cute but calm expression, do not redesign the character.

Style: warm 2D digital illustration, vertical 9:16 mobile advertisement composition, soft pastel colors, cozy lighting, clean modern mobile app visual style, gentle orange accent color, emotional but not depressing mood, trendy Gen Z short-form ad aesthetic, simple background, clear focal point, high quality, no text, no watermark.
```

## 출력 결과 요약

브랜드명, 슬로건, CTA를 편집 단계에서 삽입할 수 있는 깔끔한 엔딩 키비주얼을 확보한다.

---

# 생성 후 저장할 이미지 목록

| 씬 | 파일명 | 상태 |
|---|---|---|
| Scene 01 | `scene01_tired_user_keyvisual.png` | 생성 예정 |
| Scene 02 | `scene02_caniday_notification_keyvisual.png` | 생성 예정 |
| Scene 03 | `scene03_cani_action_card_keyvisual.png` | 생성 예정 |
| Scene 04 | `scene04_small_action_keyvisual.png` | 생성 예정 |
| Scene 05 | `scene05_success_feedback_keyvisual.png` | 생성 예정 |
| Scene 06 | `scene06_brand_ending_keyvisual.png` | 생성 예정 |

---

# 이미지 생성 시 주의사항

1. AI 이미지 안의 글자는 깨질 가능성이 높으므로, 중요한 문구는 이미지에 직접 생성하지 않는다.
2. 브랜드명, 슬로건, CTA는 CapCut 편집 단계에서 자막으로 추가한다.
3. CANI는 앱 속 서비스 캐릭터로만 표현한다.
4. 테라리움, 포털, 평행세계, 인스타툰 설정은 사용하지 않는다.
5. 모든 이미지는 9:16 세로형으로 통일한다.
6. 색감은 따뜻한 오렌지 계열과 부드러운 파스텔톤으로 맞춘다.

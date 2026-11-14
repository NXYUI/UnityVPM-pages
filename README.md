# NXYUI Avatar Tools

VRChat 아바타 작업을 돕는 Unity 에디터 패키지 모음입니다. VCC 또는 ALCOM에 이 저장소를 추가해 설치합니다.

## 저장소 추가

VCC·ALCOM의 저장소 추가(Add Repository)에 아래 주소를 넣습니다.

```
https://nxyui.github.io/UnityVPM-pages/index.json
```

저장소를 추가한 뒤 프로젝트의 패키지 관리 화면에서 원하는 패키지를 추가합니다.
모든 패키지의 창은 Unity 상단 메뉴 **NXYUI** 아래에 있습니다.

## 패키지

| 패키지 | 하는 일 | 가이드 |
| --- | --- | --- |
| **Avatar Customizer**<br>`dev.nxyui.avatar-customizer` | 빌드된 Expressions 메뉴를 정리(이름 변경·위치 이동·숨기기)하고, 그 위에 즐겨찾기 메뉴·기본값·블렌드쉐이프 컨트롤을 만듭니다. | [가이드](packages/dev.nxyui.avatar-customizer/README.md) |
| **Personal Pose Deck**<br>`dev.nxyui.personal-pose-deck` | 원하는 Humanoid 포즈 클립으로 GoGoLoco 포즈 덱을 만들고, 포즈를 탐색·미리보기합니다. | [가이드](packages/dev.nxyui.personal-pose-deck/README.md) |
| Avatar Menu Favorites<br>`dev.nxyui.avatar-menu-favorites` | 지원 종료. Avatar Customizer로 바뀌었습니다. Avatar Customizer를 설치하면 자동으로 제거되고, 씬의 설정은 그대로 이어집니다. | [Avatar Customizer](packages/dev.nxyui.avatar-customizer/README.md) |

## 공통 요구 사항

- Unity 2022.3 (VRChat 지원 버전)
- VRChat SDK - Avatars
- 패키지별 추가 요구 사항은 각 가이드에 있습니다.

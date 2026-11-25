# NXYUI Avatar Tools

VRChat 아바타 작업을 돕는 Unity 에디터 패키지 모음입니다. VCC 또는 ALCOM에 이 저장소를 추가해 설치합니다.

## 저장소 추가

VCC·ALCOM의 저장소 추가(Add Repository)에 아래 주소를 넣습니다.

```
https://nxyui.github.io/UnityVPM-pages/index.json
```

저장소를 추가한 뒤 프로젝트의 패키지 관리 화면에서 원하는 패키지를 추가합니다.
모든 패키지의 창은 Unity 상단 메뉴 **NXYUI** 아래에 있습니다.
각 도구의 창과 컴포넌트(Inspector) 맨 위에 있는 **사용 방법**을 펼치면 쓰는 순서가 나오고, 그 안의 **자세한 설명 열기**가 아래 표의 가이드를 엽니다.

## 패키지

| 패키지 | 하는 일 | 가이드 |
| --- | --- | --- |
| **Avatar Customizer**<br>`dev.nxyui.avatar-customizer` | 빌드된 Expressions 메뉴를 정리(이름 변경·위치 이동·숨기기)하고, 그 위에 즐겨찾기 메뉴·기본값·블렌드쉐이프 컨트롤을 만듭니다. 완성될 메뉴를 보면서 바로 편집할 수도 있습니다. | [가이드](packages/dev.nxyui.avatar-customizer/README.md) |
| **Personal Pose Deck**<br>`dev.nxyui.personal-pose-deck` | 원하는 Humanoid 포즈 클립으로 GoGoLoco 포즈 덱을 만들고, 포즈를 탐색·미리보기합니다. | [가이드](packages/dev.nxyui.personal-pose-deck/README.md) |
| **Asset Manager**<br>`dev.nxyui.asset-manager` | 프로젝트의 에셋을 Booth 상품 단위로 보여 주고 Booth 페이지와 연결합니다. 폴더와 압축 파일 속 .unitypackage를 대기열로 가져오고, 카드에서 바로 아바타에 조립(Modular Avatar Outfit·Bone Proxy)합니다. | [가이드](packages/dev.nxyui.asset-manager/README.md) |
| **Assembly Checker**<br>`dev.nxyui.assembly-checker` | 아바타의 복제본을 빌드해서 업로드 전에 문제를 찾습니다(합쳐지지 않은 의상 아마추어, PhysBone 중복, Anchor Override·Bounds, 꺼진 채 올라가는 오브젝트). 텍스처마다 어느 오브젝트·머티리얼·칸에 있는지 보여 주고, 빌드할 때 안 쓰는 파라미터를 지웁니다. | [가이드](packages/dev.nxyui.assembly-checker/README.md) |
| **Hair Gradation**<br>`dev.nxyui.hair-gradation` | 헤어 루트 하나로, 파츠가 나뉜 헤어 전체에 높이에 따라 이어지는 그라데이션과 그 안의 패턴을 넣습니다. TexTransTool 구성을 대신 만들고 UV 겹침을 확인하며, lilToon 메인 컬러 2nd/3rd에도 넣을 수 있습니다. | [가이드](packages/dev.nxyui.hair-gradation/README.md) |
| **AI Expression**<br>`dev.nxyui.ai-expression` | 원하는 표정을 말로 적으면 Claude가 얼굴 쉐이프키 값을 정합니다. 쉐이프키마다 무엇을 움직이는지 미리 읽어 둔 얼굴 사전으로 토큰을 아끼고, 이 창의 Claude API나 Claude Code(MCP)에서 쓸 수 있습니다. 복제본에서 작업하고 표정 클립으로 저장합니다. | [가이드](packages/dev.nxyui.ai-expression/README.md) |
| Avatar Menu Favorites<br>`dev.nxyui.avatar-menu-favorites` | 지원 종료. Avatar Customizer로 바뀌었습니다. Avatar Customizer를 설치하면 자동으로 제거되고, 씬의 설정은 그대로 이어집니다. | [Avatar Customizer](packages/dev.nxyui.avatar-customizer/README.md) |

## 공통 요구 사항

- Unity 2022.3 (VRChat 지원 버전)
- VRChat SDK - Avatars
- 패키지별 추가 요구 사항은 각 가이드에 있습니다.

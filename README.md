# EventSystem Patch
## 소개
UI의 Event System을 사용하면서 Input System을 사용한다면 유니티는 Error 경고를 보여줍니다.  
이는 기존에 사용되던 Standalone input module는 Input Manager를 기반으로 동작했기 때문입니다.  
Input System은 더이상 Input Manager를 사용하지 않기 때문에 에러를 발생시키며 유니티가 제공하는 Input System UI Input Module을 사용해야합니다.  
안타깝게도 유니티는 자동적으로 Standalone input module 컴포넌트를 Input System용 컴포넌트로 변환해주지 않습니다.  
이 플러그인을 사용하면 자동적으로 Standalone input module을 감지하여 Input System UI Input Module로 변환해줍니다.

## 설치
### Git UPM
Event System Patch 패키지를 설치하려면 다음 단계가 필요합니다.
1. Git이 설치되어 있는지 확인하십시오.
2. Package Manager를 오픈합니다.
3. +버튼을 클릭하고, Add package from git URL을 클릭합니다.
4. `https://github.com/NK-Studio/EventSystem-Patch.git` 를 입력하고 추가 버튼을 클릭하세요.

### Unity Package
[Releases](https://github.com/NK-Studio/EventSystem-Patch/releases)에서 최신 버전의 패키지를 다운로드 받아 설치합니다.
## 사용법
추가적인 사용법은 없으며 자동으로 내부에서 동작합니다.

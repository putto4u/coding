

## 💻 VS Code 설치 방법 (Windows/macOS 기준)

설치 과정은 매우 간단하여 수강생들이 쉽게 따라 할 수 있습니다.

### 1. 다운로드 (Download)
Google에 "VS Code"를 검색하거나, 공식 웹사이트(**[Visual Studio Code 공식 웹사이트](https://code.visualstudio.com/)**)로 접속합니다.
* ****
* 운영체제(Windows, macOS, Linux)에 맞는 버튼을 클릭하여 설치 파일(Installer)을 다운로드합니다.

### 2. 설치 파일 실행 (Run Installer)
다운로드된 설치 파일을 실행합니다.

* **Windows:** `.exe` 파일을 실행합니다.
* **macOS:** `.zip` 파일의 압축을 풀고, `Visual Studio Code.app` 파일을 **Applications** 폴더로 드래그합니다.

---

## ✨ 필수 유용한 설치 옵션 (Windows 기준)

Windows 환경에서 설치 시 나타나는 **"추가 작업 선택"** 단계에서 다음과 같은 옵션들을 **반드시 체크**하도록 수강생들에게 강조해 주세요. 이 옵션들은 VS Code를 **실전 개발 환경**에서 사용하기 매우 편리하게 만듭니다.

| 옵션 | 설명 | 중요도 | 실전 팁 |
| :--- | :--- | :--- | :--- |
| **바탕 화면 바로 가기 만들기** | 바탕 화면에 아이콘을 생성합니다. (선택 사항) | 중 | |
| **'Code'를 통해 동작 열기 추가** | **(가장 중요!)** 탐색기 파일/폴더의 오른쪽 마우스 메뉴(Context Menu)에 **"Code로 열기(Open with Code)"** 메뉴를 추가합니다. | **⭐상** | 특정 프로젝트 폴더를 VS Code로 바로 열 때 필수! |
| **경로(Path)에 추가 (다시 시작 필요)** | **(필수!)** 시스템 환경 변수(Path)에 VS Code 실행 명령어를 등록합니다. | **⭐상** | 명령 프롬프트나 터미널에서 `code .` 명령어로 현재 폴더를 VS Code로 즉시 열 수 있게 됩니다. **깃허브(GitHub)** 프로젝트 클론 후 사용 시 매우 유용합니다. |
| **지원되는 파일 형식에 아이콘 표시** | VS Code가 지원하는 파일 아이콘을 Windows 탐색기에 표시합니다. | 중 | |

---

## 🚀 강의 시 강조할 부분 및 실습 팁

1.  **확장성의 중요성:** VS Code는 그 자체보다 **확장 기능(Extensions)**이 핵심입니다. 설치 후 바로 **Python, Jupyter, Korean Language Pack** 등의 확장을 설치하여 실습 준비를 완료하도록 안내해 주세요. (예: `Python` 확장 설치 시 자동 디버깅 및 인텔리센스 기능 활성화)
2.  **경량 에디터의 장점:** "VS Code는 가벼워서 PC 사양에 관계없이 빠르게 코딩하고 테스트할 수 있어 **IT 입문과 실습에 최적**입니다. 대규모 IDE인 Visual Studio와는 다릅니다."라고 명확히 설명해 주세요.
3.  **하이퍼링크 활용:** 강의록에서 **깃허브 연동** 방법을 설명할 때, `code .` 명령어를 하이퍼링크로 만들어 해당 사용법 페이지로 연결하면 학습 효율이 높아집니다.


IT 전문 강사님께서 수강생들의 실습 준비를 돕기 위한 **VS Code 필수 확장 기능 추천 및 설치 준비용 Markdown 파일(.md) 초안**을 구성해 드립니다. 이 파일을 GitHub이나 웹페이지에 올려 바로 서비스하실 수 있습니다.

---

## 🛠️ VS Code 실습 환경 구축 가이드 (.md 파일 초안)

# VS Code 실습 환경 구축 및 필수 확장 기능 설치 가이드

안녕하세요. \[강사님 성함]입니다.
본 강의는 **Visual Studio Code (VS Code)**를 기반으로 진행됩니다. VS Code는 가볍고 강력하며 확장성이 뛰어나 **파이썬, Jupyter, 웹 개발**에 최적화된 에디터입니다. 아래 가이드를 따라 필수 확장 기능을 설치하여 실습 준비를 완료해 주세요.

## 1. 필수 확장 기능 (Must-Have Extensions)

이 기능들은 기본적인 개발 환경을 구축하고 코드 편집의 효율성을 극대화하기 위해 반드시 설치해야 합니다.

| 확장 기능명 | Publisher | 용도 및 특징 |
| :--- | :--- | :--- |
| **Python** | Microsoft | VS Code를 **파이썬 IDE**처럼 사용할 수 있게 합니다. IntelliSense(자동 완성), 디버깅, 가상 환경 관리, 테스트 등을 지원합니다. |
| **Jupyter** | Microsoft | VS Code에서 **Jupyter Notebook (.ipynb)** 파일을 완벽하게 실행하고 편집할 수 있게 합니다. 데이터 분석 강의에 필수입니다. |
| **Jupyter Notebook Renderers** | Microsoft | Jupyter Notebook의 결과물(차트, 표 등)을 더 풍부하게 시각화합니다. |
| **Korean Language Pack** | Microsoft | VS Code 인터페이스를 **한국어**로 전환하여 초보자의 접근성을 높입니다. |
| **Pylance** | Microsoft | Python 확장의 보완 기능으로, **더 빠르고 정확한** 자동 완성(IntelliSense)과 타입 체크 기능을 제공합니다. |

---

## 2. 유용한 확장 기능 (Highly Recommended Extensions)

강의 자료 작성(Markdown/RST) 및 공동 작업, 코드 가독성을 높이는 데 유용한 기능들입니다.

| 확장 기능명 | Publisher | 용도 및 특징 |
| :--- | :--- | :--- |
| **Prettier - Code formatter** | Prettier | 코드를 자동으로 일관된 형식으로 정리해 줍니다. 특히 웹 개발(JavaScript, CSS) 및 코드 표준 유지에 유용합니다. |
| **Live Server** | Ritwick Dey | 웹 개발 시 HTML 파일 저장과 동시에 웹 브라우저에 **자동으로 실시간 반영**해 줍니다. |
| **Markdown All in One** | Yu Zhang | `.md` 파일 작성 시 단축키 및 자동 목록 생성 등 **편리한 Markdown 기능**을 모두 제공합니다. |
| **indent-rainbow** | vunguyenthanh | 코드의 **들여쓰기(Indentation)** 레벨을 색상으로 표시하여, 파이썬의 핵심인 들여쓰기 오류를 방지하고 가독성을 높입니다. |
| **GitLens** | Eric Amodio | **GitHub** 연동 시, 각 코드 라인의 수정 이력(누가, 언제 수정했는지)을 쉽게 볼 수 있게 해줍니다. 협업 및 **보안** 관련 이력 추적에 유용합니다. |

---

## 3. 설치 방법 (실습 준비)

모든 확장은 VS Code 내의 **확장 마켓플레이스**를 통해 쉽게 설치할 수 있습니다.

1.  **VS Code 실행:** VS Code를 엽니다.
2.  **확장 아이콘 클릭:** 왼쪽 사이드바의 **네모 4개 모양 아이콘** (Extensions, 단축키: `Ctrl+Shift+X`)을 클릭합니다. \
3.  **검색 및 설치:** 위 표에 제시된 **확장 기능명**을 검색창에 입력합니다.
4.  **Install 버튼 클릭:** 검색 결과에서 해당 확장을 찾아 **"Install"** 버튼을 클릭합니다.

### 💡 실전 팁: 한국어 팩 설치 후 재시작

**Korean Language Pack**을 설치한 후에는 VS Code가 **재시작(Restart)**하라는 메시지를 표시합니다. 반드시 재시작하여 언어를 한국어로 변경해 주세요.

### 🔗 중요 단어 및 사이트 하이퍼링크

| 대상 | 하이퍼링크 예시 |
| :--- | :--- |
| Python 확장 | \[Python Extension on VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-python.python) |
| Jupyter 확장 | \[Jupyter Extension on VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) |
| GitLens 확장 | \[GitLens Documentation](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) |

---

**출처:** Visual Studio Code 공식 문서 및 Microsoft, Open Source 커뮤니티

---
> **\[강사님 팁]** 실습 시 `indent-rainbow`가 파이썬의 들여쓰기 오류를 시각적으로 잡아주는 유용한 도구임을 강조해 주세요!

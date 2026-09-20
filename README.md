<p align="center"><img src="img/icon-256.png" width="120" alt="MyMath"></p>

<h1 align="center">MyMath for InDesign</h1>

<h3 align="center">Type an equation. It lands in your InDesign page — print-ready, and editable forever.</h3>

<p align="center">
  <b>Free</b> &nbsp;·&nbsp; <b>works inside InDesign</b> &nbsp;·&nbsp; <b>re-edit in place</b> &nbsp;·&nbsp;
  <b>K100 vector</b> &nbsp;·&nbsp; <b>no sidecar files</b> &nbsp;·&nbsp; <b>no math fonts to install</b>
</p>

<p align="center">
  InDesign 문서에 수학 수식을 넣고 고치는 무료 도구 · <a href="#한국어">한국어</a>
</p>

<p align="center">
  <a href="https://mymath-indesign.web.app"><b>🌐 mymath-indesign.web.app</b></a><br>
  <a href="https://github.com/uibsee/mymath/releases/latest/download/MyMath-Setup.exe"><b>⬇ Free download</b></a>
  &nbsp;·&nbsp; <a href="docs/guide.md"><b>User guide</b></a>
  &nbsp;·&nbsp; <a href="docs/guide.ko.md"><b>사용설명서</b></a><br>
  📄 PDF guide: <a href="https://mymath-indesign.web.app/MyMath-guide-en.pdf">English</a> · <a href="https://mymath-indesign.web.app/MyMath-guide-de.pdf">Deutsch</a> · <a href="https://mymath-indesign.web.app/MyMath-guide-fr.pdf">Français</a> · <a href="https://mymath-indesign.web.app/MyMath-guide-ja.pdf">日本語</a> · <a href="https://mymath-indesign.web.app/MyMath-guide-es.pdf">Español</a> · <a href="https://mymath-indesign.web.app/MyMath-guide-zh.pdf">中文</a> · <a href="https://mymath-indesign.web.app/MyMath-guide-pt.pdf">Português</a> · <a href="https://mymath-indesign.web.app/MyMath-guide-it.pdf">Italiano</a> · <a href="https://mymath-indesign.web.app/MyMath-guide-ru.pdf">Русский</a><br>
  📘 Full manual: <a href="https://mymath-indesign.web.app/manual-en">English</a> (<a href="https://mymath-indesign.web.app/MyMath-manual-en.pdf">PDF, 187 pages</a>) · <a href="https://mymath-indesign.web.app/manual">한국어</a> (<a href="https://mymath-indesign.web.app/MyMath-manual-ko.pdf">PDF, 170쪽</a>)<br>
  <sub>Windows · 85 MB · requires InDesign 18.5 (August 2023) or later</sub>
</p>

![MyMath Editor](img/shot2-equation.png)

Type an equation and it lands in your InDesign document as a print-safe vector graphic.
The equation source (LaTeX) is stored inside the document, so you can re-edit it in place anytime.

## Install — one file

1. Download **[MyMath-Setup.exe](https://github.com/uibsee/mymath/releases/latest/download/MyMath-Setup.exe)** and double-click it.
   It installs both the editor and the InDesign plugin.
   - If "Windows protected your PC" appears, click **More info → Run anyway** (this free app is not code-signed yet).
2. Restart InDesign and choose **Plugins → MyMath**.
3. The first time you place an equation, InDesign asks whether the plugin may launch the editor —
   tick **Remember my choice** and click **Allow** (once only).

There is nothing to configure. To remove it, uninstall "MyMath Editor" in Windows Settings → Apps; the plugin goes with it.

| Requirements | |
|---|---|
| InDesign | **18.5 (August 2023) or later** — earlier versions cannot run this kind of plugin panel |
| OS | Windows 10 / 11 (Mac is planned) |

## How it works

| You want to… | Do this |
|---|---|
| Place a short equation | Put the cursor in your text → type `1/2`, `x^2`, `sqrt(2)` in the panel's **quick-insert box** → **Enter** |
| Build a long equation | **[Edit Equation]** in the panel → compose in the editor → **[InDesign]** button (`Ctrl+S`) |
| Edit an equation | Click it in the document → **[Edit Equation]** → it is replaced in the same spot |
| Convert a whole manuscript | Write `$x^2+1$` in your text, then **[Convert $...$ equations]** once |
| Bring in Word / Hangul files | **[Place manuscript]** — `.docx` / `.hwpx`, equations included |
| Refresh a whole book | **[Re-render all equations]** — every equation picks up the new settings |

See the **[user guide](docs/guide.md)** for the walkthrough, and the **[full manual](https://mymath-indesign.web.app/manual-en)** ([PDF](https://mymath-indesign.web.app/MyMath-manual-en.pdf)) for every button, preference, shortcut and palette.

## Highlights

- **Print quality** — vector PDF with pure K100 black (verified with PDF/X-1a export). CMYK, spot colours and overprint supported
- **No math fonts to install** — glyphs are drawn as outlines, so nothing goes missing at the printer
- **No sidecar files** — graphics are embedded and the LaTeX source lives inside the document
- **Gallery of 1,000+ equations** — school curricula, multi-line derivations, AI / machine-learning formulas. Pick one and tweak it
- **Automatic inline alignment** — sized to the body text and vertically aligned for you
- **Import** MathML · AsciiMath · Word equations · MediaWiki · Hangul equations /
  **Export** PDF · EPS · SVG · PNG · JPEG · GIF · BMP · WMF · MathML
- **10 UI languages** — English · 한국어 · Deutsch · Français · 日本語 · Español · 简体中文 · Português · Italiano · Русский
  (follows InDesign's language; you can change it in the panel)
- **Korean textbook notation palette** — permutations ₙPᵣ, repeating decimals, similarity ∽, parallel //, Hangul inside equations

| | |
|---|---|
| ![Equation gallery](img/shot1-gallery.png) | ![Notation palette](img/shot3-korean-palette.png) |

## Feedback

Write to **uibsee@hanmail.net** or open an [issue](https://github.com/uibsee/mymath/issues).
If something doesn't work, attaching `panel-boot.log` helps a lot — it is in the `PluginData` folder under
`%APPDATA%\Adobe\UXP\PluginsStorage\IDSN`.

## Terms

MyMath is free to use. The documentation in this repository is under the [MIT license](LICENSE).
MyMath includes these open-source libraries: [MathLive](https://github.com/arnog/mathlive) (MIT),
[MathJax](https://github.com/mathjax/MathJax) (Apache-2.0) and [Electron](https://github.com/electron/electron) (MIT).

Adobe and InDesign are trademarks of Adobe Inc. This project is not affiliated with Adobe.

---

## 한국어

**InDesign 문서에 수학 수식을 넣고 고치는 무료 도구입니다.**
수식을 입력하면 인쇄에 안전한 벡터 그래픽으로 문서에 들어가고, 수식 원본(LaTeX)이 문서 안에 함께 저장되어
언제든 같은 자리에서 다시 고칠 수 있습니다.

**[⬇ 무료 다운로드 — MyMath-Setup.exe](https://github.com/uibsee/mymath/releases/latest/download/MyMath-Setup.exe)** ·
**[사용설명서](docs/guide.ko.md)** · **[홈페이지](https://mymath-indesign.web.app)** — Windows · 85MB · **InDesign 18.5 (2023년 8월) 이상**

### 설치 — 파일 하나

1. `MyMath-Setup.exe` 를 받아 더블클릭합니다. 편집기와 InDesign 플러그인이 함께 설치됩니다.
   - "Windows의 PC 보호" 창이 뜨면 **[추가 정보] → [실행]** (아직 코드 서명을 하지 않은 무료 프로그램이라 나오는 안내입니다)
2. InDesign을 다시 켜고 메뉴 **[플러그인] → MyMath → MyMath 수식 입력**.
3. 처음 수식을 넣을 때 뜨는 「권한 요청」 창에서 **[내 선택 기억]** 체크 → **[허용]** (한 번만).

따로 설정할 것은 없습니다. 지우려면 Windows 설정 → 앱에서 "MyMath Editor"를 제거하면 플러그인도 함께 지워집니다.

### 쓰는 법

| 하고 싶은 것 | 이렇게 |
|---|---|
| 짧은 수식 | 본문에 커서 → 패널 **빠른 넣기 칸**에 `1/2`, `x^2`, `sqrt(2)` → **Enter** |
| 긴 수식 | 패널 **[수식 편집]** → 편집기에서 작성 → **[InDesign]** 버튼 (`Ctrl+S`) |
| 고치기 | 문서의 수식을 클릭 → **[수식 편집]** → 같은 자리에서 바뀝니다 |
| 원고 통째로 | 원고에 `$x^2+1$` 처럼 적어 두고 **[$...$ 수식 변환]** 한 번 |
| 워드·한글 원고 | **[원고 넣기 (워드·한글)]** — `.docx` `.hwpx` 안의 수식까지 한꺼번에 |
| 책 전체 갱신 | **[모든 수식 다시 조판]** — 문서의 수식 전부를 새 설정으로 |

자세한 내용은 **[사용설명서](docs/guide.ko.md)** 를, 환경설정·단축키·팔레트까지 담은 전체 설명서는 **[홈페이지](https://mymath-indesign.web.app/manual)** 또는 **[PDF (170쪽)](https://mymath-indesign.web.app/MyMath-manual-ko.pdf)** 로 보세요.

### 특징

- **인쇄 품질** — 벡터 PDF, 검정은 K100 단색 (PDF/X-1a 내보내기로 검증). CMYK·별색·오버프린트 지원
- **수식용 글꼴 설치 불필요** — 글자를 윤곽선으로 그립니다. 인쇄소에 글꼴을 보낼 필요가 없습니다
- **곁에 파일이 안 생깁니다** — 그래픽은 문서에 임베드, 원본 LaTeX은 문서 안에 저장
- **수식 갤러리 1,000여 개** — 초·중·고 교육과정, 여러 줄 풀이, AI·머신러닝 수식. 고르고 고치기만 하면 됩니다
- **글줄 안 세로 정렬 자동** · 본문 글자 크기 자동 반영
- **한국 교과서 표기 팔레트** — 순열 ₙPᵣ, 순환소수, 닮음 ∽, 평행 //, 수식 안 한글
- **10개 언어** — InDesign 언어를 따라가며, 패널에서 바꿀 수 있습니다

### 문의 · 오류 신고

**uibsee@hanmail.net** 또는 [Issues](https://github.com/uibsee/mymath/issues) 로 알려 주세요.
잘 안 될 때는 패널이 스스로 남기는 기록 파일 `panel-boot.log` 를 함께 보내 주시면 원인을 빨리 찾을 수 있습니다
(`%APPDATA%\Adobe\UXP\PluginsStorage\IDSN` 아래 `PluginData` 폴더).

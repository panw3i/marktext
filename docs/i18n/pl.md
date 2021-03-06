> **This documentation is outdated, based on the original readme from 14 April 2018!**

<p align="center"><img src="../../static/logo-small.png" alt="mark text" width="100" height="100"></p>

<h1 align="center">Mark Text</h1>

<div align="center">
  <a href="https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fmarktext%2Fmarktext">
    <img src="https://img.shields.io/twitter/url/https/github.com/marktext/marktext.svg?style=for-the-badge" alt="twitter">
  </a>
</div>
<div align="center">
  <strong>:high_brightness:Edytor markdown nowej generacji:crescent_moon:</strong>
</div>
<div align="center">
  Aplikacja na bazie <code>Electron</code> na platformy OS X, Windows i Linux
</div>

<br />

<div align="center">
  <!-- Version -->
  <a href="https://marktext.github.io/website">
    <img src="https://badge.fury.io/gh/jocs%2Fmarktext.svg" alt="website">
  </a>
  <!-- License -->
  <a href="https://marktext.github.io/website">
    <img src="https://img.shields.io/github/license/marktext/marktext.svg" alt="LICENSE">
  </a>
  <!-- Build Status -->
  <a href="https://marktext.github.io/website">
    <img src="https://travis-ci.org/marktext/marktext.svg?branch=master" alt="build">
  </a>
  <!-- Downloads total -->
  <a href="https://marktext.github.io/website">
    <img src="https://img.shields.io/github/downloads/marktext/marktext/total.svg" alt="total download">
  </a>
  <!-- Downloads latest release -->
  <a href="https://marktext.github.io/website">
    <img src="https://img.shields.io/github/downloads/marktext/marktext/v0.16.2/total.svg" alt="latest download">
  </a>
  <!-- deps -->
  <a href="https://marktext.github.io/website">
    <img src="https://img.shields.io/hackage-deps/v/lens.svg" alt="dependencies">
  </a>
  <!-- donates -->
  <a href="https://opencollective.com/marktext">
    <img src="https://opencollective.com/marktext/tiers/backer/badge.svg?label=backer&color=brightgreen" alt="donate">
  </a>
</div>

<div align="center">
  <h3>
    <a href="https://marktext.github.io/website">
      Strona
    </a>
    <span> | </span>
    <a href="https://github.com/marktext/marktext#features">
      Cechy programu
    </a>
    <span> | </span>
    <a href="https://github.com/marktext/marktext#download-and-installation">
      Instalacja
    </a>
    <span> | </span>
    <a href="https://github.com/marktext/marktext#development">
      Rozw??j
    </a>
    <span> | </span>
    <a href="https://github.com/marktext/marktext#contribution">
      Udzia?? w projekcie
    </a>
  </h3>
</div>

<div align="center">
  <sub>Edytor Markdown, kt??ry potrafi. Zbudowany z ?????? przez
    <a href="https://github.com/Jocs">Jocs</a> i
    <a href="https://github.com/marktext/marktext/graphs/contributors">
      innych
    </a>
  </sub>
</div>

<br />

![](../../docs/marktext.gif)

### Cechy programu

- Podgl??d na ??ywo - u??ycie [snabbdom](https://github.com/snabbdom/snabbdom) jako swojego silnika renderuj??cego.
- Wsparcie specyfikacji [CommonMark](https://spec.commonmark.org/0.29/) i [GitHub Flavored Markdown](https://github.github.com/gfm/).
- Wsparcie paragraf??w i skr??t??w klawiatowych dla styl??w wbudowanych w celu zwi??kszenia twojej wydajno??ci podczas pisania.
- Zapis do plik??w **HTML** i **PDF**.
- Ciemny i jasny motyw.
- R????ne tryby edycji: **Kod ??r??d??owy**, **Maszyna do pisania**, **Skupienie**.

<h4 align="center">:crescent_moon:Motywy:high_brightness:</h4>

| Ciemny :crescent_moon:                                             | Jasny :high_brightness:                                             |
|:------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| ![](../../docs/dark.jpg) | ![](../../docs/light.jpg) |

<h4 align="center">:smile_cat:Tryby edycji:dog:</h4>

| Kod ??r??d??owy                                                         | Maszyna do pisania                                                       | Skupienie                                                           |
|:--------------------------------------------------------------------:|:------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| ![](../../docs/source.gif) | ![](../../docs/typewriter.gif) | ![](../../docs/focus.gif) |

### Dlaczego kolejny edytor?

1. Kocham pisa??. U??ywa??em wiele r????nych edytor??w markdown, ale wci???? nie ma takiego, kt??ry by??by w pe??ni zgodny z moimi oczekiwaniami. Nie lubi??, kiedy pisanie przerywaj?? mi niemo??liwe do wytrzymania b????dy. **Mark Text** u??ywa wirtualnego DOM do wyrenderowania strony co sprawia, ??e jest bardzo wydajny. Program jest rozpowszechniany na licencji open source dla wszystkich przyjaci???? kochaj??cych markdown i pisanie.
2. Jak ju?? zosta??o wspomniane powy??ej, **Mark Text** b??dzie zawsze rozpowszechniany na licencji open source. Wierzymy, ??e wszyscy wielbiciele markdown do??o???? swoj?? cegie??k?? do kod??w ??r??d??owych programu i pomog?? w rozwijaniu **Mark Text**.
3. Istnieje wiele edytor??w markdown i ka??dy z nich ma swoje cechy szczeg??lne, jednak ci????ko jest zaspokoi?? wszystkie potrzeby u??ytkownik??w. Wierz??, ??e **Mark Text** jest w stanie zaspokoi?? potrzeby jak najwi??kszej grupy os??b. Mimo i?? najnowsza wersja **Mark Text** nie jest idealna, pr??bujemy stworzy?? go tak doskona??ym jak to jest tylko mo??liwe.

### Instalacja

![Conda](https://img.shields.io/conda/pn/conda-forge/python.svg?style=for-the-badge)

| ![]( https://github.com/ryanoasis/nerd-fonts/wiki/screenshots/v1.0.x/mac-pass-sm.png)                                                                                                             | ![]( https://github.com/ryanoasis/nerd-fonts/wiki/screenshots/v1.0.x/windows-pass-sm.png)                                                                                                                     | ![]( https://github.com/ryanoasis/nerd-fonts/wiki/screenshots/v1.0.x/linux-pass-sm.png)                                                                                                                                   |
|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| [![latest version](https://img.shields.io/github/downloads/marktext/marktext/latest/marktext.dmg.svg)](https://github.com/marktext/marktext/releases/download/v0.16.2/marktext.dmg) | [![latest version](https://img.shields.io/github/downloads/marktext/marktext/latest/marktext-setup.exe.svg)](https://github.com/marktext/marktext/releases/download/v0.16.2/marktext-setup.exe) | [![latest version](https://img.shields.io/github/downloads/marktext/marktext/latest/marktext-x86_64.AppImage.svg)](https://github.com/marktext/marktext/releases/download/v0.16.2/marktext-x86_64.AppImage) |

Nie znalaz??e?? swojego systemu? Przejd?? do strony [release](https://github.com/marktext/marktext/releases). Wci???? nie znalaz??e??? Zg??o?? [problem](https://github.com/marktext/marktext/issues).

Chcia??by?? zobaczy?? jak nowe udogodnienia wprowadzi??a najnowsza wersja? Udaj si?? do [CHANGELOG](../../.github/CHANGELOG.md)

Je??li u??ywasz systemu OS X, to mo??esz zainstalowa?? Mark Text za pomoc?? [**homebrew cask**](https://github.com/caskroom/homebrew-cask). Aby zacz???? korzysta?? z Homebrew-Cask potrzebujesz tylko [Homebrew](https://brew.sh/).

> brew cask install mark-text

![](../../docs/brew-cask.gif)

### Rozw??j

Je??eli chcia??by?? samodzielnie zbudowa?? **Mark Text**:

- sklonuj to repozytorium.
- uruchom komend?? `npm install`
- uruchom komend?? `npm run build`
- skopiuj zbudowan?? aplikacj?? do folderu Applications lub je??li u??ywasz systemu Windows uruchom instalator.

W przypadku jakichkolwiek pyta?? podczas korzystania z **Mark Text** zacz??camy do zg??oszenia problemu. Mamy nadziej??, ??e b??dziesz trzyma?? si?? ustalonego z g??ry formatu zg??aszania problem??w. Wspaniale by by??o, je??eli to w??a??nie ty naprawisz b????d i zg??osisz pull request.

## Udzia?? w projekcie

Mark Text jest w trakcie rozwijania. Upewnij si??, ??e przeczyta??e?? [Contributing Guide](../../CONTRIBUTING.md) przed stworzeniem pull request. Chcesz doda?? nowe udogodnienia do Mark Text? Udaj si?? do [TODO LIST](../../.github/TODOLIST.md)

Dzi??kujemy wszystkim osobom, kt??re ju?? wzi????y udzia?? w projekcie Mark Text! Je??eli ju?? jeste?? cz??onkiem [contributors](https://github.com/marktext/marktext/graphs/contributors), otw??rz pull request aby doda?? twoje imi?? i zdj??cie do poni??szej listy os??b, kt??re pomog??y przy projekcie.

Specjalne podzi??kowania dla @[Yasujizr](https://github.com/Yasujizr), kt??ry zaprojektowa?? logo Mark Text.

| [![Jocs](https://avatars0.githubusercontent.com/u/9712830?s=150&v=4)](https://github.com/Jocs) | [![ywwhack](https://avatars1.githubusercontent.com/u/8746197?s=150&v=4)](https://github.com/ywwhack) | [![notAlaanor](https://avatars1.githubusercontent.com/u/17591936?s=150&v=4)](https://github.com/notAlaanor) | [![fxha](https://avatars1.githubusercontent.com/u/22716132?s=150&v=4)](https://github.com/fxha) |
|:----------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------:|
| [Jocs](https://github.com/Jocs)                                                                | [ywwhack](https://github.com/ywwhack)                                                                | [notAlaanor](https://github.com/notAlaanor)                                                                 | [fxha](https://github.com/fxha)                                                                 |

### Licencja

 [**MIT**](../../LICENSE).

Copyright (c) 2017-present, @Jocs

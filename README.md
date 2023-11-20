<h1 align="center">
  <img src="./src/assets/image/logo.png" alt="Clash" width="128" />
  <br>
  Clash Verge
  <br>
</h1>

<h3 align="center">
A 接盘 Clash Meta GUI based on <a href="https://github.com/tauri-apps/tauri">tauri</a>.
</h3>

## Features

- Since the clash core has been removed. The project no longer maintains the clash core, but only the Clash Meta core.
- Profiles management and enhancement (by yaml and Javascript). [Doc](https://github.com/catherndoukasrsm/clash-verge/wiki/%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)
- Simple UI and supports custom theme color.
- Built-in support [Clash.Meta](https://github.com/MetaCubeX/Clash.Meta) core.
- System proxy setting and guard.

## Promotion

[狗狗加速 —— 技术流机场 Doggygo VPN](https://狗狗加速.com)

- 高性能海外机场，免费试用，优惠套餐，解锁流媒体，全球首家支持 Hysteria 协议。
- 使用 Clash Verge 专属邀请链接注册送 3 天，每天 1G 流量免费试用：https://verge.狗狗加速.com/#/register?code=oaxsAGo6
- Clash Verge 专属 8 折优惠码: verge20 (仅有 500 份)
- 优惠套餐每月仅需 15.8 元，160G 流量，年付 8 折
- 海外团队，无跑路风险，高达 50% 返佣
- 集群负载均衡设计，高速专线(兼容老客户端)，极低延迟，无视晚高峰，4K 秒开
- 全球首家 Hysteria 协议机场，现已上线更快的 `Hysteria2` 协议(Clash Verge 客户端最佳搭配)
- 解锁流媒体及 ChatGPT
- 官网：https://狗狗加速.com

## Install

Download from [release](https://github.com/catherndoukasrsm/clash-verge/releases). Supports Windows x64, Linux x86_64 and macOS 11+

- [Windows x64](https://github.com/catherndoukasrsm/clash-verge/releases/download/v1.3.9/Clash.Verge_1.3.9_x64_en-US.msi)
- [macOS intel](https://github.com/catherndoukasrsm/clash-verge/releases/download/v1.3.9/Clash.Verge_1.3.9_x64.dmg)
- [macOS arm](https://github.com/catherndoukasrsm/clash-verge/releases/download/v1.3.9/Clash.Verge_1.3.9_aarch64.dmg)
- [Linux AppImage](https://github.com/catherndoukasrsm/clash-verge/releases/download/v1.3.9/clash-verge_1.3.9_amd64.AppImage)
- [Linux deb](https://github.com/catherndoukasrsm/clash-verge/releases/download/v1.3.9/clash-verge_1.3.9_amd64.deb)
- [Fedora Linux](https://github.com/catherndoukasrsm/clash-verge/issues/352)

Or you can build it yourself. Supports Windows, Linux and macOS 10.15+

Notes: If you could not start the app on Windows, please check that you have [Webview2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section) installed.

### FAQ

#### 1. **macOS** "Clash Verge" is damaged and can't be opened

open the terminal and run `sudo xattr -r -d com.apple.quarantine /Applications/Clash\ Verge.app`

## Development

You should install Rust and Nodejs, see [here](https://tauri.app/v1/guides/getting-started/prerequisites) for more details. Then install Nodejs packages.

```shell
yarn install
```

Then download the clash binary... Or you can download it from [clash meta release](https://github.com/MetaCubeX/Clash.Meta/releases) and rename it according to [tauri config](https://tauri.studio/docs/api/config/#tauri.bundle.externalBin).

```shell
# force update to latest version
# yarn run check --force

yarn run check
```

Then run

```shell
yarn dev

# run it in another way if app instance exists
yarn dev:diff
```

Or you can build it

```shell
yarn build
```

## Todos

> This keng is a little big...

## Screenshots

<div align="center">
  <img src="./docs/demo1.png" alt="demo1" width="32%" />
  <img src="./docs/demo2.png" alt="demo2" width="32%" />
  <img src="./docs/demo3.png" alt="demo3" width="32%" />
  <img src="./docs/demo4.png" alt="demo4" width="32%" />
  <img src="./docs/demo5.png" alt="demo5" width="32%" />
  <img src="./docs/demo6.png" alt="demo6" width="32%" />
</div>

### Custom Theme

<div align="center">
  <img src="./docs/color1.png" alt="demo1" width="16%" />
  <img src="./docs/color2.png" alt="demo2" width="16%" />
  <img src="./docs/color3.png" alt="demo3" width="16%" />
  <img src="./docs/color4.png" alt="demo4" width="16%" />
  <img src="./docs/color5.png" alt="demo5" width="16%" />
  <img src="./docs/color6.png" alt="demo6" width="16%" />
</div>

## Disclaimer

This is a learning project for Rust practice.

## Contributions

Issue and PR welcome!

## Acknowledgement

Clash Verge was based on or inspired by these projects and so on:

- [tauri-apps/tauri](https://github.com/tauri-apps/tauri): Build smaller, faster, and more secure desktop applications with a web frontend.
- [Dreamacro/clash](https://github.com/Dreamacro/clash): A rule-based tunnel in Go.
- [MetaCubeX/Clash.Meta](https://github.com/MetaCubeX/Clash.Meta): A rule-based tunnel in Go.
- [Fndroid/clash_for_windows_pkg](https://github.com/Fndroid/clash_for_windows_pkg): A Windows/macOS GUI based on Clash.
- [vitejs/vite](https://github.com/vitejs/vite): Next generation frontend tooling. It's fast!

## License

GPL-3.0 License. See [License here](./LICENSE) for details.

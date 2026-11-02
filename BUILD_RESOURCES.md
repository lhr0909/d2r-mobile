# 本机构建资源记录

预构建 IPA 和本地游戏资源来源：[jiayx/d2r-mobile-build](https://github.com/jiayx/d2r-mobile-build)。

2026-11-03，iPhone 通过 USB 覆盖更新至 [v2.2.4 build 19.1](https://github.com/jiayx/d2r-mobile-build/releases/tag/v2.2.4-build.19.1)。沿用 Botisan AI 团队（`NFKM5YQJD7`）和 Bundle ID `io.divby0.d2r`。

本次文件保存在项目根目录：

- 原始 IPA：`D2RMobile-v2.2.4-build.19.1.ipa`，已通过发布方 SHA-256 校验。
- 重签 IPA：`D2RMobile-v2.2.4-build.19.1-Botisan.ipa`。
- 两个 IPA 的校验文件：`D2RMobile-v2.2.4-build.19.1-SHA256SUMS.txt`，同时登记在 `SHA256SUMS.txt`。

按本次确认沿用已有的游戏资源（3.3.94012 / Switch 1.0.34.0）；手机上的 18 个档案全部通过新版校验。旧版 IPA 和完整的 `D2R-Mobile-Resources.zip` 继续保留。

更新前的 Documents 备份位于 `artifacts/iphone-update-2026-11-03/Documents`，校验清单位于同目录的 `backup-sha256.json`。覆盖安装后核对了全部 23 个存档文件，内容与更新前一致；启动后已确认进入原有角色的选择画面。

安装包、资源、校验文件和备份均保存在本地，由 Git 忽略规则排除。校验本次两个安装包可运行：`shasum -a 256 -c D2RMobile-v2.2.4-build.19.1-SHA256SUMS.txt`。

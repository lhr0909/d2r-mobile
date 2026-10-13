# 本机构建资源来源

本次使用的预构建 IPA 和游戏资源来自 [jiayx/d2r-mobile-build](https://github.com/jiayx/d2r-mobile-build)。

`D2RMobile-Botisan.ipa` 由 `D2RMobile-unsigned.ipa` 使用 Botisan AI 团队重新签名生成，Bundle ID 为 `io.divby0.d2r`。

两个 IPA、完整的 `D2R-Mobile-Resources.zip` 和校验文件保存在项目根目录，由本地 Git 忽略规则排除。`SHA256SUMS.txt` 记录三个完整文件的 SHA-256，可在项目根目录运行 `shasum -a 256 -c SHA256SUMS.txt` 校验。

# MoonScoop
用于安装一些特殊定义过的软件, 如汉化、小众

> 🎯[Scoop安装使用(熟悉用户跳过)](https://zhoumoon.github.io/2022/09/02/Windows/Scoop%E5%AE%89%E8%A3%85%E4%BD%BF%E7%94%A8%E8%AE%B0%E5%BD%95/)
#### 🎨添加 buckt
`scoop bucket add moonscoop https://github.com/ZhouMoon/MoonScoop`
##### 测试(可跳过)
- 安装hello程序
`scoop install moonscoop/hello`
- 执行hello程序
    - 执行: `hello.cmd`
    - 结果: Hello, moon!
- 卸载 `scoop uninstall moonscoop/hello`
- 清理缓存 `scoop cache rm hello`

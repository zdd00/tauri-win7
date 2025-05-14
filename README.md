# Tauri + Vue 3

这个模板将帮助您快速开始使用 Tauri + Vue 3 + Vite 进行开发。兼容win7
![image](1.png)

## 适配win7需要的改动

### 1.安装rust

[官网](https://www.rust-lang.org/tools/install)

### 2.rust降级至1.77.2

[参考](https://github.com/tauri-apps/tauri/issues/12550)

``` shell
  # 安装 1.77.2
  rustup install 1.77.2
  # 切换到 1.77.2
  rustup default 1.77.2
  # 验证
  rustc --version
```

## 打包问题参考

[从零开始的 Tauri 开发 & 打包成 exe 【Windows 平台】](https://blog.csdn.net/u010263423/article/details/136006546)

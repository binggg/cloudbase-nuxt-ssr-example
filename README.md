<a href="https://github.com/TencentCloudBase/cloudbase-templates"><img src="https://main.qcloudimg.com/raw/338ce75aaf22e407a02d8b5f096212d0.png"></a>

# Nuxt SSR 应用示例

这个目录是基于云开发的一个 [Nuxt-SSR](https://zh.nuxtjs.org/) 应用示例，包含 Nuxt + 云函数 + 静态网站部署，可以基于 **[CloudBase Framework](https://github.com/TencentCloudBase/cloudbase-framework)** 框架将项目一键部署到云开发环境

## 线上演示地址

[https://framework-14c813.service.tcloudbase.com/nuxt-ssr/](https://framework-14c813.service.tcloudbase.com/nuxt-ssr/)

## 部署一个 Nuxt SSR 应用

### 步骤一. 准备工作

具体步骤请参照 [准备云开发环境和 CloudBase CLI 命令工具](https://github.com/TencentCloudBase/cloudbase-framework/blob/master/CLI_GUIDE.md)

### 步骤二. 修改配置

- 修改 `cloudbaserc.json` 中的 envId 为自己的云开发环境 id
- 修改 `nuxt.config.js` 中的 publicPath 字段为自己的云开发静态域名（也可以是自定义域名） + /nuxt-ssr/

例如
"https://framework-14c813-1259727701.tcloudbaseapp.com/nuxt-ssr/",

### 步骤三. 一键部署

进入到项目目录，在命令行执行

```
npm run deploy
```

## 开发命令及配置

### 本地开发

```
npm run dev
```

### 上线部署

```
npm run deploy
```

### Lint

```
npm run lint
```

### CloudBase Framework 相关开发配置

查看 [CloudBase Framework 配置](https://github.com/TencentCloudBase/cloudbase-framework).

### Nuxt 相关开发配置

查看 [Configuration Reference](https://zh.nuxtjs.org/guide/configuration).

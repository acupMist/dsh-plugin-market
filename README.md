# DeepSeek Harness 插件市场索引

为 [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) Web GUI 插件页「**发现**」标签页提供的插件索引源（format 1）。

## 使用方法

1. 在 DSH 中打开 **插件** → **实验性插件**，开启 **自定义插件索引**。
2. 选择 **发现** 标签页 → **添加索引源**，粘贴：

   ```
   https://raw.githubusercontent.com/acupMist/dsh-plugin-market/main/index.json
   ```

## 内容

列出 DeepSeek 官方发布在 npm 上的 DSH 组合包（bundle），包括 ACP / Headless / SDK / Web 应用入口组合包、子智能体后端、以及实验性组合包。

索引由 npm 注册表数据自动构建（仅收录声明 `dsh.bundle`、未弃用且非私有的版本），可用仓库内脚本重新生成后直接推送更新，同一 URL 持续有效。

> 注意：索引为第三方内容，安装前请核对 DSH 安装确认框中显示的来源。

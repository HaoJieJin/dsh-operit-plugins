# DSH Operit Plugins

**🌐 [English](README.md) | [简体中文](README.zh-CN.md)**

适用于 DeepSeek Harness (DSH) 移动智能体平台的 Operit 兼容工具插件。

## 插件

| 文件 | 说明 |
|---|---|
| `time.js` | 当前时间辅助工具 |
| `system_tools.js` | 系统操作：设置管理、应用安装/卸载与启动、通知、定位、设备信息、Intent/广播执行 |
| `extended_file_tools.js` | 扩展文件操作 |
| `extended_http_tools.js` | 扩展 HTTP 辅助工具 |

每个文件都是自包含的，在其头部注释中嵌入了自身的元数据（名称、显示名称、描述、工具 schema），可直接作为 Operit / DSH 插件加载。

## 许可证

MIT

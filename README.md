# 识镜素材管家 Skill

这是识镜素材管家的公开 Skill，用于指导支持 Skill 的 AI 客户端通过 MCP 只读检索和读取当前组织内有权限的图片、视频、字幕、分镜及短时媒体链接。

## 安装

将下面的请求交给支持安装 Skill 的 AI 客户端：

```text
请帮我安装skill。
仓库地址：https://github.com/leoyang-22/shijing-media-skill
Skill路径：SKILL.md
安装完成后帮我检查 MCP 是否连接成功。
```

安装 Skill 后，还需要在客户端配置识镜素材管家的 MCP 服务地址和个人访问令牌。Skill 本身不包含令牌、业务数据或后端代码。

## MCP 服务地址

正式环境请使用部署后的 HTTPS 地址：

```text
https://你的正式域名/api/v1/mcp
```

认证方式为 `Bearer Token`，令牌在识镜素材管家「用户中心 → 个人访问令牌」中生成。

完整使用规则和安全边界请阅读 [SKILL.md](./SKILL.md)。

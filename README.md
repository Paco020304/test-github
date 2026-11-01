# DeepSeek Harness → GitHub 绑定测试

此仓库用于验证：DeepSeek Harness（本工作区）写出的代码可以直接推送到 GitHub。

- GitHub 账号：**Paco020304**
- 认证方式：SSH 密钥（`~/.ssh/id_ed25519`）
- 传输协议：`git@github.com:Paco020304/<repo>.git`

## 当前状态

| 项目 | 状态 |
|------|------|
| Git | 已安装 2.52.0 |
| GitHub SSH 认证 | 通过（身份 Paco020304） |
| 直接 push 到已有仓库 | 可用 |
| 自动新建仓库（gh / Token） | 待配置 |

## 使用方式

之后你只要说类似：

> “写一个 xxx，并推送到我的 GitHub 仓库 `<repo>`”

我就可以直接 `git commit` + `git push`。

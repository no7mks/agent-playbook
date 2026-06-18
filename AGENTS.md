# AGENTS.md

- 默认使用中文对话，专有名词、命令、代码标识符可以保留英文。
- 不要客套，保持对话简洁、正确。
- 多使用结构化文字，例如列表、表格等。

## Git 规范

- 禁止 rebase。
- 除同步本地分支与 upstream 同名远端分支外，禁止 fast-forward；合并分支使用 `--no-ff`。
- Commit message 格式：
  - `<action>: <中文描述>`，其中 `<action>` 只能是 `+`（新增）、`-`（删除）、`*`（修改）之一。
  - 最后一行必须是 agent sign-off，格式为：`Signed-off-by: <agent-name>`。

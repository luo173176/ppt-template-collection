# manifests

- `files.csv` —— 214 个源文件（155 套 PPT + 59 个字体文件）的完整清单：
  - `storage`：`repo`（已入库）、`release`（Release 附件）、`duplicate`（内容重复，未重复收录）
  - `repo_path`：仓库内相对路径（仅 `repo`）
  - `source` / `source_rel`：来源目录与原始相对路径
  - `bytes` / `sha256`：字节数与 SHA-256
- `release-assets.csv` —— 23 个 Release 附件：`name`（实际附件名，ASCII）、`display`（原始中文文件名）、大小、SHA-256 与下载地址。

# learn-ai-an

学习与作业仓库。

## 目录结构

| 路径 | 用途 |
|---|---|
| `task-0/` | 第 0 次作业 |
| `task-1/` `task-2/` … | 后续每次作业新建一个目录 |

## 提交方式

每次作业完成后：

```bash
git status -sb                          # 1. 看有哪些改动
git add task-0                          # 2. 加入暂存区（只加本次作业）
git commit -m "task-0: 完成第 0 次作业"   # 3. 存档
git push                                # 4. 上传到 GitHub
```

推完用 `git status -sb` 确认，输出为 `## main...origin/main` 且没有 ahead/behind 提示，就是同步成功。

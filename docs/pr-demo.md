# 连接器演示：PR + Review 全流程

这是 2026-11-16 由 Chief（DeepSeek Harness Bot）通过 GitHub 连接器自动创建的演示文件。

## 演示了哪几步

1. 从 `main` 切出分支 `demo/pr-flow`
2. 在分支上新增本文件并提交（commit）
3. 用这个分支开一个 Pull Request
4. 在 PR 上发一条逐行 review 评论（pending review → submit）
5. 给出 review 结论：通过 / 有条件通过 / 打回

## 为什么这对你的团队有用

- 户部改台词、工部改管线，都在分支上做，主分支永远是可发布状态
- 每次修改自动留痕：谁改的、改了什么、为什么
- 廷尉审产物时，直接看 diff 就行，不用来回传文件

## 清理方式

演示结束后可以：关闭 PR、删除 `demo/pr-flow` 分支、删除本文件。都不会影响 `main`。

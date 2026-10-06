# 全量场景索引（89 条）

> 按源仓库 `k88hudson/git-flight-rules`（master）章节顺序排列。
> 每条给出**中文译名**与**英文原名**。本索引仅作导航，具体修复命令请查阅源项目 README。
> 统计口径见 [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md)。

## 1. 仓库 Repositories（4）

1. 启动一个本地仓库 — I want to start a local repository
2. 克隆一个远程仓库 — I want to clone a remote repository
3. 设置了错误的远程仓库 — I set the wrong remote repository
4. 想给别人的仓库贡献代码 — I want to add code to someone else's repository

## 2. 编辑提交 Editing Commits（13）

5. 我刚提交了什么？ — What did I just commit?
6. 提交信息写错了 — I wrote the wrong thing in a commit message
7. 提交时配错了用户名和邮箱 — I committed with the wrong name and email configured
8. 想从上一个提交里移除一个文件 — I want to remove a file from the previous commit
9. 想把一个改动从一个提交移到另一个提交 — I want to move a change from one commit to another
10. 想删除或撤销最后一个提交 — I want to delete or remove my last commit
11. 删除/移除任意提交 — Delete/remove arbitrary commit
12. amended 提交推送到远程时报错 — I tried to push my amended commit to a remote, but I got an error message
13. 不小心 hard reset，想找回改动 — I accidentally did a hard reset, and I want my changes back
14. 不小心提交并推送了一个合并 — I accidentally committed and pushed a merge
15. 不小心提交并推送了含敏感数据的文件 — I accidentally committed and pushed files containing sensitive data
16. 想把大文件从仓库历史中彻底抹除 — I want to remove a large file from ever existing in repo history
17. 想修改某个非最新提交的内容 — I need to change the content of a commit which is not my last

## 3. 暂存 Staging（9）

18. 暂存所有已跟踪文件、保留未跟踪文件 — I want to stage all tracked files and leave untracked files
19. 暂存所有未跟踪文件、保留已跟踪文件 — I want to stage all untracked files and leave tracked files
20. 把已暂存改动补到上一个提交 — I need to add staged changes to the previous commit
21. 只暂存新文件的一部分而非整个文件 — I want to stage part of a new file, but not the whole file
22. 把一个文件的改动分到两个不同提交 — I want to add changes in one file to two different commits
23. 暂存太多改动，想拆成单独提交 — I staged too many edits, and I want to break them out into a separate commit
24. 暂存未暂存改动、同时取消已暂存改动 — I want to stage my unstaged edits, and unstage my staged edits
25. 取消暂存某个特定已暂存文件 — I want to unstage a specific staged file
26. 选择整文件来暂存 — I want to choose which entire files to stage

## 4. 放弃修改 Discarding changes（5）

27. 放弃本地未提交改动（含已暂存与未暂存） — I want to discard my local uncommitted changes (staged and unstaged)
28. 放弃特定的未暂存改动 — I want to discard specific unstaged changes
29. 放弃特定的未暂存文件 — I want to discard specific unstaged files
30. 只放弃未暂存的本地改动 — I want to discard only my unstaged local changes
31. 放弃所有未跟踪文件 — I want to discard all of my untracked files

## 5. 分支 Branches（20）

32. 列出所有分支 — I want to list all branches
33. 从某个提交创建分支 — Create a branch from a commit
34. 从/向错误的分支 pull — I pulled from/into the wrong branch
35. 丢弃本地提交使分支与服务器一致 — I want to discard local commits so my branch is the same as one on the server
36. 把未暂存改动移到新分支 — I want to move my unstaged edits to a new branch
37. 把未暂存改动移到另一个已存在分支 — I want to move my unstaged edits to a different, existing branch
38. 本想建新分支却提交到了 main — I committed to main instead of a new branch
39. 从另一个引用整文件保留 — I want to keep the whole file from another ref-ish
40. 单分支上多个本应分属不同分支的提交 — I made several commits on a single branch that should be on different branches
41. 删除上游已删除的本地分支 — I want to delete local branches that were deleted upstream
42. 不小心删除了分支 — I accidentally deleted my branch
43. 删除一个分支 — I want to delete a branch
44. 删除多个分支 — I want to delete multiple branches
45. 重命名分支 — I want to rename a branch
46. checkout 到别人正在协作的远程分支 — I want to checkout to a remote branch that someone else is working on
47. 从当前本地分支创建新远程分支 — I want to create a new remote branch from current local one
48. 为本地分支设置远程上游分支 — I want to set a remote branch as the upstream for a local branch
49. 让 HEAD 跟踪默认远程分支 — I want to set my HEAD to track the default remote branch
50. 在错误的分支上做了改动 — I made changes on the wrong branch
51. 把一个分支拆成两个 — I want to split a branch into two

## 6. 变基与合并 Rebasing and Merging（6）

52. 撤销 rebase/merge — I want to undo rebase/merge
53. rebase 了但不想 force push — I rebased, but I don't want to force push
54. 合并多个提交 — I need to combine commits
55. 更新分支的父提交 — I need to update the parent commit of my branch
56. 检查某分支所有提交是否已合并 — Check if all commits on a branch are merged
57. 交互式 rebase 的常见问题 — Possible issues with interactive rebases

## 7. 储藏 Stash（5）

58. 储藏所有改动 — Stash all edits
59. 储藏特定文件 — Stash specific files
60. 带信息储藏 — Stash with message
61. 从列表应用某个特定储藏 — Apply a specific stash from list
62. 储藏但保留未暂存改动 — Stash while keeping unstaged edits

## 8. 查找 Finding（5）

63. 在任意提交中查找字符串 — I want to find a string in any commit
64. 按作者/提交者查找 — I want to find by author/committer
65. 列出包含特定文件的提交 — I want to list commits containing specific files
66. 查看某个函数的提交历史 — I want to view the commit history for a specific function
67. 查找引用某提交的标签 — Find a tag where a commit is referenced

## 9. 子模块 Submodules（2）

68. 克隆所有子模块 — Clone all submodules
69. 移除一个子模块 — Remove a submodule

## 10. 杂项对象 Miscellaneous Objects（7）

70. 把文件夹/文件从一个分支复制到另一个 — Copy a folder or file from one branch to another
71. 恢复已删除的文件 — Restore a deleted file
72. 删除标签 — Delete tag
73. 恢复已删除的标签 — Recover a deleted tag
74. 补丁被删除（PR 原 fork 被删） — Deleted Patch
75. 把仓库导出为 Zip 文件 — Exporting a repository as a Zip file
76. 推送同名的分支和标签 — Push a branch and a tag that have the same name

## 11. 跟踪文件 Tracking Files（6）

77. 不改内容改文件名大小写 — I want to change a file name's capitalization, without changing the contents of the file
78. git pull 时覆盖本地文件 — I want to overwrite local files when doing a git pull
79. 把文件从 Git 移除但保留文件 — I want to remove a file from Git but keep the file
80. 把文件回退到特定版本 — I want to revert a file to a specific revision
81. 列出某文件在提交/分支间的改动 — I want to list changes of a specific file between commits or branches
82. 让 Git 忽略对特定文件的改动 — I want Git to ignore changes to a specific file

## 12. Git 调试 Debugging with Git（0）

- 无 `###` 条目；本节约 30 行正文讲解 `git bisect` 二分定位引入 bug 的提交。

## 13. 配置 Configuration（5）

83. 为 Git 命令添加别名 — I want to add aliases for some Git commands
84. 往仓库添加空目录 — I want to add an empty directory to my repository
85. 为仓库缓存用户名密码 — I want to cache a username and password for a repository
86. 让 Git 忽略权限与 filemode 变化 — I want to make Git ignore permissions and filemode changes
87. 设置全局用户信息 — I want to set a global user

## 14. 完全不知道自己干了什么 I've no idea what I did wrong（0）

- 无 `###` 条目；本节约 20 行正文讲解 `git reflog` 急救。

## 15. Git 快捷方式 Git Shortcuts（2）

88. Git Bash 别名与函数 — Git Bash
89. Windows 上的 PowerShell 别名与函数 — PowerShell on Windows

## 16–19. 书籍 / 教程 / 脚本工具 / GUI 客户端（0）

- 这四节为资源推荐列表（Books、Tutorials、Scripts and Tools、GUI Clients），不含事故场景条目。

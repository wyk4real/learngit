git checkout & git restore
-	git checkout <filename> # 将指定文件恢复到最后一次提交时的状态，丢弃工作目录中的所有未提交的更改。
-	git checkout <commit> <filename> # 将指定文件恢复到指定提交时的状态。
-	git restore <filename> # 将指定文件恢复到最后一次提交时的状态。
-	git restore --source=<commit> <filename> # 将指定文件恢复到指定提交时的状态。

git checkout 和 git restore 都可以用于恢复未提交文件更改，但它们的区别在于对工作目录的影响：
-	git checkout：恢复文件时会强制切换到最后一次提交时的状态，丢弃所有未提交的更改。这意味着如果在切换分支或恢复文件时不小心丢失了未提交的更改，是无法找回的。
-	git restore：只会恢复指定文件，不会影响其他未提交的更改。即使在恢复文件时，也可以选择只恢复特定文件而不是整个工作目录，避免意外丢失未提交的更改。

结束：xxx



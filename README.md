# magit-study
个人magit test

# git 操作

## git init


## git status


## git add .


## git commit -m ""


## git pull  远程分支


## git push 远程分支

## git merge


## git rebase


## git continue

## git 解决冲突

~~~

git 解决冲突还是很牛比的，是这样的做的。

magit-status C-x g 调用 status 页面

magit-ediff 此时直接 E 键就可以了。（如何要解决冲突的文件太多，可以 p 或 n 来选择要解决冲突文件）

这时候会出现三个 buffer 。 即：A : 显示是本地文本。 B: 远程分支的文件。 C： 显示合并完成后的样子。
这时候按一个 ? 调用出帮助区。可以看到，n 显示下个不同的地方，p 显示上个不同的地止。选中要合并不同区的地方，按一下 b 可以把b区复制到 C 区。按一下 a 可以把 A 区复制到C区。按 SPC 确认，做下一个冲突。

然后直接再 c 打入A的 hotfix 部分。满意后按q然后保存退出。

~~~

可以参考： https://ithelp.ithome.com.tw/articles/10201002

## git 不同分支在任意commit id 下代码对比



## git 同一分支不同的 commit id 代码对比

# Lazygit使用

## lazygit add


假设你修改了文件，并进行`Ctrl`+`S`保存，lazygit会自动检测到你的修改，最好是多改几个文件，多修几行

- 在[2]中File-Worktrees-Submodules中的`File`中，可以看到当前修改的文件是`01-基础教程`，前面有`M`表示正在修改

1. 你可以直接使用`Space`空格键，直接相当于`git add file.txt`文件
2. 你可以使用`a`,表示直接使用`git add ./`，把所有修改的文件都添加到暂存区

- 点击当前的文件，然后按`Enter`回车键，进入文件修改界面
- 就是[0]状态栏中显示的样子(分为Ubstaged changes和Staged Changes)

> @@ -a,b +c,d @@ 表示：
> 旧文件从第 a 行开始的 b 行，被新文件中从第 c 行开始的 d 行替换。
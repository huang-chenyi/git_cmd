# 基础操作
1. 在需要上传的文件夹内打开控制台
 
2. ls：查看当前目录下的文件
 
3. **在github上创建仓库**

4. **git init:初始化一个本地git仓库**
 
5. git config --list:查看当前本地仓库配置（查看是否有git remote add origin https://github.com/huang-chenyi/仓库名.git）
 
6. **如果没有则输入git remote add origin https://github.com/huang-chenyi/仓库名.git**

   https://github.com/THINKER-ONLY/EdibleGod.git

7. **git branch -M main：推送至主分支**
 
8. **git add .:将本地仓库文件放到暂存区**

   **git add <文件名>：只添加特定的文件**
 
9. **git commit -m"[中间放置对提交东西的注释]"**
 
10. **git push origin main：推送（结束）**

11. **git clone https://github.com/…………:克隆远程仓库**

12. **git checkout -b <分支名>：创建一个新的分支**

13. **git push -u origin <分支名>：向分支推送**

14. **git branch -d feature/old-branch** 

    **git push origin --delete feature/old-branch**

    **删除本地和远程分支**



# 其他
11. git branch <分支名>：创建分支

12. git checkout <分支名>：切换到分支（若已经提交或者已经切换，会进行查看操作）

    或者git checkout -b <your-branch-name>一步完成创建和切换

13. git merge <要合并的分支名或main>：合并分支（将<>中的合并至当前支线或主线）

14. git rebase <要复制的分支名或main>（将<>中的合并至当前支线或主线-以复制的形式）（前置要求是两个支线要求均提交）

15. git checkout HEAD^：向上移动查看分支提交记录的指针

16. git checkout HEAD~<number>（波浪号，esc下面的键）

17. 移动分支。可以直接使用 -f 选项让分支指向另一个提交。

    例如:git branch -f main HEAD~3（波浪号，esc下面的键）

    上面的命令会将 main 分支强制指向 HEAD 的第 3 级 parent 提交。

    HEAD似乎是强制要求的指令

18. 切换到本地仓库的根目录。

    使用以下命令将另一个文件夹中的文件添加到本地仓库：

    bash git add /path/to/another/folder
    
    将/path/to/another/folder替换为另一个文件夹的实际路径。

19. git status：查看暂存区的内容

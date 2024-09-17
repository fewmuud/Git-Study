# 用于学习Git

## 如果远程仓库存在文件，但本地仓库没有
首先，你需要将远程仓库的更改拉取到本地。这可以通过 `git pull` 命令来完成。这个命令会将远程仓库的更改合并到你的本地仓库中。

然后，你可以将你的本地更改推送到远程仓库。这可以通过 `git push` 命令来完成。

以下是具体的步骤：

1. 打开你的终端。

2. 切换到你的本地仓库的目录。

3. 使用 `git pull` 命令拉取远程仓库的更改：

    ```shell
    git pull origin main
    ```

    在这个命令中，`origin` 是远程仓库的名称，`main` 是你要拉取的分支的名称。

4. 使用 `git add` 命令将你的更改添加到暂存区：

    ```shell
    git add .
    ```

    在这个命令中，`.` 表示当前目录及其所有子目录。

5. 使用 `git commit` 命令将你的更改提交：

    ```shell
    git commit -m "Your commit message"
    ```

    在这个命令中，你应该将 "Your commit message" 替换为描述你的更改的信息。

6. 使用 `git push` 命令将你的更改推送到远程仓库：

    ```shell
    git push origin main
    ```

    在这个命令中，`origin` 是远程仓库的名称，`main` 是你要推送的分支的名称。

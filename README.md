# idea中使用git同步项目到GitHub
## 1.安装git

* 安装中选择独立的git命令行

* 安装成功后桌面右键git bash设置用户名和邮箱

  * ```c
    $ git config --global user.name "dlt"
    $ git config --global user.email "qqnumber@qq.com"
    ```

## 2.idea中上传项目到本地

* `file` ,`settings` ,`version control` 中设置`git` 和`github` 。**测试连接性**。

* `CVS` ,`import version control` ,`creat git repository` 选择项目所在目录**创建本地仓库**。

* 右键项目`git` ,`add` 添加项目到本地暂存区。`commit` 提交项目到本地仓库。

  * commit时，author处可以填上本地git仓库的用户名和邮箱，格式为

    ```c
    dlt<qqnumber@qq.com>
    ```

## 3.idea中上传项目到GitHub

* 在GitHub中创建仓库，先不要创建readme，不然idea中无法pull项目来同步。
* idea中把GitHub中的仓库pull过来同步一下，然后push。
* 期间会提示输入GitHub仓库的htttp地址。
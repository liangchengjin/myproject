1. 克隆下载
git clone 地址
如：
    git clone https://github.com/xxx/myproject.git

2. 在自己的项目下面创建一个文件
    如：
        index.html

3. 添加文件
    git add -A    // 这是添加所有的文件意思
    git add index.html index.js  // 这是添加单个文件

3.1 如果我们有一个文件提交上去了。要想删除
    git rm index.html

4. 查看状态
    git status  // 查看当前增加的文件


5. 增加到暂存区
    git commit -m"注释说明"   // 把文件增加到暂存区等待上传到服务器

5. 拉取服务器上的文件到本地行对比
    git pull origin master   // 拉取服务器上的文件到本地行

6. 提交到服务器
    git push origin master // 把文件提交到服务器上去

7. 查看当前哪些人上传了文件和操作记录日志
    git log //查看日志




    
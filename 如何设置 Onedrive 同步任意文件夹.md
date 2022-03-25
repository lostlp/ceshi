

1\. 找到两个路径

路径一：Onedrive所在目录（**原路径**）

例如：E:\\OneDrive

路径二：需要同步的文件夹路径

例如：F:\\Folder

  

2\. 管理员身份运行 命令提示符

输入以下代码，回车运行：

```text
mklink/d "E:\OneDrive\COPY" "F:\Folder"
```

代码说明：

"E:\\OneDrive\\COPY "中的"COPY"为路径二在Onedrive中的名字，无需提前创建，可以任意输入。

3\. 到这里就已经大功告成了！现在"F:\\Folder"已经添加到了Onedrive中了，并且会自动备份在云端。
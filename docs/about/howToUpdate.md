# 修改内容注意事项

## 修改流程

### 网站直接修改

![image-20231205203408011](https://tuchuang-e682.obs.cn-north-1.myhuaweicloud.com/image-20231205203408011.png)

在相应的页面点击右上角的编辑按钮进行编辑，页面会跳转到GitHub的相关页面：

![image-20231205203633917](https://tuchuang-e682.obs.cn-north-1.myhuaweicloud.com/image-20231205203633917.png)

修改页面之后填写修改信息，新建分支并且提出`pull request`

![image-20231205204008080](https://tuchuang-e682.obs.cn-north-1.myhuaweicloud.com/image-20231205204008080.png)

### 本地修改页面

如果需要添加一级二级目录的话需要`git clone`到本地进行修改，首先需要根据[关于网站页面](https://eswiki.tech/)进行fork项目并且在本地进行环境配置，然后把写好的`.md`文件添加到相应的目录中去，之后编辑项目主目录下的`mkdocs.yml`文件，文件主要修改下图所示的部分：

![image-20231205204641787](https://tuchuang-e682.obs.cn-north-1.myhuaweicloud.com/image-20231205204641787.png)

按照目录顺序仿照上图的方式修改yml文件即可。

之后需要在本地运行然后调试无误后方可push到你fork的仓库内，然后提交pr即可

## 图片问题

关于`ES-Wiki`中的图片，建议使用图床，在`.md`文件中应用相应的url进行使用，如果出现相对目录的文件，会增加后期维护的麻烦，并且pr **不一定可以通过**

## 内容问题

内容上请尽可能简练的描述遇到的问题和解决的办法，但是也鼓励将遇到的过程和解决的流程思路详细的描述出来，内容可以丰富多样，如果需要上传视频等大文件，请上传到bilibili或者其他视频平台然后引用url至此站。同时上传的内容可以在相应部分的结尾注明作者相关信息。

**如果有其他问题，欢迎和本站负责人联系**

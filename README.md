
# Chen Lab Website

Visit **[feifeichen.cn](https://feifeichen.cn)** 🚀

_Built with [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs)_

想要了解项目详细内容（包括本地运行方式），请参考上面一个链接👆。

本项目采用jekyll框架和liquid模版生成静态网站

# 后期增加/修改内容步骤
## 增加homepage 内容
Chen-Lab/index.md 中按照相应格式添加
## 增加publications内容
Chen-Lab/_data/sources.yaml 文件下按照对应格式增加即可
## 增加team成员
- 增加新生：Chen-Lab/_members 下增加对应人的md文件，建议以人名命名，按照博士/硕士参考对应的例子修改；照片放在Chen-Lab/images下
- 老生毕业转为alumni：Chen-Lab/_members 下对应人的md文件中设置  role: alumni
- 硕士转博士：Chen-Lab/_members 下对应人的md文件中设置  role: phd


## 增加album内容
Chen-Lab/album/index.md文件下添加文字/时间/图片

# 缺陷
由于Manubot无法自动搜索部分文献（会出现下面这种报错：Couldn't parse Manubot response），因此采用手动覆盖的形式，将论文内容放在了Chen-Lab/_data/sources.yaml。

# gitPage 部署方式
- push到main分支上去，不管流水线是否成功
- 确定Settings/Pages/Build and deployment/Branch为gh-pages（这个分支专门用来做静态网站的）
- 点击 Action/build-site/run workflow/run workflow(最后这个是绿色按钮),将main分支同步到gh-pages分支
- 等一段时间才会更新内容（10分钟以上）


---

title: "github pages零成本创建自己的博客"

date: 2023-12-30

tags: 教程

---

😆材料：
1.一个github账号
2.一点点github的使用经历
3.一个链接，一会儿会用到：[github链接](https://github.com/new?template_owner=skills&template_name=github-pages&owner=%40me&name=skills-github-pages&description=My+clone+repository&visibility=public)

step1：访问上文链接

step2：根据需求修改Repository name，Description可有可无

step3：点击您仓库的 Settings 菜单，在右栏中找到Pages

step4：在 Build and deployment 栏中 将Source改为Deploy from a branch

step5：在下方branch栏None改为main，点击Save

step6：在项目名下方找到 main 并改为 my-pages

step7：
右上角有个编辑按钮，打开文件编辑器，编辑_config.yml
为了使用minima主题，我们在_config.yml文件里添加下面的内容

`theme: minima`

（可选）您还可以添加其他配置变量，例如站名title:, 作者author:、站点描述description:
提交修改
（可选）创建一个拉取请求以便查看您在本课程中将进行的所有更改。 单击Pull Requests tab，单击New pull request，设置base: main和compare:my-pages

剩下的留给下一期！

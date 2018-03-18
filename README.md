# 项目预览

在这个项目中，你会得到一个基于 web 的用来读取 rss 源的应用。最开始的这个项目的开发者意识到了测试的价值，他们也已经把 [Jasmine](http://jasmine.github.io) 包含在了项目之中，而且甚至已经开始写他们第一个测试用例。但是不幸的是，他们决定去创建一个他们自己的公司，所以我们现在拿到的是一个缺乏完整测试用例的应用，这样是你会参与到这个项目的原因。

## 项目目的

测试是开发过程中一个很重要的部分，很多组织把一个标准的开发过程称之为测试驱动开发。意思就是开发人员在他们开始着手编写应用代码之前先写好测试用例。当然这个时候所有的测试用例都是通不过的，然后他们就开始编写应用代码使测试全部通过。

不管你是在一个推崇测试驱动开发的组织，或者是一个编写测试只是为了防止未来的开发中出现与已有代码冲突的 bug 的团队工作，测试都是我们要掌握的一项重要技能。

## 我会学到什么

你会学到怎么使用 Jasmine 来给已经写好的应用编写一定数量的测试用例。这些测试用例既要测试深层次的商业逻辑，也要测试时间处理和 DOM 操作。

## 这对我的职业有何帮助？

* 编写测试需要分析应用中诸如 html , css , javascript 之类的各个层面。当你换了团队工作或者加入到一个新的公司，这项技能尤其重要（译者注：指阅读新的项目代码的能力）
* 长期编写测试会让你拥有不需要手动编写测试去测试所有的功能就能快速分析新的代码是否和已知代码冲突的能力。


# 我如何完成这个项目

查看订阅阅读器项目的[评审标准](https://review.udacity.com/#!/projects/3442558598/rubric)

1. 上一下 javascript Testing [课程](https://www.udacity.com/course/ud549)
2. 下载[必要的项目资源](http://github.com/udacity/frontend-nanodegree-feedreader))
3. 在浏览器里面查看一下应用的功能
4. 查看项目的 HTMl (**./index.html**), CSS (**./css/style.css**) 和 JavaScript (**./js/app.js**) 文件来对项目的工作原理有一个基本的了解。
5. 查看 Jasmine spec 文件 **./jasmine/spec/feedreader.js** 然后翻阅阅读 [Jasmine 文档](http://jasmine.github.io)。
6. 编辑 **./js/app.js** 里面的 `allFeeds` 变量使给出的测试通不过，然后观察Jasmine是怎么展示你应用的错误信息的。
7. 将 `allFeeds` 变量复原
8. 编写一个测试遍历 allFeeds 对象里面的所有的源来保证有链接字段而且链接不是空的。
9. 编写一个测试遍历 allFeeds 对象里面的所有的源来保证有名字字段而且不是空的。
10. 写一个叫做 `"The menu"` 的测试用例
11. 写一个测试用例保证菜单元素默认是隐藏的。你需要分析 html 和 css 来搞清楚我们是怎么实现隐藏/展示菜单元素的。
12. 写一个测试用例保证当菜单图标被点击的时候菜单会切换可见状态。这个测试应该包含两个 expectation ： 当点击图标的时候菜单是否显示，再次点击的时候是否隐藏。
13. 写一个叫做 `"Initial Entries"` 的测试用例
14. 写一个测试保证 `loadFeed` 函数被调用而且工作正常，即在 `.feed` 容器元素里面至少有一个 `.entry` 的元素。
15. 写一个叫做 `"New Feed Selection"` 的测试用例
16. 写一个测试保证当用 `loadFeed` 函数加载一个新源的时候内容会真的改变。
17. 每个测试都不应该依赖别的测试的结果。
18. 回调函数应该用来保证在测试运行之前源已经被加载。
19. 实现未定义变量和数组越界的错误处理。
20. 当完成所有任务的时候，所有的测试也应该通过。
21. 写一个 README 文件来详细说明运行应用的步骤。如果你已经添加了额外的测试（来提高测试覆盖率），请提供文档说明这些未来的功能点是什么和你编写的测试在检查什么。

Alex的前端纳米学位FeedReader项目
====================


## How to Load the project

- Clone the **[repo](https://github.com/jzsplk/Feed-Reader-Testing_zh.git)** and open index.html

## how to use the project
- click menu to show Feeds
- click Feed to show Details

## Resources used to create the test:

### Test Tool:

- jasmine


#### Udacity Resources:

- [Project Description](https://github.com/udacity/frontend-nanodegree-feedreader)


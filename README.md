# awesome-llvm

## Starchart

# 资源网址（[参考链接](https://llvm.org/docs/GettingInvolved.html)）
- 🐉 [LLVM官网](http://llvm.org/)，以及[文档库](https://llvm.org/doxygen/index.html)
- 🐉 [LLVM 开发者会议及相关活动](https://llvm.org/devmtg/)
  - 📹 [2023年会议视频](https://www.youtube.com/playlist?list=PL_R5A0lGi1AD9nPVlv7mG8_2mMSiL_0Ik)
- 🐉 [LLVM 官方博客](http://blog.llvm.org/)
- 🐉 [讨论社区](https://discourse.llvm.org/)
- 🐉 [LLVM 官方YouTube频道](https://www.youtube.com/@LLVMPROJ/videos?view=0&sort=dd&shelf_id=0) - 包含开发者会议及EuroLLVM等活动
- 🐉 [Open Projects](https://llvm.org/OpenProjects.html) - 开放项目
- [LLVM 每周简报](http://llvmweekly.org/) 及其 [Mastodon页面](https://fosstodon.org/@llvmweekly) - 作者：[Alex Bradbury](https://fosstodon.org/@asb)
- [开源应用架构 - LLVM 章节](http://www.aosabook.org/en/llvm.html)
- [Eli Bendersky's 个人网站](http://eli.thegreenplace.net/)
- [LLVM @ StackOverflow](http://stackoverflow.com/questions/tagged/llvm)
- [LLVM @ Reddit](https://www.reddit.com/r/LLVM/)
- [GitHub LLVM 话题](https://github.com/topics/llvm)

# 教程与文档（[参考链接](http://llvm.org/docs/index.html)）
- 🐉 [LLVM 教程](http://llvm.org/docs/tutorial/index.html) - 教程列表
  - :octocat: [LLVM 教程 Python 版](https://github.com/eliben/pykaleidoscope)
- 🐉 [LLVM 语言参考手册](http://llvm.org/docs/LangRef.html) - LLVM IR/Bitcode 详细文档
  - 🐉 [LLVM Bitcode 文件格式](http://llvm.org/docs/BitCodeFormat.html)
  - 🐉 [常被误解的 GEP 指令](http://llvm.org/docs/GetElementPtr.html)
  - 🐉 [不透明指针](https://llvm.org/docs/OpaquePointers.html) - LLVM 14 引入，LLVM 17 完全废弃了类型化指针
  - [LLVM IR 入门](https://mcyoung.xyz/2023/08/01/llvm-ir/)
  - :octocat: [PSA: 构造函数更改为仅支持迭代器插入](https://github.com/sunxfancy/vscode-llvm) - VSCode LLVM 编译器浏览器插件
- 🐉 [LLVM 开发者手册](http://llvm.org/docs/ProgrammersManual.html) - 如何使用 LLVM 开发
  - 🐉 [LLVM 代码规范](http://llvm.org/docs/CodingStandards.html)
  - 🐉 [LLVM 开发者政策](http://llvm.org/docs/DeveloperPolicy.html)
  - 🐉 [源级调试](http://llvm.org/docs/SourceLevelDebugging.html)
  - 🐉 [LLVM 中的异常处理](http://llvm.org/docs/ExceptionHandling.html)
  - 📹 [ADT 工具箱 - LLVM 开发者工具箱](https://www.youtube.com/watch?v=owQlnNYek2o&list=PL_R5A0lGi1AD9nPVlv7mG8_2mMSiL_0Ik&index=26)
- 🐉 [CommandLine 2.0 库手册](http://llvm.org/docs/CommandLine.html) - LLVM 的命令行选项解析库
- 🐉 [LLVM 系统入门](http://llvm.org/docs/GettingStarted.html) - 构建、配置和目录布局等
- 🐉 [LLVM 的分析和变换 Pass](http://llvm.org/docs/Passes.html)
  - 🐉 [使用新 Pass 管理器](https://llvm.org/docs/NewPassManager.html) - LLVM 的新优化管理器（CLI 和 API 都有所改变）
  - 🐉 [编写 LLVM Pass](http://llvm.org/docs/WritingAnLLVMPass.html)
  - 🐉 [LLVM 别名分析基础架构](http://llvm.org/docs/AliasAnalysis.html)
  - [使用 LLVM Pass 追踪内存访问](https://www.bitsand.cloud/posts/llvm-pass/) - 详细实现内存访问追踪的博客文章
- 🐉 [LLVM 测试基础架构指南](http://llvm.org/docs/TestingGuide.html)
- 🐉 [编写 LLVM Backend](http://llvm.org/docs/WritingAnLLVMBackend.html)
- 🐉 [LLVM 常见问题](http://llvm.org/docs/FAQ.html)
- :octocat: [LLVM-Tutor](https://github.com/banach-space/llvm-tutor) - 用于教学和学习的 LLVM Pass 集合
- :octocat: [学习 LLVM](https://github.com/danbev/learning-llvm) - 用于学习 LLVM 的项目
- :octocat: [LLVM Pass 分析集合](https://github.com/JohannesLiu/LLVM-Pass-Analysis-Collection) - 用于程序分析的 LLVM Pass 集合
- :octocat: [LLVM Pass 教程](https://github.com/delcypher/srg-llvm-pass-tutorial) - [软件可靠性小组](http://srg.doc.ic.ac.uk/)提供的教程
- 📃 [使用 LLVM C API 入门](https://pauladamsmith.com/blog/2015/01/how-to-get-started-with-llvm-c-api.html)
- :octocat: [LLVM 代码示例](https://github.com/lahiri-phdworks/LLVM-Examples) - 包含 LLVM Pass 和快速代码片段
- :octocat: [LLVM IR 示例](https://github.com/wuzhanglin/llvm-IR-examples) - 使用 LLVM 生成 IR 的一些示例
- :octocat: [LLVM IR 教程（中文）](https://github.com/Evian-Zhang/llvm-ir-tutorial)
- 📹 [LLVM 教程视频](https://www.youtube.com/watch?v=09EAVa7BAp4&list=PLSq9OFrD2Q3ChEc_ejnBcO5u9JeT0ufkg) - Toby Ho 的教程
- 📹 [理解编译器优化](https://www.youtube.com/watch?v=FnGCDLhaxKU&t=59s) - Chandler Carruth 在 2015 年 Meeting C++ 的开幕演讲
- 🐉 [学习 LLVM TableGen 的工具](https://blog.llvm.org/posts/2023-12-07-tools-for-learning-llvm-tablegen/) - David Spickett 的教程，介绍 LLVM 的 [TableGen](https://github.com/llvm/llvm-project/tree/main/llvm/utils/TableGen)

# 其他资源
- 还有很多官方工具库、非官方工具库、绑定、以及其他基于LLVM的编程语言的资料，大家可以根据兴趣进一步探索。我们也会不断更新，以帮助大家更好地理解和学习LLVM。

大家如果觉得这些资源有帮助，欢迎分享给更多有兴趣的朋友，共同学习进步。对于刚开始接触编译器开发的小伙伴，LLVM 是一个强大且值得投入的工具，愿大家在学习的道路上走得更远！

如果有更多问题或需要更深入的讨论，也可以留言与我们互动~


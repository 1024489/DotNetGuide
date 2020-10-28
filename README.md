# 🐮C#/.NET/.NET Core学习，面试指南(每周一更🌋)
> 概述：发现网上关于Java、前端、Android...等相关技术的学习资料，面试指南一搜都是一大把的，但是我们大.NET的相关学习资料，面试指南和一些常见的面试题都是寥寥无几，并不是没有人写，而是因为资料和学习技术点太零散了，缺少一个汇总的知识库。因此作为.NET开发中的一员当然是不想让这种现象普遍存在啦，建立这个知识库的初衷就是为了收集、汇总、总结网上优秀的.NET相关学习资料和常见的面试题以及自己的一些微薄的见解供大家参考学习，同时由衷的希望大家可以在Issues中投稿一起完善我们的.NET学习，面试的知识库。
知识库中有总结不足的地方，欢迎各位大佬给我提意见 🙌。
如果这个知识库对大家有帮助的话记得给作者一个星星哟⭐! 



## 🔍目录(善用Ctrl+F)

### 📚[C# 指南（微软提供的最权威，最全面的C#学习资料）][1]
  [1]: https://docs.microsoft.com/zh-cn/dotnet/csharp/
### 📚[.NET 文档（微软提供的最权威，最全面的.NET学习资料）][3]
  [3]:https://docs.microsoft.com/zh-cn/dotnet/
### 📚[.NET 基础知识][2]
  [2]:https://docs.microsoft.com/zh-cn/dotnet/core/introduction
### 📚[ASP.NET Core开发者指南][4]
  [4]:https://github.com/MoienTajik/AspNetCore-Developer-Roadmap/blob/master/ReadMe.zh-Hans.md
### 🛣️[ASP.NET Core学习路线图][6]
   [6]:https://github.com/YSGStudyHards/DotNetGuide/blob/main/docs/dotNet/picture/dotNetRoadMap/aspnetcore-developer-roadmap.zh-Hans.png
### 🏡[C#/.NET Core/.NET项目宝库(收集了大量优秀的C#、.NET、.NET Core项目，欢迎大家加入我们的.NET大家庭)][7]
   [7]:https://github.com/dotNetTreasury


### 📖C#/.NET/.NET Core基础
*  [.NET 中所有类的基类][5]
   >Object

   [5]: https://docs.microsoft.com/zh-cn/dotnet/api/system.object?view=netcore-3.1
   
*  [C#中类和结构的基本概念][8]
   > 类和结构是 .NET通用类型系统的两种基本构造。每种本质上都是一种数据结构，其中封装了同属一个逻辑单元的一组数据和行为。 数据和行为是类或结构的成员，包括字段、方法、属性、索引器、运算符和事件等。
  
  [8]:https://docs.microsoft.com/zh-cn/dotnet/csharp/programming-guide/classes-and-structs/
   
- C#支持的访问修饰符
    - public：共有的，访问不受限制；
    - private：私有的，只能在当前类中访问；
    - internal：内部的，只能在当前程序集中访问；
    - protected：受保护的，只能在当前类或其派生类中访问；
    - protected  internal：受保护的内部成员，当前程序集或派生自包含类的类型可访问；
    - private protected：私有受保护的成员，当前程序集中的包含类或从包含类派生的类型；

*  C#类和结构默认访问修饰符
   > Internal
   
*  C#适用于类和结构访问修饰符有哪些
   > public 或 internal

*  类成员和结构成员的默认访问修饰符为
   > private

*  结构成员（包括嵌套的类和结构）可以声明为
   > public、internal 或 private   注意：结构成员无法声明为 protected、protected internal 或 private protected，因为结构不支持继承。
   
*  类成员（包括嵌套的类和结构）可以声明为
   > public、protected internal、protected、internal、private protected 或 private

*  派生类不能具有高于其基类型的可访问性



### 🧮算法



### 🍇非NoSQL数据库



### 🍉NoSQL数据库
















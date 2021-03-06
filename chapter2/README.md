# 框架基础和技术选型

上一章中我们对需求进行了评审和分析，最终得到了具体要开发的功能点，以及对模块进行了划分。现在我们需要做的是根据要开发的功能进行框架的选择。

针对不同的场景，选择不同的技术架构，所产生的开发成本和维护成本都不一样。特定场景下合适的技术架构能够让开发人员更快速的开发系统，并且后期的维护成本也大大降低。相反，一个不合适的技术架构，会导致开发和维护成本都大大增加。

我尝试总结下在做技术选型时应该考虑的因素。
* 所选语言或者框架或者数据库是否应用广泛，有比较好的社区支持，以及大量的用户反馈。
* 语言/框架/数据库所提供的能力（功能）是否能够契合业务的需要，从而减少重复的造轮子的工作量。
* 自己团队的成员是否熟悉该框架和数据库，是否有人能够掌控开始使用框架之后遇到的所有问题。

这一章，我们会对讲下Python2和Python3的选择，以及比下flask、tornado、django这三个web框架。了解下它们的特点和应用场景。

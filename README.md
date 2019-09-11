# koa-Graphql-demo

> Graphql使用apollo-server与koa结合的hello world 
 
没有结合数据库只是简单的写了下最基本的增删改查。  
简单了解了一下，graphql在nodejs中有两种使用方式一种是通过graphql的npm包提供的各种函数创建组合；另一种使用apollo-server提供的gpl函数接收字符串参数来生成对应的对象。咋一看纯粹使用字符串生成对象似乎很不合理，实际试用过后发现无疑后者的上手成本要低的多，可以少看一个npm包的文档，代码组织的效果也没有想象中那么不好(还在摸索)
   
问题：
    1. 摸索相关特性
    2. 摸索更合理的组织方式
    3. 中间件在koa上下中间件的关系，比如能不能前处理和后处理
    4. 与数据库的组合
    5. 与Sequelize之类的库组合


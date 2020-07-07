<center><h1>2020秋-数据库原理-专有名词速查字典</h1></center>
<center><h3>制作：纪元</h3></center>
<center><h4>本提纲遵循CC-BY-NC-SA协议</h4>(署名-非商业性-相同方式共享)</center>
<img src="专有名词速查表.assets/image-20200425125730568.png" alt="image-20200425125730568" style="zoom:50%;" />

---

<h2><center>带翻译定义
---

<h1><b><center>A

<h3><mark> all-key

全码

关系模式的所有属性作为关系模式的候选码

<h3><mark> anomaly

异常

null definition

<h3><mark> atomicity

原子性

事务是数据库的逻辑工作单位，事务中包括的诸操作要么都做，要么都不做。

<h3><mark> attribute

属性

表中的一列即为一个属性/实体所具有的某一特性称为属性

<h1><b><center>B

<h3><mark> boyce-codd normal form

bc范式（第四范式）

设关系模式r<u，f>∈1nf，如果对于r的每个函数依赖x→y，若y不属于x，则x必含有候选码，那么r∈bcnf。解释一下：对于关系模式r，若 r为第一范式，且每个属性都不部分依赖于候选键也不传递依赖于候选键，那么称r是bc范式

<h3><mark> business intelligence (bi) systems

商业智能系统

null definition

<h1><b><center>C

<h3><mark> candidate key

候选码

关系中的某一属性组的值能唯一地标识一个元组，而其子集不能

<h3><mark> cardinal numbe

基数

一个域允许的不同取值个数

<h3><mark> client/server application

客户端/服务器应用程序

null definition

<h3><mark> column

行

null definition

<h3><mark> composite

组合

null definition

<h3><mark> composite determinant

组合决定因素

函数依赖的决定因素可以由多个属性组成，在这种情况下，决定因素称为组合决定因素

<h3><mark> composite key

复合键

复合键是具有两个或多个属性的键。

<h3><mark> compound clauses

复合子句

利用and和or实现复合where子句

<h3><mark> concurrency control

并发控制

当多个用户的并发进程同时存取、修改数据库时，可能会发生相互干扰而得到错误的结果或使得数据库的完整性遭到破坏，因此必须对多用户的并发操作加以控制和协调

<h3><mark> consistency

一致性

事务执行的结果必须是使数据库从一个一致性状态变到另一个一致性状态。

<h3><mark> correlated nested query

相关嵌套查询语句

包含相关子查询的整个查询语句

<h3><mark> correlated subquery

相关子查询

子查询的查询条件依赖于父查询

<h1><b><center>D

<h3><mark> dangling tuple

悬浮元组

自然连接中被舍弃的元组

<h3><mark> data

数据

描述事物的符号记录称为数据

<h3><mark> data constraints

数据约束

null definition

<h3><mark> data definition language，DDL


数据定义语言

对数据库中的数据对象的组成与结构进行定义的语言

<h3><mark> data inconsistency

数据不一致

null definition

<h3><mark> data integration

数据集成

数据集成：数据集成通过应用间的数据交换从而达到集成，主要解决数据的分布性和异构性的问题，其前提是被集成应用必须公开数据结构，即必须公开表结构，表间关系，编码的含义等

<h3><mark> data integrity problems

数据完整性问题

同一个设备的购买成本会多次出现。 任何具有重复数据的表都容易受到更新异常的影响，有这种不一致的表称为有数据完整性问题。

<h3><mark> data manipulation language，DML


数据操纵语言

操纵数据，实现对数据库的基本操作，如查询、插入、删除和修改等。

<h3><mark> data mart

数据集市

小型的专用数据仓库称为数据集市。 注意，用于数据仓库的dbms，并不要求与用来操作数据库的dbms保持一致。

<h3><mark> data model

数据模型

数据模型（data model）是数据特征的抽象，它从抽象层次上描述了系统的静态特征、动态行为和约束条件，为数据库系统的信息表示与操作提供一个抽象的框架。数据模型所描述的内容有三部分，分别是数据结构、数据操作和数据约束

<h3><mark> data warehouses

数据仓库

bi系统通常将其关联的数据存储在数据仓库中，这个数据仓库是具有专门为bi处理准备数据的数据，程序和人员的数据库系统。 它们可以像仅由一名员工兼职处理数据提取那样简单，也可以像一个拥有数十名员工维护数据和程序库的部门一样复杂。

<h3><mark> database

数据库

数据库是长期存储在计算机内有组织、大量、共享的数据集合。它可以供各种用户共享，具有最小冗余度和较高的数据独立性。数据库管理系统在数据库建立、运用和维护时对数据库进行统一控制，以保证数据的完整性和安全性，并在多用户同时使用数据库时进行并发控制，在发生故障后对数据库进行恢复。

<h3><mark> database administrator，DBA


数据库管理员

数据库管理员是这个机构的一个（组）人员，负责全面管理和控制数据库系统。

<h3><mark> database management system，DBMS


数据库管理系统

"数据库管理系统（dbms）是用于创建，处理和管理数据库的计算机程序。 dbms接收用sql编码的请求，并将这些请求转换为对数据库的操作。 （dbms是一个大型的，复杂的程序，已从软件供应商处获得许可；公司几乎从不编写自己的dbms程序。）"

<h3><mark> database recovery

数据库恢复

数据库管理系统必须具有将数据库从错误状态恢复到某一已知的正确状态（亦称为完整状态或一致状态）的功能，这就是数据库的恢复功能。

<h3><mark> database system，DBS


数据库系统

数据库系统是由数据库、数据库管理系统（及其应用开发工具）、应用程序和数据库管理员（database administrator，dba）组成的存储、管理、处理和维护数据的系统。

<h3><mark> deletion anomaly

删除异常

当我们删除一行时，我们将不再知道：这台机器是一台车床，而且它的收购价格是4750.00。 这个表的结构设计，会导致一次删除丢失关于两个不同事物的数据，即一台机器记录和一个修复记录。 这种情况称为删除异常。

<h3><mark> derived table

派生表

由子查询生成的临时表

<h3><mark> determinant

决定因素

null definition

<h3><mark> domain

域

域是一组具有相同数据类型的值的集合。属性的取值范围来自某个域。

<h3><mark> domain integrity constraint

域完整性约束

"域完整性约束的作用：限制此单元格的数据正确，不对其它单元格起作用，域代表当前单元格域完整性约束：数据类型、非空约束（not null）、默认值约束(default)"

<h3><mark> domain/key normal form 

d/k范式（域/键范式）

"函数依赖关系的每个决定因素必须是一个候选键。当然，这只是我们对 bcnf 的简单定义，实际上，bcnf 中的关系满足 dk/nf 。"

<h3><mark> durability/permanence

持续性/永久性

指一个事务一旦提交，它对数据库中数据的改变就应该是永久性的。接下来的其他操作或故障不应该对其执行结果有任何影响。

<h1><b><center>E
<h3><mark> engineering data base，EDB


工程数据库

能存储和管理各种工程设计图形和工程设计文档，并能为工程设计提供各种服务的数据库。

<h3><mark> entity

实体

客观存在并可相互区别的事物称为实体

<h3><mark> entity integrity constraint

实体完整性约束

若属性（指一个或一组属性）a是基本关系r的主属性，则a不能取空值（null value）

<h3><mark> entity set

实体集

同一类型实体的集合称为实体集。

<h3><mark> entity type

实体型

用实体名及其属性名集合来抽象和刻画同类实体，称为实体型

<h1><b><center>F

<h3><mark> field 

字段（列）

null definition

<h3><mark> file

档案（表）

null definition

<h3><mark> foreign key

外键

外键是一个列或多个列的组合，且这些列（列组合）是其它表的主键。 这个术语之所以出现，是因为它是其他表的主键，而不是本表的主键。

<h3><mark> functional dependency

函数依赖

函数依赖简单点说就是：某个属性集决定另一个属性集时，称另一属性集依赖于该属性集。函数依赖是由数学派生的术语，它表征一个属性或属性集合的值对另一个属性或属性集合的值的依赖性。需要强调的是，函数依赖是关系所表述信息本身具有的语义特性，而不能由属性构成关系的方式来决定，也不能由关系的当前内容所决定。

<h1><b><center>G

<h3><mark> general normalization

通用归一化法

等价于直达bcnf

<h3><mark> granularity

封锁粒度

封锁对象的大小

<h1><b><center>I

<h3><mark> index

索引

在关系数据库中，索引是一种单独的、物理的对数据库表中一列或多列的值进行排序的一种存储结构，它是某个表中一列或若干列值的集合和相应的指向表中物理标识这些值的数据页的逻辑指针清单。索引的作用相当于图书的目录，可以根据目录中的页码快速找到所需的内容。

<h3><mark> insertion anomaly

插入异常

当我们只想输入关于一个实体的事实时，这个表的结构要求我们输入关于两个实体的事实。 这种情况称为插入异常。

<h3><mark> instance

实例

模式的一个具体值称为模式的一个实例（经常变动）

<h3><mark> intention lock

意向锁

如果对一个结点加意向锁，则说明该结点的下层结点正在被加锁

<h3><mark> interleaved concurrency

交叉并发方式

并行操作轮流交叉运行，来实现并行事务的方式

<h3><mark> isolation

隔离性

一个事务的执行不能被其他事务干扰。

<h1><b><center>K

<h3><mark> key

码/键

也称为码键。表中的某个属性组，它可以唯一确定一个元组(唯一标识一个实体)

<h1><b><center>L

<h3><mark> left outer join

左外连接

只保留左边关系中的悬浮元组的外连接

<h3><mark> metadata

元数据

数据库是自描述的，因为它包含其自身的描述。 因此，数据库不仅包含用户数据表，而且还包含描述该用户数据的数据表。 这种描述性数据称为元数据。

<h3><mark> modification anomalies

修正异常

null definition

<h3><mark> multidetermine

多重决定

null definition

<h3><mark> multivalued dependency

多值依赖

设r(u)是一个属性集合u上的一个关系模式，x， y， 和z是u的子集，并且z=u-x-y，多值依赖x->->y成立当且仅当对r的任一个关系r，r在(x，z)上的每个值对应一组y的值，这组值仅仅决定于x值而与z值无关。
若x->->y，而z=空集，则称x->->y为平凡的多值依赖。否则，称x->->y为非平凡的多值依赖。若x->y.则x->->y   说明函数依赖是多值依赖的特殊情况。

<h3><mark> nested query

嵌套查询

将一个查询块嵌套在另一个查询块的where子句或having短语的条件中的查询

<h3><mark> non-prime / non-key attribute

非主/非码属性

不包含在任何候选码中的属性

<h3><mark> normal form，NF


范式

设计关系数据库时，遵从不同的规范要求，设计出合理的关系型数据库，这些不同的规范要求被称为不同的范式，各种范式呈递次规范，越高的范式数据库冗余越小。

<h3><mark> normalization strategy

规范化策略

null definition

<h3><mark> normalization

规范化

要求关系必须满足一定的规范条件

<h3><mark> null value

空值

"所谓空值就是""不知道""或""不存在""或""无意义""的值。"

<h1><b><center>O
<h3><mark> object relational database system，ORDBS


对象关系数据库系统

关系数据库与面向对象数据库的结合。

<h3><mark> object-relational dbms

对象关系数据库管理系统

null definition

<h3><mark> odd conditions

特殊条件

null definition

<h3><mark> ODBMS


面向对象的数据库管理系统

null definition

<h3><mark> operational databases

运营数据库

null definition

<h3><mark> outer join

外连接

把悬浮元组也保存在结果关系中，在其他属性上填空值（null）

<h1><b><center>P

<h3><mark> primary key

主键

设计数据库时，选择其中一个候选键作为主键。 之所以使用这个术语，是因为这个键将被定义到 dbms 中， dbms 将使用它作为在表中查找行的主要手段。 一个表只有一个主键。 主键可以有一列，也可以是复合键。

<h3><mark> prime attribute

主属性

候选码的诸属性

<h3><mark> project-join normal form

（项目加入范式）第五范式

null definition

<h1><b><center>Q
<h3><mark> query by example，QBE


通过例子进行查询

null

<h1><b><center>R

<h3><mark> range

范围

null definition

<h3><mark> record

记录（行）

对于表中的每一行，其记录的是特定的事物或是一种感兴趣的现象，每一行记录的都是特定事物的数据，也将行称之为记录

<h3><mark> referenced relation/target relation

被参照关系/目标关系

设f是基本关系r的一个或一组属性，但不是关系r(k，f，…)的码，k，是基本关系s(k，…)的主码。如果f与k，相对应，则称f是r的外码（foreign key），基本关系s为被参照关系（referenced relation）

<h3><mark> referencing relation

参照关系

设f是基本关系r的一个或一组属性，但不是关系r(k，f，…)的码，k，是基本关系s(k，…)的主码。如果f与k，相对应，则称f是r的外码（foreign key），并称基本关系r为参照关系（referencing relation）

<h3><mark> referential integrity constraint

参照完整性约束

null definition

<h3><mark> relation

关系

一个关系对应通常说的一张表

<h3><mark> relation schema

关系模式

关系的描述

<h3><mark> relational model

关系模型

系模型的数据结构非常简单，只包含单一的数据结构——关系

<h3><mark> relationship

联系

实体之间的联系通常是指不同实体集之间的联系。实体之间的联系有一对一、一对多和多对多等多种类型。

<h3><mark> reporting applications

报告应用程序

null definition

<h3><mark> review resolution

视图消解

从数据字典中取出视图的定义，把定义中的子查询和用户的查询结合起来，转换成等价的对基本表的查询，然后再执行修正了的查询。这一转换过程称为视图消解

<h3><mark> right outer join

右外连接

只保留右边关系中的悬浮元组的外连接

<h3><mark> row

列

null definition

<h1><b><center>S

<h3><mark> schema

模式

模式也称逻辑模式，是数据库中全体数据的逻辑结构和特征的描述，是所有用户的公共数据视图，它仅仅涉及型的描述，不涉及具体的值。（相对稳定）

<h3><mark> simultaneous concurrency

同时并发方式

多个处理机可以同时运行多个事务的并发方式

<h3><mark> single-attribute primary keys

单属性主键

null definition

<h3><mark> SKU


最小存货单位

null definition

<h3><mark> SOAP


非首字母缩写

null definition

<h3><mark> spatial data base system，SDB


空间数据库系统

描述、存储和处理空间数据及其属性数据的数据库系统。

<h3><mark> step-by-step method

循序渐进法

"通过使用前面给出的这些范式的定义逐步测试1nf、2nf、3nf 和 bcnf 的关系来消除这些问题。 我们将这种方法称为“循序渐进”法。"

<h3><mark> storage schema

内\存储模式

一个数据库只有一个内模式。它是数据物理结构和存储方式的描述，是数据在数据库内部的组织方式。

<h3><mark> straight-to-BCNF


直达bcnf法

"还可以通过简单地设计(或重新设计)表，使每个决定因素都成为候选键，从而消除这些问题。 当然，这个条件就是 bcnf 的定义，它将消除由函数依赖引起的所有异常。 我们将这种方法称为“直达 bcnf法”或“通用归一化”法。"

<h3><mark> structured querylanguage，SQL


结构化查询语言

不仅具有丰富的查询功能，而且具有数据定义和数据控制功能，是集查询、数据定义语言、数据操纵语言和数据控制语言（data control language，dcl）于一体的关系数据语言。

<h3><mark> subschema

外\子\用户模式

是数据库用户（包括应用程序员和最终用户）能够看见和使用的局部数据的逻辑结构和特征的描述，是数据库用户的数据视图，是与某一应用有关的数据的逻辑表示。

<h3><mark> surrogate key

代理键

是指在关系型数据库设计中，当资料表中的候选键都不适合当主键时，例如资料太长，或是意义层面太多，就会用一个attribute来当代理主键，此主键可能是用流水号，来代替可辨识唯一值的主键。

<h1><b><center>T

<h3><mark> table

表

null definition

<h3><mark> term domain

术语域

null definition

<h3><mark> transitive dependency

传递依赖

设x，y，z是关系r中互不相同的属性集合，存在x→y(y !→x)，y→z，则称z传递函数依赖于x。

<h3><mark> trigger

触发器

是用户定义在关系表上的一类由事件驱动的特殊过程。一旦定义，触发器将被保存在数据库服务器中。任何用户对表的增、删、改操作均由服务器自动激活相应的触发器，在关系数据库管理系统核心层进行集中的完整性控制。触发器类似于约束，但是比约束更加灵活，可以实施更为复杂的检查和操作，具有更精细和更强大的数据控制能力。

<h3><mark> tuple

元组（行）

表中的一行即为一个元组

<h3><mark> type

型

型是指对某一类数据的结构和属性的说明

<h1><b><center>U
<h3><mark> UDDI


通用描述，发现和集成

是一种用于描述、发现、集成web service的技术，它是web service协议栈的一个重要部分。

<h1><b><center>V

<h3><mark> value

值

值是型的一个具体赋值

<h1><b><center>W

<h3><mark> wildcard

通配符

通配符是一种特殊语句，用来模糊搜索文件。可以使用它来代替一个或多个真正字符。
%（百分号）代表任意长度（长度可以为0）的字符串。例如a % b示以a开头，以b结尾的任意长度的字符串。如acb、addgb、ab等都满足该匹配串。
_（下横线）代表任意单个字符。例如ab表示以a开头，以b结尾的长度为3的任意字符串。如acb、atb等都满足该匹配串

<h3><mark> WSDL


web服务描述语言

web服务描述语言，web services description language，是为描述web服务发布的xml格式。（通常采用抽象语言描述该服务支持的操作和信息，使用的时候再将实际的网络协议和信息格式绑定给该服务。

<h1><b><center>X

<h3><mark> xml

可扩展标记语言

可扩展标记语言，标准通用标记语言的子集，是一种用于标记电子文件使其具有结构性的标记语言。

---

<h2><center>无翻译定义

---

<h3><mark> 数据的语义

数据的含义称为数据的语义，数据与其语义是不可分的。

<h3><mark> 不相关子查询

子查询的查询条件不依赖于父查询

<h3><mark> 等值连接

连接运算符为“=”

<h3><mark> 二级封锁协议

在一级封锁协议基础上增加事务t在读取数据r之前必须先对其加s锁，读完后即可释放s锁。

<h3><mark> 非等值连接

连接运算符非“=”

<h3><mark> 非平凡的函数依赖

x一y，但y$$\subsetneq$$x，称x→y是非平凡的函数依赖。

<h3><mark> 平凡的函数依赖

x→y，但y$\subseteq$x，则称x→y是平凡的函数依赖。

<h3><mark> 分量

元组中的一个属性值

<h3><mark> 分组视图

定义中带有聚集函数和groupby子句查询的视图，

<h3><mark> 关系代数表达式

关系代数中，基本运算经有限次复合后形成的表达式。

<h3><mark> 关系数据库的值/关系数据库

这些关系模式在某一时刻对应的关系的集合

<h3><mark> 关系数据库模式/关系数据库的型

对关系数据库的描述。

<h3><mark> 行列子集视图

从单个基本表导出的，并且只是去掉了基本表的某些行和某些列，但保留了主码的视图

<h3><mark> 据的完整性约束条件

据的完整性约束条件是一组完整性规则

<h3><mark> 连接字段

连接谓词中的列名称型，必须是可比的，但名字不必相同。

<h3><mark> 逻辑独立性

用户的应用程序与数据库的逻辑结构是相互独立的。

<h3><mark> 平凡的多值依赖

x→→y，而z=$\emptyset$，即z为空，则称x→→y为平凡的多值依赖。

<h3><mark> 三级封锁协议

在一级封锁协议的基础上增加事务t在读取数据r之前必须先对其加s锁，直到事务结束才释放。

<h3><mark> 数据操作

数据操作是指对数据库中各种对象（型）的实例（值）允许执行的操作的集合，包括操作及有关的操作规则。

<h3><mark> 数据的安全性

保护数据以防止不合法使用造成的数据泄密和破坏。

<h3><mark> 数据的完整性

数据的正确性、有效性和相容性。

<h3><mark> 数据共享

数据共享可以大大减少数据冗余，节约存储空间。数据共享还能够避免数据之间的不相容性与不一致性

<h3><mark> 数据结构

数据结构描述数据库的组成对象以及对象之间的联系

<h3><mark> 数据库系统与文件系统的本质区别

数据库系统实现整体数据的结构化，这是数据库的主要特征之一，也是数据库系统与文件系统的本质区别。

<h3><mark> 完整性检查

将数据控制在有效的范围内，并保证数据之间满足一定的关系。

<h3><mark> 物理独立性

用户的应用程序与数据库中数据的物理存储是相互独立的

<h3><mark> 显式封锁

应事务的要求直接加到数据对象上的锁

<h3><mark> 虚拟列

在基本表中不存在的派生属性

<h3><mark> 一级封锁协议

事务t在修改数据r之前必须先对其加x锁，直到事务结束才释放

<h3><mark> 隐式封锁

该数据对象没有被独立加锁，而由于其上级结点加锁而使该数据对象加上了锁。

<h3><mark> "整体""结构化”"

据库中的数据不再仅仅针对某一个应用，而是面向整个组织或企业;不仅数据内部是结构化的，而且整体是结构化的，数据之间是具有联系的。

<h3><mark> 自然连接

在等值连接中把目标列中重复的属性列去掉

<h3><mark> 自主存取控制

"用户可以""自主""地决定将数据的存取权限授予何人、决定是否也将""授权的权限授予别人。因此称这样的存取控制是自主存取控制。"

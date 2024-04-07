# AndroidFinalDesign_FreeStudy
 安卓期末设计——乐享学习

1.设计目的
1.1项目背景
疫情背景下，教育资源逐渐向互联网平台移动，如今的学习形式也是多种多样，学习经验分享、学习自我监督、学习各种知识都可以以在网络平台中进行了，大众（以学生为主）针对智能化移动智能终端的应用要求也在不断提升。因此，学习类APP手机软件也伴随着市场需求而渐渐兴起。
学习是一个不断积累过程，能够坚持下去需要合理的方法与强大的信念，开发学习类APP软件能够让用户在知识的海洋当中领悟学习，爱上学习，并且获得学习的紧迫感和压力。
针对文化教育的网络化发展趋势，各种学习行为都可以通过学习APP手机软件来开展，便捷了用户利用碎片化时间随时学习；对于一些学习自觉性较低的用户，需要通过制定学习计划使学习效率更高；对于需要学习指导的用户，需要吸取别人的学习经验调整自我的学习方式。
根据这些学习需求，为提升优化用户利用学习类APP自主学习的感受，本小组开发出FREE STUDY这一学习APP，帮助用户开展自主学习，协助用户完成对个人任务的制定，用户还能够给每次完成任务制定时间期限，给自己带来完成任务的紧迫感。除了个人学习任务的制定与实现，用户还能够在APP里发布日志，阅读他人发布的日志，融合他人发布的学习方法和题型分析，通过多个角度改善自己的学习方式，掌握更多的学习技巧和解题方法。
本小组开发的此款学习类APP FREE STUDY有如下几点优势：
1.1.1蕴含的巨大的市场商机
作为一项学习类的APP软件，它自身的制定任务功能自然少不了，对于部分学习自觉性不高的用户，会去应用市场下载类似倒数日、任务清单功能的APP，这些APP的功能各自分散，使用时需要经常切换，不利于用户集中精力学习。如果这些功能能够集中到一款APP中，对用户来说这款APP就会更加实用而且方便用户随时进行学习。在教育行业上，这种集成多种功能的APP会具有更好的市场需求。
1.1.2用户能够从中受益，提升成绩
用户在平时的积累可能会产生知识储备不齐全，成绩提升不了或者提升不明显等情况，这是由于用户没有找到适合自己的学习方法。我们的APP正好抓住了这些用户的需求，通过发帖功能和浏览他人发帖功能，帮助用户巩固专业知识，通过网上的学习打好基础，取得学习上的进步。用户能够从他人的学习方法中受益，提升成绩。
1.1.3丰富的学习功能，每天监督用户的学习进程
拥有着任务清单、倒数日、闹钟、课程表等功能，不仅能让用户自主安排学习计划，还能针对任务的轻重缓急使用不同的功能督促自己。对手边的紧急任务，可以设定闹钟和任务清单，不仅可以在闹钟的督促下及时完成任务，还可以通过完成任务清单获得学习的成就感；对未来的重要日程和纪念日，可以用倒数日进行记录，每日的例行日程可以制定课程表，每日的学习时间打卡能够更好得规范学习态度，让学习可以做到每日的打卡，保证每天的学习质量。
网络和手机为我们的日常生活带来了诸多的便利，一部手机可以完成各种各样的事情。对于学习上的任务， FREE STUDY能够赋予原本枯燥无味的学习更多的有趣元素，让用户可以在学习的道路上越走越远。
1.2需求分析
系统的需求分析是进行系统功能设计，进而进行系统详细实现的前提。本系统作为一个服务性质的信息系统，对实系统直接服务的人群——学生进行调研，是进行需求调研的最直接也是最方便的途径。我们团队在对我校不同年级的学生群体进行需求调研中发现，学生普遍反映由于自身不够自律，平常空闲时间就会通过多种娱乐手段打发时间，每到deadline的时候，时间就供不应求，平常的时候让自己静下心来专心完成任务并不容易。学生们迫切需要一个装载在智能手机上的能够自定义任务清单，交流完成任务心得的软件。 虽然目前应用市场中已经有一些例如ToDoList、倒数日、小红书等的移动客户端软件出现，但是经过调研发现，这些软件无论从功能上还是用户体验上都远远没有达到方便快捷实时的要求。这些软件仅仅只能分别部分满足用户的需求，未能将这些功能整合起来方便用户的使用。 
根据以上分析，整理出本系统的具体需求： 
1.本应用采用SQLite技术，将数据存储在本地，保证了应用数据的安全性。 
2.本应用需满足学生最基本的自定义任务清单需求，包括自定义任务标题，任务细节来定制学习计划，监督自己不拖拉，同时在该模块设置计时功能，让用户计时来掌握自身专注时间，并可以设置闹钟给予自己任务提醒。 
3.本应用需提供未来沙漏模块，在该模块中，用户可以自定义各种deadline日期，应用可以及时更新距离deadline时间，给予用户提示，督促用户的任务进度。
4.本应用需提供用户积极分享自己的生活状态、学习经验等的平台，借助这个平台用户可以积极交流日常生活学习中遇到的问题，携手好友共同进步。
5.本应用需提供用户自定义课程安排的需求，根据课程表合理规划空闲时间，与自定义任务清单紧密结合起来，可以更好的帮助用户自律。
6.本应用需提供卡片激励模块，在该模块中，用户可以浏览多种卡片，在配上背景音乐的同时，观看励志卡片，让用户自己在情绪低落时来调整心情，实现情绪最大化放松。
1.3 关键技术
本项目主要是基于JAVA编程语言的Android开发，开发工具使用的是Android Studio。在开发过程中，需要用到以下技术：Activity生命周期，界面技术：如使用xml文件布局（layout布局、常用控件、页面美化）、数据存储技术（SQLite）存储。
1.3.1 Android
Android平台是在Linux内核的基础上使用C语言和JAVA语言开发的一类开放式源码，良好的兼容性、可操作性和移植性是Android平台的优点，Android发展如此迅猛的优势在于其开源性，从而使很多优秀的开发人员投入Android平台中，这得益于它的平台无关性和良好的发展前景，这也使其越来越强大。
(1)	开源
在优势方面，Android平台首先就是其开放性 。Android系统是开源的，“开源”是用于描述那些源码可以被公众使用的软件，并且此软件的使用、修改和发行也不受许可证的限制。Android操作系统的开源意味着开放的平台允许任何移动终端厂商加入到Android联盟中来。因为Android的开源，专业人士可以利用开放的源代码来进行二次开发，打造出个性化的Android。显著的开放性可以使其拥有更多的开发者，随着用户和应用的日益丰富，一个崭新的平台也将很快走向成熟。而且开放性可以缩短开发周期，降低开发成本，如此一来跟有利于Android的发展。
(2)	给用户更高的自由度
 Android操作系统给予了用户跟高的自由度，熟悉Android的都清楚：用户可以根据自己的喜好来设置手机界面，Android的应用市场甚至上还有各式各样的启动器来供用户自己选择，让自己的手机与众不同。例如，用户要是喜欢HTC的操作界面，便马上可以在应用市场上找到，甚至还能模仿IOS的界面。相比于IOS操作系统，Iphone手机只有一成不变的手机界面，不能对其进行更改。
(3)	选择多样化
由于Android的开放性，众多的厂商为了迎合大众会推出层出不穷的新产品。迄今为止，以Android为操作系统的机型已经达到了几十上百种。但是这些功能、机型上的差异不会影响到数据的同步、软件的兼容等等。这样便给了消费者更多地购机选择。这一优势是IOS、Blackberry OS当今主流操作系统所不能比拟的。
1.3.2 SQLite
SQLite，是一款轻型的数据库，是遵守ACID的关系型数据库管理系统，它包含在一个相对小的C库中。它能够支持Windows/Linux/Unix等等主流的操作系统，同时能够跟很多程序语言相结合，比如 Tcl、C#、PHP、Java等，还有ODBC接口，同样比起Mysql、PostgreSQL这两款开源的世界著名数据库管理系统来讲，它的处理速度比他们都快。不像常见的客户-服务器范例，SQLite引擎不是个程序与之通信的独立进程，而是连接到程序中成为它的一个主要部分。所以主要的通信协议是在编程语言内的直接API调用。这在消耗总量、延迟时间和整体简单性上有积极的作用。整个数据库(定义、表、索引和数据本身)都在宿主主机上存储在一个单一的文件中。它的简单的设计是通过在开始一个事务的时候锁定整个数据文件而完成的。
SQLite的主要优点：
(1)	一致性的文件格式
在SQLite的官方文档中是这样解释的，我们不要将SQLite与Oracle或PostgreSQL去比较，而是应该将它看做fopen和fwrite。与我们自定义格式的数据文件相比，SQLite不仅提供了很好的移植性，如大端小端、32/64位等平台相关问题，而且还提供了数据访问的高效性，如基于某些信息建立索引，从而提高访问或排序该类数据的性能，SQLite提供的事务功能，也是在操作普通文件时无法有效保证的。
(2)	在嵌入式或移动设备上的应用
由于SQLite在运行时占用的资源较少，而且无需任何管理开销，因此对于PDA、智能手机等移动设备来说，SQLite的优势毋庸置疑。
(3)	内部数据库
在有些应用场景中，我们需要为插入到数据库服务器中的数据进行数据过滤或数据清理，以保证最终插入到数据库服务器中的数据有效性。有的时候，数据是否有效，不能通过单一一条记录来进行判断，而是需要和之前一小段时间的历史数据进行特殊的计算，再通过计算的结果判断当前的数据是否合法。在这种应用中，我们可以用SQLite缓冲这部分历史数据。还有一种简单的场景也适用于SQLite，即统计数据的预计算。比如我们正在运行数据实时采集的服务程序，我们可能需要将每10秒的数据汇总后，形成每小时的统计数据，该统计数据可以极大的减少用户查询时的数据量，从而大幅提高前端程序的查询效率。在这种应用中，我们可以将1小时内的采集数据均缓存在SQLite中，在达到整点时，计算缓存数据后清空该数据。可以充分利用SQLite提供SQL特征，完成简单的数据统计分析的功能。这一点是CSV文件无法比拟的。
(4)	产品测试
在需要给客户进行Demo时，可以使用SQLite作为我们的后台数据库，和其他关系型数据库相比，使用SQLite减少了大量的系统部署时间。对于产品的功能性测试而言，SQLite也可以起到相同的作用。
1.4系统设计原则
系统设计原则是整个系统开发中不可忽视的部分，有了这些原则我们才能更全面的开发系统，能够使我们考虑得更加周全，本疫苗接种管理系统设计结合该行业实际需要和特点，确保架构合理性、技术可行性，能够满足后期业务扩张新需求，按照下面原则进行设计：
1.4.1系统性原则
系统设计要从整个系统的角度进行考虑。系统代码要统一，设计标准要规范，传递语言要一致，实现数据或信息全局共享，提高数据重用性。
1.4.2扩展性原则
为满足系统将来进一步扩展的需要，应在设计初期就考虑数据库的结构、系统功能模块与子模块的可扩展性，避免后期出现的各种繁琐问题。信息系统具有较好的开放性、结构的可变性和环境适应性，所以可以维持较长的生命周期。在信息系统设计中，应尽量采用模块化结构，提高数据、程序模块的独立性，这样，既便于模块的修改，又便于增加新的内容，提高信息系统适应环境变化的能力。
1.4.3可靠性原则
可靠性是指信息系统抗干扰的能力及受外界干扰时的恢复能力，一个成功的信息系统必须具有较高的可靠性，如安全保密性、检错及纠错能力、抗病毒能力等。本系统通过数据加密技术、数据库访问安全性授权、备份机制、数据访问权限的设计，确保在网络传输、系统物理、操作业务数据的安全性，给用户提供一个可靠的服务系统。
1.5可行性分析
1.5.1使用可行性
近年来，新冠疫情对中国教育带来了一场全新的变革，“网上授课”的教育模式席卷大部分高校，同学们在家上网课，学习氛围和学习效率难免会大打折扣，学生学习专注力不高、在家学习孤单、时间安排不合理、懒散消极的学习态度等问题纷纷呈现，长此以往必会对学生的素质发展带来不可逆转的影响。以上问题迫使市场科学统筹制定一套适合敦促激励学生“自主学习、快乐学习”的方案。如若存在一个相对完善的集“自主打卡、时间规划、友链交流、焦虑缓解”功能于一体的学习类App供学生用户群体使用，不仅可以让学生从枯燥无味的居家学习中解放出来，而且可以有效地培养学生的自主规划能力，在与友链分享交流的同时也可以了解对方的学习动态，相互促进共同进步，提高学习效率。
综上所述，在大环境下已经具备了应用本系统的条件。
1.5.2技术可行性
技术可行性是指决策的技术和决策方案的技术不能突破组织所拥有的或有关所掌握的技术条件的边界。本项目通过使用UI中的layout和view以及安卓的生命周期实现基本的底层设计，Json进行数据传输，数据库管理用户数据，然后通过进一步调试和优化使得功能更加完善。
1.5.3经济可行性
为了新开发的系统能够适应未来一段时间新增业务的需求，在条件允许的情况下，应尽量提高软、硬件的配置，并使用大型关系数据库。但在满足系统需求的前提下，也应尽量节约成本。一方面，在硬件投资上不能盲目追求技术上的先进，而应以满足应用需要为前提。另一方面，信息系统设计中应尽量避免不必要的复杂化，各模块应尽量简洁，以便缩短处理流程、减少处理费用。
本小组通过在Android Studio中升级完善开发所需的软件硬件设施，建立了一个良好的环境，很大程度上降低了成本，减少了经费，避免了过多的成本投入，是一个经济的方式。
1.5.4操作可行性
操作可行性是指在现有的工作人员，工作硬件设备以及开发环境下能对系统做出适应以及补充维护的可能性和范围规模。为了方便用户的后期维护，使用户群体能过够轻松地通过本平台对时间进行充分地利用，并且能够更好地相互交流，本系统设计的界面也是非常简洁明了，给人机交互提供一个更舒适美观的展示，使用户得以通过简单快捷的操作实现Free Study，让受众易懂、易上手。
在功能上，要具备详细的信息，操作方便快捷。本自主学习规划与探讨APP对用户要求低，只需要简单的操作便能完成，所以使用起来相当便捷。同时，管理人员也不需要很高的技术，只需要日常定期维护后台以及具备SQL能力即可。
由此可见，在使用可行性、技术可行性、经济可行性、操作可行性上，本系统都具有其开发设计的理由。
2．功能描述
2.1 项目整体结构
Free Study App包含注册登录模块、任务清单模块、未来沙漏模块、记录分享模块、课表制定模块、卡片收集模块和个人中心模块。
注册登录模块包括用户注册和用户登录的功能；任务清单模块包括新建待办任务、任务及时、长按任务删除、闹钟制定和闹钟删除的功能；未来沙漏模块为用户提供倒数日记录的服务，其主要功能包括新增倒数本、查看倒数本、删除倒数本、新增倒数日、查看倒数日的功能；记录分享模块为用户提供一个分享交流的平台，其主要功能包括查看经验分享专栏、查看计划分享专栏、查看日常分享专栏、上传图片、发布分享日志的功能；卡片收集模块为用户提供励志鸡汤文案并配以舒缓学习压力的背景乐，其主要功能包括展示励志卡片集和音乐播放的功能；最后个人中心模块包括查看个人信息、编辑个人信息、查看个人发布、删除个人发布、退出登录等功能。
 
图2.1-1 Free Study整体结构
2.2 各模块用例图
2.2.1注册登录模块
 
2.2.2任务清单模块
 
2.2.3未来沙漏模块
 
2.2.4记录分享模块
 
2.2.5课表定制模块
 
2.2.6个人中心模块
 
2.2.7个人中心模块
 
2.3功能与程序的关系
功能	程序一	程序二	程序三	程序四	程序五	程序六	程序七	程序八	程序九
注册登录	MainActivity	RegisterActivity	ForgetPasswordActivity						
任务清单	todolistMainActivity	todolistDetailActivity	AlarmMainActivity	PlayAlarmActivity					
未来沙漏	DaoshuriMainActivity	AddTypeActivity	BaseActivity	MatterAddActivity	MatterDetailActivity	MatterEditActivity	QueryByTypeActivity	TypeListActivity	TypeManagerActivity
记录分享	PublishMainActivity	RecommendActivity							
课表定制	MainActivity	AddCourseActivity							
卡片收集	CardViewPaferActivity								
个人中心	CheckMyPublishActivity								
底部导航栏	BaseActivity								

3．详细设计
3.1 系统业务逻辑
业务是指一个实体单元向另一个实体单元提供的服务。
逻辑是指根据已有的信息推出合理的结论的规律。
业务逻辑是指一个实体单元为了向另一个实体单元提供服务，应该具备的规则与流程。
就像你家的规矩–“吃饭前必须洗手”“有客人来要起立”“睡觉前各自说晚安”-就是业务逻辑的生活化实例。
在软件系统架构中，软件一般分为三个层次：表示层、业务逻辑层和数据访问层：
表示层：负责界面和交互；
业务逻辑层：负责定义业务逻辑（规则、工作流、数据完整性等），接收来自表示层的数据请求，逻辑判断后，向数据访问层提交请求，并传递数据访问结果，业务逻辑层实际上是一个中间件，起着承上启下的重要作用；
数据访问层：负责数据读取。
业务逻辑的内容包括四个部分：
领域实体：定义了业务中的对象，对象有属性和行为；
业务规则：定义了需要完成一个动作，必须满足的条件；
数据完整性：某些数据不可少；
工作流：定义了领域实体之间的交互关系。

3.2.1 注册登录和任务清单模块业务逻辑
 
3.2.2 未来沙漏模块业务逻辑
 
3.2.3 分享交流模块业务逻辑
 

3.2.4 课程制定模块业务逻辑
 


3.2.5 卡片收集模块业务逻辑
 


3.2.6 个人中心模块业务逻辑
 

3.2 数据库模块设计
本次课程设计采用的SQLite轻量级数据库，分别构建了用户表、任务清单表、帖子分享表和课程表这四张表，各表之间的关系如下图所示：
 
图3.2-1 数据表搭建

3.2.1用户表（user表）
字段名	中文名称	数据类型	主键	外键	允许为空	是否自增
userId	用户编号	Integer	是		否	是
username	用户姓名	varchar(20)			否	
pwd	用户密码	varchar(20)			否	
phone	用户手机号	varchar(15)			否	

3.2.2任务清单表（todolist表）
字段名	中文名称	数据类型	主键	外键	允许为空	是否自增
taskId	任务编号	Integer	是		否	是
userId	用户编号	Integer		是	否	
taskTitle	任务标题	varchar(50)			否	
taskContent	任务内容	Varchar(500)			否	
isComplete	是否完成	枚举			否	

3.2.3帖子分享表（share表）
字段名	中文名称	数据类型	主键	外键	允许为空	是否自增
shareId	帖子编号	Integer	是		否	是
userId	用户编号	Integer		是	否	
shareTitle	分享标题	Varchar(50)			否	
shareLabel	分享标签	Varchar(20)			否	
shareImg	分享图片	Byte[ ]			否	
shareContent	分享内容	Varchar(500)			否	
shareReap	点赞次数	Integer			否	
publishTime	发布时间	DateTime			否	

3.2.4课程表（course表）
字段名	中文名称	数据类型	主键	外键	允许为空	是否自增
courseId	课程编号	Integer	是		否	是
userId	用户编号	Integer		是	否	
courseName	课程名	Varchar(20)			否	
teacher	任课老师名	Varchar(20)			否	
class	课程地点	Varchar(20)			否	
classDay	上课日子	Integer			否	
classStart	开始节次	Integer			否	
clssEnd	结束节次	Integer			否	

3.3 系统功能模块设计
3.3.1用户登录与注册
为了保障用户数据的安全，使用SQLite技术，将注册的相关信息存储在本地，而不是上传到云端。因为软件面向任何用户，所以登录的方式较为简单，在注册界面输入用户名、密码、手机号以及对密码的确认。点击注册按钮后将返回登录界面，在登录界面输入在已经注册好的用户名以及密码，将会进入首页推荐页面，若用户名不存在或者密码不正确，将会给出相应的提示信息，但不会进入首页。
 
图3.3.1-1 登录注册流程
3.3.2任务清单模块
任务清单用于记录用户想要完成的任务，并且可以实现增添任务、标记已完成任务和未完成任务、修改任务的功能，在进入任务页面后，可以点击闹钟按钮进入钟表界面，钟表界面可以实现闹钟功能，帮助用户掌握完成任务的时间，在点击按钮存储任务后，钟表会开始计时，记录用户完成任务所需额的时间。
闹钟模块写在任务清单模块的主页面，闹钟模块任务清单的主页面，用户在点击进任务清单主页面后，可以点击闹钟的Imagebutton进入闹钟页面，给写任务设定闹钟，提醒自己及时完成即时任务。
 
图3.3.2-1 任务清单流程
3.3.3未来沙漏模块
倒数日功能用于实现重要特殊日期的倒数，可提醒用户离目标日还有几天，主页面展示出用户设定的目标日期还有几天或已经过去几天，实现正数或者倒数功能，在主页面的倒数或正数日的展示可以改变，采用线性形式或网格形式展示，用户还可以对添加的倒数日进行分类，对分类的图标和标题进行自定义，点击进每一个倒数日可单独查看其内容并作出内容的修改。
 
图3.3.3-1 未来沙漏模块
3.3.4 分享交流模块
分享交流模块主要给用户提供浏览分享帖子和发布个人帖子的功能。用户可以分别根据经验栏、计划栏和记录栏对应浏览相关内容帖子。同时，用户点击“发布”悬浮按钮还可以进入发布个人帖子页面，在发布个人帖子页面可上传图片、输入发布内容、选择发布内容所属标签栏目进行发布。如果内容没有填写完整则会提醒用户补全完整信息，在发布成功后会同步跳转至浏览帖子页面，到相应栏目下拉刷新可以看到该用户刚刚发布的帖子内容。
 
图 3.3.4-1 分享交流模块
3.3.5课表定制模块
在该模块用户可以根据自己的课程安排计划来对自身课表进行定制。包括课程名、课程时间、课程开始时间、课程结束时间、教师名、教室地址等信息。采用图文结合的方式对用户定制的课表进行展示。同时用户也可以根据自身时间安排需要，及时对新建的课程进行删除操作。
 
图3.3.5-1 课表定制流程
3.3.6卡片收集模块
在该模块用户可以通过滑动欣赏各式各样的励志卡片，同时也可以在这个模块点击音乐播放按钮实现聆听好听的音乐，再次点击该按钮实现音乐的暂停播放。
 
图3.3.6-1 卡片收集流程
3.3.7 个人中心模块
个人中心模块主要给用户提供查看个人信息、编辑个人信息、查看个人发布、删除个人发布、查看App设置、退出登录的功能。个人中心模块采用侧边导航栏的形式展现，侧边导航栏头部将显示用户的基本个人信息，导航栏菜单包括编辑个人信息的选项，可以实现用户对密码和电话的修改；导航栏菜单包括个人发布的选项，点击该选项可以跳转至个人发布页面对个人发布帖子进行查看，同时，左滑个人帖子可以对相应个人帖子进行删除；导航菜单栏包括查看App设置选项，可以点击查看关于我们和检查更新的相关信息；最后，在侧边导航栏的右下角有退出登录的按钮，点击该按钮，以弹出对话框的形式提示用户是否退出本App，若点击“确定”则退出该App，若点击“取消”则重新返回至个人中心模块。
 
图 3.3.7-1 个人中心模块
3.4 系统界面设计
3.4.1登录注册界面
 
3.4.2课程定制界面
 
3.4.3卡片集界面
 
3.4.4任务清单界面
 
3.4.5未来沙漏界面
 
3.4.6 分享交流界面
 
3.4.7 个人中心页面
 
4．程序实现
4.1登录注册
4.1.1登录注册功能实现
在进入安卓应用程序后，首先需要实现的功能是登录，若有账号密码直接登录；若没有账号则需要注册账号再登录；若已有账号忘记密码，则需要重新注册，（这里我是这样想的，由于未购买服务器数据保存在本地忘记密码功能就不是很有必要，因此我在个人中心板块设置了修改个人信息的功能，相当于替代了忘记密码功能，修改个人信息的功能我将在后面展开详细实现过程）注册的用户名和密码存在User表中。
登录页面具有一个按键、两个EditText、两个TextView，两个EditText分别用于获取用户名和密码，按键为登录按键，两个TextView为忘记密码和注册账户，分别跳往不同的页面。登陆成功后，进入到安卓程序的主界面。注册跳转到注册页面，注册成功后，将数据存储到数据库中，返回登录页面将数据库中的数据填充到输入框中，即可实现登录。忘记密码跳转到界面“重新注册”，重新注册再登录即可。界面设计的具体步骤我将在下个模块展开详细叙述。
登录界面——MainActivity.Java
注册界面——RegisterAcyivity.java
忘记密码界面——ForgetPasswordActivity.java
数据库——SQLiteHelper.java
登录页面的布局文件——activity_splash_login.xml
注册页面的布局文件——activity_register.xml
忘记密码页面的布局文件——activity_forget_password.xml
刚进入安卓应用程序的动画布局文件——activity_splash.xml
Android studio从启动到创建MainActivity的时候就自动extends AppCompatActivity，AppCompatActivity是继承自v7包的FragmentAvtivity，并且加入了很多新特性，可以做到兼容老设备。AppCompatActivity 和 Activity 的区别主要体现在app运行后的界面（app name显示或者不显示），对程序本身没有影响。继承AppCompatActivity会在页面中显示一个Label也就是项目的标签，而继承Activity则不会显示标签。标签的文字来源于AndroidManifest.xml中application中的android:label 如果继承的是Activity那这个标签的内容不会显示出来。
4.1.1.1注册登录
这个板块比较简单，主要就是三个函数的构造，下面我将分别展开。
（1）user表创建以及增删改查函数构建
构建用户表达的SQL语句：
db.execSQL("create table if not exists user" +
				"(userId integer primary key  AUTOINCREMENT,"+
				"userName varchar(20) not null,"+
				"pwd varchar(20) not null," +
				"phone varchar(15))");
或者采用另一种表达方式：
public SQLiteHelper(Context context, SQLiteDatabase.CursorFactory factory, int version) {
		super(context, dbname, factory, version);
		// TODO Auto-generated constructor stub
		sd=context.openOrCreateDatabase(dbname, Context.MODE_PRIVATE, factory);
		String ct="create table if not exists user (userId integer primary key  AUTOINCREMENT,"
		+"userName varchar not null,"
		+"pwd varchar not null, phone varchar);";
		sd.execSQL(ct);
	}
根据创建的user表，构造相应的插入、查询、删除、更改等函数，来完成用户的注册登录以及更改等操作。
public void insertuser(String username,String pwd,String phone) {

		String sql="insert into user (username,pwd,phone) values ('"+username+"','"+pwd+"','"+phone+"');";
		sd.execSQL(sql);
	}
	
	public void updateuser(String username, String pwd, String phone) {
		String sql="update user set pwd='"+pwd+"',phone='"+phone+"'where username='"+username+"';";
		sd.execSQL(sql);
	}
	
	public Cursor selectuser(String username) {
		String selection="username='"+username+"'";
		Cursor cr=sd.query( "user", null, selection, null, null, null,null);
		return cr;
	}
	
	public Cursor selectalluser() {
		Cursor cr=sd.query( "user", null, null, null, null, null,null);
		return cr;
	}
	
	public void deleteuser(String username) {
		String sql="delete from user where username='"+username+"';";
		sd.execSQL(sql);
	}
该部分主要要注意的是SQL语句的正确性，不然目标功能将不能实现。

（2）有账号密码直接登录（ViewInit函数）
首先声明两个textview，两个edittext以及一个button，再获取控件对象，在输入框里输入自己的账户和密码，输入框获取到输入的内容后，转化为String类型的数组，根据利用数组的相关特性，设置条件语句进行约束。
下面对账户和密码进行长度判断，如果输入均不为空，则把输入的账户和密码与存在数据库中。否则显示“请登录账号或密码”。
对数据库中的记录项进行查询，若没有则为0，若有则大于0。当记录项大于0时，将光标移到position为0的位置，默认位置为-1。若查询结果输入的账户和密码与数据库中已存的账户密码不相符，则显示“用户名不存在”，需要用户注册。
判断输入的账号密码是否与已存的账号密码相符，如果相符则跳转到RecommendActivity中，即登录成功进入应用程序；否则显示“密码不正确”。
 
同时设置intent将从数据库中获取到的username以及pwd传到RecommendActivity中用于在个人中心显示。
（3）创建账号实现登录（RegisterInit）
若之前没有注册过，在登录应用程序时则需要创建账号。点击TextView“Register Here”实现界面跳转注册用户。这个地方主要用到了老师讲的SpannableString来实现。
 
来到注册界面，注册时先创建方法ViewInit()，此界面有4个EditText和1个按键，4个EditText分别用于接收注册时用户输入的用户名、密码、确认密码、手机号。
同样的，也是先声明控件对象然后是获取控件对象。首先判断输入的用户名、密码、确认密码是否为空，如果不是则进行下一步的判断，如果其中有一项为空，则显示“请填写必要信息”。
若用户名、两个输入密码均不为空，则判断两次输入的密码是否一致，如果一致则存入数据库，若不一致则显示“两次密码不一致”。
在讲输入的数据存入数据库中时再做一次判断，如果查询出来的记录项的条数没有该用户，记数据为0条，存入用户名、密码、手机号，写入方法showMsg()，若该用户已存在，则显示“该用户已被注册”。
 
实现方法与登录类似，注册主要就是将输入的数据获取到后插入在user表中，在插入之前先根据username查询username是否已经存在（已在前面对数据库的设计中进行了相应的阐释，在后面注册登录的时候直接引用构建好的函数就行），否则给予相应提示。
注册完成后调用showMsg()方法，显示“恭喜你，注册成功，点击确定返回登录界面”，点击确定按键后结束注册，回到登录界面进行登录。
（4）点击忘记密码可显示界面“重新注册”RegisterInit
点击TextView“forget password”后，跳转进入忘记密码界面，显示“重新注册吧”。实现跳转类似超链接的功能也是使用SpannableString来实现。
 
（5）数据库
在写入登录注册模块的数据库时，class SQLiteHelper extends SQLiteOpenHelper，封装一个继承SQLiteOpenHelper类的数据库操作类。SQLiteOpenHelper类是一个抽象的辅助类，主要用来生成一个数据库并对数据库的版本进行管理，在SQLiteOpenHelper类的构造方法中分别传入Context、数据库名称，CursorFactory(一般传入null，否则为默认数据库)，数据库版本号(不能为负数)。
在SQLiteOpenHelper中首先执行的是onCreate方法(当数据库第一次创建时)，一般在这个方法里生成数据表。要注意的是，在构造函数时并没有真正创建数据库，而是在调用getWriteableDatabase()或者getReadableDatabase()方法的时候系统才会真正创建数据库，如果当时系统中不存在这个数据库，系统会自动生成一个数据库，然后返回SQLiteDatabase对象。onUpgrade方法用于实现数据库更新。
（6）个人中心板块的显示当前用户的username以及实现修改个人信息
这个地方也是较为简单，就是一个传数据的过程，在MainActivuty将username参数putExtra，在RecommendActivity中getStringExtra就可以实现。将传到的参数用textview显示出来即可。
 
然后介绍一下如何修改个人信息。
修改个人信息主要用到的就是对数据库的更改，通过获取到传来的username，然后根据username对数据库进行查询，对查询结果根据用户输入的数据进行更改。
 
4.1.2登录注册界面
 
4.1.2.1登录界面
  
为了使进入app时能够更加美观，我采用创建 MotionScene： app:layoutDescription 属性引用一个 MotionScene。MotionScene 是一个 XML 资源文件，其中包含相应布局的所有运动描述。为了将布局信息与运动描述分开，每个 MotionLayout 都引用一个单独的 MotionScene。请注意，MotionScene 中的定义优先于 MotionLayout 中的任何类似定义。
第一步：添加依赖
如果要使用MotionLayout请将ConstraintLayout更新到2.0及以上。在build.gradle文件中添加依赖。
我们使用的是AndroidX，添加依赖如下：
dependencies {
   implementation 'androidx.constraintlayout:constraintlayout:2.1.3'
}
第二步：创建布局和动画资源文件
使用MotionLayout除了布局文件外。我们还需要编写一个描述动画的xml文件，这个文件用来描述动画开始、结束时的状态和一些中间点的状态。

创建布局
创建一个布局文件名为activity_splash_login.xml根布局为ConstraintLayout。然后我们可以通过Android studio将布局转换为MotionLayout。
选中刚刚的布局文件，选择Design标签找到ComponentTree面板，找到根布局右键选择Conver to MotionLayout
转换后能看到Design面板变成了大致下面这个样子，多出了一个动画预览的窗口。
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.motion.widget.MotionLayout                                          xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    app:layoutDescription="@xml/motion_scene_splash">
</androidx.constraintlayout.motion.widget.MotionLayout>
根布局自动改为了MotionLayout并且添加了一个属性app:layoutDescription，这个属性所引用的文件就是我们要编写的动画描述文件了。
创建MotionScene动画资源文件：
ConstrainSet描述了开始或结束时页面控件的状态
Transtion指定了动画要使用的ConstrainSet，动画的触发方式等。
有了布局文件和MotionScene文件，MotionLayout就能帮我们完成动画了。

如果我们不使用AndroidStudio来转换布局为MotionLayout的话，就需要自己在res\xml文件夹下创建一个根节点为<MotionScene>的xml文件。
建议使用Android Studio来转换，这样在xml面板中能预览动画效果，手动创建的有时不能正常显示预览，需要重启Android Studio。
完善布局
<androidx.constraintlayout.motion.widget.MotionLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    app:layoutDescription="@xml/motion_scene_splash"
    android:layout_height="match_parent"
    tools:context="com.example.finalwork.Activity.login.MainActivity">

    <ImageView
        android:id="@+id/imgView_logo"
        android:layout_width="130dp"
        android:layout_height="130dp"
        android:layout_marginTop="80dp"
        android:scaleType="centerInside"
        android:src="@drawable/icon"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <ImageView
        android:id="@+id/imgView_logo_rays"
        android:layout_width="130dp"
        android:layout_height="130dp"
        android:layout_marginTop="80dp"
        android:scaleType="centerInside"
        android:src="@drawable/icon2"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <ImageView
        android:id="@+id/imgView_cloudLeft"
        android:layout_width="130dp"
        android:layout_height="130dp"
        android:layout_marginTop="16dp"
        android:scaleType="centerInside"
        android:src="@drawable/cloud"
        android:translationX="-20dp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:tint="@color/lightGrey" />

    <ImageView
        android:id="@+id/imgView_cloudRight"
        android:layout_width="130dp"
        android:layout_height="130dp"
        android:layout_marginTop="120dp"
        android:scaleType="centerInside"
        android:src="@drawable/cloud"
        android:translationX="20dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:tint="@color/lightGrey" />
添加动画
接下来在为MotionScene文件添加内容。其中详细描述了图片的运动轨迹，以此来实现动画。最难的动画实现完毕后，后面就是基本控件的添加在登录界面中需要的控件主要有四个文本框，两个输入框，一个按钮。其中两个文本框用来显示欢迎用户，两个文本框用来进行SpannableString来实现页面跳转，输入框用来实现与用户的交互，得到用户输入的信息。按钮用来监听器的相应。输入框，按钮，文本框的样式设置均引用了提前设置好的xml文件以及图片资源。
4.1.2.2注册界面
 
布局与登录界面类似，不过取消了动画，主要的控件有一个文本框，用来给予用户提示信息，四个输入框，四个输入框中分别用hint属性用来提示用户输入相应的内容。
4.1.2.3忘记密码界面
 
本界面主要是用来补充基本登录界面该有的东西，但是由于本软件未将数据存储在云端，因此忘记密码界面作用不大，其页面布局与登录注册类似。
4.1.2.4修改密码界面
  
修改密码界面主要用到的控件是四个文本框，四个输入框，采用DialogInterface对话框的形式将changepwd.xml界面展示出来，来完成修改个人信息的相关操作。
4.2 课程定制
4.2.1课程定制功能实现
在该模块用户可以根据自己的课程安排计划来对自身课表进行定制。包括课程名、课程时间、课程开始时间、课程结束时间、教师名、教室地址等信息。采用图文结合的方式对用户定制的课表进行展示。同时用户也可以根据自身时间安排需要，及时对新建的课程进行删除操作。通过这些灵活的操作，用户可以每天合理规划自己的任务，辅助以todolist可以将任务更加细化，更加充分利用用户的空余时间。
课程定制主界面——MainActivity.java
新建课程界面——AddCourseActivity.java
数据库——CourseDatabaseHelper.java
实体类对象封装——Course.java
在课程定制主界面。构造函数loadData（），该函数的目的是从数据库中读取数据。由于一开始时，数据库中没有数据，我就从课程的添加开始讲起。
（1）course表的创建以及增删改查
创建course表的SQL语句为：
public void onCreate(SQLiteDatabase db) {
        db.execSQL("create table courses(" +
                "id integer primary key autoincrement," +
                "course_name text," +
                "teacher text," +
                "class_room text," +
                "day integer," +
                "class_start integer," +
                "class_end integer)");
    }
创建course表后，将用户输入的课程名、课程时间、课程开始时间、课程结束时间、教师名、教师地址获取存储在数据库的course表中，存储完毕后为了用户查看，将从数据库中读取数据读取出来的课程信息来加载课程表视图
实现插入功能的SQL语句为：
SQLiteDatabase sqLiteDatabase =  courseDatabaseHelper.getWritableDatabase();
        sqLiteDatabase.execSQL
                ("insert into courses(course_name, teacher, class_room, day, class_start, class_end) " + "values(?, ?, ?, ?, ?, ?)",
                        new String[] {course.getCourseName(),
                                course.getTeacher(),
                                course.getClassRoom(),
                                course.getDay()+"",
                                course.getStart()+"",
                                course.getEnd()+""}
                );

（2）添加课程
老样子，先声明控件对象，然后获取控件。这里主要用到了六个输入框，用来接收用户输入的课程名、课程时间、课程开始、课程结束、教师名、教室地址。分别定义六个变量来接收用户传来的数据。
 
设置条件语句，对用户填写信息做出约束，要保证课程名、课程时间、课程开始、课程结束为必填项，否则提示用户基本信息未填写。由于实体类对象封装的是course，创建一个空对象，将用户输入的信息分别传入数据库course表中的对应列，这里采用intent传输数据，在主界面接收数据。
 
由于传输的数据是打包好的，于是在主界面要相应得到对应的变量（通过SQL语句，对course进行搜索），将查到的信息存入列表中。
 
然后使用从数据库读取出来的课程信息来加载课程表视图
 
（3）分别创建视图
在进行界面间的跳转和传递数据的时候，我们有的时候要获得跳转之后界面传递回来的状态，数据等信息。这个时候，我们不一定需要使用Intent进行跳转回原先设置的界面，而是使用onActivityResult方法就可以解决这个问题。这里与添加课程界面相呼应。添加课程界面点击完成后返回主界面时，onActivityResult将会根据传回的数据做出相应操作。
 
创建“第几节数”视图，这里用到的也是动态设置布局LayoutParams，在下面单个课程表视图的创建我会详细说明。这里定义的maxCoursesNumber为0；endNumber获取的是课程的结束时间。
 
创建单个课程视图，这个地方在填写星期几的时候有约束，应是在1到7之间以及课程开始的时间应小于课程结束时间，否则将会给予用户提示“星期几没写对,或课程结束时间比开始时间还早~~”。
 
这个地方用到了动态设置布局LayoutParams，LayoutParams相当于一个Layout的信息包，它封装了Layout的位置、高、宽等信息。假设在屏幕上一块区域是由一个Layout占领的，如果将一个View添加到一个Layout中，最好告诉Layout用户期望的布局方式，也就是将一个认可的layoutParams传递进去。
可以这样去形容LayoutParams，在象棋的棋盘上，每个棋子都占据一个位置，也就是每个棋子都有一个位置的信息，如这个棋子在4行4列，这里的“4行4列”就是棋子的LayoutParams。
但LayoutParams类也只是简单的描述了宽高，宽和高都可以设置成三种值：
1，一个确定的值；
2，FILL_PARENT，即填满（和父容器一样大小）；
3，WRAP_CONTENT，即包裹住组件就好。
 
保存数据到数据库，这里实质上跟注册功能差不多，也是根据已创建好的数据库中的表，将用户输入的数据插入到表中。
 
结束实现这些函数后，再次执行loadData函数，从数据库中加载数据，令其在视图中展现出来。
（4）删除课程
通过对产生的课程视图长按设置响应器，来执行改操作，主要用到的是setOnLongClickListener函数。删除功能实质上还是对数据库的操作，在数据库中删除该课程信息后，重新从数据库中加载数据，令其在视图中展现出来。
 
4.2.2课程定制界面实现
 
4.2.2.1课程定制主界面
 
因为用户的课表长度未知，因此要用到ScrollView组件，ScrollView也是一个容器，它是FrameLayout的子类，它的主要作用就是将超出物理屏幕的内容显示出来，（就是滚动条效果）ScrollView提供垂直滚动，进而可将超出物理屏幕的内容显示出来。
可以将一个采用垂直方式布局组件的LinearLayout作为ScrollLayout容器的子组件，同时，在LinearLayout容器中可以显示超出屏幕物理高度的内容。确定好整齐采用什么组件后，接下来就是将课程表的视图呈现出来，这里主要用到linearlayout布局不断嵌套linearlayout将课程表视图呈现出来，但需要注意的是，由于每个用户不同上课日子以及当天课程开始和结束的时间不一致，这里采用垂直方向的Realtivelayout布局来呈现课程定制的视图。这个部分最麻烦的地方在于对于布局的调整，此步骤较为繁琐。
最后便是使用小组其它成员规划好的底部导航栏按钮直接嵌套进该页面即可。
4.2.2.2新增课程界面
 
新增课程界面也是采用了ScrollView组件，提供垂直滚动，进而可将超出物理屏幕的内容显示出来。该界面也是类似修改个人信息界面，主要通过对话框的形式显示该界面，用户通过对六个输入框的输入，提供课程名、课程时间、课程开始、课程结束、教师名、教室地址。最后通过button控件实现对监听器的响应事件。
4.3卡片集
4.3.1卡片集功能实现
该模块主要用来在各种卡片上展示一些好看的图片，同时配上一些激励人心的语句，给予用户疲劳时一些放松，同时辅助以音乐放松心情，自由控制音乐播放与否，在切换其它界面的时候将其先尝结束，防止与其它模块冲突。后续倘若接着开发，可以卡片集所实现的功能与计时器进行配合，当用户进入任务清单完成任务时，可点击闹钟图标进行计时，当累计的计时长达到某一个值，即可解锁卡片集里的卡片，卡片颜色设置由灰色的锁定状态变为彩色的解锁状态。不仅可以使用户在查看卡片时获得学习的成就感。
卡片界面先采用LinearLayout(vertical)作为主体页面布局的容器，可在其中添加卡片，添加相关代码使得该容器的底端和导航栏的顶端彼此约束，确保该容器的占用空间不会覆盖导航栏。卡片的设置由两个ImageView和一个TextView组成，两个ImageView组成解锁和上锁的功能，当达到图片对应的学习时长后即可完成解锁，图片设置由灰色变为彩色。卡片界面添加ImageButton作为音乐播放按钮，点击按钮可实现音乐播放和停止。
卡片集主界面——CardViewPagerActivity.java
卡片切换方式——AlphaAndScalePageTransformer.java
实体类对象封装——ViewPagerItemBean.java
卡片适配器——MyPagerAdapter.java
音乐播放器——MusicService.java
卡片页面的布局文件——activity_card_view_pager.xml
卡片的布局文件——cardviewpager_item.xml
（1）卡片的切换
ViewPager是google SDk中自带的一个附加包的一个类，可以用来实现屏幕间的切换。PagerAdapter就是ViewPager提供的一个适配器。
ViewPager在使用时有如下几个步骤：
1.创建一个class，继承自PagerAdapter
2.MyPagerAdapter实现构造方法
3.需要重写4个方法
①getCount(),告诉ViewPager，有多少个View要显示，返回当前页卡数量；
②instantiateItem(),该方法两个作用：一是把要被显示的视图加载ViewGroup,二是返回要加载的View
③isViewFromObject(),实例化一个页卡，position代表当前的位置（所定位的View），用来判断instantiateItem返回的Object与当前的View是否是同一对象；
④destroyItem(),销毁页卡，该方法在View被移除时调用。
我们知道在做Android应用开发的时候都需要创建一个Activity，但很多时候我们的程序有多个界面并且每个界面都有相似的内容（例如：Toolbar、DrawerLayout）和后台的操作有共同的方法，这个时候我们写一个BaseActivity作为每一个Activity的基类，统一管理程序中的每个Activity。这里的BaseActivity是底部导航栏模块的BaseActivity。
实现切换的transformPage方法，第一个参数表示当前正在滑动的页面，第二个参数表示滑动的视图，page滑到中间的时候position为0，page在左侧时position取值区间为(-1, 0)，page在右侧时position取值区间为(0, 1)，根据这个再结合setPivotX、setPivotY、getWidth()、getHeight()等属性的设置就能实现左右切换效果。
（2）卡片的展示
该部分也是主要通过适配器将其能够进行切换，该部分主要是将图片与文字存入List中，list类型根据封装好的ViewPagerItemBean对象实现取用。同时分别将图片资源存储在数组中，以及将填充的文字存储在list中，使用textview显示出来。
存储图片资源：
 
 
存储文字信息：
 

（3）音乐的播放
用于实现音乐播放功能的bindService(Intent service, ServiceConnection conn, int flags)方法有flag参数，可以控制需要绑定的Service的行为和运行模式，其中BIND_AUTO_CREATE和BIND_WAIVE_PRIORITY两个flag在Ice Cream Sandwich也就是Android4.0版本前后有一些区别，主要是：
在4.0之前，Service的优先级被默认视同后台任务，如果设置了BIND_AUTO_CREATE则Service的优先级将等同于宿主进程，也就是调用bindService的进程。
在4.0及以上就完全变了，Service的优先级默认等同于宿主进程，只有设置了BIND_WAIVE_PRIORITY才会使Service的被当做后台任务对待，WAIVE就是放弃的意思嘛。
基于上述区别，必须对不针对4.0以上开发的App进行兼容。这种App跑在4.0以上时，bindService的时候没有同时设置BIND_AUTO_CREATE则Service应被视为后台任务，那么BIND_WAIVE_PRIORITY会被偷偷加上去。
通过bindService()绑定服务，如果客户端绑定时，第三个参数为Context.BIND_AUTO_CREATE，表示只要绑定存在，就自动建立Serice。
一个服务可以给多个客户端绑定，在真正销毁服务前，会检查和该服务绑定的连接信息（调用该次unbindService的连接在前面已经被过滤掉），如果扔有设置过BIND_AUTO_CREATE的链接存在，就不进行销毁。换句话说，一个BoundService是否被销毁，取决于当前带有BIND_AUTO_CREATE标志的连接数目，不带有BIND_AUTO_CREATE标志的连接会在服务销毁前收到onServiceDisconnected回调。一定要在AndroidManifest.xml文件中添加写好的MusicService，不然无法播放音乐哦。
音乐的播放通过点击ImageView实现，音乐文件存放在assets里，必须创建在app/src/main这个目录下面。声明相关变量：int类型的playstatus、cposition，boolean类型的isplaying，String类型的音乐文件列表。cposition指出当前音乐播放的位置，playstatus判断当前播放音乐的状态，0为未播放，1为播放。
新建一个MusicService类继承Service，onBind方法会在服务绑定的时候返回一个ibinder，我们可以让Mybinder类继承自Binder类并且实现(MusicService.Mybinder)service)接口。服务绑定成功并且返回的ibinder不为空的时候，onServiceConnected方法会被调用。musicservice即是接口的实现。接下来初始化对应的监听事件，通过对音乐播放状态和音乐播放位置的信息获取，实现音乐的播放控制，如停止、开始、切换。
4.3.2卡片集界面实现
 
本界面的实现主要需要注意的地方是使用了viewpager以及cardview。
ViewPager就是一个简单的页面切换组件，我们可以往里面填充多个View，然后我们可以左右滑动，从而切换不同的View，我们可以通过setPageTransformer()方法为我们的ViewPager 设置切换时的动画效果。这里我设置的滑动方式为：AlphaAndScalePageTransformer。
效果展示如下：
  
而采用cardview是因为CardView是可用于实现卡片式布局效果的重要控件，实际上也是一个frameLayout,只是额外提供了圆角和阴影，看上去有立体效果。将cardview嵌套在ViewPager中，同时在主界面保留有底部导航栏以及，imagebutton分别实现导航栏不同界面的跳转以及音乐的播放。
<ImageButton
            android:id="@+id/btnPlay"
            android:layout_width="50dp"
            android:layout_height="50dp"
            android:scaleType="centerInside"
            android:padding="0dp"
            android:src="@drawable/play" />

        <androidx.viewpager.widget.ViewPager
            android:id="@+id/cardViewPager"
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_weight="1"
            android:layout_marginBottom="40dp"
            android:layout_marginLeft="70dp"
            android:layout_marginRight="70dp"
            android:layout_marginTop="0dp"
            android:clipChildren="false"
            android:overScrollMode="never"/>
以上代码分为imagebutton以及cardview嵌套在viewpager中的代码实现。
4.4任务清单（我负责的是润色以及将计时功能添加到里面）
在底部导航栏中出现的第一个模块是任务清单，用于记录用户想要完成的任务，并且可以实现增添任务、标记已完成任务和未完成任务、修改任务的功能，在进入任务页面后，可以点击闹钟按钮进入钟表界面，钟表界面可以实现闹钟功能，帮助用户掌握完成任务的时间。一开始我想的是在todolistdetailActivity中能够在点击按钮存储任务后，钟表会开始计时，记录用户完成任务所需额的时间。但是在实现过程中我发现若点击保存按钮开始计时，实现是可以实现，但是实现后若不将本界面finish，在todolistMainActivity中点击新增任务的时候，始终还是打开刚刚点击计时的那个todo任务里，始终不能真正新增一个，而且由于保存之后没有finish掉本界面，由于保存后设置的状态表示栏未达到make complete的要求，将不能make complete。但是若finish掉本界面，计时功能将不能（开始与结束）完整实现，因为在点击make complete之后计时线程就还是会被干掉。很奇怪的一点就是，中途有一段时间既可以开始计时，可以结束计时，但是跟小组其它成员设计的模块结合到一起后，计时功能就会时常闪退，为了保证程序的正常运行最终还是将在todolistdetailActivity的计时功能砍掉了，放在了todolistMainActivity中。下面我将对计时功能展开具体介绍。
tv_time=(TextView)findViewById(R.id.tv_time);//计时器

        final Button btn_start = (Button)findViewById(R.id.btn_start);
        btn_start.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                String str = btn_start.getText().toString();//获取按钮字符串
                if(str.equals("开始")){ //切换按钮文字
                    btn_start.setText("暂停");
                    initView();
                }
                else{
                    btn_start.setText("开始");
                    timer.cancel();//终止线程
                }
            }
        });
private void initView() {
        timer = new Timer();
/**
 * 每一秒发送一次消息给handler更新UI
 * schedule(TimerTask task, long delay, long period)
 */
        timer.schedule(new TimerTask() {
            @Override
            public void run() {
                handler.sendEmptyMessage(COUNT);
            }
        }, 0, 1000);
    }

    private Handler handler = new Handler(){
        int num = TOTAL_TIME;
        public void handleMessage(android.os.Message msg) {
            switch (msg.what) {
                case COUNT:
                    tv_time.setText(String.valueOf(num)+"秒");
                    num++;
                    break;
                default:
                    break;
            }
        };
    };
在todolistMainActivity中实现计时功能想要达到的目标就是点击计时，开始计时，在点击其它界面的时候计时不会中断计时。点击暂停计时后计时将会暂停。
这个地方主要用到的是通过 timer 执行周期延时的任务，handler 中将计时信息更新，并在计时结束时结束 timer 的周期任务。用text显示传来的数据即可，（若不需要用到多线程，可以使用chornometer实现，这是Android专门用来显示时间的。这样显示的会更加美观一点。
5、运行结果
5.1注册登录
登录注册页面如下图所示：
登录界面：
 
 
在此界面输入已经注册好的账号和密码，若未注册，则点击Register Here，进入注册界面。
注册界面：
 
这里注册的用户名，密码，手机号都是123的账户。点击注册，完成注册，弹出提示框：
 
点击确定返回登录界面，输入账号和密码，进入主页。
5.2任务清单
任务清单主页面如下图所示，点击开始可以计时，点击闹钟图标可以进入闹钟页面，点击右上角的加号可以添加任务。
 
当点击开始后，button变为结束，点击实现计时停止，计时的功能展示如下：
 
点击闹钟的图标可以进入闹钟页面：
 
点击加号可以添加闹钟，在添加闹钟时，我们可以选择使用钟表样式或者键盘样式：
  
设置好时间后点击OK即为设置完成，跳转回第一个页面并且显示你所设置的闹钟，此闹钟可实现长按删除：
 
点击右上角的加号可以添加任务：
 
写任务后，点击右上角的减号删除写入的内容，点击保存实现写入新任务的存储，写入任务的删除可以在主页面通过长按任务条目进行删除。
  
在任务完成后可以标记任务已经完成，会在任务前面打上对勾：
 
5.3未来沙漏
下面对未来沙漏模块的内容进行展示，该页面为未来沙漏的主页面，由于展示所写入的未来倒数日，右上角的按钮分别用于切换展示视图（线性展示、网格形式展示），添加新任务和管理任务（查看所有任务、删除所有任务）：
 
写入任务时可以通过设置不同的日期，设置正数日和倒数日，点击OK完成保存，在未来沙漏主页面展示：
  
对于添加的任务可改变其任务展示方式：
 
直接点击任务可进入该任务的视图，对任务进行修改、删除，在该页面设置任务导航：
  
 
倒数日可添加分类，点击倒数本给写入的倒数日添加分类，更换图标并自定义名称：
  
 
5.4 记录分享
点击底部导航栏进入记录分享界面，记录分享界面的浏览帖子区域分了三个专栏，分别为“经验技巧栏”、“计划安排栏”、“日常分享栏”，点击任一专栏可以切换对应专栏的帖子内容：
经验技巧栏浏览页面：
 



计划安排栏浏览页面：
 
 
日常分享栏浏览页面：
 

 
点击浏览页面右下角的悬浮“发帖”按钮，进入到发布个人帖子页面，个人帖子页面包含上传个人照片、输入分享标题编辑框、选择分享标签下拉框、输入分享内容编辑框和“确认发布”按钮：
 
 
上传分享内容，将内容发布至经验栏，点击“发布”，发布成功：
 
 
在经验栏下下拉刷新内容，可以看到该用户已经成功发帖：
 
 
上传分享内容，将内容发布至计划栏，点击“发布”，发布成功：
 
 
在计划栏下下拉刷新内容，可以看到该用户已经成功发帖：
 
 
上传分享内容，将内容发布至记录栏，点击“发布”，发布成功：
 
 
在记录栏下下拉刷新内容，可以看到该用户已经成功发帖：
 
 
现在登录另外一个账号“1304075594”，查看是否可以看见“123”用户发布的内容：
登录的是“1304075594”用户：
 






“1304075594”用户可以看到“123”用户的发布帖子：
   
5.5课程定制
点击底部导航栏进入课程定制界面：
 
点击右上角添加图标，新增课程（课程名：Android，星期几：4，第几节课开始：6，第几节课结束：8，教师名：lh，教师地址：wbl）：
 
点击完成后，主界面显示如下：
 
长按对课程进行删除，删除后结果如下：
 
5.6卡片收集
点击底部导航栏进入卡片收集模块：
 
点击音乐图标可以播放音乐，因为该音乐作为bgm因此我觉得一首歌单曲循环较为合适故如此构造相关函数。再次点击图标，图标会变灰，音乐将会暂停播放。
 
左右滑动将可以切换卡片：
 
 
5.7 个人中心
点击“123”用户记录分享头部左上角的抽屉icon，个人中心以抽屉的形式展现出来：
 





“123”用户点击修改密码，可以弹出对话框对密码和手机号进行重新设置：
 
 
点击确认后，跳出对话框提醒用户重新返回登录界面进行登录：
   

 
此外，点击个人中心的第二个菜单项“我的发布”，可以查看“123”用户目前所有的发布：
 
 
帖子之间可以根据“123”用户的喜好对帖子进行上下拖动摆放，例如当“123”用户想把计划栏帖子放在第一个位置，则“123”用户可以长按该帖子往上拖动：
   
 
“123”用户向左拖动任意帖子，可以显示出“删除”的button进行相应帖子的删除：
   
 
返回到记录分享对应“计划栏”浏览区域，可以看到该帖子不见了：
 
 
最后，“123”用户可以点击个人中心右下角的退出登录按钮，app将会弹出对话框提示用户是否要进行退出，点击“确定”，手机完全退出该app：
   
6．总结
在本次Free Study App的设计及完成过程中，一开始便遇到了一个不小的难题——对使用Android Studio开发的不熟悉。在本学期学习Android开发的过程当中，不论是老师平时在课堂上授课，还是在课下完成相关的实验，使用的开发工具都是Eclipse。而为了使我们设计出来的App功能更加完备，呈现的界面更加美观，我们选择了Android Studio作为本次项目的开发工具。即便在本学期课余时间有花时间学习相关的一些技术，具备一定的编程能力基础，但在真正上手开发一个项目的时候，还是遇到了不少困难，由于平常上课的时候也想着能够同步完成android的一些简单操作。因此，我同时安装了Android Studio和Eclipse。
尽管它具有强大的支持多工程的构建、支持多方式依赖管理的功能，能够提供最大的便利去构建工程，但在进行整个App设计与开发的过程中，我是丝毫没有感受到它的便捷之处。反而因为我下载的是最新版的AS，产生了很多和gradle相关的问题，一开始的安装就因为本身下载了Eclipse时安装了许多SDK，因此在安装AS时，就不能再次检测到，为了保证两个运行软件不冲突，只能让其它同学把适配AS的SDK发给我，我再安装。同时由于版本的更新，使得AS很多包的使用规则更新，最显著的一个就是，老版的添加依赖项是，android.support，新版的是androidx，因此，为了找到对应的依赖项就不少费工夫。 
而且在一开始的数据库的讨论设计是一个复杂的过程，首先需要整理概念数据模型，在绘制ER图的基础上，逐渐分析出表与表之间的关系和关系的命名及数量，对于多元关系，尝试抽出共有部分进行简化，对于双向关联，关系本身应作为一个数据库表。通过讨论，我们的数据库修改了好几版，最终通过进行探讨才确定了最终的数据库字段以及数据库中各表之间的关系。
在整个项目开发的过程当中，即便在实现功能时遇到了诸多困难，但基本上都能通过不断的学习，在自己的努力下找到解决方法，自身也在其中提高了Android开发能力，受益匪浅。在进行系统测试时，我懂得了反复测试系统的重要性，只有不断改善、不断测试，才能提高系统运行的稳定性。
本项目存在不足之处在于由于我们APP功能较多，因此主线程需要处理的任务太多，导致有时候APP运行的不太稳定，在以后的开发过程中应及时避免这个问题，来保证程序运行的顺畅。
同时，我也在本次系统开发的过程中受益良多，无论是知识层面、问题解决层面、沟通交流层面都有了明显进步，也体会到了团队合作在项目开发中的重要性。总之，我非常感激与珍惜这次的项目开发机会，在未来，我也会进一步学习移动平台应用开发的课程，不断汲取移动端软件的开发思想、原理以及技术等相关知识，精进Android开发技术，不断提高自身的开发能力及综合能力，争取实现更大的进步。

## LAS分析

#### 简介

####	**什么是LAS分析服务**

LAS分析服务通过客户端及Cloud Data，收集应用及用户的各种数据，并在Leap Cloud中进行专业分析，最终生成面向运营者的报表。

####	**为何您需要LAS分析服务**

LAS分析服务是实时、免费、专业的移动应用统计分析服务，它将帮助您全面分析运营状况，深度了解典型用户并优化运营策略。最终实现：

*	洞察运营概况及趋势：从产品新增用户、活跃用户、应用启动次数、版本分布，到用户的使用细节、用户属性以及行为特征，你可以洞察到各类数据指标，全面了解产品运营情况和迭代效果。
*	洞察用户行为：还原每位用户的使用行为链条，并掌握其活跃度，留存率及转化率。
*	提升用户体验：定义用户分群，针对不同用户群体提供个性化体验。
*	提升应用营收：跟踪消费行为，制定营销策略，最大化的提升营销效果。


####	**LAS分析如何工作**

“LAS分析”SDK，帮助我们跟踪用户行为，为云端的分析服务提供数据。主要包括：
1.  自动收集信息（如终端信息等）
2.  追踪会话
2.  自定义事件
3.  追踪消费
4.  追踪页面访问
5.  收集安装信息

LAS"分析"服务将通过以下功能，帮助您更了解用户及其行为，做出更有效的运营策略，

> **1.   用户分析：** 包括“趋势”，“留存”，“终端”等模块

> **2.   使用行为分析：** 包括”使用率“，”用户行为“等模块

> **3.   消费行为分析：** 包括”收入“等模块

 优势：
> 1.    最佳实践：LAS提供业内极具竞争力的分析参数和模型，经过亿级用户量应用的验证
> 2.    用户群划分：您可以分析自定义用户群的属性及行为
> 3.    丰富的报表：透过运营者视角，LAS提供一套完整的，直观的报表:
>
>>	我们还可以通过下列筛选因子，自定义报表的显示数据：
>> 
>>	* 用户群：指定查看特定用户群的指标变化
>>	* 过滤器：指定应用版本和渠道
>>	* 时间段：指定特定的时间跨度

#### 概览

仪表盘向您快速展示：主要用户指标（新增用户，活跃用户，会话）及收入的变化：

1.  昨日主要指标概览

    img
    
	主要包括：昨日三个主要指标（新增用户/活跃用户/会话）及收入的数量以及增长率
	
2.  主要指标随时间的变化

    img

3.  主要指标的地理分布

    img
    
4.  新用户和会话 ？？TO ASK ？？

    img

#### 趋势

趋势向您展示：主要用户指标（新增用户，活跃用户，会话）在不同维度中的变化。

>   在这里，您可获取的信息,包括但不仅限于：

> * 用户增长情况，用户使用情况
> * 受欢迎的应用版本

1.  实时

    快速展示：48小时内，三个主要指标每小时的数量变化

    img
	
2.  新用户/活跃用户/会话

    img1；img2；img3

3.  应用程序版本/渠道

    展示三个主要指标在各个应用版本/渠道的数量分布

    img1； img2

#### 留存

留存报表向您展示：不同时间段新增用户随后的留存率。

> 在这里，您可获取的信息,包括但不仅限于：

> * 何时新增的用户忠诚，及其忠诚度
> * 新增用户多久之后开始流失

1.  留存率

    img

#### 收入

收入向您展示：重要营收指标（总收入，订单数，消费用户数，用户首单，转化率）的变化。

> 在这里，您可获取的信息，包括但不仅限于：

> * 用户购买情况变化
> * 购买规律（何时，注册后多久出现购买高峰）
> * 用户购买力/潜在购买力

1.  趋势
    
    快速展示三个主要营销指标（总收入，订单数，消费用户数）的变化趋势
    
2.  首单

    展示：
    1. 首日/首周/首月付费率
    2. 首单用户数量
    3. 首单完成所耗时常
    4. 首单金额分布
    
3.  转化率

    展示：
    1. ARPU：平均从每位活跃用户获得的收入
    2. ARPPU：平均从每位活跃用户获得的收入百分比
    
    
4.  国家

    展示营销指标在不同国家的分布
    
5.  分布
    
    展示：
    1.  每单消费金额的分布
    2.  消费单数对应用户数量的分布

    
#### 用户使用率

用户使用率向您展示：应用的使用率及用户的活跃度。

1.  会话时长

    展示某一天中，不同会话时长对应的会话数量及用户数量
	
2.  会话频率

    展示某一天中，不同会话数量对应的用户数量

	请注意，我们还可以自定义报表：
	> * 向报表增加另一天的数据，以作对比

#### 用户行为

用户行为向您展示：用户在应用内留下的痕迹。

> 在这里，您可获取的信息，包括但不仅限于：

> * 应用被访问最多的页面
> * 导致用户离开的页面
> * 自定义行为的使用偏好及离开原因分析

1.  使用路径

    展示：
    1.  用户在应用内不用页面的流向
    2.  每个页面的访问量及停留时间
    3.  导致用户退出的页面，及相应的退出比例（退出数占所有会话的比例）
	
2.  自定义事件

    展示所有自定义事件在两天内的触发次数
    
    img
    
	请注意，我们还可以添加自定义事件：
	> 1. 点击管理事件 -> 添加事件
	> 2. 填写事件名称和描述
	关于自定义事件的实现，请移步至[LAS分析服务SDK使用向导](...)
	
	img
	
3.  路径沙漏

    展示所有自定义沙漏中各个事件之间的流向
    
    img
    
    请注意，我们还可以添加自定义路径沙漏：
	> 1. 点击管理沙漏 -> 添加沙漏
	> 2. 填写沙漏名
	> 3. 点击添加步骤，按照顺序，添加目标事件
	    	
    img

#### 终端

终端向您展示：用户所持移动终端的信息。

1.  终端设备型号
2.  分辨率
3.  操作系统版本
4.  网络接入
5.  通信供应商
6.  国家

#### API使用

API使用向您展示：应用对LAS提供的云服务的使用情况。

1.  云数据

    展示所有类的访问次数（总数/成功次数/失败次数）
    
2.  云代码

    展示所有任务/云函数的访问次数
    
3.  文件流量

    展示文件上传/下载/删除的总流量
    
    
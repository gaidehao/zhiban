# zhiban
2020年8月26日起，想通过自己努力，制作一个通过python语言设计的值班表排版程序。

一、排班顺序。
    每天值班分为  带班领导  和  值班员   两类人。
        带班领导 共8人，其中1人周末和法定节假日不值班、节假日回来的前两个工作日值班、或周一周二值班。如遇节假日回来只有两个工作日。则只安排值第一个工作日的，因为周末前晚不值班。
        剩下7人其他时间 插空  轮流值。
    
        值班员  按值班规定分，分成两种顺序
    
        1. 双排-------法定节假日（不一定包括周末）和特殊日期                    值班员 每天两人  （10个中层中10选1，    普通员工17选1）
        2. 单排-------不是法定节假日（不是特殊日期和节假日，平时周末也算单排）    值班员 每天一人   （10+17共27人，27选1）

二、名单
    代码简写 带班领导两类
    name_daiban1=(liu1)
    name_daiban2=[li,liu2,cao,sun,shi,zhai,wan]    
    
    双排名单两个
    name_zhongceng=[a,b,c,d,e,f,g,h,i,j]
    name_putong=[p1,p2,p3......p17]
    
    单排名单1个
    name_all=[1,2,3,4,5,6....27]

三、下一步 在思想
   

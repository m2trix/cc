# h1 ----- TEST-CC-TEST
## h2
### h3
#### h4
##### h6
###### h7


#### 无序列表
- 列表1
  - 列表1.1
  - 列表1.2
- 列表2
- 列表3



#### 有序列表
1. 列表1
    1. 列表1.1
    2. 列表1.2
2. 列表2
3. 列表3



### 引用
> 如果你需要在文稿中引用一段别处的句子，那么就要用到「引用」格式。



### 粗体斜体
*这是斜体*

**这是粗体**


### 插入链接
[显示文本](https://avatars2.githubusercontent.com/u/4901197?s=40&v=4)

### 插入图片
![显示文本](https://avatars2.githubusercontent.com/u/4901197?s=40&v=4)



### 分割线
***


### 表格


header 1 | header 2
---|---
row 1 col 1 | row 1 col 2
row 2 col 1 | row 2 col 2


| Item     | Value   | Qty|
| :------- | ------: |:--:|
| Computer | 1600USD | 5  |
| Phone    | 12USD   | 12 |
| Pipe     | 1USD    | 234|





### 代码高亮
``` python
#%%
import matplotlib.pyplot as plt
import matplotlib as mpl
import numpy as np 

x = np.linspace(0, 20, 100)
plt.plot(x, np.sin(x))
plt.show()
```

### To-do list
- [x] 已完成项目1
  - [x] 已完事项目1
  - [x] 已完事项目2
- [ ] 未完成项目1
  - [ ] 未完事项目1
  - [ ] 未完事项目2


### 绘制图表
#### 流程图
```
graph TD
    A[Christmas]-->B(Go Shopping)
    B --> C{Let me think}
    C --> |one| D[Laptop]
    C --> |two| E[iPhone]
    C --> |three| F[Car]
```


#### 序列图
```
sequenceDiagram
    loop every day
        Alice->>John: hello John,how are you?
        John-->>Alice: Great!
    end
```


#### 甘特图
```
gantt
dateFormat YYYY-MM-DD
title 产品计划表
section 初期阶段
明确需求:2016-03-01, 10d
section 中期阶段
跟进开发:2016-03-11, 15d
section 后期阶段
走查测试:2016-03-20, 9d
```

```
gantt
dateFormat YYYY-MM-DD
title 计划进度表

section 问卷确认阶段
项目确认:done,des1,2015-06-01,2015-06-06
问卷设计:done,des2,2015-06-04,4d
试访    :done,des3,2015-06-06,4d
问卷确定:done,des4,after des3,1d

section 问卷调查阶段
实地执行:done,des5,after des4,10d

section 问卷录入阶段
数据录入:active,des6,after des5,5d
数据分析:active,des7,2015-06-23,3d
报告提交:active,des8,2015-06-26,5d

```
[Markdown 更详细的 Gantt图语法](http://knsv.github.io/mermaid/#styling39)

[Markdown 语法杂记](https://blog.csdn.net/wangyaninglm/article/details/52887045)

# lagou comment analysis
[notebook view](http://nbviewer.jupyter.org/github/xchaoo/lagouComment/blob/master/lagou_comment.ipynb)
## Background
通过分析拉勾招聘平台上拉勾公司的面试评价,帮助企业发现招聘问题。
## solution
通过爬虫获取拉勾网公司2015全年面试评论数据,利用Python数据 处理框架pandas进行清洗、结构化,采用全年面试反馈数据指标结 合文本挖掘聚类分析的方法,分别从全公司、部门、用户维度,对面 试评论进行分析。
## Data Set
数据维度:时间、面试评价、个人总评分、所属部门、是否回复 
## Data fields
* isAnonymous
* usefulCount 
* comprehensiveScore
* replyCount
* tag_used
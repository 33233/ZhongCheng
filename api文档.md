# api 列表
## GET /api/content
请求公司简介
#### request
```
slug: introduction-2327e6d7-f5a5-402c-82ee-cef96d110e12
```
#### response
```
{
    "data": [
        {
            "timestamp": "创建时间",
            "updated": "最后修改时间",
            "slug": "后缀",
            "content": "公司介绍",
            "shiming": "企业使命",
            "jiazhi": "核心价值",
            "linian": "发展理念",
            "mubiao": "战略目标",
            "yuanjing": "企业愿景",
            "tuandui": "技术团队",
            "yeji": "公司业绩"
        }
    ]
}
```
## GET /api/content
请求团队信息
### 地质灾害管理及预报预警系统研发团队
#### request
```
slug: team-a4da4587-d2ab-497b-bdde-506a008f9516
```
#### response
```
{
    "data": [
        {
            "timestamp": "创建时间",
            "updated": "最后修改时间",
            "slug": "后缀",
            "name": "团队名称",
            "introduction": "团队介绍"
        }
    ]
}
```
### 黄土高原生态保护修复关键技术研究团队
#### request
```
slug: teamc185686a-e961-4b9d-89ff-68819e7e474f
```
#### response
```
{
    "data": [
        {
            "timestamp": "创建时间",
            "updated": "最后修改时间",
            "slug": "后缀",
            "name": "团队名称",
            "introduction": "团队介绍"
        }
    ]
}
```
## GET /api/content
获取单条新闻
#### request
```
slug: 在获取所有新闻时返回
```
#### response
```
{
    "data": [
        {
            "timestamp": "创建时间",
            "updated": "最后修改时间",
            "slug": "后缀",
            "title": "标题",
            "content": "文章内容"
        }
    ]
}
```
## GET /api/contents
获取所有新闻
#### request
```
type: News
count: 返回的文章数 默认为 10 ，-1 为返回所有文章
offset: 分页数，默认为 0
```
//注意大小写
#### response
```
{
    "data": [
        {
            新闻一
        },
        {
            新闻二
        }
        ··· ···
    ]
}
```
## GET /api/content
获取联系方式
#### request
```
slug: contact-528f2059-b7cb-4104-a96e-caff7623d3e6
```
#### response
````
{
    "data": [
        {
            "timestamp": "创建时间",
            "updated": "最后修改时间",
            "slug": "后缀",
            "name": "联系人姓名",
            "tele": "联系电话“
        }
    ]

}
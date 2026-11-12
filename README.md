对用户来说，使用该平台，可以在同一个页面集中搜索出不同来源、不同类型的内容，提升用户的检索效率和搜索体验。
对企业来说，当企业内部有多个项目的数据都存在搜索需求时，无需针对每个项目单独开发搜索功能，可以直接将各项目的数据源接入搜索中台，从而提升开发效率、降低系统维护成本。
聚合搜索页面 ，可以搜索文章、用户、图片等，一次搜索各种类型数据均可查出。


技术选型
前端
•	Vue 3
•	Ant Design Vue 组件库

后端
•	Spring Boot 2.7 框架 + springboot-init 脚手架
•	MySQL 数据库（8.x 版本）
•	Elastic Stack
o	Elasticsearch 搜索引擎（重点）
o	Logstash 数据管道
o	Kibana 数据可视化
•	数据抓取（jsoup、HttpClient 爬虫）
o	离线
o	实时
•	设计模式
o	门面模式
o	适配器模式
o	注册器模式
•	数据同步（4 种同步方式）
o	定时
o	双写
o	Logstash
o	Canal
•	JMeter 压力测试

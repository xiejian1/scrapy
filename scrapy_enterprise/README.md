## 简介

- python scrapy 开发企业级分布式爬虫开发架构，使用该架构可快速搭建分布式爬虫环境。

***

## 相关技术

- 使用scrapy_redis进行分布式爬虫操作。
- 使用mongodb存储数据
- 开发环境与生产环境的配置分离
- 自动化部署爬虫脚本，爬虫部署采用scrapyd框架
- 支持部署到docker中
- 使用中间件自动处理随机user-agent
- 重写make_request_from_data，实现基于scrapy_redis的Feeding模式，可自定义发送请求

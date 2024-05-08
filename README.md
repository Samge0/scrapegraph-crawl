## scrapegraph-crawl
just a test code

[scrapegraph](https://github.com/VinciGit00/Scrapegraph-ai?tab=readme-ov-file)
[scrapegraph-doc](https://scrapegraph-ai.readthedocs.io/en/latest/getting_started/examples.html)

AI 辅助的开源爬虫

初步用ollama模型跟chatgpt3.5模型尝试后感觉：

优点：
    忽略页面差异，直接提取结构化数据
    非编程人员可以把玩
    某些领域的数据提取，泛化能力不错

缺点：
    - 效率较低，识别耗时高
    - 稳定性不是太高
    - 识别效率有点低
    - 错误率有点高。同一字段不同请求可能返回差异数据，存在捏造数据的情况

至于缺点，可能跟模型能力及依赖库的默认提示词有挺大关系，或许后续模型能力越来越强，价格越来越低，使用AI模型辅助的爬虫将成为主流。毕竟，自动化执行一些不是很复杂的页面数据采集任务，可以解放很多非编程人员的双手。
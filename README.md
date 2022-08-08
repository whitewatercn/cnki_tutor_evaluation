# Cnki_TuTor_Evaluation
这是一个小爬虫，用于爬取并导师在CNKI收录文献的相关信息
基于selenium、jieba、wordcloud，通过词云，直观了解导师研究方向

# 使用说明
需手动填写`DRIVER—_PATH`,`作者`,`作者单位`,`TXT_PATH`,`STOPWORDS.add()`,`TFF_PATH`

# 目前已实现
爬取文献名，绘制词云


# TODO
- [ ] 爬取合作作者，绘制作者词云，锁定其他相关导师
- [ ] 根据时间段选择展示，如每5年绘制一版（方便缕清导师研究方向的变更
- [ ] 爬取文献摘要，绘制词云，比只爬文献名更细化（也更头秃

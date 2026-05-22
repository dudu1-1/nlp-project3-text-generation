# nlp-project3-text-generation
项目3：可控文本生成与参数对比实验

## 项目简介
基于轻量级中文GPT2模型 `uer/gpt2-chinese-cluecorpussmall`，对比不同温度参数与采样策略对文本生成效果的影响。

## 实验内容
- 对比温度参数：0.2 / 0.6 / 0.9
- 对比采样策略：随机采样 vs 贪婪搜索
- 评价指标：词汇多样性(TTR)、文本重复率、生成耗时
- 可视化结果：params_effect.png

## 运行环境
- Python 3.8+
- PyTorch
- Transformers
- Matplotlib

## 运行方式
打开 `project3_text_generation.ipynb`，逐 cell 运行即可。

# NLP
通过词向量+神经网络进行深度学习，构建模型，实现用户意图的预测  

# 基于
- keras  
- gensim  
- sklearn  

# train.ipynb
根据用户输入样本及标签的格式，通过递归创建模型树，为每个分支训练模型

# predict.ipynb
根据训练好的网络模型，对未标记的数据进行预测

# test.ipynb
根据训练好的网络模型，使用标记好的数据进行测试

# build_w2v_model.ipynb
构建词向量模型

# 用户输入样本及标签.xlsx
存放了训练集样本及对应的标签

# stopwords.txt
存放了分词时的停用词

# newdic.txt
存放了加载jieba库时导入的自定义词典

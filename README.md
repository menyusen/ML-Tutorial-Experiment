# ML-Tutorial-Experiment

1、mnist_sklearn：利用mnist数据集进行scikit_learn实践。

     在mnist数据集上，对'NB'、'KNN'、'LR'、'RF'、'DT'、'SVM'、'GBDT'算法进行了测试，在这个数据集中，由于数据分布的团簇性较好为，因此KNN的效果不错，准确率96.64%，GBDT(96.17%)是个非常不错的算法，在kaggle等数据竞赛中应用较多，且效果较好，SVM(94.35%)也具有不错的效果，但计算量较大，训练时间较长。
  
2、spam_filtering：利用Euron-spam语料库及scikit-learn实现垃圾邮件分类过滤。

      数据来源：Euron-spam 语料库（http://www.aueb.gr/users/ion/data/enron-spam) 的预处理数据，在6个目录中包含33716封邮件，其中包含「ham」和「spam」两个文件夹，非垃圾邮件和垃圾邮件的总数分别为 16545 和 17171。
      通过以下步骤构建此应用程序：
      1. 准备文本数据
      2. 创建词典
      3. 特征提取过程
      4. 模型训练
      5. 测试
      利用scikit-learn的支持向量机(SVM)和多项式朴素贝叶斯(MultinomialNB)进行模型的训练，以7:3的比例分成训练集和测试集，从训练结果看，支持向量机略优于朴素贝叶斯分类器。
      SVM precision: 97.47%, recall: 98.25%
      MultinomialNB precision: 96.72%, recall: 97.80%

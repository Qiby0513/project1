# Project1
In this project, The dataset that we used was’ breast cancer-wisconsin ’, which can be download at https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/breast-cancer-wisconsin.data. There are 698 samples in this data, each samples has 9 features and 1 target variable ‘Class’. A total of five machine learning methods were selected, namely: Decision Tree Classifier, Logistic Regression, SGD Classifier, Linear SVC, K-Neighbors Classifier. 
## **Decision Tree Classifier**
Decision tree is a prediction model; It represents a mapping between object attributes and object values, Each node in the tree represents an object, and each fork path represents a possible property value, Each leaf is the value of the object represented by the path from the root node to the leaf. Decision tree is the best choice to describe nonlinear relationship.
# 线性分类模型
线性分类模型是透过特征的线性组合来做出分类决定，以达到预测的目的。
# 支持向量机
支持向量机是一类按监督学习方式，是对数据进行二元分类的广义线性分类器，其决策边界是对学习样本求解的最大边距超平面
# k近邻算法
k近邻算法的思路是：在特征空间中，如果一个样本附近的k个最近(即特征空间中最邻近)样本的大多数属于某一个类别，则该样本也属于这个类别。

# 实验过程
1. 将数据导入，存储到 data中；
2. 去除有数据缺失的样本；
3. 对数据进行划分，80%的样本作为训练集，20%的样本作为测试集；
4. 对数据进行预处理，保证数据的每个维度均值为0，方差为1；
5. 分别用单一决策树，逻辑斯蒂回归模型，随机梯度参数，支持向量机和k近邻算法进行训练和预测；
6. 比较几种方法训练的准确率和r2评分。
方法      单一决策树     逻辑斯蒂回归     随机梯度参数    支持向量机    k近邻算法
准确率     0.920         0.949           0.956          0.949        0.956
方法      单一决策树     逻辑斯蒂回归     随机梯度参数    支持向量机    k近邻算法
r2-score  0.694          0.786           0.817          0.786        0.817
由上述数据可知，在“良/恶性乳腺癌肿瘤预测”的样本中，随机梯度参数的预测准确率最高，单一决策树的预测准确率最低。

# 实验心得
通过此次机器学习的作业，我对老师上课所讲的几种机器学习的方法有了根深一层的理解，有许多上课不是很清楚的知识点，都通过此次作业，在课后进行自主学习和巩固，了解到了精确度（precision），召回率（recall），f1指标（f1-score）的具体概念和计算方法，了解了混淆矩阵的概念。总的来说此次作业受益匪浅，对我之前几次课程所学习的内容有一个巩固和提高。


# 使用RFM分析和KMeans聚类探索客户细分
Exploring Customers Segmentation With RFM Analysis and K-Means Clustering

在商业领域中，营销人员通常会花费大量时间和资金来吸引新客户，但是忽略了维护现有客户的重要性。然而，保持现有客户的满意度和忠诚度同样重要，因为在客户保留率低于新客户获取率的情况下，整个客户群体将会逐渐减少。因此，企业需要将现有客户的需求和需求放在首位，而不是只关注新客户。

在营销计划中，企业需要确保所投资的资金和资源能够最大限度地满足客户的需求和利益。营销人员的目标是通过定制计划，更好地了解客户的需求和行为，并针对不同的客户群体提供个性化的服务和优惠。

为了更好地了解客户的行为和需求，营销人员可以使用不同的方法来对客户进行分类和分析。其中一种常见的方法是使用“最近购买时间”、“购买频率”和“消费金额”等因素来对客户进行细分。这可以帮助企业更好地了解不同客户群体的需求和行为，从而制定更加精准的营销计划和服务方案。

通过维护现有客户和吸引新客户的有效结合，企业可以实现业务的长期稳定发展。因此，营销人员需要更加关注现有客户的需求和需求，并采取措施来提高客户的忠诚度和满意度，以确保业务的持续增长和成功。

## 本项目旨在使用数据挖掘技术对客户进行分类，以实现精准营销。

具体目的如下：

使用K-MEANS聚类初步发现数据集中的大类客户群，为进一步客户细分提供参考。

在每个大类内使用RFM客户分类细分，发挥RFM客户分类在表达性强和结果易解释这两个方面的优势。因为在同一大类内,客户的属性相近,所以RFM客户分类细分结果也比较容易理解。

结合K-MEANS聚类和RFM客户分类两种方法的优势,进行全面而深入的客户分类，更好地了解客户需求和购买习惯，制定更针对性的营销策略，从而实现精准营销的目的。

## Datasets

"这是一个跨国数据集,包含2010年12月1日至2011年12月9日之间一家以英国注册的非实体店铺在线零售商的所有交易。该公司主要销售各种场合的独特礼物。该公司的许多客户是批发商。"

Context
Typically e-commerce datasets are proprietary and consequently hard to find among publicly available data. However, The UCI Machine Learning Repository has made this dataset containing actual transactions from 2010 and 2011. The dataset is maintained on their site, where it can be found by the title "Online Retail".

Acknowledgements
Per the UCI Machine Learning Repository, this data was made available by Dr Daqing Chen, Director: Public Analytics group. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK.

[Dataset Link](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

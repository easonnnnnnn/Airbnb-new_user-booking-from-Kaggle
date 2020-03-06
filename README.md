# Airbnb-new_user-booking-from-Kaggle
___
### 首先介绍一下这个竞赛，这是一个四年前的Kaggle上的一个比赛，采用的是Airbnb2010年到2014年的真实用户数据，通过数据集对用户的订房国家进行预测。
竞赛地址：   
https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings   
竞赛描述：   
In this challenge, you are given a list of users along with their demographics, web session records, and some summary statistics. You are asked to predict which country a new user's first booking destination will be. All the users in this dataset are from the USA.
There are 12 possible outcomes of the destination country: 'US', 'FR', 'CA', 'GB', 'ES', 'IT', 'PT', 'NL','DE', 'AU', 'NDF' (no destination found), and 'other'. Please note that 'NDF' is different from 'other' because 'other' means there was a booking, but is to a country not included in the list, while 'NDF' means there wasn't a booking.
The training and test sets are split by dates. In the test set, you will predict all the new users with first activities after 7/1/2014 (note: this is updated on 12/5/15 when the competition restarted). In the sessions dataset, the data only dates back to 1/1/2014, while the users dataset dates back to 2010.    
在这个挑战中，将向您提供一个用户列表以及他们的人口统计信息、web会话记录和一些汇总统计信息。要求您预测新用户的第一个预订目的地是哪个国家。这个数据集中的所有用户都来自美国。
目的地国家有12种可能的结果:“US”、“FR”、“CA”、“GB”、“ES”、“IT”、“PT”、“NL”、“DE”、“AU”、“NDF”(没有找到目的地)和“other”。请注意，“NDF”与“other”是不同的，因为“other”表示有预订，而“NDF”表示没有预订。
训练和测试集按日期划分。在测试集中，你将预测2014年1月7日以后所有有第一次活动的新用户(注意:这是在12月5日15日比赛重新开始时更新的)。在sessions数据集中，数据只追溯到2014年1月1日，而用户数据则追溯到2010年。
___
在此文件夹中，文件有3个part：   
*  数据探索、特征工程、模型搭建   
*  在参考几个kernel后，感慨万分，学习之路漫漫，抱着谦卑的心去学习，脚踏实地不要着急一步一步的来。
*  通过学习别人的代码，我对于数据有了理解和简化，便试着逐渐写写看，逐步理解工作流程和思路。
*  一些细节标注在Jupyter notebook里。
___
Reference:
其中代码参考学习的大多数来自于Kaggle 上前辈的Kernel，包括不限于David Gasquez,Sanro,Kwu2u.

# TikTok视频数据分析


## 项目描述
这个数据分析项目使用 Python 和以下库：numpy, pandas, matplotlib, seaborn, spicy, scikit-learn 以及statsmodels。  
该项目旨在探究如何在抖音上增加粉丝以及如何对热门视频进行分析，从而提高粉丝数量。该项目包括 EDA 来分析数据集，包括描述性统计，可视化和数据清理。还包括一个基本的线性回归模型，用于预测影响视频播放量的影响因子。探索性数据分析部分分析了参与度、粉丝数量和视频流行度之间的关系，并对高参与度和高粉丝的用户进行了聚合、计算和可视化分析。在分析人气前十的创作者视频标签与其参与度的关系后，项目提出了关于如何在抖音上获得更多粉丝和更多参与度的建议。基本线性回归部分使用线性回归模型来探索各个因变量与目标变量之间的关系，通过绘制聚类图和混合可视化的方法对变量的相关性进行了初步了解和可视化。最后，拟合模型来确定各自变量对因变量的影响，对得出的结论进行解释，并提出了模型的不足和改进建议。
<br>
</br>

## 运行要求
运行这个项目，首先需要安装jupyter notebook；  

然后运行以下命令以安装这些包及其版本：  
`pip install -r requirements.txt`
  
或者手动安装这些库：  
`pip install numpy pandas matplotlib seaborn scipy scikit-learn statsmodels`

如果你使用conda，则运行这个命令：  
`conda install numpy pandas matplotlib seaborn scipy scikit-learn statsmodels`
<br>
</br>

## 数据
所使用的数据包含作者信息（姓名和粉丝数量）、视频统计信息（点赞数、评论数、播放数和分享数）、视频元数据（视频长度）以及搜索标签信息（标签名称和浏览量）。
新加的一列是 ‘engagement’（参与度），是根据其他某些列的值计算得出的新列。计算公式如下：  
<div style="text-align: center;">
<strong> (点赞数 + 评论数 + 分享数) / 粉丝数) * 100</strong>
</div>   

### 数据集来源： [Kaggle](https://www.kaggle.com/datasets/anasmahmood000/tiktok-dataset)    
<br>
</br>

## 结论
本研究的分析结果表明，想要成为受欢迎的 TikTok 用户并增加粉丝数量，应该采取以下措施：
- 经常发布新视频，保持活跃度；
- 与观众进行互动，回复评论、与他们互动等，增加粉丝的忠诚度；
- 优化视频内容，创造独特和有趣的内容，使用特殊效果和创意的剪辑等，以吸引更多的观众。

同时，增加 TikTok 粉丝数量需要关注以下指标：
- 视频参与度指标，包括播放数、点赞数和评论数；
- 视频的观看次数和视频参与度，观看数和参与度反映视频的受欢迎程度和观众的兴趣程度；
- 视频的话题和标签，根据受众喜欢的视频风格来选择合适的话题和标签。

为了创作受欢迎的 TikTok 视频，需要注意以下几点：
- 视频长度要控制在适当的范围内，短视频更容易吸引观众；
- 创作让观众喜欢的独特且有趣的内容，坚持原创作品，优化视频内容和提升视频质量；
- 使用流行的话题和合适的标签，可以使视频更容易被发现，更容易获得观众的喜爱。

需要注意的是，标签浏览量和点赞、播放量之间的相关性并不是非常强烈，因此在视频推广过程中，使用标签要适度，不可过度依赖标签浏览量来提高视频的表现。

通过分析自己的视频类型和观众参与度，我们可以了解自己的优势和粉丝的需求，构建用户画像；并结合目前所处的人气阶段，制定适合自己的视频发布策略。

最后，作者的粉丝数、分享数和点赞数对播放次数具有正相关性，而视频时长对播放次数的影响是负相关关系。因此，在制定社交媒体营销策略时，要注重提高关键因素，以增加视频的播放量。
  
<br>
</br>



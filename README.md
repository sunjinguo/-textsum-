# -textsum-
数据集准备处理（线下）
文本数据预处理（线上）
（１）过滤表情
（２）过滤短链
（３）替换日期、字母数字组合、数字为TAG_DATE,TAG_COMBINE,TAG_NUMBER （正则匹配）
 (4) jieba 分词/新浪分词(自定义词 TAG_DATE,TAG_COMBINE,TAG_NUMBER)
 （5）繁简体转换
 （6）全角转半角
文本数据后处理
（1）unk未登录词处理
（2）重复词处理
（3）TAG_DATE,TAG_COMBINE,TAG_NUMBER召回
（4）相似度判定（线上评测指标）

方案1：基于词  词表较大，未登录词多
方案2：基于字  词表小，无未登录词

 

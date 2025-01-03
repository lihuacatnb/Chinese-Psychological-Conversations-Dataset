# 中文心理对话数据集
# Chinese Psychological Conversations Dataset

## 1.数据集简介（Dataset Introduction）
数据内容主要来自于简单心理的心理问答，另收集了其他中文心理平台的问答对话，数据量相对较少，适合新手用于模型微调。<br>
<br>
_The data primarily comes from psychological Q&A on the Simple Psychology platform, supplemented by Q&A dialogues from other Chinese psychological platforms. The dataset is relatively small and suitable for beginners for model fine-tuning._

## 2.数据集内容（Dataset Contents）
数据集涵盖了包括人际关系、情感问题、就业焦虑、精神健康、心理知识以及梦境解析等心理议题，还特别加入了关于伦理困境（如乱伦、猥亵）以及高风险心理干预（如自杀倾向）的案例及心理咨询师的专业回复来提升心理咨询模型的专业性与覆盖度。数据集还引入连续回答和一问多答的问答形式来针对性优化大模型微调的 BLEU-4 和 ROUGE-2 等关键指标。未来，数据集将持续扩充数据量，为心理健康领域提供更多支持。<br>
<br>
_The dataset covers psychological topics such as interpersonal relationships, emotional issues, employment anxiety, mental health, psychological knowledge, and dream interpretation. It also includes cases and professional responses from psychologists on ethical dilemmas (e.g., incest, molestation) and high-risk psychological interventions (e.g., suicidal tendencies) to enhance the professionalism and comprehensiveness of the psychological consultation model.The dataset also incorporates continuous answering and one-to-many Q&A formats to specifically optimize key metrics such as BLEU-4 and ROUGE-2 during large model fine-tuning.In the future, the dataset will continue to expand, providing more support for the field of mental health._

## 3.注意事项（Precautions）
由于数据量较少，使用此数据集容易出现过拟合问题，建议设置训练轮次为5-10次，批量大小次数4或8并增加正则化项。<br>
<br>
_Due to the small dataset size, __overfitting__ issues are likely to occur. It is recommended to set the __training epochs__ to 5–10, use a __batch size__ of 4 or 8, and increase the __regularization terms__._

## 4.开发人员（Developers）
狸猫C型AI&nbsp;&nbsp;(LH-Cat AI)

## 5.商务合作 (Business cooperation)
微信：maxiuwo1314 &nbsp;&nbsp;&nbsp;&nbsp; 邮箱：zhaogangbjm@gmail.com<br> 
<br>
_WeChat: maxiuwo1314 &nbsp;&nbsp;&nbsp;&nbsp; Email：zhaogangbjm@gmail.com_


# OffensEval-20-
Text Classification, Semantic Analysis - Deep NLP


2 Task Description
In this study, our task is Identifying and Categorizing Offensive Language in Social Media (OffensEval) which organized
at (SemEval 2020) (Task 12). Promoters supplied us with the Offensive Language Identification Dataset (OLID) which
consists of over 14,000 annotated tweets regarding the sign of offensive language, type of offense and target of offense.
The task consists of 3 sub-tasks [6].
2.1 Sub-Task A: Offensive Language Identification
The first sub-task is a binary classification problem that gets the particular tweet as input and decides whether that
tweet contains offensive or non-offensive content. Offensive posts can be described as messages containing any type of
outrage, threats, insults and any kind of disturbing message with or without direct target [5]. The Following two labels
will be assigned to particular posts as a result of binary classification.
• Not Offensive (Not):
Post that does not contain any form of offense.
• Offensive (Off):
Post that contains offensive signs.
∗
2.2 Sub-task B: Automatic categorization of offense types
As a result of Sub-task A, part of the initial inputs will be classified as an "Offensive" post. Sub-task B is again a binary
classification problem that takes the "Offensive" labeled instances as input and decides whether an offensive post has
any target or not. In other words, it predicts the type of offense [5]. The Followings are the labels that will be assigned
after Sub-task 2.
• Targeted Insult (TIN):
Post that contains outrage, threats, insults and any kind of disturbing message to with direct target. Targets
might be individual, group or others [5] [5].
• Untargeted (UNT):
Post that contains offensive signs without direct target [5].
2.3 Sub-task C: Offense Target Identification
After Sub-task B, part of offensive posts classified as a "Targeted Insult". In other words, the classification model of
Sub-task B decides whether offensive messages have any targets. Sub-task 3 multi-class classification problem that
focuses on the specific target of offenses such as, individual, group or others. Thus, only the posts labeled as a "TIN" be
able to be input for sub-task C [5]. The Followings are the final labels that will be assigned after Sub-task 3.
• Individual (IND):
Posts that show signs of cyberbullying which targets a direct individual who can be a celebrity, reputable
individual or random individual [5] [7].
• Group (GRP):
Post that targets a specific group or community that shares common characteristics, such as ethnic origin,
religious opinion or benefit. These types of offensive messages described as hate speech [5] [8].
• Other (OTH):
The posts that contain offensive signs but do not directly target individuals or groups, e.g., situation, a
phenomenon.

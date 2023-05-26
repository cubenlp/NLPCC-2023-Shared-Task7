# Shared-Task-7 Chinese Essay Discourse Coherence Evaluation


# 最新消息

| 时间 | 消息 |
| --- | --- |
| 5月23日 |  track4的训练集和验证集有更新，训练集增加250条数据，验证集增加10条数据|
| 5月20日 |  测试集已发布，结果提交链接已发送至各组队长邮箱，提交结果榜单详见各赛道Github主页|
| 5月8日 | 已通过邮件的方式将官方微信群二维码发送给5月5日之前报名的队伍 |

# 排行榜

&emsp;&emsp;结果统计截止至2023年5月26日，榜单更新时间：2023年5月26日。

## Track 1 (每队历史最好成绩排行榜)

| Team Name | Email | Precision | Recall | Macro-F1 | Accuracy |
| --- | --- | --- | --- | --- | --- |
| EssayFlow | 210***@stu.pku.edu.cn | 38.50 | 43.54 | 32.54 | 43.99 |
| Evay Info AI Team | 921***@qq.com | 36.07 | 38.24 | 33.38 | 37.19 |
| ouchnai | zhe***@ouchn.edu.cn | 36.38 | 41.32 | 33.22 | 34.92 |
| CLsuper | yxi***@163.com | 34.20 | 34.14 | 32.79 | 32.88 |

### Track 1 (2023年5月26日提交结果，未排名)

| Team Name | Email | Precision | Recall | Macro-F1 | Accuracy |
| --- | --- | --- | --- | --- | --- |
| Evay Info AI Team | 921***@qq.com | 35.39 | 34.01 | 29.36 | 41.27 |


## Track 3 (每队历史最好成绩排行榜)

| Team Name | Email | Precision | Recall | Macro-F1 | Accuracy |
| --- | --- | --- | --- | --- | --- |
| ouchnai | zhe***@ouchn.edu.cn | 54.66 | 52.45 | 52.16 | 71.03 |
| wuwuwu | don***@sjtu.edu.cn | 28.36 | 25.43 | 26.80 | 51.10 |
| BLCU_teamworkers | sol***@163.com| 25.89 | 25.15 | 24.19 | 46.56 |

### Track 3 (2023年5月26日提交结果，未排名)

| Team Name | Email | Precision | Recall | Macro-F1 | Accuracy |
| --- | --- | --- | --- | --- | --- |
| ouchnai | zhe***@ouchn.edu.cn | 54.66 | 52.45 | 52.16 | 71.03 |



## Track 4 （每队历史最好成绩排行榜）

| Team Name | Email | Precision | Recall | Macro-F1 | Accuracy |
| --- | --- | --- | --- | --- | --- |
| ouchnai | zhe***@ouchn.edu.cn | 36.63 | 36.36 | 34.38 | 53.95 |

### Track 4 (2023年5月26日提交结果，未排名)

| Team Name | Email | Precision | Recall | Macro-F1 | Accuracy |
| --- | --- | --- | --- | --- | --- |
| ouchnai | zhe***@ouchn.edu.cn | 35.86 | 39.22 | 32.68 | 55.90 |

# Introduction
 
In the scoring of the Chinese National College Entrance Examination (NCEE) and the Senior High School Entrance Examination, essay assessment is the most time-consuming and controversial task. While existing research has focused on language factors such as characters, words, and sentences, it has not explored the relationship between discourse coherence and text quality. The logical structure and coherence within an essay are essential for evaluation, but the lack of large-scale, high-quality discourse coherence evaluation data resources has hindered the development of AI essay grading. To address this issue, the CubeNLP laboratory of East China Normal University and Microsoft have constructed a Chinese essay coherence evaluation dataset called LEssay, which provides high-quality data resources and is significant for the development of automatic essay evaluation.

This shared task includes four tracks:  
Track 1. **Coherence Evaluation (CE)**. Given a middle school student essay, annotators will assess its coherence on a three-level scale of excellent, moderate, and poor. A score of 2 indicates excellent coherence, 1 indicates moderate coherence, and 0 indicates incoherence.  
Track 2. **Text Topic Extraction (TTE)**. Given a middle school student essay, annotators need to identify the topic sentence for each paragraph and one main topic sentence for the whole essay.  
Track 3. **Paragraph Logical Relation Recognition (PLRR)**. Given two paragraphs sorted in order from a composition, the annotator needs to determine the logical relationship between the two paragraphs based on the given definitions and examples of logical relationships.  
Track 4. **Sentence Logical Relation Recognition (SLRR).** Given two sentences from an essay that are ordered sequentially, the annotator needs to determine what type of logical relation exists between them based on given definitions and examples.

The detailed content of the guideline can be found in the file _Chinese Essay Discourse Coherence Evaluation.pdf_

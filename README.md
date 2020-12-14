## DT-QDC
Project for Paper "DT-QDC: A Dataset for Question Comprehension in Online Test", including our dataset and codes.
[![Paper](http://img.shields.io/badge/paper-arxiv.2010.04513-blue.svg)](https://www.aclweb.org/anthology/2020.coling-main.569/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Authors: Sijin Wu, Yujiu Yang, Nicholas Yung, Zhengchen Shen and Zeyang Lei,

Contact: yang.yujiu@sz.tsinghua.edu.cn

Abstract:
As education switches from the traditional classroom environment to online education and assessment, teachers could not follow students’ learning behavior closely which leads to inaccurate assessment of students’ knowledge. A well-defined method to precisely measure difficulty of questions is critical as it can guide teachers in assessing students’ performance and help provide customized attention to students. In this paper, we explore the concept of question difficulty and share our new Chinese Driving Test Question Difficulty Comprehension (DT-QDC) dataset. Different from the existing question datasets, we mainly design for question evaluation and comprehension in online testing, so each question has enriched attributes and difficulty label. Additional attributes such as keywords, chapter, and question type would allow models to understand questions more precisely. We proposed the Ordinal Regression Multi-Source BERT (ORMSBERT) model to assess the difficulty of the question, which outperforms different baselines by 6.77% on F1-score and 15.92% on MAE, 28.26% on MSE on the DT-QDC dataset, laying the foundation for the question difficulty comprehension task.

## Dataset Agreement
The DT-QDC dataset is available for non-commercial research purposes only.
You agree not to reproduce, duplicate, copy, sell, trade, resell or exploit for any commercial purposes, any portion of derived data.
You agree not to further copy, publish or distribute any portion of the DT-QDC dataset. Except, for internal use at a single site within the same organization it is allowed to make copies of the dataset.
## License and Citation
The use of this software is RESTRICTED to non-commercial research and educational purposes.
If you are interested in our work, please consider to cite:
```
@inproceedings{wu-etal-2020-dt,
    title = "{DT}-{QDC}: A Dataset for Question Comprehension in Online Test",
    author = "Wu, Sijin  and Yang, Yujiu  and Yung, Nicholas  and Shen, Zhengchen  and Lei, Zeyang",
    booktitle = "Proceedings of the 28th International Conference on Computational Linguistics",
    year = "2020",
}
```


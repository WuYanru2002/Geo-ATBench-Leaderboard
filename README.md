# Geo-ATBench Leaderboard

This repository maintains the leaderboard and evaluation results for **Geo-ATBench**.

**Note:**  
This repository is only used to track model performance and rankings.  
For dataset details, task definitions, and baseline implementations, please visit the main repository:

**Geo-ATBench Main Repository**:  
https://github.com/WuYanru2002/Geo-ATBench

---

## Leaderboard

| Rank | Model | Audio Backbone | Text Encoder | Fusion Strategy | mAP | Paper |
|-----|------|---------------|--------------|----------------|------|------|
| 1 | AST + BERT | AST | BERT | Early Fusion | 0.846±0.010 | [Geo-ATBench](https://arxiv.org/abs/2603.10623) |
| 2 | AST + BERT | AST | BERT | Late Fusion | 0.843±0.010 | [Geo-ATBench](https://arxiv.org/abs/2603.10623) |
| 3 | CLAP + BERT | CLAP | BERT | Inter Fusion | 0.842±0.006 | [Geo-ATBench](https://arxiv.org/abs/2603.10623) |
| 4 | PANNs + BERT | PANNs | BERT | Late Fusion | 0.833±0.007 | [Geo-ATBench](https://arxiv.org/abs/2603.10623) |
| 5 | CLAP + BERT | CLAP | BERT | Early Fusion | 0.831±0.007 | [Geo-ATBench](https://arxiv.org/abs/2603.10623) |
| 6 | AST + BERT | AST | BERT | Inter Fusion | 0.829±0.003 | [Geo-ATBench](https://arxiv.org/abs/2603.10623) |
| 7 | CLAP + BERT | CLAP | BERT | Early Fusion | 0.826±0.010 | [Geo-ATBench](https://arxiv.org/abs/2603.10623) |
| 8 | PANNs + BERT | PANNs | BERT | Inter Fusion | 0.824±0.010 | [Geo-ATBench](https://arxiv.org/abs/2603.10623) |
| 9 | CLAP | CLAP | - | - | 0.824±0.008 | [Geo-ATBench](https://arxiv.org/abs/2603.10623) |
|10 | AST | AST | - | - | 0.820±0.015 | [Geo-ATBench](https://arxiv.org/abs/2603.10623) |
|11 | PANNs + BERT | PANNs | BERT | Early Fusion | 0.812±0.010 | [Geo-ATBench](https://arxiv.org/abs/2603.10623) |
|12 | PANNs | PANNs | - | - | 0.770±0.006 | [Geo-ATBench](https://arxiv.org/abs/2603.10623) |

**Metric:** micro-mean Average Precision (mAP)

---
## Submission

We welcome researchers to submit their results evaluated on **Geo-ATBench**.

If you would like your model to appear on the leaderboard, please ensure that the evaluation follows the official evaluation protocol of Geo-ATBench. Detailed descriptions of the dataset, tasks, evaluation procedure, and implementation details can be found in:

- **Paper:** https://arxiv.org/abs/2603.10623  
- **Official Repository:** https://github.com/WuYanru2002/Geo-ATBench

To submit results, please open a Pull Request updating the leaderboard table and include the following information:

- Model name  
- Audio backbone  
- Text encoder (if applicable)  
- Fusion strategy or model architecture  
- Evaluation results (mAP)  
- Paper or project link (if available)

Submissions that follow the official evaluation setup will be reviewed and added to the leaderboard.

---

## Citation

If you use **Geo-ATBench**, please cite:

```bibtex
@misc{hou2026geoatbenchbenchmarkgeospatialaudio,
      title={Geo-ATBench: A Benchmark for Geospatial Audio Tagging with Geospatial Semantic Context}, 
      author={Yuanbo Hou and Yanru Wu and Qiaoqiao Ren and Shengchen Li and Stephen Roberts and Dick Botteldooren},
      year={2026},
      eprint={2603.10623},
      archivePrefix={arXiv},
      primaryClass={eess.AS},
      url={https://arxiv.org/abs/2603.10623}, 
}

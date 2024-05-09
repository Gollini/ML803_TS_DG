# ML803_TS_DG
ML803 Course Project - Domain Generalization Techniques for Real-World Time-Series Data

Based on GLOBEM repository https://github.com/UW-EXP/GLOBEM

## Example run algorithm 

```
python evaluation/model_train_eval.py \
  --config_name=dl_erm_1dCNN \
  --pred_target=dep_weekly \
  --eval_task=allbutone \
  --train_optimizer=sgd \
  --learning_rate=0.1
```
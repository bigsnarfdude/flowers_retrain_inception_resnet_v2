# flowers_retrain_inception_resnet_v2
demo flowers dataset retrain inception resnet v2 model

Step 0

```
cd slim
```

Step 1
Get flowers dataset

```
bash scripts/01_get_data.sh
```

Step 2
Run last layers retrain on Inception ResNet v2

```
bash scripts/02_run_finetune_inception_resnet_v2.sh	
```

Step 3
Retrain all layers on Inception ResNet v2

```
bash scripts/03_run_train_all_layers_inception_resnet_v2.sh
```


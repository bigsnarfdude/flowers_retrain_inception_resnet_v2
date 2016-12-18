# flowers_retrain_inception_resnet_v2
demo flowers dataset retrain inception resnet v2 model - tested ubuntu14.04 tensorflow 0.12 cuda8
http://download.tensorflow.org/models/inception_resnet_v2_2016_08_30.tar.gz

Step 0

```
git clone https://github.com/bigsnarfdude/flowers_retrain_inception_resnet_v2.git
cd flowers_retrain_inception_resnet_v2
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


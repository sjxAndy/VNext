### Training

To train SeqFormer on YouTube-VIS 2019 or OVIS with 8 GPUs , run:

```
python3 projects/IDOL/train_net.py --config-file projects/IDOL/configs/ovis_swin.yaml --num-gpus 8 
```



### Inference & Evaluation



Evaluating on YouTube-VIS 2019 or OVIS:

```
python3 projects/IDOL/train_net.py --config-file projects/IDOL/configs/XXX.yaml --num-gpus 8 --eval-only
```
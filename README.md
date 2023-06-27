# NER_Test

## 目录结构
bert_bilstm_crf_ner_pytorch 为bert_bilstm_crf模型训练代码及数据集
```text
|-- log 训练日志
|-- torch_ner 
| |-- data 数据集
| |-- output 训练结果
| |-- source 模型代码
| | |-- train.py 训练入口
| |-- requirements.txt
```

Flat-Lattice-Transformer 为Flat模型训练代码及数据集
```text
|-- data 训练时需要的文件
|-- ResumeNER 数据集
|-- V0 Flat-withoutBert模型代码
| |-- flat_main.py 训练入口
|-- V1 Flat-withBert模型代码
| |-- flat_main.py 训练入口
```
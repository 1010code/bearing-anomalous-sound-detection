


```
# yamnet to onnx
!python -m tf2onnx.convert --opset 14 --saved-model savedmodel  --output model.onnx
```
## Dataset Resource
- [challenge2022 Task2](https://dcase.community/challenge2022/task-unsupervised-anomalous-sound-detection-for-machine-condition-monitoring#download)
    - [DCASE 2022 Challenge Task 2 Development Dataset(dev)](https://zenodo.org/records/6355122)
- [challenge2023 Task2](https://dcase.community/challenge2023/task-first-shot-unsupervised-anomalous-sound-detection-for-machine-condition-monitoring)
    - [DCASE 2023 Challenge Task 2 Development Dataset(dev)](https://zenodo.org/records/7882613)

## Yamnet material
- [Transfer learning with YAMNet for environmental sound classification](https://www.tensorflow.org/tutorials/audio/transfer_learning_audio)
- [yamnet visual colab](https://colab.research.google.com/github/tensorflow/docs-l10n/blob/master/site/zh-cn/hub/tutorials/yamnet.ipynb#scrollTo=Vmo7griQprDk)

## Reference
- [機台異常聲音偵測](https://wenwender.wordpress.com/2020/10/24/%e6%a9%9f%e5%8f%b0%e7%95%b0%e5%b8%b8%e8%81%b2%e9%9f%b3%e5%81%b5%e6%b8%ac%e4%b8%8a/)
- [challenge2020/task-unsupervised-detection-of-anomalous-sounds](https://dcase.community/challenge2020/task-unsupervised-detection-of-anomalous-sounds)
- [yamnet to onnx](https://github.com/onnx/tensorflow-onnx/issues/1743)
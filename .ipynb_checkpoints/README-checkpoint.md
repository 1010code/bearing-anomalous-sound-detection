


```
# yamnet to onnx
!python -m tf2onnx.convert --opset 14 --saved-model savedmodel  --output model.onnx
```

## Reference
- [機台異常聲音偵測](https://wenwender.wordpress.com/2020/10/24/%e6%a9%9f%e5%8f%b0%e7%95%b0%e5%b8%b8%e8%81%b2%e9%9f%b3%e5%81%b5%e6%b8%ac%e4%b8%8a/)
- [challenge2020/task-unsupervised-detection-of-anomalous-sounds](https://dcase.community/challenge2020/task-unsupervised-detection-of-anomalous-sounds)
- [yamnet to onnx](https://github.com/onnx/tensorflow-onnx/issues/1743)
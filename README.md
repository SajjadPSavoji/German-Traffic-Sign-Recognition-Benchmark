# GTSRB

![project banner](https://github.com/SajjadPSavoji/German-Traffic-Sign-Recognition-Benchmark/blob/master/German.jpeg)

The German Traffic Sign Benchmark is a multi-class, single-image classification challenge held at the International Joint Conference on Neural Networks (IJCNN) 2011. In this case study we examine the effect of common components in CNNs(including normalization layers) on the traceability and generalization capabilities


## Resutls
### base model
<table>
  <tr>
    <td> Model </td>
    <td> Accuray </td>
    <td> Loss</td>
  </tr>
  <tr>
    <td> Base Model </td>
    <td> <img src="https://github.com/SajjadPSavoji/German-Traffic-Sign-Recognition-Benchmark/blob/master/Assets/acc-base.png"> </td>
    <td> <img src="https://github.com/SajjadPSavoji/German-Traffic-Sign-Recognition-Benchmark/blob/master/Assets/loss-base.png"> </td>
  </tr>
</table>

### activation functions

![activation functions accuracy](https://github.com/SajjadPSavoji/German-Traffic-Sign-Recognition-Benchmark/blob/master/Assets/activation-fn.png)

### optimizaton method

![optimization method](https://github.com/SajjadPSavoji/German-Traffic-Sign-Recognition-Benchmark/blob/master/Assets/opt.png)

### drop out layers

<table>
  <tr>
    <td> Model </td>
    <td> with Drop out </td>
    <td> no Drop out</td>
  </tr>
  <tr>
    <td> ----- </td>
    <td> <img src="https://github.com/SajjadPSavoji/German-Traffic-Sign-Recognition-Benchmark/blob/master/Assets/no-dropout-model.png"> </td>
    <td> <img src="https://github.com/SajjadPSavoji/German-Traffic-Sign-Recognition-Benchmark/blob/master/Assets/dropout-model.png"> </td>
  </tr>
</table>

### data augmentation

![dataaugmentation](https://github.com/SajjadPSavoji/German-Traffic-Sign-Recognition-Benchmark/blob/master/Assets/augmentation.png)

### batch normalization

<table>
  <tr>
    <td> Model </td>
    <td> accuracy </td>
    <td> loss </td>
  </tr>
  <tr>
    <td> Batch Norm </td>
    <td> <img src="https://github.com/SajjadPSavoji/German-Traffic-Sign-Recognition-Benchmark/blob/master/Assets/norm-accuracy.png"> </td>
    <td> <img src="https://github.com/SajjadPSavoji/German-Traffic-Sign-Recognition-Benchmark/blob/master/Assets/norm-loss.png"> </td>
  </tr>
</table>


## Resources
- [GtSR Benchmark Paper](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)
- [Traffic Sign Recognition Database](http://www.nlpr.ia.ac.cn/pal/trafficdata/recognition.html)

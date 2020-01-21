# GAN Assignments
## 1. [2020.1.16] GAN 예제
MNIST 데이터셋과 DCGAN으로 숫자 이미지 생성하기

TensorFlow 튜토리얼의 [심층 합성곱 생성적 적대 신경망](https://www.tensorflow.org/tutorials/generative/dcgan)을 참고하였습니다.

### 생성자(좌)와 감별자(우) 모델

<div style="width:50%; float:left">
<img src="./images/DCGAN_MNIST/generator.png" width="40%"></img>
</div>
<div style="width:50%; float:right">
<img src="./images/DCGAN_MNIST/discriminator.png" width="40%"></img>
</div>

### 학습 결과물
![dcgan_mnist](images/DCGAN_MNIST/dcgan_mnist.gif)

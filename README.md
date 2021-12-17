<h1>
Do You Even Need Attention? A Stack of Feed-Forward Layers Does Surprisingly Well on ImageNet 

[arXiv](https://arxiv.org/abs/2105.02723)
</h1>

![Model](https://github.com/dslisleedh/LinearVisionTransformer-tensorflow2/blob/master/Model.PNG)

<h3>
요약:  

ViT의 성공이 과연 Self Attention의 존재 때문일지에 대해 의문을 던지며, 이를 확인하기 위해 Self Attention layer를
Patch간의 FFN으로 대체함. 해당 모델은 ViT에 비해 약간 낮은 성능을 보이지만, Base model 기준, 25퍼센트나 적은 parameter를 가짐.

FFN들을 일종의 convolution 연산으로 해석할 수 있음.
</h3>


<h5>
MLP-Mixer는 새로운 구조를 제안했다면, 본 논문은 단순히 ViT에서 SA만 FFN으로 대체했다는 느낌이강함.


MLP-Mixer에서는 GAP로 토큰간의 평균을 가져왔다면, 본 모델에서는 CLS token을 사용한 점에서 이런 인상을 받았음.

LearnedPositionalEncoding에 대해 공부해야할듯.
</h5>

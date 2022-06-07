# POZA Labs Assignment

- Achievements 
  1. Groove midi dataset를 tfrecords 형식으로 변환
  2. 변환된 midi dataset을 이용하여 2bar-drum 모델 학습
  3. 생성된 모델을 load해서 2마디의 드럼비트를 생성, 생성된 비트 2개를 이어서 4마디 드럼비트 생성, 다운

\\
- Self-review
  1. GPU를 가지고 있지 않아서 Colab 환경에서 작업을 했고, 거의 모든 directory를 저의 개인 google drive로 맞췄기 때문에 보는 사람이 어려울 수 있습니다. 
  2. Tensorflow, midi 파일, magenta library 등 처음 접해보는 요소들이 많았고, 대부분 magenta github repo에 있는 소스코드들을 가져와서 작업했습니다.
  3. Colab 환경에서 작업을 하다보니, 학습 도중 GPU 할당량이 만료되서 학습을 온전히 다하지 못했습니다. 메일에 model checkpoint를 첨부해서 보내드립니다.
     학습 간 loss가 0.2664 정도로 제일 낮았던 모델이라 best model로 선정했습니다.
 
\\
 - 마치며..
\\
덕분에 새로운 영역에 발을 들여본 것 같아서 결과가 좋지 않아도 수확이 있었던 것 같습니다. 좋은 기회 주셔서 다시 한번 감사드립니다!

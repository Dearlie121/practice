# Github practice

## 프로젝트 개요

목표 : MNIST 숫자 데이터 분류  
기간 및 장소: 2023년 1월부터 2월부터 알파코 딥러닝 부트캠프에서 진행  
데이터 : 0~9의 숫자 이미지로 이루어진 MNIST data (train:60,000장, test:30,000장)  

## 프로잭트 수행 내역

ViT 아키텍쳐를 사용하여 딥러닝 엔진을 개발하였으며, Flask로 웹을 구현했다.  

![architecture](https://github.com/Dearlie121/practice/assets/161268753/667e4a89-eee0-4bf8-9483-ba61da27ad02)

MNIST data test result  

![output](https://github.com/Dearlie121/practice/assets/161268753/57678943-6524-41e2-8651-c639acd4ff78)


## 결론

느낌점은, ViT로는 0~9 이미지의 학습 성능이 잘 나왔지만 transform을 어떻게 주냐에 따라서 성능을 감소시키는 기법들이 뭐인지 리포트하고 싶었다.  


참조 : Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E. Hinton. "Imagenet classification with deep convolutional neural networks." Advances in neural information processing systems 25 (2012)

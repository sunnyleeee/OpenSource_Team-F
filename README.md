<h1 align="center">COVID-19 Face Mask Detection  </h1>

<h4 align="center">코로나의 장기화에 따라 OpenCV, TensorFlow, Keras를 활용하여 마스크 감지 시스템 제작
</h4>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.6+-white.svg)
![tensorflow](https://img.shields.io/badge/tensorflow-1.15.2-red.svg)
![keras](https://img.shields.io/badge/keras-v2.3.1-orange.svg)
![numpy](https://img.shields.io/badge/numpy-1.18.2-yellow.svg)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src=https://raw.githubusercontent.com/sunnyleeee/OpenSource_Team-F/main/dataset/with_mask/mask_img%20(22).png width=500 height = 300> 
 
 
<h3 align="center">Team Member</h3>

박진홍 [![Generic badge](https://img.shields.io/badge/github-go-red?logo=github)](https://github.com/HallymhongE)
김기훈 [![Generic badge](https://img.shields.io/badge/github-go-orange?logo=github)](https://github.com/daedu0813)
윤찬우 [![Generic badge](https://img.shields.io/badge/github-go-green?logo=github)](https://github.com/GitCWoo)
용권순 [![Generic badge](https://img.shields.io/badge/github-go-blue?logo=github)](https://github.com/reversesky)
이선재 [![Generic badge](https://img.shields.io/badge/github-go-blueviolet?logo=github)](https://github.com/sunnyleeee)
유예린 [![Generic badge](https://img.shields.io/badge/github-go-ff69b4?logo=github)](https://github.com/yl-zzzz)


------------------------------------------


# 1. 기획 계기
 > &nbsp;현재 전 세계적으로 `코로나`가 고조되고 있으며, 몇 나라를 제외하고 아직 많은 나라들이 `코로나`로 인하여 고통을 호소하고 있다.  
우리는 이미 창궐한 상황에서 가장 중요한 것은 `마스크`라고 생각했다. 실제로 확진자와 같은 장소에 있었더라도 마스크를 정확히 착용한 사람은 비 접촉자로 간주하며, 질병관리본부 자료를 보았을 때, **마스크를 제대로 착용하는 것 하나로 감염률이 100%에서 1.5%로 현저히 감염률이 감소한 것을 확인할 수 있었다.**  
&nbsp;이런 결과로 토대로 사람이 많이 모이게 되는 지하철 혹은 음식점 및 카페를 통과할 때 마스크의 착용 유무를 한 번 더 집어주는 쪽으로의 발전가능성 또한 미루어 볼 수있을 것이라 생각했으며 코로나의 확산 방지에 도움이 될 것이라 생각되어 프로젝트로 구현  

"""
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;<img src = mask_image.png width = 250 height= 400>
"""

  
 
# 2. 개발환경 선택  

<p align= "center">
<img src="/environment.png" width="500" height="120"></p>  

>  &nbsp;각기 다른 개발환경에서 `GIT`을 통한 협업 프로젝트로, 오픈소스를 활용하여 `OpenCV, TensorFlow, Keras`로 Mask-detection을 목표로 매끄러운 결과를 위해 여러 시도를 하였다.  
처음에는 jupyter notebook, pycharm, spider 다른 환경에서 개인개발 및 협업을 위해 증진하였고 , 알고리즘 선택과정에서 Google에서 만들어진 트레이닝 알고리즘(MobileNet_v2)을 사용하게 되어, Google에서 지원하는 Colab환경과 Linux 환경에서 개발

</br></br>

# 3. 프로젝트 내용  
### 1.단계(오픈소스 활용)  
 * 오픈소스를 이용한 얼굴인식/ keras를 활용한 마스크검사(딥러닝)  
 
 </br>
 
### 2.단계(데이터 라벨링 테스트)  
 * 팀원들 마스크사진 및 기타 마스크 사진 업로드  

 </br>

### 3.단계(알고리즘 커스텀마이징)
* 오픈소스 활용 및 알고리즘 수정  

</br>

### 4.단계(결과 확인)
* 결과 확인   

</br>

### 5.단계(협업)
* Git을 통한 버그/개선사항 수정
* 데모 모델 생성

</br></br> 
  
# 4. Model Selection  

### 1) Faster R - CNN

<p align="center"><img src=Faster_R_CNN.jpg width=550 height = 200></p>

<p align="center">
정확하고 겹쳐지거나 작은 사물에 대한 인식률이 높지만, 느리고 실시간연동을 생각하고 만든 네트워크가 아니므로 배제  
</p>

### 2) MobileNet_V2(선택)

<p align="center"><img src=MobileNet_V2.png width=550 height = 200></p>

<p align="center">
Google에서 만든 Network 이며, Colab과 리눅스 기반 OS에 이용하기 적합하고, 연산량 및 모델 사이즈 축소가 가능하여 선택</p>
   
### 3) Yolo  

<p align="center"><img src=Yolo.png width=550 height = 400></p>

<p align="center"> 
빠르고 정확하고 사용이 쉽지만, 겹친사물의 구분이 어려운 단점과 지속적으로 사용시도는 하였으나 라이브로리 충돌로 인하여 배제</p>

</br></br>  
  
# 5. 프로젝트 과정

<p align="center">
<img src=mask.png width=680 height = 280></p>

**1. OpenCV 이용 - 얼굴 인식** ➡ **2. MobileNet_V2 이용 - 마스크 인식** ➡ **3. 착용 및 미착용 구분**  

</br></br>
  
#  테스트 결과

<p align="center"><img src="ezgif-3-03558c22f237.gif" width="600" height ="600"></p>

------------------------------
  
  
  
## (cnt). Dataset  
프로젝트 멤버들의 사진과 Kaggle을 통한 사진   
  
**>with_mask(마스크 착용)_300장) : Pexels Image + Project Member picture**  

**>without_mask(마스크 미착용)_1000장) : Pexels Image + Project Member picture**  

  
[•데이터 수집한 곳•][Pexels]

## (cnt). train & Accuracy

>GPU : 1050ti 사용(15분소요)  
**>정확도 99%**  
  
  
## (cnt). 참고 자료

OpenCV 관심영역 :  https://lepton.flir.com/application-notes/people-finding-with-a-lepton  

마스크 인식과 기존 opensource 활용 : https://github.com/chandrikadeb7/Face-Mask-Detection  

마스크 인식(yolo) 참고 : https://github.com/VictorLin000/YOLOv3_mask_detect  

마스크 인식 원리 참고 : https://towardsdatascience.com/covid-19-face-mask-detection-using-tensorflow-and-opencv-702dd833515b  

Mobilenetv2 원리 참고 : https://n1094.tistory.com/29  


[Pexels]: https://www.pexels.com/ko-kr/

---
layout: post
title:  "[퀵랩]Introduction to docker"
date:   2020-02-17 01:34:34
categories: qwiklabs
author: znot34
---
<src ="https://cdn.qwiklabs.com/GMOHykaqmlTHiqEeQXTySaMXYPHeIvaqa2qHEzw6Occ%3D"/>
도커는 어플리케이션의 개발, 배포, 실행을 담당하는 오픈 플랫폼이다.
도커를 사용하여 인프라스트럭처에서 애플리케이션을 분리할 수도,
인프라스트럭처를 관리형 애플리케이션으로 사용할 수도 있다.

도커는 코드 배포와 테스트를 더 빠르게 도와준다.
또한 코드를 작성하고 실행하는 과정을 단축시켜준다.

도커는 커널 컨테이너화 기능을 통해 앱의 관리와 배포를 더욱 빠르게 도와준다.

도커 컨테이너들은 쿠버네티스 엔진에서 구동시켜 쉽게 사용될 수 있다.
도커의 필요한 사항들을 배우고, 쿠버네티스와 컨테이너화 된 애플리케이션들을 배포하는 것을 배워보자.

이번 랩에서 배울 내용은 아래와 같다.
1) 도커 컨테이너를 만들고, 구동시키고, 디버깅하는 과정을 배운다.
2) 도커 이미지를 도커 허브와 구글 컨테이너 레지스트리에서 가져오는 법을 배워본다.
3) 도커 이미지를 구글 컨테이너 레지스트리에 푸시하는 법을 배운다.

<h2><필요한 선수지식></h2>

이번 랩은 소개 레벨의 랩입니다. 도커와 컨테이너를 사전에 경험해 본 적이 없다고 해도 괜찮습니다.
클라우드 쉘과 커맨드 라인에 친숙하시면 좋습니다. 

좀 더 난이도가 있는 랩을 진행해보고 싶으시다면 아래 랩들을 참고 하세요:
App Dev: Deploying the Application into Kubernetes Engine - Python
Hello Node Kubernetes
Managing Deployments Using Kubernetes Engine


<h2>도커</h2>
docker run hello-world



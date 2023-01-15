---
layout: post
title: mini SONATA
subtitle: Design and development of an electic autonomous car for visual  impairment children
cover-img: /assets/img/miniSONATA/mini_sonata_01.png
tags: [miniSONATA, autonomous driving, visual impairment, james Yoo]
comments: true
---

## Overview

현대자동차 독자개발 자율주행 기술을 적용한 앞이 보이지 않아도 청각과 촉각만으로 운전할 수 있는 **미니쏘나타** 개발 프로젝트. 기획부터 설계, 개발, 테스트, 놀이터 구축, 광고촬영까지 약 1년 6개월가량 진행된 장기 프로젝트.  
  <br/>
  
## Technology
자율주행 차량에서 활용되는 알고리즘 뿐만 아니라 시각 장애를 보완하기 위한 첨단 기술이 함께 적용되었다. 청각과 촉각 피드백을 통해 주변 환경에 대한 정보를 제공할 수 있는 운전자 인터페이스 연구 및 설계가 함께 진행되었다.
<br/>

### LiDAR 기반 주변 환경 인식
LiDAR(Light Detection and Ranging) 센서는 현존하는 대부분의 자율주행 시스템에 적용되는 센서이다. 정확한 거리 측정과 공간 분해능으로 *자율주행 시스템의 눈* 이라고 일컬어지며 미니쏘나타에도 LiDAR 센서를 채용하여 차량 주변환경을 센싱한다.  
<br/>
이 프로젝트에서 내가 기여했던 부분은 LiDAR 센서 전처리(노이즈 제거 등), 공간 분석(장애물 지도 생성) 및 주행 제어를 위한 경로 생성(Bezier 커브)으로 통상 인지/판단/제어로 이루어지는 자율주행 핵심 파이프라인의 대부분을 담당하였다.  

![LiDAR 센서](/assets/img/miniSONATA/mini_sonata_02.png)  

### 사운드 피드백
사운드 피드백 시스템은 미니쏘나타에서 자율주행 기술 만큼 중요한 핵심 파트로 앞이 보이지 않는 운전자가 장애물을 회피할 수 있게 핸들 조향을 가이드하는 역할을 담당한다.   
<br/>
![사운드 피드백](/assets/img/miniSONATA/mini_sonata_03.png)  

### 진동 가이드
사운드 피드백과 함께 운전석 시트에서도 진동을 통한 방향 가이드를 제공한다. 운전자는 청각 뿐만 아니라 촉각 형태로도 조향 정보를 전달 받을 수 있기 때문에 보다 입체적인 공간 인식이 가능하다.  
<br/>
![햅틱 피드백](/assets/img/miniSONATA/mini_sonata_04.png)  
  
<br/>

## 광고스토리

<iframe width="800" height="480" src="https://www.youtube.com/embed/tcl0pJUcJUk" title="[광고] [쏘나타(SONATA)] 차카차카 놀이터 - 키재기 편" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
  <br/>

<iframe width="800" height="480" src="https://www.youtube.com/embed/9Y3UMIpIk0I" title="[광고] [쏘나타(SONATA)] 차카차카 놀이터 - 다큐멘터리 편" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
  <br/>

## 차카차카 놀이터
  
![차카차카 놀이터](/assets/img/miniSONATA/mini_sonata_05.png)  

현대자동차와 서울시가 함께 어린이들을 위해 설립한 신개념 자동차 테마 놀이터. **차카차카 놀이터**는 현대자동차가 쏘나타 출시 30주년을 기념하며 서울대공원 내 계곡광장 인근 부지에 시설 연면적 2,045m² 규모로 조성해 서울대공원에 기부한 것으로 ▲시각장애아도 이용 가능한 '미니 쏘나타 트랙' ▲'대형 쏘나타 모형 놀이 시설' ▲멸종 위기 동물 이야기를 전해주는 '동물 이야기 산책로' 등 어린이들이 즐길 수 있는 다양한 공간으로 구성돼 있다.
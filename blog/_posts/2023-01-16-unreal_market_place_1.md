---
layout: post
title: Becoming an Unreal Market Place Seller
subtitle: 언리얼 마켓플레이스 도전기 
gh-repo: james-yoo/james-yoo.github.io
tags: [UE5, Unreal Market Place, Robotics, Differential Drive]
comments: true
---
  
## Overview
  
2023년 새해에는 언리얼 엔진 마켓플레이스의 판매자가 되기로 결심하였다. 그 동안 에픽게임즈와 많은 창작자분들이 제공해준 고퀄리티 애셋, 플러그인 등이 있어 언리얼 엔진을 시작할 수 있었고 단시간에 레벨업이 가능했다. 이제 나도 창작 커뮤니티에 조금이나마 도움이 되고 싶은 심정이 되었다고나 할까.  
  
![Unreal Market Place01](/assets/img/blog_unreal_market_place_1/market_place_1.png)  
  
과연 어떤 컨텐츠를 만들 것인가? 지금도 고민되는 주제이지만 우선은 나의 전문 분야를 최대한 살릴 수 있는 아이템으로 시작해보는 것이 좋겠다는 생각을 했다. 로보틱스 또는 자율주행 기술과 관련된 컨텐츠를 마켓플레이스에서 찾아보았지만 거의 발견을 할 수가 없었기 때문에 우선 이 방향으로 진행하는 것으로 결정.

언리얼 마켓플레이스의 판매자가 되기 위해서 필요한 절차가 있는데 영문으로만 되어 있다 보니 처음에는 겁이 나는게 사실이다. 연초에 셀러 등록을 해야겠다고 마음을 먹고 구글에 셀러 등록 과정을 찾아보았는데 의외로 한국어로 된 후기는 찾아보기 어려웠다. 그 중에서 [친절한 효자손](https://rgy0409.tistory.com/786)님의 블로그가 자세하게 과정을 설명하고 있었지만 이것도 2015년에 작성된 포스트라 지금과는 다소 변경된 점이 있는 것 같았다. 이번 기회를 통해 최신 판매자 등록 과정을 정리해야겠다고 생각했다.  
  
## 언리얼 마켓플레이스 판매자 등록 과정
  
![Unreal Market Place02](/assets/img/blog_unreal_market_place_1/market_place_2.png)  
  
판매자가 되기 위해서 가장 먼저 해야될 일은 (당연하지만) 에픽게임스 계정을 생성해야 한다. 계정을 만들었다면 마켓플레이스 [판매자 사이트](https://publish.unrealengine.com/v3/welcome)로 이동한다(UE5가 출시되고 해가 바뀌었는데 아직도 대문은 UE4라니..에픽게임즈님들아 너무하는거 아닌가요). **판매 시작** 버튼을 누르면 본격적으로 판매자 등록 과정이 시작되며 크게 5가지 단계로 이루어져 있다.
  
  1. Publisher Info : 기본 정보 입력
  2. Store Info : 상점(샐러) 정보 입력
  3. Tax Info : 세금 정보 입력
  4. Payout Info : 결재 방식 등록
  5. Open Shop : 샐러샵 오픈
  
  
### **기본 정보 입력**
  
판매자 등록 과정은 모두 영문으로 되어 있는데 크게 어려운 부분이 없다(이해가 되지 않는 문장이 있다면 복사해서 파파고를 열심히 돌리자). 첫 번째 단계로 판매자의 기본 정보를 입력하고 사용자 동의서를 읽고 체크하면 되는데 여기에 입력하는 정보는 마켓플레이스에 노출되지 않으니 안심하자. 
  
![Unreal Market Place03](/assets/img/blog_unreal_market_place_1/market_place_3.png)  
  
### **상점 정보 입력**
  
기본 정보 다음에는 상점 정보를 입력해야 한다. 여기에 입력하는 정보가 실제 마켓플레이스에서 노출이 되기 때문에 신중하게 설정하자. 개인적인 의견으로는 상점 전용으로 이메일(예: mystore@gmail.com 등등)을 하나 파서 등록하는게 좋은 것 같다. 상점 이름과 이메일만 필수 입력 항목이고 나머지는 선택사항이다.
  
![Unreal Market Place04](/assets/img/blog_unreal_market_place_1/market_place_4.png)  
  
### **세금 정보 입력**
  
이번 단계부터 난이도가 상승하긴 하지만 에픽게임즈에서 편리하게 등록 시스템을 만들어 놓아서 그런지 생각보다 어렵진 않다. 나는 개인판매자 신분이니 첫번째 항목(PERSONAL tax profile)을 선택하고 **TAKE TAX INTERVIEW** 버튼을 클릭하면 세금 정보 입력 화면으로 넘어간다. 
  
![Unreal Market Place05](/assets/img/blog_unreal_market_place_1/market_place_5.png)  

- **Step1) Tax Interview 안내**  
    아래와 같은 인터뷰관련 안내사항이 표시된다. Continue를 클릭한다.  
      
    ![Unreal Market Place06](/assets/img/blog_unreal_market_place_1/market_place_6.png)  
    
- **Step2) 개인 정보 입력**  
    여기에 작성하는 내용은 미국 국세청(US IRS)에서 수집할 수 있기 때문에 거짓없이 작성되어야 한다. 정보 수집에 동의한다고 체크하고, 이름/성/국적/생일/핸드폰 번호를 정확히 입력하도록 한다(핸드폰 번호는 8210XXXXXXXX 형태로 입력).
      
    ![Unreal Market Place07](/assets/img/blog_unreal_market_place_1/market_place_7.png)  

- **Step3) 영구 주소 입력**  
    실제 거주지 주소를 영문으로 입력하면 된다. 빨간색 asterisk로 표시된 항목만 입력해도 다음 단계로 넘어갈 수 있다(하단에 있는 체크박스는 선택사항).
      
    ![Unreal Market Place08](/assets/img/blog_unreal_market_place_1/market_place_8.png)  

- **Step4) 전자 서명 및 정보 반환에 대한 동의**  
    납세자(판매자) 신원 서류에 전자 서명을 하기 위해서 여러분의 동의를 얻어야 한다는 내용이다. 여기에 동의하지 않는다면 직접 서류 양식을 다운로드해서 출력후에 서명을 하고 우편과 같은 형태로 보내야 한다. 생각만해도 귀찮으므로 동의한다에 체크.. 
      
    ![Unreal Market Place09](/assets/img/blog_unreal_market_place_1/market_place_9.png)  
      
- **Step5) 미국 시민 확인**  
    미국 국적자/미국 거주자/미국 파트너쉽/미국 기업에 해당하지 않는다면 'No'를 선택하면 된다. 
      
    ![Unreal Market Place10](/assets/img/blog_unreal_market_place_1/market_place_10.png)  

- **Step6) 수익 소유자 확인**  
    앞서 세금 정보 입력 단계에서 'Persenal tax profile'을 선택했으므로 자동적으로 individual로 설정되고 변경이 불가능하다. 그냥 Continue 클릭! 
      
    ![Unreal Market Place11](/assets/img/blog_unreal_market_place_1/market_place_11.png)  

- **Step7) 서비스 수익 지역 확인**  
    마켓플레이스에서 제공하는 서비스가 어디에서 발생하는지 확인하는 것으로 한국에서 제작되고 퍼블리싱되는 것이므로 *All services are performed outside the U.S.* 를 선택하고 넘어가자.
      
    ![Unreal Market Place12](/assets/img/blog_unreal_market_place_1/market_place_12.png)  

- **Step8) 미국내 사업 운영 확인**  
    미국에서 소유하거나 운영중인 서비스/제품 등이 있는지 확인하는 절차로 있다면 Yes를 없다면 No를 선택한다(나의 경우 당연히 No).
      
    ![Unreal Market Place13](/assets/img/blog_unreal_market_place_1/market_place_13.png)  

- **Step9) 세금 신고서 확인**  
    위의 단계까지 완료했다면 지금까지 작성한 내용을 바탕으로 만들어진 아래와 같은 서류 양식(W-8BEN, 외국인용 미국 세금 신고서)을 보여주는데 입력한 내용이 모두 맞다면 스크롤을 아래로 내려서 Continue를 클릭하면 된다.
      
    ![Unreal Market Place14](/assets/img/blog_unreal_market_place_1/market_place_14.png)  

- **Step10) W-8BEN 인증**  
    지금까지 작성한 내용이 모두 사실이고 기재한 내용중에 잘못된 것이 있으면 30일 이내에 새로 작성하겠다 등등의 내용에 동의하는 단계이다. 체크표시 부분을 모두 체크하고 수익자 이름(정확한 본인 영문명)과 이메일 주소를 기입한 이후 ***Submit W-8BEN*** 버튼을 클릭하면 된다.
      
    ![Unreal Market Place15](/assets/img/blog_unreal_market_place_1/market_place_15.png)  
  

### **결재 방식 입력**  
  
세금 신고서까지 작성 완료하여 접수를 했다면 이제 결재 방식을 입력하는 일만 남았다. 에픽게임즈에서는 HYPERWALLET이라는 결재 시스템을 이용하고 있는데 결재 정보를 입력하기 위해서 활성화하려고 해도 아래 그림과 같이 버튼이 먹통인 상태가 계속되었다(처음에 당황한 부분). 다음날 다시 들어와서 확인해보니 활성화 되어 있던 것으로 보아 세금 신고서 정보를 입력하고 내부적으로 이를 처리하기까지 시간이 걸려서 그랬던 것으로 생각된다.
    
![Unreal Market Place16](/assets/img/blog_unreal_market_place_1/market_place_16.png)  
  

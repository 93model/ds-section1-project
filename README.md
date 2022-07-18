## Video Game Data Analysis

## ❓ 데이터 소개
vgchartz(https://www.vgchartz.com/gamedb/)의 Game DB에서 추출한 데이터에 기초
약 16000건

## 🛠 문제
다음 분기에는 어떤 장르의 게임을 설계 해야 할까?

## 🧹 데이터 전처리
# 데이터의 한계점
1)'게임'이 아닌 '비디오 게임'에 대한 출고량 데이터
 판매를 한 장 단위로 출고량으로 계산하는 '비디오 게임' 데이터 
 최근에는 부분 유료화 또는 랜덤 뽑기, 추가 확장팩 등 다양한 비즈니스 모델이 많아 짐 
 또한 한 장의 게임의 가격은 천차만별 
 '몇 백만장이 팔렸다'는 마케팅 문구 외에는 크게 쓰이지 않음  → 매출액 단위의 데이터가 분석에 더 유리

2) 현재 게임의 트렌드는 모바일 게임 :  모바일 게임에 대한 통계가 없음 

3) 현재 가장 성장하는 게임 시장은 중국 : 중국 시장에 대한 통계를 기타 국가로 집계 

4) 게임의 장르 구분이 갈수록 희미 해짐 : 장르가 명확하지 않은 게임의 등장 
 게임과 메타버스(로블록스, 마인 크래프트 등)의 경계가 무의미 해지는 시점 
 마인 크래프트 안에도 (FPS, RPG, 카드 게임 등 ) 다양한 서버가 존재 

- 데이터를 활용하기 위한 전제 조건 
   플레이 스테이션, xbox, PC 등 다양한 플랫폼에 진출할 수 있는 개발력
   모바일 게임보다 리스크가 높은 비디오 게임 시장에 진출하려 하는 기획팀
   결국은 Money !

- 과거의 데이터 (하나의 히트작이 기록적인 판매고를 기록하거나, 플랫폼이 다양) 
  현재의 게임과 양상이 다름

->10년 이내(2010 ~), 최소 출고량 10만장 이상으로 분석 대상을 한정
약 3000개 게임


## ✔️ 결과
가장 중요한 시장 : North America -> 영어 기본 탑재
그 외 언어는 유럽(프랑스어 ,독일어, 스페인어)

사람들이 가장 선호하는 장르 (Action, Shooter) / 일본만 RPG

플랫폼은 Playstiaton 근소 우위,
But, 플랫폼 독점 출시가 아니라면 멀티 플랫폼(PS, xbox, PC) 지향


## 🔍 현황
출시 기대 한국 비디오 게임

Action RPG 게임 (Open World Action Adventure) : 붉은 사막, Dokev , 프로젝트 BBQ 등

Shooter 게임 : 루트 슈터, 플랜 8


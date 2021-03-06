---
title: "정보통신망 - 클라우드 컴퓨팅에 대하여"
categories:
 - 공부
tags:
 - 정보통신망
 - 클라우드컴퓨팅
 - cloud computing
 - 방송대
 - 방송통신대
date: 2021-03-06 21:30
comments: true 
---

정보통신망 주제: Cloud Computing 
===========

> 목차: 
[1. 정의 및 필요성](#-1.-정의-및-필요성)
[2. 장점과 문제점](#-2.장점과-문제점) 
[3. 정보통신망과의 관련성](#-3.-정보통신망과의-관련성)
[4. 활용될 수 있는 정보통신망 기술](#-4.-활용될-수-있는-정보통신망-기술)
[5. 결론](#-5.-결론)


## 1. 정의 및 필요성

큰 의미의 클라우드 컴퓨팅이란 정보 통신망을 관리하는 시스템 중 하나로서, 집적 또는 공유된 통신기기 설비 소프트웨어 등의 자원을 이용자의 요구에 따라 필요한 만큼 이용할 수 있도록 해주는 시스템을 의미한다. 클라우드라는 명칭은 구름과 같이 안쪽이 보이지 않아 사용자가 시스템이 어떻게 돌아가는지 알 필요 없이, 어디 어디서나 원하는 작업을 할 수있다는 의미에서 붙여졌다.[출처](https://namu.wiki/w/%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C%20%EC%BB%B4%ED%93%A8%ED%8C%85)

클라우드 컴퓨팅은 세부적으로 아래와 같이 [구분](https://www.whatap.io/ko/blog/9/)된다. 

`Infrastructure as a Service(IaaS)`  
컴퓨팅 네트워킹 스토리지 등의 물리적인 자원들을 가상화한 서비스를 뜻한다.

`Platform as a Service(PaaS)`  
응용프로그램을 개발하는 데 있어서 필요한 플랫폼을 제공하는 서비스를 Paas라고 한다. Pass를 통해 응용프로그램 개발하는 경우 별도의 설치 없이 미들웨어 API를 사용할 수 있다.

`Software as a Service(SaaS)`  
SaaS란 클라우드 환경에서 동작하는 응용프로그램을 가상화하여 서비스 형태로 제공하는 것이다. 사용자는 시스템이 어떤 식으로 작동하고 어떻게 이루어져 있는지 알 필요 없고 또한 별도의 다운로드 없이도 서비스를 이용할 수 있다. 

사용자가 클라우드 컴퓨팅을 이용하면 모든 데이터와 자원은 클라우드 서비스를 제공하는 기업의 클라우드 내부에만 존재한다. 그러므로 사용자의 컴퓨터에는 어떠한 데이터도 남아있지 않고 클라우드와 커뮤니케이션하는 것만 담당한다. 이러한 클라우드 컴퓨팅 서비스는 Amazon Web Services, Microsoft Azure, Google Cloud Platform 등이 있으며 국내에는 Naver Cloud Platform이 존재한다. 클라우드 컴퓨팅 주요 업체의 서비스 시장 규모는 다음과 같다. 

올해 전 세계 클라우드 시장은 18% 성장이 전망되며, 글로벌 기업의 30% 이상이 클라우드에 투자하는 것을 최우선으로 간주하고 있을 정도로 기업의 클라우드 서비스 수요는 폭발적으로 증가하고 있다. 특히 클라우드 서비스가 폭증하는 데이터 수요를 감당하고 AI, Big Data 분석 등에 매우 유용하게 활용되기 때문에, 그 필요성과 중요성은 점점 커지고 있다. 

## 2. 장점과 문제점

### 클라우드 컴퓨팅의 장점

#### 확장성 
클라우드는 Window, Linux 등 PC와 Android, iOS 등의 모바일의 표준 운영시스템에서 사용할 수 있다. 만약, 갑작스럽게 서비스 사용자가 늘거나 줄어드는 일이 발생하거나 새로운 사업으로 확장하게 될 때 기상기기와 스토리지를 빠르게 변경하여 그것을 유연하게 대처할 수 있다. 

#### 경제성 
클라우드 컴퓨팅의 사용자가 직접 서버를 운영하지 않는다는 점은 결국 시간과 비용이 절감된다는 것과 같다. 또한 데이터베이스 서버 등의 자본 비용이 발생하지 않는다. 사용자가 원하는 만큼의 자원 혹은 사용되는 양만큼의 자원만 사용하므로 자원의 낭비가 없다. 거기에 더해 사용자가 사용한 서비스의 양에 따라 비용이 결정되기 때문에 비용관리 측면에서도 유리하다. 이러한 점으로 사용자는 서버 운영에 적게 투자하고 운영에만 집중할 수 있게 된다.

#### 이동성 
클라우드 컴퓨팅은 사용자가 사용하는 디바이스 혹은 운영시스템의 종류 등에 상관없이 서비스가 제공되기 때문에 다수의 사용자가 다양한 디바이스를 통해 아무 때나 상관없이 혹은 언제든지 클라우드에 접근할 수 있다. 

### 클라우드 컴퓨팅의 단점

#### 보안에 취약 

클라우드 서비스를 제공하는 회사에 문제가 생긴다면 클라우드 서비스 사용자의 데이터가 갑자기 증발하거나 외부로 유출될 수 있다. 실제로 2012년에 클라우드 서비스 업체 퍼스트 서버에서 통신장애가 발생하여 5,698개 기업의 데이터가 삭제된 일이 발생하였다.[출처](http://www.ddaily.co.kr/cloud/news/article.html?no=945715) 또한 클라우드 제공자뿐 아니라, 사용자의 개인정보가 해킹되어 발생하는 사고가 문제가 되고 있다. Amazon Web Service(AWS)를 사용하는 금융사 캐피탈원의 클라우드가 해킹되어 고객 1억여 명의 개인정보가 유출[출처](https://m.etnews.com/20190903000106?obj=Tzo4OiJzdGRDbGFzcyI6Mjp7czo3OiJyZWZlcmVyIjtOO3M6NzoiZm9yd2FyZCI7czoxMzoid2ViIHRvIG1vYmlsZSI7fQ%3D%3D)되었는데 범인은 AWS 직원으로 캐피탈원의 방화벽 오류를 이용한 것이었다. 이렇게 클라우드 서비스 제공 회사에 문제가 발생한다면 그 회사뿐만 아니라 서비스를 이용하는 모든 회사에 문제가 발생할 수 있다.

#### 인터넷 종속 
클라우드라는 서비스 자체가 인터넷에 접속해야만 이용할 수 있으므로 통신망에 
장애가 발생하거나 해킹 등의 불법적인 이유로 클라우드에 접속이 중단되면 클라우드 서비스의 사용이 불가능하다. 다수의 기업이 클라우드 컴퓨팅 방식을 채택함에 따라서 네트워크 장애나 서비스에 장애가 발생하게 되면 기업의 중요 
활동이 멈추게 되고 이로 인해 손실이 발생할 수 있다.

#### 초과 비용의 위험 
회사의 규모가 클수록 사용하는 IT 자원이 커지며 그로 인해 더이상 클라우드를 사용하는 비용적 이익을 기대하기 어렵다. 인터넷 전송 용량이 커진다면 데이터를 읽기 위한 엄청난 네트워크 대역폭이 필요하고 그 비용이 매우 많이 소요되므로, 
이런 경우에는 private 스토리지를 이용하는 것이 더 경제적인 선택지가 된다.[참고](http://www.itworld.co.kr/news/56158) 

## 3. 정보통신망과의 관련성

정보통신망이란 “ 전기통신설비를 이용하거나 전기통신설비와 컴퓨터 및 컴퓨터의 이용기술을 활용하여 정보를 수집·가공·저장·검색·송신 또는 수신하는 정보통신체제(정보통신망법 제 2조 제 1항 제 1호)를 뜻한다. 하드웨어나 소프트웨어가 눈부시게 발전하기 전에는 하나의 컴퓨터가 모든 데이터를 처리하는 중앙집중형 방식이 대부분이었다. 하지만 자원의 공유, 신뢰도, 처리 기능 분산, 안정성 등의 이유로 정보통신망을 이용한 자료 처리 방식으로 바뀌게 되었는데 그중에서도 클라우드 컴퓨팅은 정보통신망의 핵심 시스템 중 하나로 꼽힌다. 사용자는 정보통신기기와 설비 등의 자원을 통하여 언제 어디서나 클라우드 컴퓨팅을 이용할 수 있다. 이러한 클라우드 컴퓨팅이 다른 시스템과 구분되는 특징은 사용자의 디바이스에 처리되던 대부분 작업이 클라우드에 맡겨진다는 것이다. 

## 4. 활용될 수 있는 정보통신망 기술

클라우드 컴퓨팅에는 아래와 같은 정보통신망 기술들이 핵심적으로 활용된다.

### 서버 가상화(Hypervisor)

서버 가상화는 독립적인 CPU, 메모리 네트워크 그리고 운영체제를 갖는 여러 개의 가상머신들이 서버의 자원을 각각 나누어 사용하는 기술을 의미한다. 하이퍼바이저(Hypervisor) 는 하드웨어에서 이러한 가상머신들을 운영하는 플랫폼을 말하며 VMM(Virtual Machine Monitor) 라고도 부른다. 즉, 하이퍼바이저는 컴퓨터의 운영체제와 응용프로그램을 물리적 하드웨어에서 분리해 내는 프로세스이다. 이러한 하이퍼바이저는 물리적인 호스트 시스템이 여러 대의 G uset로 운영할 수 있게 함으로써, CPU, 메모리, 네트워크 대역폭 등과 같은 컴퓨터의 자원을 더 효과적으로 사용할 수 있게 도와준다. 이 기술을 통해 가상머신들은 논리적으로 서로 분리됨으로써 한 가상머신에 오류가 발생하거나 악성코드 등의 공격을 받거나 가동을 멈춘다고 하더라도 그 문제가 다른 가상머신이나 시스템으로 번지지 않다는 장점이 있다. 또한 하이퍼바이저는 이동성이 매우 강한 특징을 갖는데, 하드웨어로부터 독립적이기 때문에 로컬 또는 원격 가상화 서버 사이를 이동할 수 있기 때문이다.[참고](http://gotocloud.co.kr/?p=615) 

### 네트워크 가상화 
클라우드 환경은 이용자가 원하는 때에 사용자가 원하는 자원을 받을 수 있는 구조이다. 이때 가상 라우터가 사용자별로 네트워크를 분리하고, 분리된 네트워크는 인터넷과 통신하는 역할을 한다. 각 사용자가 사용하기 위한 가상머신을 생성하면, 그 가상머신에 대한 사설 IP가 VLAN에 자동으로 할당되고, 이렇게 할당된 가상 라우터를 통해 인터넷과 통신한다. 통신 중에 가상머신은 분리되고 통신이 차단된다.

### 분산 스토리지클라우드 
서비스 이용자의 증가로 데이터 저장 시 필요한 용량의 크기가 수십 혹은 수백 테라바이트 이상으로 요구된다. 이러한 요구를 단일 스토리지로 커버하는 것은 매우 어렵다. 따라서 단일 스토리지가 아닌 단일 스토리지를 네트워크로 연결하여 대용량의 저장공간을 제공할 수 있는 분산 스토리지가 반드시 필요하다.

## 5. 결론

클라우드 시스템으로 인해 업무의 커뮤니케이션이 더욱 신속해지고, 사용자는
원하는 서비스를 언제 어디서나 다양한 디바이스로 이용할 수 있으며, 즉각적인 동기화로 사적/공적 업무 커뮤니케이션 면에서 그 편의성이 어느 때보다도 극대화되고 있다. 그러나 클라우드 컴퓨팅은 이용과 관리가 매우 쉽지만 또 그만큼 보안에도 취약해서 보안 사고가 꾸준히 발생하고 있다. 이러한 취약점은 클라우드 시스템에 집중되고 의존적인 환경에서 치명적인 단점이 된다. 만약 보안 사고가 발생할 경우 크나큰 손실이 발생할 가능성이 항상 존재한다. 따라서 클라우드 서비스를 이용하는 사용자는 항상 클라우드 외에 백업 시스템을 갖추고 중요한 데이터에는 이중의 암호화 시스템을 마련하여 혹시 모를 사고에 대비해야 할 필요가 있다.

한편 구글은 2025년이면 전 세계의 총 데이터양이 현재의 5,175배 이상인 제타바이트로 증가할 것으로 예상하며 대부분의 기업이 집약적 멀티 클라우드 환경을 이용하게 될 것이라고 예측하고 있다. 클라우드 컴퓨팅의 미래는 서버 자원의 요청에 
따라 동적으로 할당되는 서버리스 시스템이라고 보는 시각도 있다. 이렇게 빠르게 변화하는 클라우드 컴퓨팅 환경 속에서 각 사용 주체들은 자신에게 맞는 모델을 선택하여 장점은 극대화하고, 단점은 최소화하는 수단을 취하여 이러한 미래를 대비해 나갈 필요가 있다. 
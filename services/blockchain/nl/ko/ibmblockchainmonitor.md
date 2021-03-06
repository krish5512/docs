---

copyright:
  years: 2016

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:pre: .pre}

# 대시보드 모니터
{: #blockchain_dashboard_monitor}
마지막 업데이트 날짜: 2016년 10월 13일
{: .last-updated}

대시보드 모니터는 성능 데이터 및 배치된 체인코드를 포함하여 블록체인 환경의 개요를 제공합니다. 모니터를 사용하여 피어, 로그, 원장 상태, API 및 체인코드에 대한 네트워크 정보를 볼 수 있습니다.  
{:shortdesc}

<br>
## 모니터 탭
{: #blockchain_dashboard_monitor_tabs}

다음 탭이 대시보드에 표시됩니다.
  - 네트워크
  - 블록체인
  - 데모 체인코드
  - API
  - 로그
  - 상태
  - 지원

**네트워크 탭**: 그림 1에 표시된 대로, 실행 중인 체인코드 컨테이너 및 피어의 상태를 모니터합니다. 결합된 노드 호스트와 포트 값인 유효성 검증 피어 및 인증 기관에 대해 발견 및 API 라우트를 봅니다. 예를 들어, **서비스 대시보드**에서 Bluemix **서비스 신임 정보**의 JSON 코드 스니펫은 `"discovery_host"` 및 `"discovery_port"`가 **네트워크** 탭에 표시된 라우트와 동일시됨을 표시합니다. 이러한 값은 Bluemix에 수동으로 연결하는 데 유용합니다. 

![](images/IBC_BMX_Monitor_Network.png "네트워크 탭")
*그림 1. 네트워크 탭*


**블록체인 탭**: 블록체인의 현재 상태를 봅니다. 그림 2에 표시된 대로, 모든 트랜잭션, 네트워크의 현재 원장 상태 및 성능 데이터를 볼 수 있습니다. 

![](images/IBC_BMX_Monitor_Blockchain.png "블록체인 탭")
*그림 2. 블록체인 탭*


**데모 체인코드 탭**: 네트워크에서 배치하고 호출할 수 있는 3개 샘플 체인코드 템플리트를 학습하고 실험합니다. 그림 3에서 표시된 대로, 지시사항이 프로세스를 안내하기 위해 제공됩니다. 체인코드의 모든 배치 및 호출은 로그에 쓰여지며, 이를 라이브 로그, 블록체인 및 API 탭에서 볼 수도 있습니다.   

![](images/IBC_BMX_Monitor_Demo.png "데모 체인코드 탭")
*그림 3. 데모 체인코드 탭*


**API 탭**: 그림 4에 표시된 대로, Swagger UI를 사용하여 REST API를 통해 블록체인 네트워크와 상호작용합니다.   

![](images/IBC_BMX_Monitor_API.png "API 탭")
*그림 4. API 탭*


**로그 탭**: 네트워크의 모든 트랜잭션의 결과가 포함된 유효성 검증 피어 및 멤버십 서비스에 대한 로그를 봅니다. 로그 정보를 사용하여 트랜잭션을 검사하고 체인코드의 문제점을 해결할 수 있습니다.   

![](images/IBC_BMX_Monitor_Logs.png "로그 탭")
*그림 5. 로그 탭*


**상태 탭**: 그림 6에 표시된 대로, 서비스, 네트워크 및 자동화된 테스트의 성능 메트릭을 봅니다. 전월의 데이터를 표시합니다. 이 탭에는 IBM Blockchain의 릴리스 정보 및 코드 공지사항, 일반 포럼, 알려진 문제점도 포함되어 있습니다.   

![](images/IBC_BMX_Monitor_Status.png "상태 탭")
*그림 6. 상태 탭*


**지원 탭**: 그림 7에 표시된 대로, 문제를 보고하고 서비스 상태를 봅니다. 

![](images/IBC_BMX_Monitor_Support.png "지원 탭")
*그림 7. 지원 탭*

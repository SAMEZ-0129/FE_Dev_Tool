# NETWORK
네트워크 요청 정보를 확인할 수 있는 부분.

각 요청에 대한 로딩 성능 및 병목을 체크할 수 있는 부분.

네트워크 탭에서 새로고침을 하거나, 우측 상단에 녹음 버튼을 클릭할 경우 해당 페이지에 발생하는 네트워크 요청을 확인할 수 있음.

## Load 이벤트
네트워크 패널에서는 2개의 주요 이벤트를 알려줌.
1. DOMContentLoaded: 초기 HTML 문서가 로드된 후 파싱이 완료된 경우.
2. load: 페이지와 페이지에서 요청한 모든 리소스가 로드가 완료될 경우.

## Request Table
![image](https://github.com/SAMEZ-0129/FE_Dev_Tool/assets/81644075/d896d8e6-466b-468c-8c09-ae492e89e553)

전달되는 리소스를 확인할 수 있는 부분, 전달되는 순서대로 위에서부터 쌓인다.

특정 리소스를 선택할 경우 해당 리소스가 의존하는 리소스를 확인 할 수 있음.

SHIFT를 누르고 리소스를 선택할 경우 해당 리소스를 호출한 리소스 확인 가능.

## Film Strip
상단에 카메라 버튼을 클릭하면 특정 리소스들이 로드되는 각 화면을 확인 할 수 있음.

## Filters
특정 리소스 확장자만 구분해서 확인하고 싶은 경우 필터를 통해 파악 가능.
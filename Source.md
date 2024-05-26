#  Source 탭
왼쪽에는 파일 탐색기의 역할, 가운데는 실제 소스코드, 오른쪽은 콜스텍/breakpoint/이벤트 리스너 등을 확인할 수 있다

1. Break point
> 소스코드에서 원하는 위치를 지정하여 실행 중 멈추게 할 수 있으며 멈춰진 상태에 대한 정보 확인 가능.
> 값을 변경하거나 함수를 실행할 수 있음.
> conditional break point라는 기능을 통해 특정 조건에서만 break가 걸리도록 사용할 수도 있다.
> XHR Break point를 통해 네트워크 요청에 대한 break를 걸 수도 있다. (특정 웹 요청에 대한 디버깅도 가능)
> EventListener Break point를 통해 이벤트가 발생했을 때 break를 걸고 코드 위치 확인 가능.
> break on exception을 통해 코드에 에러가 발생하면 해당 위치를 확인(콘솔에서도 확인 가능한 부분임)

2. Source Map
> 원본소스와 변환된 소스를 맵핑해 주는 Map 파일.
> 원본 소스와 최종소스를 매핑해서 디버깅시 용이.

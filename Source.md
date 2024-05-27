# Source
소스 탭: js를 개발할 경우 가장 많이 사용하는 부분 중 하나.

코드를 수정하거나 디버깅용도로 많이 사용.

1. Break point Debugging
> 스크립트 실행 도중 중단 점을 설정하여 오류 위치 에서의 값 확인
2. SourceMap
> 최소화되고 난독화된 소스코드를 원본 코드로 디버깅하는 기능 확인
3. Snippets
> 자주 사용하는 코드 조각들을 모아 두는 기능

## Break point
소스코드의 원하는 위치에 멈춰서 멈춰진 상태에 대한 정보 확인이 가능.

값을 변경하거나 특정 함수를 수행할 수 있음.

동적으로 만들어진 페이지는 break point가 잘 안걸릴 수 있음. 

Conditional Break point를 통해 조건에 따른 break를 걸어줄 수도 있다.(소스코드 넘버링에 우클릭)

XHR에 breakpoint: XHR Break point를 통해 네트워크 요청에 대한 break를 걸 수도 있다. (특정 웹 요청에 대한 디버깅도 가능)

EventListener break point: EventListener Break point를 통해 이벤트가 발생했을 때 break를 걸고 코드 위치 확인 가능. break on exception을 통해 코드에 에러가 발생하면 해당 위치를 확인(콘솔에서도 확인 가능한 부분임)

## Source map
원본 소스와 변환된 소스를 맵핑해 주는 Map파일.

설정에서 javascript source map 설정을 활성화 시켜줘야함.

원본 코드를 통해 디버깅을 할 수 있는 기능을 제공합니다.

## tip
ctrl/command + p를 통해 개발자 도구 안에서 검색(파일 혹은 텍스트)가 가능합니다.

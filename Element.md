## 개발자 도구 열기
1. Element 탭 (요소 탭)
![image](https://github.com/SAMEZ-0129/FE_Dev_Tool/assets/81644075/715fe3fe-8647-4f07-a8ca-60291157c667)

- Element 탭에서 왼쪽 부분은 HTML의 MarkUp을 보거나 직접 수정해서 반영된 내용을 볼 수 있는 부분입니다.(Text Editor같이)
- 오른쪽은 부분에서 Style(CSS)은 속성이나 Box 모델을 확인 및 수정할 수 있는 부분
- Event Listner는 각 Elements의 어떤 EventListner가 등록이 되어 있는지, 각 요소의 이벤트 핸들러를 찾아낼 수 있다.
- DOM Breakpoint는 Element에 변화를 감지하여 break point를 걸어 줄 수 있습니다.

![image](https://github.com/SAMEZ-0129/FE_Dev_Tool/assets/81644075/4d5144c0-ca33-48ee-b132-246f393541fa)

왼쪽 상단에 있는 Instect 버튼을 통해 브라우저 내 요소를 선택할 경우 해당 요소의 위치를 Element 패널 하단의 breadcrumb trail을 통해 확인이 가능하다. (해당 요소의 위치는 왼쪽부터 오른쪽으로, 부모 요소 -> 자식 (본인))

직접 브라우저 페이지 내 요소를 선택할 수 있고, HTML 코드 내에서 원하는 요소 선택 시 동일하게 작동한다.

![image](https://github.com/SAMEZ-0129/FE_Dev_Tool/assets/81644075/5e5e53b0-7811-453d-91aa-8b9c7ba78bcf)
***
### Edit Style
선택된 요소의 Style을 실시간으로 변경할 수 있다. (CSS)

![image](https://github.com/SAMEZ-0129/FE_Dev_Tool/assets/81644075/e9618f6e-c009-4d13-bdc1-6de9454da99b)
> 변경 전

![image](https://github.com/SAMEZ-0129/FE_Dev_Tool/assets/81644075/a8bd79bd-4594-4928-87f1-dc43e5f322a8)
![image](https://github.com/SAMEZ-0129/FE_Dev_Tool/assets/81644075/cc4b9576-85ac-4c22-b52f-4e98f853abd1)
> 색상 변경 및 width 50으로 수정

![image](https://github.com/SAMEZ-0129/FE_Dev_Tool/assets/81644075/2eb7cbab-c979-4a12-a5b4-649cfc478a7a)
> 변경 후
***
### Edit DOM
HTML 코드 영역에서 1번 박스 영역인 div를 **드래그**해서 2번 위로 옮기기.

3번 박스 영역 div 코드를 delete 키를 통해 삭제하기.

위 실습 진행 시 실제로 브라우저에 반영된다. 
![image](https://github.com/SAMEZ-0129/FE_Dev_Tool/assets/81644075/616d2269-5137-4f12-b42b-247971ec9a3a)

### Scroll Into View
HTML 코드에서 특정 요소를 우클릭 후 Scroll into View 선택 시 해당 요소의 위치로 페이지가 이동.

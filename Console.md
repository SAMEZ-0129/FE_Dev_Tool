# console
1. 일반적으로 많이 사용하는 console.log()
2. 그외 콘솔 출력을 제공하는 다양한 API 들
3. 콘솔 출력 formatting 하기
4. 성능 측정에 활용하기

![image](https://github.com/SAMEZ-0129/FE_Dev_Tool/assets/81644075/79b37bff-a578-4b52-bf16-3dc7f8d28fda)

1. console.log
> 가장 많이 사용하는 일반 콘솔 출력문
2. console.info
> 일반적인 콘솔 출력문(인포랑 유사)
3. console.warn
> 흔히 오류 콘솔 출력처럼 노란 배경에 출력하는 기능. (콜스텍 정보도 같이 표시)
4. console.error
> 빨간색으로 콘솔창에 출력(콜스택 정보 표시)
5. console.assert
> 조건문을 통해 해당 조건이 만족하지 않았을 때 얼럿을 출력하는 기능. 파라미터로 조건문,출력문 이 필요함.
> ![image](https://github.com/SAMEZ-0129/FE_Dev_Tool/assets/81644075/99c5fc26-9a01-4d0f-910f-fb97d770a543)

## console 이려이 많아진 경우, clear()를 통해 삭제 가능.

## 타임스탬프 노출하기
우측 상단 설정에서 콘솔 탭에 가면 타임스탬프 보기 체크박스 확인 가능.

체크박스 선택 시 로그 출력마다 출력 시간이 타임스탬프도 같이 찍혀서 나옴.

# Advanced
콘솔에서 출력할 시 formatting이 가능. 
![image](https://github.com/SAMEZ-0129/FE_Dev_Tool/assets/81644075/924667f8-4d97-42ed-a1f3-22e23a637ce8)

특정 Element의 속성 정보가 궁금한 경우
![image](https://github.com/SAMEZ-0129/FE_Dev_Tool/assets/81644075/facd8636-8d6b-4a57-b002-818feedf6bf9)

그룹핑 하기: console.group() 과 console.groupEnd() 사이에 console.log 를 그룹핑해서 묶어서 관리 가능.

테이블 만들기: console에서 테이블을 만들어서 확인도 가능함.

![image](https://github.com/SAMEZ-0129/FE_Dev_Tool/assets/81644075/3044a3db-3f21-4083-be86-ad151e720f63)

# Diagnose (진단)
1. console.trace를 통해 콜스택 정보/위치 확인 가능함.
2. console.time() 과 console.timeEnd() 사이에 구동 시간을 측정하는 코드를 삽입하면 수행시간을 출력할 수 있다.
3. console.count()를 통해 동일한 문자열 key 이 몇번 수행되었는지를 누적하여 알려준다.


# REST-API 활용 방법

## 학습 내용

<ul>
    <li>요청에 대한 상태를 useState로 관리</li>
    <li>요청에 대한 상태를 useReducer로 관리</li>
    <li>리팩토링 기능으로 한 파일에 있는 function을 다른 파일로 분리 가능(VSCode 기준)</li>
    <li>만들어놓은 reducer를 기반으로 useAsync custom hook 만들어서 사용</li>
    <li>반복되는 코드는 custom hook을 만들어서 사용하면 코드 절약</li>
    <li>요청에 대한 상태를 react-async 라이브러리로 관리</li>
    <li>context에서 비동기 작업 상태 관리(특정 상태가 전역적으로 필요할때만 사용 권장)</li>
    <li>context에서 반복되는 코드 리팩토링</li>
</ul>

## API 요청시 관리해야 하는 상태 세가지

<ul>
    <li>요청의 결과</li>
    <li>로딩 상태</li>
    <li>에러</li>
</ul>

## react-async 장점

<ul>
    <li>필요할 때 설치해서 바로 사용 가능</li>
    <li>컴포넌트에서 비동기 작업할 때 필요한 대부분의 기능 탑재</li>
    <li>hook이 아닌 컴퍼넌트 형태로도 사용 가능</li>
    <li>특정 promise를 기다리는 작업을 도중에 취소할 수 있음<li>
</ul>

## react-async 단점

<ul>
    <li>옵션이 조금 복잡하다</li>
</ul>

# # Prepping Components

* atomic design을 통하여 컴포넌트 기반의 프로그래밍인 리액트 사용을 극대화 하기 위한 레포지토리.
* 계층 구조를 기반으로 컴포넌트를 작성하는 것은 아토믹 디자인에서 중요한 기초작업.
* Atoms(원자) -> Molecules(분자) -> Organisms(유기체) -> Templates(템플릿) -> Pages(페이지)의 구성을 가지고 효과적인 인터페이스 시스템을 만든다.



### Atoms(원자)

: 버튼, 제목, 텍스트 입력 필드와 같은 가장 작은 구성 컴포넌트. 모든 컴포넌트의 기초가 되며 더 이상 분해 될 수 없는 필수 요소.



### Molcules(분자)

: 2개 이상의 원자 컴포넌트로 구성되어 있음. 하나의 단위로 함께 동작하는 UI컴포넌트의 그룹. 텍스트 입력 필드, 레이블, 오류 메세지 또는 **HTML 텍스트 입력 필드와 버튼으로 구성된 검색 컴포넌트**가 대표적인 예. Atom들을 최소의 역할을 수행할 수 있도록 합한 그룹.

### Organisms(유기체)

: 분자 또는 원자 컴포넌트 또는 다른 유기체의 그룹으로 구성된 비교적 복잡한 그룹. 인터페이스의 개별적인 영역 형성



### Template(템플릿)

: 컴포넌트들을 배치하고 설계의 구조를 보여줌. 페이지가 어떻게 보일지에 대한 골격이다. 페이지는 실제 컨텐츠들을 배치한 UI를 보여주는데 이는 템플릿의 구체화된 인스턴스이다. ( 템플릿과 페이지는 유기체, 분자, 원자를 포함한다.)

## 

## Atomic Design을 적용한 폴더구조

: 팀원과의 상의에 따라 달라질 수 있음.

### 예시 

- src
  - components
    - pages
    - templates
    - UI
      - atoms
      - molecules
      - Organisms



참고 자료 :

https://velog.io/@thsoon/%EC%93%B8%EB%95%8C%EC%97%86%EC%9D%B4-%EA%B3%A0%ED%80%84%EC%9D%B8-%ED%88%AC%EB%91%90%EB%A6%AC%EC%8A%A4%ED%8A%B8-%EB%A7%8C%EB%93%A4%EA%B8%B0-FE-2.-%EB%B7%B0-%EC%84%A4%EA%B3%84

https://ui.toast.com/weekly-pick/ko_20200213



https://blog.hyungsub.com/entry/%EC%95%84%ED%86%A0%EB%AF%B9%EB%94%94%EC%9E%90%EC%9D%B8-Atomic-Design-%EC%9B%90%EC%9E%90%EB%8B%A8%EC%9C%84%EB%94%94%EC%9E%90%EC%9D%B8-%EB%B0%A9%EB%B2%95%EB%A1%A0-%EA%B0%84%EB%8B%A8%ED%95%98%EA%B2%8C-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B3%A0-%EC%9D%91%EC%9A%A9%ED%95%98%EA%B8%B0



### react-responsive를 활용한 반응형 구현

```node
$ npm install react-responsive --save

```

# components

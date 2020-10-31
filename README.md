# KIMJIHYEON

이름 : 김지현 <p>
사는 곳 : 서초구 잠원동 <p>
나이 : 22 <p>
취미 : 운동
  
  <br>
  <br>
  
  ## 모듈(Module) (internalModule.js, externalModule.js)

- 하나의 공간 밖에 기능을 만들어 놓고 필요할 때마다 호출해서 기능을 쓸 수 있음, 여기서의 기능들을 모두 모듈이라고 부른다
- 모듈을 호출할 때엔 require 메서드로 호출, 모듈로서 호출되기 위해선  exports 전역 객체를 이용
- 내부모듈 - 노드에서 기본적으로 제공하는 모듈들

- 외부모듈 
  - node.js에서 제공하지 않는 모듈로 개인이나 단체 등에서 배포 https://npmjs.org
  - 외부모듈설치 -> npm install 외부모듈명

> 근데 npm을 사용해서 request 모듈을 불러오려고 했더니 package-lock.json이라는 파일이 같이 생기고 뭔가 많은 warn들이 찍혔다
>
> ***알고보니 npm을 사용하려면 우선 해당 프로젝트 내에서 npm init을 해준 다음 모듈을 불러와야 했다 (iOS 의 pod과 비슷해보여서 신기했다***
>
> npm init을 해주면 package.json 파일이 생긴다. 구글링 해보니 이 파일은 프로젝트에 대한 명세라고 한다.(해당 프로젝트의 이름, 버전, 사용되는 모듈 등의 스펙이 정해져 있다고 함)
>
> - package-lock.json은 모듈의 버전이 달라져 생길 버그들을 방지하기 위해 생기는 것 (?)
> - 보통 깃에 js 프로젝트를 커밋할 때 node_modulessms 부피가 커서 커밋에서 제외한다고 하는데, 이 때 꼭 package-lock.json은 포함시켜야한다고 함 (다른 사람이 풀 받았을 때 동일한 버전의 모듈들이 설치되도록 하기 위해)

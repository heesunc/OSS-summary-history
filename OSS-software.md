# 01. Linux
![image](https://user-images.githubusercontent.com/110728160/201847506-981b751d-4cf5-4928-848d-e62ea2db9072.png)

```
리눅스는 검증받은 운영체제인 유닉스와 완벽하게 호환되는 데다 공개 소프트웨어라는 점 때문에 등장하면서부터 큰 주목을 받았다. 
리눅스는 PC용 운영체제로 시작했지만 슈퍼컴퓨터에서도 동작하고 임베디드 시스템이나 모바일 기기등 다양한 환경에서도 사용된다. 
```

### 1. 리눅스의 특징
- 리눅스는 **공개 소프트웨어**이며 무료로 사용할 수 있음
- **유닉스와의 완벽한 호환성**을 유지
-  **서버용 운영체제**로 많이 사용
-  **편리한 GUI 환경**을 공공

### 2. 리눅스와 GNU 프로젝트
리누스 토르발스가 최초로 개발했고, 자체 커널 개발에 난항을 겪고 있던 중 GNU 프로젝트를 통해 완전한 운영체제로 거듭났다. 
컴퓨터 OS 커널의 일종인 리눅스 커널, 또는 리눅스 커널을 사용하는 운영체제를 가리키는 말이다. GNU 관련 사람들은 Linux는 커널일 뿐이며, 
커널만으로는 사용자가 운영체제를 활용할 수 없으니 GNU/Linux를 명칭으로 할 것을 주장하고 있다. 

### 3. 배포판의 종류
한편 리눅스에는 다양한 배포판이 존재한다. 
리눅스 배포판은 크게 **레드햇 계열, 데비안 계열, 슬랙웨어 계열**로 구분할 수 있고 계열별로 수백 가지의 리눅스 배포판이 만들어졌다, 사라졌다를 반복하고 있다. 
 * **레드햇 계열**: Redhat Enterprise Linux(RHEL), Fedora, CentOs 등
 * **데비안 계열**: 우분투, Mint 등
 * **슬랙웨어 계열**: Slaware Linux, OpenSUSE, slax등등

<img src="https://user-images.githubusercontent.com/110728160/201558682-4a4e5a90-6f44-41e5-9ed1-3d5727d16e5a.png" width="1000" height="430">


<br>

# 02. Visual Studio Code
![image](https://user-images.githubusercontent.com/110728160/201843002-ce8a3242-fd3e-492b-8ab5-ae6c12da64fa.png)
```
마이크로소프트에서 오픈소스로 개발하고 있는 소스 코드 에디터로, 2016년 4월 15일에 1.0.0 정식판이 발표되었다. 
Github의 Electron 프레임워크를 기반으로 만들었으며, Winodw, macOs, Linux를 모두 지원하고 있다. 
```

### 1. VS Code의 역사
- `2015년 04월 29일` 마이크로소프트 빌드 컨퍼런스에서 처음 소개되었으며, 미리보기 버전이 공개되었다.
- `2015년 11월 18일` MIT 라이선스 하에 배포가 진행되었고, 깃허브에 소스 코드가 올라왔으며, 확장 기능 지원 또한 발표되었다.
- `2016년 04월 14일` 퍼블릭 베타 단계가 끝나고, 정식 버전이 웹을 통해 배포되었다.

### 2. VS Code의 특징
- 가져온 모듈을 기반으로 스마트 완성을 제공하는 **IntelliSense를 사용**하여 구문 강조 표시 및 자동 완성 이상의 기능을 제공
- 중단점, 호출 스택 및 대화형 콘솔을 사용하여 **편집기에서 코드를 바로 디버깅**
- **Git 명령이 내장**되어 있어 편집기에서 바로 diff를 검토하고, 파일을 준비해 커밋
- **사용자 정의 및 확장**이 가능하다.





<br>

# 03. React
<img src="https://user-images.githubusercontent.com/110728160/201862135-d35582b5-a9ba-450a-b37a-cc2b56805357.png" width="350" height="200">

```
메타에서 개발한 오픈 소스 자바스크립트 라이브러리이다. SPA(웹페이지 렌더링 방식)을 전제로 하고 있으며, 
Dirty checking과 Virtual DOM을 활용하여 요구되는 해당 부분만 업데이트하기 때문에 빠른 퍼포먼스가 가능하다. 
React는 라이브러리이기 때문에 다른 프레임워크에 붙여 사용하는 것도 가능하며, 
강력한 메소드들을 지원하면서 웹프론트엔드 개발의 표준으로 자리잡았다.
```


### 1. React의 역사
리액트는 **페이스북**의 소프트웨어 엔지니어 **Jordan Walke**가 개발하였다. 그는 PHP용 HTML 컴포넌트 프레임워크인 XHP에 영향을 받았다.
* `2011년` 페이스북의 뉴스피드에 처음 적용되었다.
* `2012년` 인스타그램닷컴에 적용되었다.
* `2013년 5월` JSConf US에서 오픈 소스화되었다.

### 2. React의 특징

- **가상 돔** 
```
- DOM 업데이트를 추상화 시켜놓은 것 이다.
- 브라우저에서 html을 열게되면 DOM을 만들게 된다. html코드의 특정 부분이 변경되면 전체 DOM을 새롭게 만들게되어 매우 비효율 적이다.
- 이를 개선하기위해 리액트는 가상 DOM을 만들어 진짜 DOM과 비교한다. 그리고 변경된 부분만 진짜 DOM에 반영하는 방식으로 작업을 수행한다.
- in-memory에 존재해서 실제 렌더되지 않는다.
```
- **단방향 데이터 바인딩**
```
- 리액트는 데이터의 흐름은 단방향이다.
- 즉, 위에서 아래, 부모에서 자식, 한방향으로만 흐르며 거꾸로 부모의 데이터를 바꿔주기 위해서는 state를 이용해야 한다.
```
- **JSX**
```
- JSX(JavaScript XML)는 Javascript에 XML을 추가한 확장한 문법으로, 리액트에서 element를 제공해 준다.
```
- **선언형 프로그래밍**
```
- 선언형 프로그래밍은 제어 흐름을 설명하지 않고 계산 논리에 집중하는 프로그래밍이다.
- 선언형 뷰는 코드를 예측가능하고 디버그하기 쉽게 만들어 준다.
```
- **컴포넌트 기반**
```
- 웹 페이지에서 컴포넌트는 화면을 이루는 작은 요소들이다.
- 컴포넌트들은 여러 화면에서 사용될 수 있다. 즉 재사용성을 가지고 있다.
- 컴포넌트의 종류는 클래스형과 함수형으로 나뉜다.
```


<br>

# 04. Tensorflow
![image](https://user-images.githubusercontent.com/110728160/201854933-cb45e6bf-afab-47bb-b74b-6f2af81c6842.png)

```
구글이 2015년에 오픈 소스로 공개한 기계학습 라이브러리로, 딥러닝과 기계학습 분야를 일반인들도 사용하기 쉽도록 다양한 기능들을 제공한다. 
2016년 알파고와 함께 한국에서도 관심이 높아진 추세이며 관련 컨퍼런스들도 개최되고 있다.
하이 레벨 프로그래밍 언어로 알려진 Python을 활용하여 연산처리를 작성할 수 있다. 
```

### 1. Tensorflow의 장점
- 데이터 플로우 그래프를 통한 풍부한 표현력
- 아이디어 테스트에서 서비스 단계까지 이용 가능
- 계산 구조와 목표 함수만 정의하면 자동으로 미분 계산을 처리
- Python, C++, Go, Java, R[1]을 지원하며, SWIG를 통해 다양한 언어 지원 가능

### 2. Tensorflow의 단점
- 메모리를 효율적으로 사용하지 못하고 있음
- Symbolic Loop 기능이 유연하지 못하며, 함수가 있어도 텐서 타입으로만 적용해야 함

### 3. 버전 소개
공개된 버전은 일반 버전과 GPU 가속 버전 두 가지이다. 

- `일반 버전`: 어떤 컴퓨터에서든 실행할 수 있다는 장점
- `GPU 가속 버전`: 은 GPGPU를 사용해 대량 연산을 빠르게 수행하므로 훨씬 빠르게 동작하게 된다. 

그 외에 구글이 자사 서비스를 위해 내부적으로 사용하고 있는 버전도 있는데, 
이것은 구글이 자체개발한 AI 가속 하드웨어인 TPU(Tensor Processing Unit) 위에서 동작하기 때문에 인텔 제온이나 엔비디아 테슬라보다도 15~30배 더 빠르다.

TensorFlow 2.0이 출시되면서 CPU 버전과 GPU 버전이 통합되었다. CUDA 환경 설치가 올바르게 되었다면 자동으로 GPU를 인식해준다.


<br>

# 05. Pytorch

<img src="https://user-images.githubusercontent.com/110728160/201855443-c884cfdd-8ca6-465c-9996-43a35236356e.png" width="300" height="100">

```
토치(Torch) 및 카페2(Caffe2)를 기반으로 한 텐서플로우와 유사한 딥러닝 라이브러리이다. 
페이스북 인공지능 연구팀에 의해 주로 개발되어 왔다. 
텐서플로우 2.0 이후 자유로운 네트워크 수정의 난이도가 점점 높아져, 최근 연구원들 사이에서는 PyTorch의 사용 비중이 높아지고 있다. 
```

### 1. Pytorch의 장점
- 익히기 쉽고 간결하며 구현이 빠르게 됨
- 비교적 빠른 최적화가 가능함
- 그래프를 만들면서 동시에 값을 할당하는 define by run 방식으로 코드를 깔끔하게 작성할 수 있음

### 2. Pytorch의 단점
- 텐서플로우에 비해 학습에 필요한 예제를 구하기 쉽지 않음
- 텐서플로우보다 디테일한 모델링이 불가능함

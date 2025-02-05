# :point_up: OSS 저작권

* 오픈소스 SW는 핵심 기술인 소스코드가 공개되어 있지만 *저작권과 라이선스 규칙이 있으며 이를 어기면 법적 책임도 져야한다.*
* 보안이나 사용성을 위해서 소스를 소수에게 공개했으나 원본이나 수정본의 재배포를 금지한 경우는 오픈소스가 아니다.

***

<br>

![3](https://user-images.githubusercontent.com/112846188/201647455-090a65ee-e5c4-48c1-9013-3a8a000c2875.png)

## :point_right: OSI (Open Source Initiative)
* 오픈소스 sw의 활성화와 인증을 담당
* **10개의 항목**으로 된 기준을 정의함
1. 자유 배포(Free Redistribution)
2. 소스코드 공개(Source Code Open)
3. 2차적 저작물(Derived Works) (허용)
4. 소스코드 수정 제한(Integrity of The Author's Source Code)
5. 개인이나 단체에 대한 차별 금지 (No Discrimination Against Persons or Groups)
6. 사용 분야에 대한 제한 금지 (No Discrimination Against Fields of Endeavor)
7. 라이선스의 배포 (Distribution of License)
8. 라이선스 적용상의 동일성 유지 (License must not be specific to a product)
9. 다른 라이선스의 포괄적 수용 (License must not contaminate other software)
10. 라이선스의 기술적 중립성 (License must be Technology-Neutral)
* 인정되는거에는 OSI 인정 마크가 부여됨

***

## :point_right: 대표적인 오픈소스 라이센스 종류
![1](https://user-images.githubusercontent.com/112846188/201646835-fe9b6085-c788-44a1-b143-07d1f2356ed7.png)

***

### :+1: GPL
* 가장 많은 오픈소스SW가 채택하고 있는 라이선스 (리눅스)
* GPL은 다른 오픈소스SW 라이선스에 비해 의무사항이 엄격

![image](https://user-images.githubusercontent.com/112846188/201648798-8d3998e1-0cfd-478b-a774-8c26752a9961.png)

### :+1: GPL 2.0
* SW를 배포하는 경우 저작권 표시, 보증책임이 없다는 표시 및 GPL에 의해 배포된다는 사실을 명시
* SW를 수정하거나 새로운 소프트웨어를 링크(정적 및 동적 링크 모두)하는 경우 GPL에 의해 소스코드를 제공해야 함
* Object Code 또는 실행 파일 형태로 GPL 소프트웨어를 배포하는 경우, 소스코드 그 자체를 함께 배포하거나 또는 소스코드를 제공받을 수 있는 방법에 대한 정보를 함께 제공해야 함
* 자신의 특허를 구현한 프로그램을 GPL로 배포하는 경우에는 그 프로그램을 GPL 조건에 따라 특허에 대한 사용료를 받을 수 없음

### :+1: GPL 3.0 
* GPL 3.0의 소스코드를 특정한 제품에 포함시키거나 혹은 그와 함께 배포하는 경우에는 해당 소스에 설치 정보를 함께 제공해야 함.
다만 소프트웨어가 롬(ROM)에 설치된 경우는 제외
* DRM과 관련하여 각국의 법률에 의해 보호되는 이익을 포기해야 함
* 특허와 관련해 원래의 소스코드를 개선하여 배포한 기여자의 경우 자신이 기여한 부분에 대해서는 비차별적이고, 특허 사용료가 없다는 내용의 라이선스를 제공해야 함
* 특허 소송을 제기할 경우 소송을 제기한 날에 소송을 제기한 라이선시의 오픈소스 SW 라이선스는 종료됨
* Apache License 2.0 및 Affero GPL과 양립 가능함
<br>

*:pray:<GPL 저작권 표시와 의무사항>:pray:*   
"본 제품은 GPL 라이선스 하에 배포되는 SW인 (사용한 GPL SW 이름)을 포함합니다"
위의 문구를 매뉴얼 혹은 그에 준하는 매체에포함시키고, GPL 전문을 첨부해야 함

***

### :+1: LGPL
* FSF가 GPL보다 소스코드 공개 정도를 다소 완화된 형태로
사용할 수 있도록 만든 라이선스로 기업에게 오픈소스SW를 장려하기 위해 만든 라이선스
<br>

![image](https://user-images.githubusercontent.com/112846188/201649506-dfe0159d-f4ab-48c3-81a1-08ab820395da.png)

* SW를 배포하는 경우 저작권 표시, 보증책임이 없다는 표시 및 LGPL에 의해 배포된다는 사실을 명시
* LGPL라이브러리의 일부를 수정하는 경우 수정한 라이브러리의 소스코드 공개
* 라이브러리에 응용프로그램을 링크할(정적 및 동적 링크 모두) 경우 해당 응용프로그램의 소스를 공개할 필요 없음.
다만 사용자가 라이브러리 수정 후 동일한 실행 파일을 생성할 수 있도록 정적 링크시에는 응용프로그램의 오브젝트 코드를 제공해야 함
* 특허의 경우 GPL과 동일

***

### :+1: BSD
* 소프트웨어의 소스코드를 공개하지 않아도 되는 오픈소스SW 라이선스
* 누구라도 BSD기반 소스코드를 이용하여 새로운 프로그램을 개발, 소스코드를 공개하지 않고 판매 가능
<br>

![image](https://user-images.githubusercontent.com/112846188/201649658-3565c644-df6d-47eb-967d-df6724a50cb1.png)

* 소프트웨어를 배포하는 경우 저작권 표시, 보증책임이 없다는 내용을 표시
* 수정 프로그램에 대한 소스코드 공개를 요구하지 않기 때문에 상용 소프트웨어에 무제한 사용가능
* 프로그램을 바이너리 형태로 재배포하고자 할 경우 소스코드를 배포하는 경우와 마찬가지로 배포판과 함께 제공되는 문서 또는 
그 밖의 매체에 저작권 표시와 함께 면책조항을 유지하여야 함

***

### :+1: Apache 
* 아파치 라이선스는 아파치 웹서버를 포함한 아파치 재단(ASF : Apache Software Foundation)의 모든 SW에 적용되는 라이선스
* BSD 라이선스와 비슷하여 소스코드공개 등의 의무가 발생하지 않음
* GPL 2.0과는 결합이 어렵지만 GPL 3.0과는 가능
<br>

![image](https://user-images.githubusercontent.com/112846188/201649742-49cdac1d-8587-4e30-9994-1769040e6706.png)

* "Apache"라는 이름에 대한 상표권을 침해하지 않아야 함
* SW를 배포하는 경우 저작권 표시, 보증책임이 없다는 내용을 표시
* 수정프로그램에 대한 소스코드의 공개를 요구하지 않기 때문에 상용 SW에 무제한 사용가능

***

### :+1: MPL
* Netscape 브라우저의 소스코드를 공개하기 위해 개발된 라이선스
* 공개하여야 할 소스코드의 범위가 GPL에 비해 훨씬 명확
<br>

![image](https://user-images.githubusercontent.com/112846188/201649977-4c469c8a-a2c9-4d5f-a49c-4621b6da0873.png)

* SW를 배포하는 경우 저작권 표시, 보증책임이 없다는 표시 및 MPL에 의해 배포된다는 사실을 명시
* MPL 코드를 수정한 부분은 다시 MPL에 의해 배포
* MPL코드와 다른 코드를 결합하여 프로그램을 만들 경우 MPL코드를 제외한 결합 프로그램에 대한 소스코드는 공개할 필요가 없음
* 소스코드를 적절한 형태로 제공하는 경우, 실행파일에 대한 라이선스는 MPL이 아닌 다른 것으로 선택가능
* 특허기술이 구현된 프로그램의 경우 관련 사실을 'LEGAL'파일에 기록하여 배포

***

### :+1: MIT
* 미국 MIT에서 해당 대학 소프트웨어 공학도를 돕기 위해서 개발된 라이선스로 저작권 관련 명시만 지키면 되는 라이선스

![image](https://user-images.githubusercontent.com/112846188/201650643-1c68109b-2438-4ccc-91c4-a2a314735df7.png)

* 소프트웨어를 누구라도 무상으로 제한없이 취급해도 됨
* 저자 또는 저작권자는 소프트웨어 관하여 아무런 책임을 지지 않음

***

### :+1: 요약 정리
![2](https://user-images.githubusercontent.com/112846188/201646914-a449cdbb-5930-4b20-8f8d-b8dc31531a28.png)

***

### :+1: 라이선스 비교 되어있는 사이트
* 오픈소스SW 라이선스 종합정보시스템

https://www.olis.or.kr/license/compareGuide.do

***

### :+1: 오픈소스 라이선스 표기법

* 특별히 정해진 사항은 없으나 대부분의 기업에서 표기한 사항을 살펴보았을 때   
*이름-사이트주소-저작권자-라이선스* 로 별도 페이지를 이용하여 작성함
* 오픈소스로 재배포하는 경우 프로젝트의 NOTICE 문서나 서드파티 관련 메뉴에서 저작권과 라이선스 정보 표기

***

#### 참고
https://changun516.tistory.com/110
http://kossa.kr/materials/KSH/ot/7.%20OSS%EB%9D%BC%EC%9D%B4%EC%84%A0%EC%8A%A4%20%EC%9D%B4%ED%95%B4%EC%99%80%20%EA%B4%80%EB%A6%AC.pdf

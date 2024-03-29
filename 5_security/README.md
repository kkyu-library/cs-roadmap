## 5. 외워서 끝내는 SSL과 최소한의 암호기술

### 섹션 0. 강의소개 및 수강조건

#### 교욱목표

- Hash, Checksum에 대해 이해한다.
- 대칭키, 비대칭키 차이를 이해한다.
- PKI 기술의 원리를 이해한다.
- HTTPS의 작동원리를 이해한다.
- SSL 인증서 검증방법을 이해한다.

### 섹션 1. 기초이론

#### 이름 궁합과 Checksum

###### Checksum(검사합)

- 데이터의 오류 여부 홧인 방법으로 널리 사용된다.
- 일정 자릿수를 정하고 범위를 넘는 자리 올림은 버려서 자릿수를 유지한다.

#### Hash에 대해 외울 것들

###### Hash 함수의 특징

- 단방향성
- 입력값의 크기와 상관없이 결과갑의 길이(혹은 크기)가 일정
- 데이터 무결성 확보와 관련해 IT기술 전반에서 사용된다.

###### 대표적인 Hash 기술 활용 예

- 무결성 확보
    - 인증서 검증
    - 디지털 포렌식
    - 디지털 서명 (Hash + PKI)
- 패스워드 단방향 암호화
- 블록체인

### 섹션 2. 암호기술에 대한 이해

#### 매우 쉽게 외우는 대칭키 시스템

- 키 하나로 암호화/복호화를 모두 수행하는 방식
- 비대칭키 방식에 비해 효율적이다.
- DES, 3DES, SEED-128, ARIA, AES-128, AES-256 알고리즘잉 유명하다.

#### 외워서 끝내는 비대칭키 시스템

- 한 쌍의 키가 서로 상호작용하는 구조를 갖는다.
- 두 키 중 하나로 암호화 하면 쌍을 이루는 다른 키로 복호화 한다.
- 보통 Public Key와 Private key으로 구분하며 PKI(Public Key Infrastructure) 기술의 근간을 이룬다.
- PSA-2048, ECC 알고리즘이 있다.

#### 디지털 서명이란?

### 섹션 3. PKI 시스템과 인터넷

#### 인터넷을 위한 비대칭키 체계

#### 효율 극대화를 위한 혼합 활용

#### 비대칭키 체계의 문제점

#### 공개키 신뢰를 위한 검증체계

#### 웹 서비스와 공인인증서


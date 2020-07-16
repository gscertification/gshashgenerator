# gshashgenerator 
GS Hash Generator는 TTA의 GS인증에서 사용할 목적으로 개발된 프로그램입니다. 

GS Hash Generator는 GNU 라이센스를 사용합니다. 

## 1. GS Hash Generater

## 2. 프로그램 구동 환경
 - 지원 운영체제 : Microsoft Windows 10 (64bit) 
 - 권장 메모리: 8GB 이상

## 3. GS Hash Generater 설치하기 

### 3.1. Python 설치
GS Hash Generater는 파이썬 기반으로 Python을 설치해야 합니다.  

* Python 웹 사이트 주소 : https://www.python.org/
* 권장 파이썬 설치 버전 : Python 3.7.0 (64bit) 이상
   * 파이썬 32bit 환경은 지원하지 않습니다. 
    
### 3.2. GS Hash Generater 다운로드
'Code' 버튼 클릭 > 'Download ZIP' 버튼을 클릭하여 프로그램을 다운로드 받습니다.

### 3.3. GS Hash Generater 설치
다운로드 받은 파일의 압축을 풀면 설치가 완료 됩니다. 

## 4. GS Hash Generater 실행하기

## 5. GS 인증 Hash 실행 가이드

### 5.1 해시 대상 파일 구성

Hash 대상 파일은 아래와 같습니다.
 1. 소스코드 파일 
 2. 실행 프로그램 파일
   * 실행 프로그램 파일은 시험품 제출 형상과 동일하게 구성 (매뉴얼은 포함하지 않습니다.)
 
소스코드 파일과 실행 프로그램 파일은 각각 다른 디렉토리로 구성하셔야 합니다. 
 
 예) 디렉토리 구성의 예    
``` 
  GS-A-20-000
      |--- 우리제품 v1.0(소스코드)
      |--- 우리제품 v1.0
```

### 5.2 GS Hash Generator 실행
GS Hash Generater 수행 시, 소스코드 및 실행 프로그램의 상위 디렉토리를 지정하여 Hash 파일을 생성합니다.  
 예) 

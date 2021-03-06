## 1. GS Hash Generater
GS Hash Generator는 디렉토리내에 있는 파일의 Hash 값을 일괄적으로 추출하는 프로그램입니다.    

사용하는 해시 알고리즘은 SHA-256 입니다.  

## 2. 프로그램 구동 환경
 - 지원 운영체제 : `Microsoft Windows 10 (64bit)` 
 - 권장 메모리 : `8GB 이상` 

## 3. GS Hash Generater 설치하기 

### 3.1. Python 설치
GS Hash Generater는 파이썬 기반으로 Python을 설치해야 합니다.  

* Python 웹 사이트 주소 : https://www.python.org/
* 권장 파이썬 설치 버전 : `Python 3.7.0 (64bit) 이상`
   * 파이썬 32bit 환경은 지원하지 않습니다.  
* Python 3.7.8 다운로드 링크 : https://www.python.org/ftp/python/3.7.8/python-3.7.8-amd64.exe 
    
### 3.2. GS Hash Generater 다운로드 
1. GitHub 페이지( https://github.com/gscertification/gshashgenerator )로 접속합니다. 
2. `Code` 버튼을 클릭합니다. 
3. `Download ZIP` 버튼을 클릭하여 프로그램을 다운로드 받습니다.

### 3.3. GS Hash Generater 설치
다운로드 받은 파일의 압축을 풀면 설치가 완료됩니다. 

## 4. GS Hash Generater 실행하기
gshashgenerator 디렉토리로 이동하여 `gshashgenerator.bat` 파일을 실행합니다. 

## 5. GS인증 산출물에 대한 Hash 추출 가이드

### 5.1. Hash 대상 파일 구성

Hash 값 추출 대상은 아래와 같습니다. 
```
 1. 시험 대상 제품의 소스코드 파일
 2. 시험 대상 제품의 실행 프로그램 파일
   * 실행 프로그램 파일은 시험품 제출 형상과 동일하게 구성 (매뉴얼은 포함하지 않습니다.)
```
 
소스코드 파일과 실행 프로그램 파일은 각각 다른 디렉토리로 구성하고, 두개의 디렉토리를 포함하는 상위 디렉토리를 생성합니다.  
 
 예) 디렉토리 구성의 예    
``` 
  GS-A-20-000
      |--- 우리제품 v1.0(소스코드)
      |--- 우리제품 v1.0

- 소스코드는 '우리제품 v1.0(소스코드)' 디렉토리를 생성하여 저장함
- 실행 프로그램 파일은 '우리제품 v1.0' 디렉토리를 생성하여 저장함    
- 위 두개의 디렉토리를 포함하는 상위 디렉토리(GS-A-20-000)를 생성함
```

### 5.2. GS Hash Generator 실행
GS Hash Generater 수행 시, 소스코드 및 실행 프로그램 디렉토리의 상위 디렉토리를 지정하여 Hash 파일을 생성합니다.  

예) Hash 대상 디렉토리 선택 예 
```
추가하기
```

## 6. 트러블슈팅 가이드

### 6.1. 프로그램을 실행하면 () 오류가 발생합니다.

## 7. 라이센스 
GS Hash Generator는 `GNU` 라이센스를 사용합니다. 




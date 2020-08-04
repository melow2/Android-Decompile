# Android-Decompile
안드로이드 디컴파일

1. 디컴파일 대상이 되는 apk파일 준비.
2. apktool 다운로드.
```
https://ibotpeaches.github.io/Apktool/install/
```
3. JD-GUI 다운로드
```
http://java-decompiler.github.io/
```
4. dex2jar 다운로드
```
https://sourceforge.net/projects/dex2jar/
```
5. 환경변수 설정
* 시스템 환경변수에 apktool의 경로를 추가한다.
* 본인은 현재까지 다운로드 받은 모든 파일을 아래 경로에 저장하였음.
```
D:\reference\decompile\
```
6. apktool d memoapp.apk
* 위 명령어로 manifest와 resource파일을 확인할 수 있다.

7. apk파일을 dex2jar 폴더에 복사한다.
* 파일을 복사 한뒤 아래 명령어로 jar파일을 생성한다.
```
.\d2j-dex2jar.bat .\memoapp.apk
```

8. 생성된 jar파일을 JD-GUI로 확인한다.



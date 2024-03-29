
[GREEN 플레이 해보기](https://webmsx.org/?ROM=https://github.com/pdpdds/ubox_example/releases/download/v1.0/green.rom)

## 2.2 WSL2
WSL2 자동 설치 내용을 참고해서 WSL2를 설치한다.   
자동 설치가 잘되지 않을 때 수동 설치를 시도해 본다.   

* [WSL2 자동 설치](https://learn.microsoft.com/ko-kr/windows/wsl/install)
* [WSL2 수동 설치](https://docs.microsoft.com/ko-kr/windows/wsl/install-manual)

만약 수동으로 설치 방법으로 진행했다면 5단계까지 정상적으로 인스톨을 진행해야 한다. 

## 2.4 빌드 시스템 구축
WSL Manager의 경우 업데이트가 중지된 상태이며 특정 머신에서 정상 실행되지 않는 경우가 있다.   
이 경우에는 책에서 설명한 것처럼, 먼저 수동으로 배포판을 설치한다.   
그런다음 아래의 툴을 다운받아 활용하자.
링크에 접속한 다음 릴리즈 탭에서 최신 버전을 다운받는다.

[WSL Distro Manager](https://github.com/bostrot/wsl2-distro-manager)

툴을 실행하면 WSL에 설치된 리눅스 배포판들을 확인할 수 있다.  
WSL Manager와 마찬가지로 특정 배포판의 설치가 가능하며  
특정 리눅스 배포판을 바로 실행할 수 있다.

## 2.5 소스코드 설치  
예제코드는 책에서 언급했듯이 WSL상에서 다운받거나 압축파일로 다운받도록 한다.   
윈도우용 깃허브 프로그램을 사용해서 소스코드를 다운받으면   
다운받는 과정에서 파이썬 스크립트의 개행문자를 \n에서 \r\n으로 변경하는 현상이 발생하여  
빌드과정에서 문제를 일으키기 때문이다.    

* 2023년 1월 2일 현재, 개행문자에 관계없이 빌드가 가능하도록 수정했으나  
테스트가 필요하다.   

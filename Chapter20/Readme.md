# 20 SDL + HX DOS 익스텐더
* [HX DOS Extender](https://www.japheth.de/HX.html)  

## 20.2 환경구축
* [HX DOS Extender 다운로드](https://sourceforge.net/projects/hx-dos/files/)  
* [SDL 1.2 다운로드](https://sourceforge.net/projects/libsdl/files/SDL/1.2.15)  

## 20.3 샘플 프로젝트
* [샘플 프로젝트 다운로드](https://github.com/pdpdds/hxdos-sdl-example)

### 샘플 프로젝트 원본 링크
* [팩맨#1](https://sourceforge.net/projects/pacmanincwithsd)  
* [팩맨#2](https://github.com/Ahmed310/PacMan)  

## 20.4 GREEN 프로젝트
### PCEM 테스트  
[![PCEM 테스트](https://img.youtube.com/vi/Kx5M5g9e66A/0.jpg)](https://www.youtube.com/watch?v=Kx5M5g9e66A)

### 펜티엄3, 프리도스 테스트
도스박물관 카페 회원이신 윤슈님께서   
GREEN 프로젝트의 도스 실기 테스트를 진행해 주셨습니다.   
펜티엄3, 프리도스 환경에서 진행했습니다.

[![도스 실기 테스트](https://img.youtube.com/vi/EeggC8leCfI/0.jpg)](https://www.youtube.com/watch?v=EeggC8leCfI)

## 레퍼런스
아래 링크에서 소개하는 SDL 1.2 게임 프로젝트는  
SDL 1.2로 작성된 프로그램에 생명력을 부여하기 위해
진행중인 프로젝트입니다.   
SDL 1.2로 작성된 게임 프로젝트의 경우 여러가지 이유로   
SDL 2.0으로 마이그레이션 하는 경우가 많습니다.  
하지만 SDL 2.0으로 마이그레이션하는 비용은 많많치 않은 작업입니다.  
그래서 게임 프로젝트를 수정하지 않고 SDL 1.2 API 래퍼를  만들어서 내부적으로 SDL 2.0 API를 호출하게끔  
수정을 했습니다.   
게임 소스코드 자체는 SDL 1.2로 작성되어 있는 만큼   
약간 수정을 해서 빌드를 하면 도스에서도 동작가능할 수 있으니 살펴보시기 바랍니다.   
* [SDL 1.2 게임 프로젝트](https://github.com/pdpdds/sdldualsystem)  

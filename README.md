# cocos2d-x Cafe SDK 

> 본 저장소는 Cafe SDK를 사용하기위한 library 및 관련 파일들을 포함하고 있습니다.

Cafe SDK에 대하여 자세히 알고싶으시면 [네이버 CafeSDK 공식카페](http://cafe.naver.com/navercafesdk)를 참조해 주세요.

![Overviw](/guide/images/widget_screenshot.gif)

v.1.7.2
-------------
####updated
1. 동영상 녹화 시 권한 획득을 위해 얼럿 창을 띄웁니다. (구글 피처드)


####fixed
1. 세로모드 배너 사이즈 늘어나 보이던 이슈 수정
2. 기타 버그 수정


v.1.7.0
-------------
####updated
1. 위젯을 통하여 동영상 녹확 기능을 제공합니다.
2. 콜백 API 개선 (투표 완료 콜백을 제공합니다)

폴더 구조
-------------

file      | 설명 		
---			| ---		
guide/			| 가이드 문서 및 CafeSDK 설명
lib/		 	| CafeSDK Android, iOS 라이브러리 파일
sample/Classes/plugincafe/platform/ios | iOS Plugin
sample/Classes/plugincafe/platform/android | Android Plugin
sample/proj.ios_mac		| iOS 샘플
sample/proj.android		| Android 샘플
LICENSE     | 라이선스 파일
README.md   | readme 파일


의존 라이브러리 iOS
-------------

1. [네이버 아이디 로그인-4.0.7](https://nid.naver.com/devcenter/docs.nhn?menu=IOS)
2. [AFNetworking](https://github.com/AFNetworking/AFNetworking)(UIImageView+AFNetworking)
<br>1.x ~ 2.x 모두 사용 가능하며 2.6.3에서 테스트 진행했습니다.


의존 라이브러리 Android
-------------

1. [네이버 아이디 로그인](https://nid.naver.com/devcenter/docs.nhn?menu=Android)
2. android support library v4
3. [naver volleyer](http://mvnrepository.com/artifact/com.navercorp.volleyextensions/volleyer)   (2.0.1 사용 중)
4. [volley](http://mvnrepository.com/artifact/com.mcxiaoke.volley/library/) (1.0.2사용 중)
5. [google gson](http://mvnrepository.com/artifact/com.google.code.gson/gson)  (2.3.1 사용 중)
6. [glide](http://mvnrepository.com/artifact/com.github.bumptech.glide/glide)  (3.6.1 사용 중)
7. [otto](http://mvnrepository.com/artifact/com.squareup/otto)  (1.3.8 사용 중)

라이선스
-------------
NAVER Cafe SDK for cocos2dx

Copyright 2016 NAVER Corp.
All rights reserved.

Unauthorized use, modification and redistribution of this software are strongly prohibited.

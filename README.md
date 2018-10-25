# HLSL-Development-Cookbook
http://www.acornpub.co.kr/book/hlsl-cookbook 에서 다운로드 받은 HLSL Development Cookbook 도서의 소스 코드를 VC++ 2008 에서 빌드할 수 있도록 수정하는 프로젝트입니다.

http://www.acornpub.co.kr/book/hlsl-cookbook 에서 다운로드 받은 HLSL Development Cookbook 도서의 소스 코드는 VC++ 2010 에서 빌드할 수 있도록 개발된 것 같고 VC++ 2008 에서 빌드하려면 빌드 환경을 다시 구성해야 하므로 VC++ 2008 에서 빌드할 수 있도록 빌드 환경을 다시 구성하는 프로젝트를 시작하게 되었습니다.

수작업으로 VC++ 2008 솔루션 및 프로젝트를 생성하고 빌드 환경을 구성하는 것은 다소 번거로움이 있어서 소스 코드 폴더를 지정하면 해당 소스 코드 폴더에 VC++ 2008 술루션 파일 및 프로젝트 파일을 자동으로 생성하고 빌드 환경을 구성해 주는 CreateVC2008Project 프로그램을 개발하였습니다. CreateVC2008Project 프로그램의 소스 코드는 CreateVC2008Project 폴더를 참고하세요.

본 프로젝트의 소스 코드를 빌드하려면 DirectX SDK(June 2010) 이 설치되어 있어야 하고 DirectX SDK(June 2010) 의 기본 설치 폴더인 "C:\Program Files (x86)\Microsoft DirectX SDK (June 2010)" 폴더에 설치되어 있어야 합니다. 또한 VC++ 2008 이 설치되어 있어야 합니다.

본 프로젝트를 진행하는 개발자 정보는 다음과 같습니다.

* 개발자 블로그: http://blog.naver.com/websearch

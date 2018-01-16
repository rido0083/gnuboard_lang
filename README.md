/*****************************************************************************************

프로젝트명 : 그누보드 다국어 플러그인 (SRD_LANG)

개발자 : Rido (rido0083@gmail.com)

개발목적 : 그누보드에 다국어를 사용할 수 있는 확장 프로그램제작 

버전 : 0.01 (테스트 버전)

*****************************************************************************************/

사용방법 : 해당 파일을 다운로드 후 모든 파일을 설치된 그누보드에 덮어서 사용

해당 플로그인에 필요한 Database는 자동생성된다.

자동생성되지 않는경우 아래 해당 sql문을 실행 생성해 준다.

[구누접두어_] 의 경우 그누보드 설치시 사용한 접두어를 입력해 준다. 

---------------------------------------------------------------

      CREATE TABLE `구누접두어_srd_lang` (
      `id` int(16) NOT NULL,
      `include` varchar(255) NOT NULL,
      `lang` char(10) NOT NULL,
      `tokey` text NOT NULL,
      `getval` text NOT NULL
      ) ENGINE=MyISAM DEFAULT CHARSET=utf8;		
	";

---------------------------------------------------------------


라이센스는 그누보드의 LGPL를 그대로 따른다.

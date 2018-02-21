## Compute > Release Notes

### 2018.02.22

#### 기능 개선

* Windows 2012 R2 Standard 이미지 업데이트
	* 이미지 정보
		* Name : Windows 2012R2std
		* Language : KO
		* Description : Windows 2012 R2 STD (2018.02.22)
	* Windows Time Zone 설정 변경
		* 동기화 주기 변경 : [기존) 604800초 (7일) -> [변경] 256초
		* Time Zone Peer 도메인 변경 : [기존] 1.kr.pool.ntp.org , 1.pool.ntp.org -> [변경] 1.pool.ntp.org , time.windows.com
	* MS 2018.02.13 Windows Update 적용
		* https://support.microsoft.com/ko-kr/help/4074594/windows-81-update-kb-4074594
	
* Ubuntu Linux 14.04 이미지 업데이트
	* 이미지 정보
		* Name : Ubuntu 14.04
		* Description : Ubuntu Linux 14.04.5 (2018.02.22)
	* 취약점 패치를 위한 관련 커널 업데이트
		* Linux Kernel Version : [기존] 3.13.0-32 --> [변경] 3.13.0-141
		* Variant 1 (CVE-2017-5753) - patched
		* Variant 3 (CVE-2017-5754) - patched
		
* Debian Linux 8.2 이미지 업데이트
	* 이미지 정보
		* Name : Debian Linux 8.2.0
		* Description : Debian Linux 8.2.0 (2018.02.22)
	* 호스트명 설정 변경
		* 인스턴스 생성시 지정한 이름으로 호스트명 적용되도록 수정
		* [기존] localhost-192.168.0.x -> [변경] 콘솔에서 지정한 이름
	* 취약점 패치를 위한 관련 커널 업데이트
		* Linux Kernel Version : [기존] 3.16.0-4 --> [변경] 3.16.0-5
		* Variant 3 (CVE-2017-5754) - patched

* CentOS Linux 6.5 이미지 업데이트
	* 이미지 정보
		* Name : CentOS Linux 6.5
		* Description : CentOS Linux 6.5 (2018.02.22)
	* 호스트명 설정 변경
		* 인스턴스 생성시 지정한 이름으로 호스트명 적용되도록 수정
		* [기존] localhost-192.168.0.x -> [변경] 콘솔에서 지정한 이름
	* 취약점 패치를 위한 관련 커널 업데이트
		* Linux Kernel Version : [기존] 2.6.32-431 --> [변경] 2.6.32-696.20.1
		* Variant 1 (CVE-2017-5753) - patched
		* Variant 3 (CVE-2017-5754) - patched

* CentOS Linux 7.1 이미지 업데이트
	* 이미지 정보
		* Name : CentOS Linux 7.1
		* Description : CentOS Linux 7.1 (2018.02.22)
	* 호스트명 설정 변경
		* 인스턴스 생성시 지정한 이름으로 호스트명 적용되도록 수정
		* [기존] localhost-192.168.0.x -> [변경] 콘솔에서 지정한 이름
	* Firewall daemon default 값 변경
		* 인스턴스 부팅시 Firewall daemon 자동 시작되지 않도록 설정 변경
	* Swap Disk Mount 설정 변경
		* 신규 인스턴스 생성시 swap 파티션 자동 마운트되도록 설정 변경
	* 취약점 패치를 위한 관련 커널 업데이트
		* Linux Kernel Version : [기존] 3.10.0-229.20.1 --> [변경] 3.10.0-693.17.1
		* Variant 1 (CVE-2017-5753) - patched
		* Variant 3 (CVE-2017-5754) - patched

* CentOS Linux 6.5 with MySQL 5.6.38 신규 이미지 업데이트
	* 이미지 정보
		* Name : CentOS Linux 6.5
		* Description : CentOS Linux 6.5 with MySQL 5.6.38 (2018.02.22)
	* MySQL 5.6.38 패키지 설치됨
	* 그외 설정은 CentOS Linux 6.5 이미지와 동일함

* CentOS Linux 6.5 with MySQL 5.7.20 신규 이미지 업데이트
	* 이미지 정보
		* Name : CentOS Linux 6.5
		* Description : CentOS Linux 6.5 with MySQL 5.7.20 (2018.02.22)
	* MySQL 5.7.20 패키지 설치됨
	* 그외 설정은 CentOS Linux 6.5 이미지와 동일함

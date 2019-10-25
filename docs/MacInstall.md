# 스나이퍼 Mac 버전 설치하기

### 1. TunTapOsX 설치하기

스나이퍼 Mac 베타 버전을 이용하기 위해서는 TunTapOsX를 먼저 설치해야 합니다.

> [TunTapOsX 다운로드](https://sourceforge.net/projects/tuntaposx/files/tuntap/20150118/tuntap_20150118.tar.gz)

###### :warning:다음과 같이 TunTapOsX가 설치되지 않을 경우, 보안센터에서 TuntapOsX를 허용해준 다음에 시스템을 재시작하면 설치됩니다.
![TunTap](https://user-images.githubusercontent.com/53137855/62031804-28d29680-b223-11e9-9dab-bbdb1a95776d.png)



### 2. Sniper 설치하기

> [다운로드 ](https://github.com/sniper-internet/Sniper-desktop-release/releases/download/v0.0.36/Sniper-0.0.36.dmg)

<br>

### 문제해결

현재 어플리케이션 업데이트에 문제가 있어 새 버전 업데이트가 있을 경우 기존 버전 삭제 후 이 페이지에서 다시 다운로드 받아 설치해주시기 바랍니다. 빠른 시일 내로 앱스토어에 등록하여 편리하게 사용할 수 있도록 노력하겠습니다!

<br>

![DMG_Error](https://github.com/sniper-internet/Sniper-desktop-release/blob/master/images/DMG%20Error%201.png)

아직 베타 버전이라 앱스토어에 출시가 되지 않아 발생하는 문제입니다.<br/>
터미널에 아래 명령어를 입력한후에 다시 진행해 주시기 바랍니다.

1. 터미널(Terminal) 앱을 연다
2. 아래 명령어를 입력한다
> `sudo spctl --master-disable`
3. 컴퓨터 비밀번호를 입력한다.

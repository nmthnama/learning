# 1 docker 설치
## 1) windows
### i) windows 10 pro 이상
> [docker_desktop_for_windows](https://docs.docker.com/docker-for-windows/install/)
### ii) windows 10 home 이하
> [docker_toolbox_for_windows(legacy)](https://docs.docker.com/toolbox/toolbox_install_windows/)

## 2) Linux
> 모름


# 2 nodejs, mysql 환경 설정
## 1) docker quickstart terminal 실행
### +) install troubleshooting 
> - VBoxManage.exe: error: Details: code E_FAIL (0x80004005)
>   * VirtualBox 버전 확인 후 remove&reboot<br>
>   * 확인한 VirtualBox 버전 download<br>
>   * 아래 명령어 사용하여 virtualbox reinstall<br>
>     + c:\downloads\VirtualBox-5.0.11-104101-Win.exe -msiparams NETWORKTYPE=NDIS5
## 2) nodejs 이미지 pull
> $docker pull node
## 3) mysql 이미지 pull
> $docker pull mysql
## 4) 설치한 이미지 확인
> $docker images

## n) nodejs 컨테이너에서 mysql-client 설치
> #sudo apt-get update && sudo apt-get dist-upgrade <br>
> #sudo apt-get install mysql-client <br>

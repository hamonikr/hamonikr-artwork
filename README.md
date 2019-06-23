# HamoniKR Artwork

하모니카 리눅스에서 사용되는 배경이미지, 아이콘, 소리 등의 리소스와 관련 설정파일들을 포함하고 있는 패키지

Maintainer: Kevin Kim <root@hamonikr.org>

# Install

```
$ wget -O - http://apt.hamonikr.org/hamonikr.key | sudo apt-key add -

$ echo "deb https://apt.hamonikr.org me main upstream" | sudo tee -a /etc/apt/sources.list.d/hamonikr.list

$ sudo apt update

$ sudo apt install hamonikr-artwork
```

# Build

데비안 패키지를 생성하기 위하여 아래와 같이 명령을 실행하면 생성됩니다.

```
$ apt build
```

# License

GPL-3+

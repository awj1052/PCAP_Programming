# PCAP_Programming

C 기반 PCAP API를 활용하여 PACKET의 정보를 출력하는 프로그램

## Compile

```
gcc -o assignment assignment.c -lpcap
```

## Execution

```
sudo ./assignment
```

## Library

이 프로그램을 실행하려면 `libpcap` 라이브러리가 필요합니다. 설치되지 않은 경우 다음 명령어로 설치할 수 있습니다:

**Ubuntu/Debian:**

```
sudo apt update && sudo apt install libpcap-dev
```

**CentOS/RHEL:**

```
sudo yum install libpcap-devel
```

**MacOS (Homebrew):**

```
brew install libpcap
```


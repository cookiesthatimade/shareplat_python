
# sharePlat python version
### sharePlat_py는 React로 만들어진 sharePlat([원본](https://gitlab.com/sunnyfactory2/shareplat))을 Flask를 사용하여 재구성하였습니다.

<br>

### Installation 📦


### sharePlat을 설치하려면 다음과 같은 과정을 참고하세요.

## 1. 레포지토리 클론 :
```
'https://github.com/sunnyfactory2/shareplat_py'
```


## 2. 가상환경 생성 :
```
  python3 -m venv env
```


## 3. 가상환경 진입 :
```
  source env/bin/activate
```


## 4. 패키지 설치 :
```
  pip install -r requirements.txt
```


## 5. 로컬 실행 -> Go to localhost:5000
```
  cd/app
  python3 main.py 
```
## 5-1. 서버 실행 ->  Go to www.shareplat.com
flask 백그라운드 실행 커맨드
```
  sudo nohup python3 main.py &
```
PID값 확인 커맨드
```
  ps -ef | grep main.py
```
백그라운드 종료 커맨드
```
  sudo kill -9 PID값
```

<br>

### Reconstructed by Seongha Kim and Seongwook Kim.

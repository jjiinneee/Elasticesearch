# Elasticesearch 설치방법


#### Homebrew로 설치하려면, elasic/tap 저장소에 탭(Tap) 해야 한다. <br/>
#### 그리고, eleasticsearch를 인스톨한다.

#### $ brew tap elastic/tap
#### $ brew install elastic/tap/elasticsearch-full

<img width="1280" alt="스크린샷 2022-09-30 오후 3 35 13" src="https://user-images.githubusercontent.com/67133692/193205988-9902598c-a48a-40a7-bbb5-e2f17826dcd9.png">

#### 위처럼 뜨면 성공!




## 실행
#### $ elasticsearch
#### elasticsearch 는 기본적으로 9200 포트를 갖는다.
<img width="853" alt="스크린샷 2022-09-30 오후 3 37 28" src="https://user-images.githubusercontent.com/67133692/193206255-0287ee07-467e-477b-8c8f-4b6a9e282a62.png">


## 디렉토리 구조
#### homebrew를 이용하여 설치를 하게 되면 아래와 같은 디렉토리 구조를 갖게 된다.

### ▪︎ home : elasticsearch의 홈 디렉토리
#### /usr/local/var/homebrew/linked/elasticsearch-full

### ▪︎ bin : elasticsearch의 바이너리가 존재하는 곳
#### /usr/local/var/homebrew/linked/elasticsearch-full/bin

### ▪︎ conf : elasticsearch.yml 파일이 존재하는 곳으로, 설정 파일이 존재
#### /usr/local/etc/elasticsearch

### ▪︎ data : elasticsearch의 데이터 파일이 존재하는 디렉토리 / 만약 경로를 변경하려면 path.data를 수정한다.
#### /usr/local/var/lib/elasticsearch

### ▪︎ logs : 로그파일이 존재하는 디렉토리 /  만약 경로를 변경하려면 path.logs를 수정한다.
#### /usr/local/var/log/elasticsearch

### ▪︎ olugins : 플러그인이 존재하는 디렉토리
#### /usr/local/var/homebrew/linked/elasticsearch/plugins

##  Reference 
www.elastic.co/guide/en/elasticsearch/reference/current/brew.html

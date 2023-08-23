# HappyJava
intelliJ 설정 파일은 공유하지 말아야 한다.

#### 첫 번째 문제 
intellij가 class 파일을 못찾아서 빌드가 안된디 
다른 사람들이 한 해결 방법을 봐도 도저히 해결이 안난다 미치것다
걍 갑자기 git에 커밋, 푸시하자마자 클래스 파일들은 다 잠겨버리고,, 

1. jdk 11로 다시 설치 후 환경변수 다시 설정해주기 -> 실패
다른 버전으로 하면 오류가 많이 난다고 하길래 원래 20버전에서 11버전으로 다시 설정!
3. 결과 path out폴더로 정확하게 설정하기 -> 실패
4. .idea 폴더 삭제 후 재부팅..?
5. 그냥 프로젝트를 새로 만들었다..
   그러니까 바로 해결,,

#### 두 번째 문제
이 문제를 해결하고 나니까 또 다른 문제가 발생했다ㅏ,, 
갑자기 한글이 깨지는 이상한 현상이 발생,,ㅎ 오늘 왜이럼
1. 파일 인코딩 설정 -> 실패
2. vm 옵션 설정 -> 실패
3. 캐시 파일 지우기 -> 전혀 안됨 ㅎㅋ
4. 프로젝트 sdk 바꿔줌,, 17version으로,,
아니 jdk 설치한건 20인데 왜 17version 에서만 동작하는거지..?
그 전까지는 20에서 제대로 동작 했자나,, 뭔일이야 도대체가


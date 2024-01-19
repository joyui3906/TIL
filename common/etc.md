# 기억 안날 때 확인하는 치팅시트

- 윈도우에서 이미 사용중인 포트라고 할 때
1. 사용 중인 포트로 pid 확인  
```netstat -aon | findstr {pid}```

2. pid로 taskkill  
``` taskkill /f /pid {pid} ```

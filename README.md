# AI_for_prosthetics
About 2018 NIPS AI for proesthctics competition



## 1. About the competition
https://www.crowdai.org/challenges/nips-2018-ai-for-prosthetics-challenge

## Installation 
https://github.com/stanfordnmbl/osim-rl





---

- Action space 
example : 

```env.action_space.sample()
array([0.28173012, 0.58641016, 0.06395527, 0.4856276 , 0.97749513,
       0.87650526, 0.33815897, 0.96157014, 0.23170163, 0.9493188 ,
       0.9413777 , 0.79920256, 0.6304479 , 0.87428796, 0.29302028,
       0.84894353, 0.6178767 , 0.01323686, 0.3472335 ], dtype=float32)
```


# Submit할때 Client함수 사용법

`from osim.http.client import Client`
- Client에서 사용가능 함수들
```>>> Client.
Client.env_close(          Client.env_step(
Client.env_create(         Client.mro(
Client.env_monitor_start(  Client.submit(
Client.env_reset(```      

그러므로 submit, creat, reset, close,stet만 사용




- Client 

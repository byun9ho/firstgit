# 제목1
안녕하세요. 엔터키2번

박병호입니다.
---
***
안녕하세요? 엔터키1번
박병호입니다.


## 제목2
---
***

### 제목3
1. 안녕하세요?
2. 박병호입니다.
3. 반가워요.


#### 제목4
- 안녕하세요? 아무기호나 다 같은 글머리 기호(O)로 나옴
- 박병호입니다.
- 반가워요
* 안녕하세요?
* 박병호입니다.
* 반가워요
  * 반가워요
    * 진짜 반가워요

##### 제목5
**안녕**하세요
_박병호_ 입니다.
__박병호__ 입니다.
~~반가워요.~~

<https://cafe.naver.com/hicode>

[hello코딩놀이터](https://cafe.naver.com/hicode)

###### 제목6

# 과제코드

1. 한줄소스코드

`P=0
Z=0
N=0`

3. 여러줄 소스코드
```python
for t in range(10):
    prompt='숫자'+str(t+1)+'입력 : '
    #KeyIn=int(input(f'숫자{t}입력 : '))
    #KeyIn=int(input('숫자'+str(t+1)+'입력 :'))
    KeyIn = int(input(prompt))
    if KeyIn > 0:
        P+=1
    elif KeyIn < 0:
        N+=1
    else:
        Z+=1
print('----------------')
print('양의 개수 : ',P)
print('음의 개수 : ',N)
print('0의 개수 : ',Z)
```


# 1.1  코드가 초래하는 세 가지 혼란
.. 코드가 이해하기 어렵고 혼란스러우면 불편하고 꺼림칙하기 마련인데 이러한 혼란을 초래하는 원인을 세 개의 예제 프로그램을 통해 살펴봤다.   
첫째, 프로그래밍 언어나 알고리즘 혹은 업무 영역에 대한 지식이 없는 경우 혼란이 생길 수 있다.    
둘째, 코드를 이해하기 위해 필요한 정보를 충분히 가지고 있지 못하는 경우에도 그렇다. 요즘은 코드가 다양한 라이브러리, 모듈, 패키지를 사용하기 때문에 코드를 잘 이해하기 위해서는 이들에 
대한 정보를 얻기 위해 많이 찾아봐야 하고, 동시에 찾아보는 일을 하기 전에 무엇을 하고 있었는지도 기억해야 한다.   
셋째, 코드가 너무 복잡해서 혼란이 생기는 경우인데, 이는 두뇌의 처리 용량이 부족하기 때문이다.

![image](https://user-images.githubusercontent.com/31182783/188247991-fb41c880-5b93-42b2-99f2-4e1b05ce3dc8.png)



# 2장 연습문제

다음 코드를 주제로 연습함.    
https://github.com/netty/netty/blob/3ba2eed16a627371839c63113cdb39df9d6bfe35/codec-http/src/main/java/io/netty/handler/codec/http/HttpObjectDecoder.java    

작성한 코드:   
```
class Scratch {
    public static void main(String[] args) {
        String mode = "";
        switch(mode) {

            case "READ_HEADER": {

            }

            case "READ_VARIABLE_CONTENT": {

            }

            case "READ_FIXED_CONTENT": {

            }

            case "READ_CHUNK": {

            }
            
            case "BAD_REQUEST": {
                
            }
        }
    }
}
```
1. 어느 부분을 쉽게 기억했는가? switch문
2. 부분적으로 기억한 코드가 있는가? switch문
3. 전체를 기억하지 못한 코드가 있는가? 많다.
4. 기억하지 못한 라인들이 있따면 그 이유가 무엇일까? 라인이 많다.
5. 기억하지 못한 라인에 본인이 익숙하지 않은 프로그래밍 개념이 들어 있지는 않은가? 모르겠다.
6. 기억하지 못한 라인에 본인이 익숙하지 않은 도메인 지식이 있지는 않은가? 비즈니스 코드가 아님.

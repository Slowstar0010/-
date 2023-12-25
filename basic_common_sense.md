# 기초상식

**Syntax Errors**  
*Syntax Error*는 문법 오류를 뜻한다.  
코드 구조에 문제가 있을 경우 생기며 다음과 같은 상황에서 발생한다.  
```C
std::count 

return 0; 
```
C++는 모든 구문에는 ;으로 끝나야 하지만.  
해당코드 ```std::count```마지막에 ;이 들어가지 않아  
Syntax Error를 일으킨다.  

**Semantic Errors**     
*Semantic Error*는 구문이나 구조가 맞지만.  
컴파일러에게는 코드의 의미가 이해되지 않는 상태에서 발생하는 에러이다.  
```C
char a = "abc"
int b = 5;
a + b; 
```
해당 예시는 a라는 변수에 b라는 변수를 더하시오 라는 코드이다.
하지만 a는 문자이고 b는 숫자이기 때문에 *Semantic Error*를 일으킨다.    
    
# Error 수정  
Error를 수정 할 때에는 제일 첫번째 Error부터 수정한다.  
한가지의 Error가 발생한다면 당연한 말이지만.  
여러개의 Error 발생시 첫번째 Error만 고쳐도 모든게 작동 할 때가있다.  



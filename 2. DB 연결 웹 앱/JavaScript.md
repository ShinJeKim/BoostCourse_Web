# JavaScript

1. 자바스크립트에서는  ==과 ===이 큰 차이가 있다. 비교할 때 == 보다는 ===를 사용한다. 그 이유는 무엇인가?

2. 타입(type)이 결정될 때는 선언할 때인가? 아니면 실행타임인가?

3. 자바스크립트의 문자와 문자열은 다른 타입이다 ( O, X )

4. 자바스크립트에서 함수의 매개변수의 개수와 인자값이 일치하지 않을 때 오류는 발생한다 ( O, X )

5. 아래 코드의 결과는 무엇인가?

   ~~~
   function boostCourse() {
       var name = fc();
   
       console.log('Welcome to ' + name);
   
       console.log('our');
   
       function fc() {
           return 'BoostCourse';
       }
   }
   
   boostCourse();
   ~~~

6. 자바스크립트에서 "a"와 'a'는 같은 타입이다. ( O , X )

7. 자바스크립트에서는 함수가 실행되면 arguments라는 특별한 지역변수가 존재한다. 넘어온 인자를 arguments로 하여 배열의 메소드를 사용하여 접근할 수 있다. ( O , X ) 

8. 아래의 코드를 arrow function으로 바꿔 보시오

   ~~~
   function Hello(name){
       return "Hello " + name + "BoostCourse";
   }
   ~~~

   
# eos_coding_test
eos coding test for GXC x Decenter

다음은 core EOS 수업 수강 전, 본인의 블록체인 지식 및 c++에 대한 필요한 지식이 있는지를 묻는 질문입니다. 

- background


1. 비트코인에서 UTXO란 무엇인가? 이더리움은 UTXO 대신 어떤한 방식으로 데이터를 저장하는가?

2. 이오스 코어가 c++로 작성되어서 블록체인 TPS의 유의미한 개선을 가질 수 있다고 생각하는가? 그렇게 생각한 이유는?

3. 오라클이란 무엇인가? 

4. 51% attack이란 무엇인가? BTG(bitcoin gold)는 어떠한 방식으로 해당 공격을 당했는가?


- c++ Coding test.


1. simple algorithm

다음 문제를 푸시오.

https://programmers.co.kr/learn/courses/30/lessons/12973

2. 

다음 문제를 푸시오.
```c++
#include <iostream>

using namespace std;

typedef int (*ifunc)(int, int);

int process(int a, int b, ifunc f)
{
   return f(a, b);
}

int main()
{
   int a = 10;
   int b = 20;

   // ???를 완성하여 a와 b의 합을 출력하시오
   cout << process(a, b, ???) << endl;
}
```

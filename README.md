 * <a href="https://book.naver.com/bookdb/book_detail.nhn?bid=14144026" target="_blank">파이썬 코딩 도장: 따라하기, 연습하기, 심사하기로 배우는 파이썬 프로그래밍</a>

![](http://i.imgur.com/BzEJ1yv.png)


https://www.gilbut.co.kr/book/view?bookcode=BN002245&pdscode=pds#bookTab


정오표 입니다.

 

전체 수정 내역은 첨부 파일로 확인하세요.

 

--- 

 

파이썬 3.7의 언어 변경으로 파이썬 3.7 사용자는 다음 예제에서 런타임 에러(Runtime Error)가 발생합니다.

 

Unit 41.4.1 예제 coroutine_stopiteration.py

 

            raise StopIteration(total)    # StopIteration에 반환할 값을 지정

-> 

            return total                    # StopIteration에 반환할 값을 지정

 

파이썬 3.7부터 StopIteration이 Runtime Error로 변경되었습니다.

값을 반환할 때는 raise StopIteration 대신에 return을 사용해주세요.

 

파이썬 공식 문서의 설명은 다음과 같습니다(영어)

 

-. PEP 479 -- Change StopIteration handling inside generators

https://www.python.org/dev/peps/pep-0479/

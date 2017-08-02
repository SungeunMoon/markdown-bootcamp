Markdown
====
<br />

### 배워야 하는 이유

1.	텍스트 파일이기 때문에 버전관리시스템을 이용하여 **변경이력을 관리**할 수 있다.<br />
2.	간단한 문법을 통해 문서의 표시를 제어하고 굵게 또는 기울임을 통해 단어 **서식을 지정**하고, 이미지 추가, 목록을 만듭니다.
<br />
<br />
<br />

### 문법


<table>
<tr style=text-align:center>
<td></td>
<td><strong>Bitbucket</strong></td>
<td><strong>github</strong></td>
<td><strong>Or</strong></td>
<td><strong>	… to Get</strong></td>
</tr>
<tr>
<td style=text-align:center><strong>문단<br />나누기</strong></td>
<td colspan=2>1. 문단이란 하나 이상의 문장의 집합니다.<br>2. 하나 이상의 빈 줄로 구분된다.<br />3. 작성자 : 수정이 편리<br />4. 읽는 사람 : 가독성 향상<br /><hr>문단1 이다.<br>(빈줄)<br>문단2 이다.</td>
<td></td>
<td>문단1 이다.<br><br>문단2 이다.</td>
</tr>
<tr>
<td style=text-align:center><strong>개행<br />(줄바꿈)</strong></td>
<td colspan=2>1. 강제로 줄바꿈 하고 싶을 경우 사용한다.<br /><hr>두 개의 공백 (&nbsp&nbsp&nbsp&nbsp)<br />여백사이에 < br / >을 입력</td>
<td>백 슬래시 (\)</td>
<td>문단 1이다.<br />문단 2이다.</td>
</tr>
<tr>
<td style=text-align:center><strong>제목<br />Header</strong></td>
<td colspan=2>1. 가장 많이 쓰게 되는 서식 중 하나입니다.<br />2. 해시태그(#)를 앞, 뒤에 모두 붙여도 되고, 앞에만 붙여도 됩니다. <br />3. 글머리 1~6까지만 지원됩니다.<br />4. 해시태그(#) 개수가 늘어날 때마다 제목의 수준이 내려간다.<br /><hr># 1번째 수준 제목 (H1) <br />## 2번째 수준 제목 (H2) <br />### 3번째 수준 제목 (H3) <br />#### 4번째 수준 제목 (H4) <br />##### 5번째 수준 제목 (H5) <br />###### 6번째 수준 제목 (H6) <br /><hr>H1<br />========<br />H2<br />--------------</td>
<td></td>
<td><h1>H1</h1><h2>H2</h2><h3>H3</h3><h4>H4</h4><h5>H5</h5><h6>H6</h6></td>
</tr>
<tr>
<td style=text-align:center><strong>기울기<br />italic</strong></td>
<td colspan=2>*텍스트*<br />_텍스트_</td>
<td></td>
<td><em>텍스트</em></td>
</tr>
<tr>
<td style=text-align:center><strong>굵기<br />Bold</strong></td>
<td colspan=2>**텍스트**<br />__텍스트__</td>
<td></td>
<td><strong>텍스트</strong></td>
</tr>
<tr>
<td style=text-align:center><strong>굵고<br />기울게</strong></td>
<td colspan=2>***텍스트***<br />___텍스트___</td>
<td></td>
<td><strong><em>텍스트</em></strong></td>
</tr>
<tr>
<td style=text-align:center><strong>밑줄</strong></td>
<td colspan=2>< u >텍스트< /u ></td>
<td></td>
<td><u>텍스트</u></td>
</tr>
<tr>
<td style=text-align:center><strong>취소선</strong></td>
<td colspan=2>< del >텍스트< /del ></td>
<td>~~텍스트~~</td>
<td><del>텍스트</del></td>
</tr>
<tr>
<td style=text-align:center><strong>가로선</strong></td>
<td colspan=2>1. 내용을 구분 지어 나눌 때 유용합니다.<br />2. 선을 표시해야 할 곳에 세 개나 혹은 그 이상의 중간 선(대시) 기호를 입력합니다.<br /><hr>---</td>
<td></td>
<td><hr></td>
</tr>
<tr>
<td style=text-align:center><strong>인라인<br />주소삽입</strong></td>
<td colspan=2>1. 주소 대신 단어가 보이는 링크입니다.<br />2. [주소에 대한 설명](주소)<br /><hr>[Mirero](http://www.mirero.co.kr)</td>
<td></td>
<td><a href="http://www.mirero.co.kr">Mirero</a></td>
</tr>
<tr>
<td style=text-align:center><strong>참조링크<br />삽입</strong></td>
<td colspan=2>1. 링크 삽입 : [주소에 대한 설명] [참조 번호]<br />2. 참조 번호 작성 : [참조 번호]: 주소<br /><hr>이 부분은 [Google] [1]을 참조하시면 됩니다.<br />[1]: http://www.google.com</td>
<td></td>
<td>이 부분은 <a href="http://www.google.com">Google 1</a>을 참조하시면 됩니다.</td>
</tr>
<tr>
<td style=text-align:center><strong>함축적링크<br />삽입<strong></strong></td>
<td colspan=2>1. 링크 삽입 : [참조 이름]<br />2. 참조 이름 작성 : [참조 이름]: 주소<br /><hr>이 부분은 [Google]을 참조하시면 됩니다.<br />[Google]: http://www.google.com</td>
<td></td>
<td>이 부분은 [<a href="www/google.com">Google</a>]을 참조하시면 됩니다.<br />[<a href="www/google.com">Google</a>]: http://www.google.com</td>
</tr>
<tr>
<td style=text-align:center><strong>URL주소삽입<strong></strong></td>
<td colspan=2>1. <주소><br /><hr>Mirero System 홈페이지 주소는 < http://www.mirero.co.kr > 입니다.</td>
<td></td>
<td>Mirero System 홈페이지 주소는 <a href="http://www.mirero.co.kr">http://www.mirero.co.kr</a> 입니다.</td>
</tr>
<tr>
<td style=text-align:center><strong>그림삽입<strong></strong></td>
<td colspan=2>1. 인라인 주소 삽입 문법 그대로 앞에 !(느낌표)만 추가하면 된다.<br />2. ![그림주소](그림주소)<br /><hr>![구글 로고](http://www.google.co.kr/images/srpr/logo11w.png)</td>
<td></td>
<td><img src="http://www.google.co.kr/images/srpr/logo11w.png" /></td>
</tr>
<tr>
<td style=text-align:center><strong>숫자목록</strong></td>
<td colspan=2>1. 숫자를 연속적으로 사용하면 됩니다.<br /><hr>1. 사과<br />2. 바나나<br />3. 오렌지<br />4. 포도</td>
<td></td>
<td><ol><li>사과</li><li>바나나</li><li>오렌지</li><li>포도</li></ol></td>
</tr>
<tr>
<td style=text-align:center><strong>글머리기호<br />목록</strong></td>
<td colspan=2>1. -(대시), +(덧셈기호), *(별표)를 연속적으로 사용하면 됩니다.<br /><br /><table><tr><td>- 사과<br />- 바나나<br />- 오렌지<br />- 포도</td><td>+ 사과<br />+ 바나나<br />+ 오렌지<br />+ 포도</td><td>* 사과<br />* 바나나<br />* 오렌지<br />* 포도</td></table></td>
<td></td>
<td><ul><li>사과</li><li>바나나</li><li>오렌지</li><li>포도</li></ul></td>
</tr>
<tr>
<td style=text-align:center><strong>표<br />Table</strong></td>
<td colspan=2>1. 각 열을 파이프라고도 불리는 사직 막대 기호로 분리합니다.<br />2. 가로 선 기호(대시)를 제목 아래에 입력한 다음 이들 사이에 수직 막대 기호를 추가합니다.<br /><hr>좋은 음식 | 나쁜 음식<br />--- | ---<br />과일 | 사탕<br />당근 | 감자튀김</td>
<td></td>
<td><table><tr><td>좋은 음식</td><td>나쁜 음식</td></tr><tr><td>과일</td><td>사탕</td></tr><tr><td>당근</td><td>감자튀김</td></tr></table></td>
</tr>
<tr>
<td style=text-align:center><strong>코드</strong></td>
<td colspan=2>1. 빈 줄 하나 아래 탭(tab) 하나를 넣고 코드를 입력하면 됩니다.<br /><hr>ViewModel - ReactiveObject 상속<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;public class MainViewModel : ReactiveObject</td>
<td></td>
<td>ViewModel - ReactiveObject 상속<br /><code>public class MainViewModel : ReactiveObject</code></td>
</tr>
<tr><td style=text-align:center><strong></strong></td><td></td><td></td><td></td><td></td></tr></table>

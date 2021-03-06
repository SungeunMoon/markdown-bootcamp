> # **Markdown**

### 배워야 하는 이유

1.	**텍스트 파일**이기 때문에 버전관리시스템을 이용하여 **변경이력을 관리**할 수 있다.<br />
2.	**간단한 문법**을 통해 문서의 표시를 제어하고 굵게 또는 기울임을 통해 단어 **서식을 지정**하고, 이미지 추가, 목록을 만듭니다.
&nbsp;  
&nbsp;  
&nbsp;  
### 1. 파일 형식
1. 파일이름은 **대문자**를 사용합니다.   
2. 파일확장자는 **.md** 입니다.  
&nbsp; Ex. **README**.md, **SLIDE**.md  
3. notepad(또는 notepad++)를 사용하여 작성할 때 **인코딩**은 **UTF-8 BOM 없음**으로 설정합니다.<br />![Markdown 문법을 글에 사용할 때](./Images/Markdown-03.png)  
&nbsp;  
### 2. 문법
<table style="width:800px;">
    <tr style=text-align:center>
        <td></td>
        <td><strong>설명</strong></td>
        <td><strong>마크다운<br />(Markdown)</strong></td>
        <td><strong>마크다운 결과</strong></td>
    </tr>
    <tr>
        <td style=text-align:center><strong>제목<br />(Header)</strong></td>
        <td>1. 가장 많이 쓰게 되는 서식 중 하나입니다.<br />2. 해시태그(#)를 앞, 뒤에 모두 붙여도 되고, 앞에만 붙여도 됩니다. <br />3. 글머리 1~6까지만 지원됩니다.<br />4. 해시태그(#) 개수가 늘어날 때마다 제목의 수준이 내려간다.</td>
        <td>
            <strong>#</strong> 1번째 수준 제목 (H1) <br /><strong>##</strong> 2번째 수준 제목 (H2) <br /><strong>###</strong> 3번째 수준 제목 (H3) <br /><strong>####</strong> 4번째 수준 제목 (H4) <br /><strong>#####</strong> 5번째 수준 제목 (H5) <br /><strong>######</strong> 6번째 수준 제목 (H6)
        </td>
        <td style=background:#D0E9F7;><h1>H1</h1><h2>H2</h2><h3>H3</h3><h4>H4</h4><h5>H5</h5><h6>H6</h6></td>
    </tr>
    <tr>
        <td style=text-align:center rowspan=2><strong>인용<br />(Blockquotes)</strong></td>
        <td rowspan=2>1. > 로 시작하는 텍스트</td>
        <td><strong>></strong></td>
        <td><Blockquote>인용문</Blockquote></td>
    </tr>
    <tr>
        <td><strong>>></strong></td>
        <td><Blockquote><Blockquote>인용문</Blockquote></Blockquote></td>
    </tr>
    <tr>
        <td style=text-align:center><strong>문단<br />나누기</strong></td>
        <td>1. 문단이란 하나 이상의 문장의 집합니다.<br>2. 하나 이상의 빈 줄로 구분된다.<br />3. 작성자 : 수정이 편리<br />4. 읽는 사람 : 가독성 향상</td>
        <td>문단1 이다.<br>(빈줄)<br>문단2 이다.</td>
        <td>문단1 이다.<br><br>문단2 이다.</td>
    </tr>
    <tr>
        <td style=text-align:center><strong>개행<br />(줄바꿈)</strong></td>
        <td>1. 강제로 줄바꿈 하고 싶을 경우 사용한다.</td>
        <td>여백사이에 <strong>< br / ></strong>을 입력</td>
        <td>문단 1이다.<br />문단 2이다.</td>
    </tr>
    <tr>
        <td style=text-align:center><strong>기울기<br />(italic)</strong></td>
        <td rowspan=5>1. 강조할 때 많이 사용됩니다.</td>
        <td><strong>*</strong>텍스트<strong>*</strong></td>
        <td><em>텍스트</em></td>
    </tr>
    <tr>
        <td style=text-align:center><strong>굵기<br />(Bold)</strong></td>
        <td><strong>**</strong>텍스트<strong>**</strong></td>
        <td><strong>텍스트</strong></td>
    </tr>
    <tr>
        <td style=text-align:center><strong>굵고<br />기울게</strong></td>
        <td><strong>***</strong>텍스트<strong>***</strong></td>
        <td><strong><em>텍스트</em></strong></td>
    </tr>
    <tr>
        <td style=text-align:center><strong>밑줄</strong></td>
        <td><strong>< u ></strong>텍스트<strong>< /u ></strong></td>
        <td><u>텍스트</u></td>
    </tr>
    <tr>
        <td style=text-align:center><strong>취소선</strong></td>
        <td><strong>< del ></strong>텍스트<strong>< /del ></strong></td>
        <td><del>텍스트</del></td>
    </tr>
    <tr>
        <td style=text-align:center><strong>가로선</strong></td>
        <td>1. 내용을 구분 지어 나눌 때 유용합니다.<br />2. 선을 표시해야 할 곳에 세 개나 혹은 그 이상의 중간 선(대시, 별표) 기호를 입력합니다.</td>
        <td><strong">---</strong></td>
        <td><hr></td>
    </tr>   
    <tr>
        <td style=text-align:center><strong>참조링크<br />삽입</strong></td>
        <td>1. <strong>링크 삽입 : [주소에 대한 설명] [참조 번호]</strong><br />2. <strong>참조 번호 작성 : [참조 번호]: 주소</strong></td>
        <td><strong>[</strong>Mirero<strong>] [</strong>1<strong>]</strong></strong><br /><strong>[</strong>1<strong>]:</strong> http://www.mirero.co.kr</strong></td>
        <td>이 부분은 <a href="http://www.mirero.co.kr">Mirero 1</a>을 참조하시면 됩니다.</td>
    </tr>
    <tr>
        <td style=text-align:center><strong>함축적링크<br />삽입<strong></strong></td>
        <td>1. <strong>링크 삽입 : [참조 이름]</strong><br />2. <strong>참조 이름 작성 : [참조 이름]: 주소</strong></td>
        <td><strong>[</strong>Mirero<strong>]</strong><br /><strong>[</strong>Mirero<strong>]: </strong>http://www.mirero.co.kr</strong></td>
        <td>이 부분은 [<a href="http://www.mirero.co.kr">Mirero</a>]을 참조하시면 됩니다.<br />[<a href="http://www.mirero.co.kr">Mirero</a>]: http://www.mirero.co.kr</td>
    </tr>
    <tr>
        <td style=text-align:center><strong>URL주소삽입<strong></strong></td>
        <td>1. <strong><주소></strong></td>
        <td><strong><</strong> http://www.mirero.co.kr <strong>></strong></td>
        <td>Mirero System 홈페이지 주소는<br /><a href="http://www.mirero.co.kr">http://www.mirero.co.kr</a> 입니다.</td>
    </tr>
    <tr>
        <td style=text-align:center><strong>그림삽입<strong></strong></td>
        <td>1. 인라인 주소 삽입 문법 그대로 앞에 !(느낌표)만 추가하면 된다.<br />2. <strong>![그림명칭](그림주소)</strong></td>
        <td><strong>![</strong>구글 로고<strong>](</strong>http://www.google.co.kr/images/srpr/logo11w.png<strong>)</strong></span></td>
        <td><img src="http://www.google.co.kr/images/srpr/logo11w.png" width="400" /></td>
    </tr>
    <tr>
        <td style=text-align:center><strong>숫자목록</strong></td>
        <td>1. 숫자를 연속적으로 사용하면 됩니다.</td>
        <td><span style="color:green; font-weight:bold;">1.</span> 사과<br /><span style="color:green; font-weight:bold;">2.</span> 바나나<br /><span style="color:green; font-weight:bold;">3.</span> 오렌지<br /><span style="color:green; font-weight:bold;">4.</span> 포도</td>
        <td><ol><li>사과</li><li>바나나</li><li>오렌지</li><li>포도</li></ol></td>
    </tr>
    <tr>
        <td style=text-align:center><strong>글머리기호<br />목록</strong></td>
        <td>1. -, +, *를 연속적으로 사용하면 됩니다.<br />2. 세 가지 기호 중 어떤것을 사용하든 동일한 결과가 나타납니다.</td>
        <td><strong>-</strong> 사과<br /><strong>-</strong> 바나나<br /><strong>-</strong> 오렌지<br /><strong>-</strong> 포도</td>
        <td><ul><li>사과</li><li>바나나</li><li>오렌지</li><li>포도</li></ul></td>
    </tr>
    <tr>
        <td style=text-align:center><strong>글머리기호<br />들여쓰기</strong></td>
        <td>1. tab키를 누른 뒤 -, +, *를 입력하면 됩니다.<br />2. 세 가지 기호 중 어떤것을 사용하든 동일한 결과가 나타납니다.</td>
        <td><strong>-</strong> 빨강<br />&nbsp;&nbsp;&nbsp;&nbsp;<strong>-</strong> 녹색<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>-</strong> 파랑</td><td>
            <ul>
                <li>빨강
                    <ul>
                        <li>
                            녹색
                            <ul><li>파랑</li></ul>
                        </li>
                    </ul>
                </li>
            </ul>
        </td>
    </tr>
    <tr>
        <td style=text-align:center><strong>표<br />(Table)</strong></td>
        <td>1. 각 열을 파이프라고도 불리는 사직 막대 기호로 분리합니다.<br />2. 가로 선 기호(대시)를 제목 아래에 입력한 다음 이들 사이에 수직 막대 기호를 추가합니다.</td>
        <td>
            좋은 음식 <strong>|</strong> 나쁜 음식<br /> 
            <strong>--- | ---</strong> <br />
            과일 <strong>|</strong> 사탕<br />
            당근 <strong>|</strong> 감자튀김
        </td>
        <td>
            <table>
                <tr>
                    <td>좋은 음식</td>
                    <td>나쁜 음식</td>
                </tr>
                <tr>
                    <td>과일</td>
                    <td>사탕</td>
                </tr>
                <tr>
                    <td>당근</td>
                    <td>감자튀김</td>
                </tr>
            </table>
        </td>
    </tr>
    <tr>
        <td style=text-align:center><strong>c#코드</strong></td>
        <td>1. ```cs 아래줄에 코드 입력 후 ```로 닫아줍니다.</td>
        <td><strong>```cs</strong><br />public class MainViewModel : ReactiveObject<br /><strong>```</strong></td>
        <td><img src="./Images/Markdown-02-08-02.png" width="400" /></td>
    </tr>    
</table>
<br />
<br />

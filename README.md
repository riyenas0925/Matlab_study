<h1 id="matlab">matlab</h1>
<blockquote>
<p><strong>Matrix + Laboratory</strong><br><strong>Not</strong> <del>Math + Laboratory</del></p>
</blockquote>
<h2 id="-">특징</h2>
<blockquote>
<p>element를 구분하려면 space 사용<br>Interactive System<br>Matrix and Vector formulations</p>
</blockquote>
<blockquote>
<p>매틀랩의 기본적인 구성 요소는 행렬이다.<br>내장 함수들은 벡터 연산을 위하여 최적화 되어 있다.<br>매틀랩에서 벡터화된 명령과 코드는 훨씬 빨리 수행된다. </p>
</blockquote>
<h2 id="-">온라인 도움</h2>
<ol>
<li><p>help : 도움 받을수 있는 주제 열거</p>
</li>
<li><p>Helpwin : 양방향 도움 창을 오픈함</p>
</li>
<li><p>helpdesk : 웹브라우져 기반의 도움기능을 오픈함</p>
</li>
<li><p>help topic : topic에 관한 도움을 제공함</p>
</li>
<li><p>lookfor : 문자열을 포함하는 도움 주제를 열거함</p>
</li>
<li><p>demo : 데모 프로그램을 시작함</p>
</li>
</ol>
<h2 id="-">작업공간정보</h2>
<ol>
<li><p>who : 변수를 열거</p>
<blockquote>
<p>사용자 변수:
a  b</p>
</blockquote>
</li>
<li><p>whos : 변수와 변수의 크기를 열거  </p>
</li>
</ol>
<table>
<thead>
<tr>
<th style="text-align:center">Name</th>
<th style="text-align:center">Size</th>
<th style="text-align:center">Bytes</th>
<th style="text-align:center">Class</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">a</td>
<td style="text-align:center">1x1</td>
<td style="text-align:center">8</td>
<td style="text-align:center">double</td>
</tr>
<tr>
<td style="text-align:center">b</td>
<td style="text-align:center">1x1</td>
<td style="text-align:center">8</td>
<td style="text-align:center">double</td>
</tr>
</tbody>
</table>
<ol start="3">
<li><p>what : 디스크 안의 m-, mat-, mex- 파일을 열거함</p>
<pre class="editor-colors lang-"><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;현재&nbsp;폴더&nbsp;C:\Users\riyenas0925\Documents\MATLAB의&nbsp;MATLAB&nbsp;Code&nbsp;files&nbsp;Untitled</span></span></div></pre></li>
<li><p>clear :작업공간과  모든 변수를 지움</p>
</li>
<li><p>clear x y z : x, y, z 변수를 지움</p>
</li>
<li><p>clc : 명령창을 지움</p>
</li>
<li><p>home : 명령창을 지움</p>
</li>
<li><p>clf : 그림창을 지움</p>
</li>
</ol>
<h2 id="-">디렉토리 정보</h2>
<ol>
<li><p>pwd : 현재 작업 디렉토리를 나타냄</p>
</li>
<li><p>cd : 현재 작업 디렉토리를 변경함</p>
</li>
<li><p>dir : 현재 디렉토리의 내용을 열거함</p>
</li>
<li><p>mkdir : 디렉토리를 생성함</p>
</li>
</ol>
<h2 id="-">일반적인 정보</h2>
<ol>
<li><p>computer : 사용하고 있는 컴퓨터의 형태를 알려줌</p>
</li>
<li><p>clock : 시간과 날짜를 벡터로서 알려줌</p>
</li>
<li><p>date : 날짜를 문자열로 알려줌</p>
</li>
<li><p>more : 화면 크기에 맞추어 페이지 당 출력을 조절함</p>
</li>
<li><p>ver : 매트랩의 라이센스와 버전에 관한 정보를 줌</p>
</li>
</ol>
<h2 id="-">종료</h2>
<ol>
<li><p>^c : 현재 명령의 수행을 중단</p>
</li>
<li><p>quit : 매트랩을 종료함</p>
</li>
<li><p>exit : 매트랩을 종료함</p>
</li>
</ol>
<h2 id="-">수학</h2>
<h3 id="-">산술 연산자 : + - * / ^</h3>
<blockquote>
<p>element by element 으로 연산하려면 .(dot) 연산자를 사용해야한다.</p>
</blockquote>
<h3 id="-">지수와 로그함수</h3>
<ol>
<li><p>e^3 -&gt; exp(3)</p>
</li>
<li><p>lnx -&gt; log(x)</p>
</li>
<li><p>logx -&gt; log10(x)</p>
</li>
<li><p>sqrt(x) -&gt; sqrt(x)</p>
</li>
</ol>
<h3 id="-">삼각함수</h3>
<ol>
<li><p>sin, cos, tan, cot, sec, csc</p>
</li>
<li><p>asin, acos, atan</p>
</li>
</ol>
<h3 id="-">복소수</h3>
<ol>
<li>i, j 는 허수 sqrt(-1) 로 인식한다.</li>
</ol>
<h3 id="-">벡터의 생성</h3>
<ol>
<li><p>a = [1 2 3 4]</p>
<blockquote>
<p>a = {1 2 3 4 } 는 집합이다.</p>
</blockquote>
</li>
<li><p>a = [1 2 3 4; 5 6 7 8]</p>
</li>
<li><p>a = [1 2 3 4<br>5 6 7 8]</p>
</li>
<li><p>z = a : b  </p>
<blockquote>
<p>a = 1 : 5<br>a = 1 2 3 4 5  </p>
</blockquote>
</li>
<li><p>a = 0 : 10 : 100  </p>
<blockquote>
<p>0 &lt;=  a &lt;= 100  (101개)   </p>
</blockquote>
</li>
<li><p>b = 0 : pi/50 : 2*pi  </p>
</li>
<li><p>u = 2 : 10  </p>
</li>
<li><p>a = 100 : -7 : 50</p>
<blockquote>
<p>100 93 86 79 72 65 58 51</p>
</blockquote>
</li>
<li><p>u = linspace(a, b, n)  </p>
<blockquote>
<p>u = a : (b - a)/(n - 1) : b  두개는 같다.</p>
</blockquote>
</li>
<li><p>u = linspace(a, b - esp(0), n)</p>
<blockquote>
<p>a &lt;= u &lt; b<br>eps()는 매우 작은 값을 의미한다. </p>
</blockquote>
</li>
<li><p>v = logspace(a,b,n)  </p>
<blockquote>
<p>v = 10.^(linspace(a,b,n))  두개는 같다.</p>
</blockquote>
</li>
</ol>
<h3 id="-">유틸리티 행렬</h3>
<ol>
<li><p>eye(m,n)</p>
<blockquote>
<p>eye(3,3)  </p>
</blockquote>
<pre class="editor-colors lang-"><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;1&nbsp;0&nbsp;0&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;0&nbsp;1&nbsp;0&nbsp;&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;0&nbsp;0&nbsp;1&nbsp;&nbsp;</span></span></div></pre></li>
<li><p>zeros(m,n)</p>
<blockquote>
<p>zeros(3,3)</p>
</blockquote>
<pre class="editor-colors lang-"><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;0&nbsp;0&nbsp;0&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;0&nbsp;0&nbsp;0&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;0&nbsp;0&nbsp;0&nbsp;&nbsp;</span></span></div></pre></li>
<li><p>ones(m,n)</p>
<blockquote>
<p>ones(3,3)</p>
</blockquote>
<pre class="editor-colors lang-"><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;1&nbsp;1&nbsp;1&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;1&nbsp;1&nbsp;1&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;1&nbsp;1&nbsp;1&nbsp;&nbsp;</span></span></div></pre></li>
<li><p>rand(m,n)</p>
<blockquote>
<p>rand(3,3)</p>
</blockquote>
<pre class="editor-colors lang-"><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;2&nbsp;1&nbsp;4</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;5&nbsp;8&nbsp;2</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;1&nbsp;3&nbsp;8</span></span></div></pre></li>
<li><p>diag(v)</p>
<blockquote>
<p>행렬의 diagonal을 추출</p>
</blockquote>
</li>
<li><p>diag(v,1)</p>
<blockquote>
<p>행렬의 diagonal에서 위로 1칸을 추출</p>
</blockquote>
</li>
<li><p>rot90(A)</p>
<blockquote>
<p>행렬을 90도 회전한다.</p>
</blockquote>
</li>
<li><p>fliplr(A)</p>
<blockquote>
<p>행렬을 좌우 반전한다.</p>
</blockquote>
</li>
<li><p>flipud(A)</p>
<blockquote>
<p>행렬을 상하 반전한다.</p>
</blockquote>
</li>
<li><p>tril(A)</p>
<blockquote>
<p>아래 삼각 부분을 추출</p>
</blockquote>
</li>
<li><p>triu(A)</p>
<blockquote>
<p>행렬의 위부분을 추출</p>
</blockquote>
</li>
<li><p>reshape(A,[m,n])</p>
<blockquote>
<p>A의 행렬을 mxn 행렬로 변환한다.</p>
</blockquote>
<pre class="editor-colors lang-"><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>A&nbsp;=&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>1&nbsp;&nbsp;4&nbsp;&nbsp;7&nbsp;&nbsp;&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>2&nbsp;&nbsp;5&nbsp;&nbsp;9&nbsp;&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>3&nbsp;&nbsp;6&nbsp;10&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>reshape(A,[1,&nbsp;9])&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>A&nbsp;=&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>1&nbsp;2&nbsp;3&nbsp;4&nbsp;5&nbsp;6&nbsp;7&nbsp;8&nbsp;9&nbsp;</span></span></div></pre></li>
<li><p>length(a)</p>
<blockquote>
<p>matrix의 가로 길이를 출력한다.</p>
</blockquote>
</li>
</ol>
<h3 id="-">행렬의 조작</h3>
<ol>
<li><p>A = rand(3)  </p>
<blockquote>
<p>A = rand(3,3) 하고 같다</p>
</blockquote>
</li>
<li><p>A = rand(1,10)</p>
<blockquote>
<p>1열 10행짜리 랜덤 벡터를 생성한다.</p>
</blockquote>
</li>
<li><p>A = fix(10.*rand(a))</p>
<blockquote>
<p>정수로된 axa 크기의 랜덤변수를 출력한다. </p>
</blockquote>
</li>
<li><p>A( : , 2) = [ ]</p>
<blockquote>
<p>2행 모든 열을 삭제 한다.
만약 기존의 행렬의 범위를 넘어갈시 행렬이 확장된다.</p>
</blockquote>
</li>
<li><p>A([1,3] , : ) = [ 1 2 3 ; 4 5 6]</p>
<blockquote>
<p>1행과 3행을  1 2 3 과 4 5 6으로 치환한다.
이때 열은 3열이어야 한다.</p>
</blockquote>
</li>
<li><p>A = [ ]</p>
<blockquote>
<p>빈행렬 만들기</p>
</blockquote>
</li>
<li><p>A( : , 3 : 5) = [ ]</p>
<blockquote>
<p>3열에서 5열까지 삭제</p>
</blockquote>
</li>
<li><p>A([1 3] , : ) = [ ]</p>
<blockquote>
<p>1행과 3행을 삭제</p>
</blockquote>
</li>
<li><p>B = A([1 3] , [1 3])</p>
<blockquote>
<p>1행 3행, 1열 3열 교차점의 값을 추출</p>
</blockquote>
</li>
<li><p>A(2 : 3 , 1 : 2) = [1 2 ; 3 4]</p>
<blockquote>
<p>행 2~3 열 1~2 에 2x2 행렬을 삽입한다.</p>
</blockquote>
</li>
<li><p>u(5 : length(u)) = [ ]</p>
<blockquote>
<p>1에서 4를 제외한 백터 u의 모든 성분</p>
</blockquote>
</li>
<li><p>A = [A ; b]</p>
<blockquote>
<p>A<br>+<br>b</p>
</blockquote>
</li>
<li><p>A = [A   a]</p>
<blockquote>
<p>A + a</p>
</blockquote>
</li>
<li><p>A = A(m,n)</p>
<blockquote>
<p>행렬 A의 m행 n열의 값을 A에 넣는</p>
</blockquote>
</li>
<li><p>A(m,n) = a</p>
<blockquote>
<p>행렬 A의 m행 n열에 a값을 넣는다</p>
</blockquote>
</li>
<li><p>sin(A)</p>
<blockquote>
<p>element by element 행렬</p>
</blockquote>
</li>
<li><p>A'</p>
<blockquote>
<p>A transpose</p>
</blockquote>
</li>
<li><p>[col, row] = find(B == max(B(:)))</p>
<blockquote>
<p>행렬 B에서 가장 큰값을 찾은다음 col, row에 값을 넣는다.</p>
</blockquote>
</li>
<li><p>[col, row] = find(B == min(B(:)))</p>
<blockquote>
<p>행렬 B에서 가장 큰값을 찾은다음 col, row에 값을 넣는다.</p>
</blockquote>
</li>
<li><p>Matrix에서 최대값 찾기  </p>
<pre class="editor-colors lang-"><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>[a,&nbsp;b]&nbsp;=&nbsp;max(B);&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>%&nbsp;각&nbsp;열에서&nbsp;제일&nbsp;큰&nbsp;값을&nbsp;벡터로&nbsp;a에&nbsp;넣는다.&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>%&nbsp;a&nbsp;값에&nbsp;해당하는&nbsp;&nbsp;행의&nbsp;값을&nbsp;벡터로&nbsp;b에&nbsp;넣는다.&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>[&nbsp;c&nbsp;,col]&nbsp;=&nbsp;max(a')&nbsp;&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>%&nbsp;a의&nbsp;값을&nbsp;transpose&nbsp;하면&nbsp;벡터&nbsp;a의&nbsp;최대값과&nbsp;행값이&nbsp;나오게&nbsp;된다.&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>row&nbsp;=&nbsp;b(col)&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>%&nbsp;행값을&nbsp;b에&nbsp;넣으면&nbsp;row&nbsp;값이&nbsp;나온다.&nbsp;</span></span></div></pre></li>
<li><p>A(20 &lt; A) = n;</p>
<blockquote>
<p>행렬A에서 조건에 맞는 값에 n을 대입한다.</p>
</blockquote>
</li>
</ol>
<h3 id="-">행렬 및 배열 연산</h3>
<ol>
<li><p>A+B , A-B : 크기가 같아야 한다.  </p>
</li>
<li><p>A*B : A의 열수가 B의 행수와 같아야한다.  </p>
</li>
<li><p>A/B : 동일 크기의 정방행렬 A,B에 대하여 유효하며 AB^-1과 동일  </p>
</li>
<li><p>A^2 :  A가 정방일 경우에만 의미를 가진다. A*A와 동일  </p>
</li>
<li><p>A + a , A * a, A / b : a가 스칼라일때 </p>
</li>
</ol>
<h3 id="-">출력</h3>
<ol>
<li><p>plot(x,y)</p>
<blockquote>
<p>x,y 축으로 이루어진 실선 그래프를 그린다.</p>
</blockquote>
</li>
<li><p>plot(x)</p>
<blockquote>
<p>plot(x, index_num) 로 판단하여 그래프를 그린다.</p>
</blockquote>
</li>
<li><p>plot(x,y,'--')</p>
<blockquote>
<p>x,y 축으로 이루어진 파쇄선 그래프를 그린다.</p>
</blockquote>
</li>
<li><p>plot3(x, y, z)</p>
<blockquote>
<p>x,y,z 축으로 이루어진 실선 그래프를 그린다,</p>
</blockquote>
</li>
<li><p>semilogx(x,y)</p>
<blockquote>
<p>x 축을 log10 스케일로 플롯한다.</p>
</blockquote>
</li>
<li><p>semilogy(x,y)</p>
<blockquote>
<p>y 축을 log10 스케일로 플롯한다.</p>
</blockquote>
</li>
<li><p>loglog(x,y)</p>
<blockquote>
<p>x,y 축을 log10 스케일로 플롯한다.</p>
</blockquote>
</li>
<li><p>subplot(a,b,c)</p>
<blockquote>
<p>한창에 여러개의 그래프를 띄울때<br>subplot(행, 열 ,  번호)<br>여기서의 번호는 알반적인 매트릭스의 번호와 다르다.</p>
</blockquote>
<pre class="editor-colors lang-"><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;%&nbsp;세로로&nbsp;그래프&nbsp;3개</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;subplot(3,1,1);</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;plot(x,y);</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;subplot(3,1,2);</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;plot(t,r);</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;subplot(3,1,3);</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;plot(t,theta);</span></span></div></pre></li>
<li><p>figure(A)</p>
<blockquote>
<p>여러창에 그래프를 띄울때</p>
</blockquote>
</li>
<li><p>spy(A)</p>
<blockquote>
<p>Matrix를 그래피컬 하게 보여준다.</p>
</blockquote>
</li>
<li><p>axis squre</p>
<blockquote>
<p>그래프를 정사각형으로 맞춘다,</p>
</blockquote>
</li>
<li><p>axis off</p>
<blockquote>
<p>좌표축 선과 배경을 표시하지 않는다.</p>
</blockquote>
</li>
<li><p>xlabel("content")</p>
<blockquote>
<p>x 축에 이름을 붙인다.</p>
</blockquote>
</li>
<li><p>ylabel("content")</p>
<blockquote>
<p>y 축에 이름을 붙인다.</p>
</blockquote>
</li>
<li><p>title("contnent")</p>
<blockquote>
<p>제목을 붙인다.</p>
</blockquote>
</li>
<li><p>axis([xmin xmax ymin ymsx])</p>
<blockquote>
<p>x, y 축의 범위를 제한한다.</p>
</blockquote>
</li>
</ol>
<h3 id="-">함수</h3>
<pre class="editor-colors lang-"><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>function&nbsp;=&nbsp;plot_graph(a,&nbsp;b,&nbsp;c,&nbsp;x);</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>%function[함수출력]&nbsp;=&nbsp;함수이름(함수입력);</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>%2Dpicture&nbsp;function&nbsp;test&nbsp;&nbsp;-&gt;&nbsp;H1&nbsp;태그</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>%출력&nbsp;x,&nbsp;y,&nbsp;z&nbsp;/&nbsp;입력&nbsp;a,&nbsp;b,&nbsp;c&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>i&nbsp;=&nbsp;a.*min(x).^2&nbsp;+&nbsp;b.*min(x)&nbsp;+&nbsp;c</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>j&nbsp;=&nbsp;a.*max(x).^2&nbsp;+&nbsp;b.*max(x)&nbsp;+&nbsp;c</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>k&nbsp;=&nbsp;a.*median(x).^2&nbsp;+&nbsp;b.*(median(x))&nbsp;+&nbsp;c</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>&nbsp;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>y&nbsp;=&nbsp;&nbsp;a.*x.^2&nbsp;+&nbsp;b.*x&nbsp;+&nbsp;c;</span></span></div><div class="line"><span class="syntax--text syntax--plain syntax--null-grammar"><span>plot(y,x);</span></span></div></pre>

My solutions to problems on [Code-Golf](https://code-golf.io).

The website accepts only a fixed set of programming language
as solution, including [J](https://www.jsoftware.com/). Unfortunately
I am only interested in creating my solution in 
APL](https://en.wikipedia.org/wiki/APL_(programming_language)) 
using [NARS2000](http://www.nars2000.org/). So I am posting / sharing
my answers here instead.  

Answers are listed in ascending difference in number of char between my
solutions and those of champion's. In some problems, I actually manage
to beat the champion with quite a margin.

Problem:            [Pascal Triangle](https://code-golf.io/pascals-triangle#python)<br />
Date:               2019-12-21<br />
Length (champion):  52<br />
Length (mine):      26<br />
Code:               K←{1,⍨1,(¯1↓⍵)+1↓⎕←⍵}⍣20 1<br />

Problem:            [Emirp Numbers](https://code-golf.io/emirp-numbers)<br />
Date:               2019-10-30<br />
Length (champion):  27<br />
Length (mine):      24<br />
Code:               ⍪P∩⍎¨⌽¨⍕¨P←V/⍨0π¨V←⍳1000<br />

Problem:            [Fibonacci](https://code-golf.io/fibonacci)<br />
Date:               2019-10-30<br />
Length (champion):  17<br />
Length (mine):      18<br />
Code:               ⍪{⍵,+/¯2↑⍵}⍣29⊢0 1<br />

Problem:            [Evil Numbers](https://code-golf.io/evil-numbers)<br />
Date:               2019-10-31<br />
Length (champion):  18<br />
Length (mine):      27<br />
Code:               ⍪N/⍨~2|+/¨{(6⍴2)⊤⍵}¨N←0,⍳50<br />

Problem:            [Divisors](https://code-golf.io/divisors)<br />
Date:               2019-10-30<br />
Length (champion):  20<br />
Length (mine):      30<br />
Code:               ⍪{(~∨/¨'r'=¨⍕¨⍵÷V)/V←⍳⍵}¨⍳100x<br />

Problem:            [Happy Numbers](https://code-golf.io/happy-numbers)<br />
Date:               2019-10-30<br />
Length (champion):  28<br />
Length (mine):      40<br />
Code:               ⍪V/⍨1∊¨{⍵,+/2*⍨⍎¨⍕¯1↑⍵}⍣{⍵∊⍨¯1↑⍺}¨V←⍳200<br />

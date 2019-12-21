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

Problem:            [Pascal Triangle](https://code-golf.io/pascals-triangle#python)
Date:               2019-12-21
Length (champion):  52
Length (mine):      26
Code:               K←{1,⍨1,(¯1↓⍵)+1↓⎕←⍵}⍣20 1

Problem:            [Emirp Numbers](https://code-golf.io/emirp-numbers)
Date:               2019-10-30
Length (champion):  27
Length (mine):      24
Code:               ⍪P∩⍎¨⌽¨⍕¨P←V/⍨0π¨V←⍳1000

Problem:            [Fibonacci](https://code-golf.io/fibonacci)
Date:               2019-10-30
Length (champion):  17
Length (mine):      18
Code:               ⍪{⍵,+/¯2↑⍵}⍣29⊢0 1

Problem:            [Evil Numbers](https://code-golf.io/evil-numbers)
Date:               2019-10-31
Length (champion):  18
Length (mine):      27
Code:               ⍪N/⍨~2|+/¨{(6⍴2)⊤⍵}¨N←0,⍳50

Problem:            [Divisors](https://code-golf.io/divisors)
Date:               2019-10-30
Length (champion):  20
Length (mine):      30
Code:               ⍪{(~∨/¨'r'=¨⍕¨⍵÷V)/V←⍳⍵}¨⍳100x

Problem:            [Happy Numbers](https://code-golf.io/happy-numbers)
Date:               2019-10-30
Length (champion):  28
Length (mine):      40
Code:               ⍪V/⍨1∊¨{⍵,+/2*⍨⍎¨⍕¯1↑⍵}⍣{⍵∊⍨¯1↑⍺}¨V←⍳200

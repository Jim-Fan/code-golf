Answers are listed in ascending difference in number of char with champion
solution. In some problems, I actually managed to beat the champion:
<br />
<br />
Problem:            [Emirp Numbers](https://code-golf.io/emirp-numbers) \
Date:               2019-10-30 \
Length (champion):  27 \
Length (mine):      24 \
Code:               ⍪P∩⍎¨⌽¨⍕¨P←V/⍨0π¨V←⍳1000
<br />
<br />
Problem:            [Fibonacci](https://code-golf.io/fibonacci) \
Date:               2019-10-30 \
Length (champion):  17 \
Length (mine):      18 \
Code:               ⍪{⍵,+/¯2↑⍵}⍣29⊢0 1
<br />
<br />
Problem:            [Evil Numbers](https://code-golf.io/evil-numbers) \
Date:               2019-10-31 \
Length (champion):  18 \
Length (mine):      27 \
Code:               ⍪N/⍨~2|+/¨{(6⍴2)⊤⍵}¨N←0,⍳50
<br />
<br />
Problem:            [Divisors](https://code-golf.io/divisors) \
Date:               2019-10-30 \
Length (champion):  20 \
Length (mine):      30 \
Code:               ⍪{(~∨/¨'r'=¨⍕¨⍵÷V)/V←⍳⍵}¨⍳100x
<br />
<br />
Problem:            [Happy Numbers](https://code-golf.io/happy-numbers) \
Date:               2019-10-30 \
Length (champion):  28 \
Length (mine):      40 \
Code:               ⍪V/⍨1∊¨{⍵,+/2*⍨⍎¨⍕¯1↑⍵}⍣{⍵∊⍨¯1↑⍺}¨V←⍳200

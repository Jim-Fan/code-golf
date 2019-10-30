Problem:            [Fibonacci](https://code-golf.io/fibonacci) \
Date:               2019-10-30 \
Length (champion):  17 \
Length (mine):      18 \
Code:               ⍪{⍵,+/¯2↑⍵}⍣29⊢0 1
<br />
<br />
Problem:            [Happy Numbers](https://code-golf.io/happy-numbers) \
Date:               2019-10-30 \
Length (champion):  28 \
Length (mine):      40 \
Code:               ⍪V/⍨1∊¨{⍵,+/2*⍨⍎¨⍕¯1↑⍵}⍣{⍵∊⍨¯1↑⍺}¨V←⍳200
<br />
<br />
Problem:            [Divisors](https://code-golf.io/divisors) \
Date:               2019-10-30 \
Length (champion):  20 \
Length (mine):      30 \
Code:               ⍪{(~∨/¨'r'=¨⍕¨⍵÷V)/V←⍳⍵}¨⍳100x

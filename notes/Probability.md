# Probability #rushmode 
## Notation
- $P(x)$ means probability that event $x$ will occur.
- $P(x')$ means probability that event $x$ will not occur. (**NOT**)
	- ![[A-prime.png]]
- $P(A\cap B)$ means $A$ i**n**tersection $B$, meaning that the probability that $A$ and $B$ occur. (**AND**)
	- ![[A-cap-B.png]]
- $P(A\cup B)$ means $A$ **u**nion $B$, meaning that the probability that $A$ or $B$ occur. (**OR**)
	- ![[A-cup-B.png]]
- $P(A|B)$ means $A$ given $B$, meaning that the probability that $A$ occurs given that $B$ also occurs.
## Equations
- $P(A\cap B)=P(A|B)\times P(B)=P(B|A)\times P(A)$ (multiplication rule)
	- $P(A|B)=\frac{P(A\cap B)}{P(B)}$
	- $P(B|A)=\frac{P(A\cap B)}{P(A)}$
- $P(A\cup B)=P(A)+P(B)-P(A\cap B)$ (addition rule)
- $P(A')=1-P(A)$
## Independent events
- Independent events are events that are not affected by previous events.
	- If I roll a 6 on a dice, that does not affect my next roll. **This is independent**
	- If I have a bag of coloured marbles and I draw one marble (and don’t return it), it affects my next draw. **This is NOT independent**
- Given independence:
	- $P(A|B)=P(A)$, thus *multiplication rule* reduces to $P(A\cap B)=P(A)\times P(B)$
	- Also, $P(B|A)=P(B)$
- If any of these work, then an event is independent.
## Mutually Exclusive
- Mutually exclusive events cannot occur together. For example, I can’t roll a six and a three at the same time on one dice.
- For mutually exclusive:
	- $P(A\cap B)=0$, thus *addition rule* reduces to $P(A\cup B)=P(A)+P(B)$
Homework 2 (Due April 29, 2020, 23:00)

BLM 2502: Theory of Computation — Spring 2020

Print family (or last) name: ————————————————————————————

Print given (or first) name: ————————————————————————————

Print given student number: ————————————————————————————

I see that this homework has 10 questions in total 5 pages.

I agree that I have to submit my homework solution before the deadline (April 29, 2020, 23:5900)
otherwise my homework solution will not be accepted and will not be graded. I accept that I will
add the signed version of this instruction page as a first page into my homework solution;
otherwise my homework solution will not be graded. I know that I have to give my solutions
written on white A4-sized pages; otherwise my homework solution will not be graded. I will take
care of the readability of my solutions, from which I may lose 10 points. For any proofs, I am sure
to provide a step-by-step argument, with justifications for every step. I understand that, during
solving this homework, it is prohibited to exchange information about solutions with any other
person in any way, including by talking or ex-changing solutions / papers.

I know that the course book is “Introduction to the Theory of Computation, 2nd Ed., Massachusetts
Institute of Technology, by Micheal Sipser.”

I have read, understand and accept all of the instructions above. On my honor, I pledge that I have
not violated the provisions of the Academic Integrity Code of Yıldız Technical University.

————————————————————
Signature and Date

1
20 pts

2
20 pts

3
20 pts

4
20 pts

5
20 pts

6
20 pts

7
20 pts

8
20 pts

9
20 pts

10
20 pts

Total
200 pts

1

1.  [20 points] For each of the following languages, state the class of the language (whether it
is regular, context-free (but not regular) or neither). Prove your answer. Make sure, if you
claim that a language is context free, that you show that it is not also regular.

(a)  L={w{0,1}* : k 0 and w is a binary encoding (leading zeros allowed) of 2k+1}.

(b) L={a*b*c* - {anbncn : n  0}}.

2

(c)  L={x  {a, b}* : |x| is even and the first half of x has one more a than the second half}.

2.  [20 points] Let L = {w  {a, b}* : the first, middle, and last characters of w are identical}.

a.  Show a context-free grammar that generates L.

b.  Design a PDA that accepts L.

3

c.  Prove that L is not regular.

3.  [20 points] CConsider the following grammar G:

S  1 S 1 | T

T  1 X 1 | X

X 0 X 0 | 1

a.  What are the first (shortest) four strings L(G)?

b.  Give an example of a string w  {0, 1}* such that |w| > 7 and w  L(G).

4

c.  Show that G is ambiguous.

4.  Find grammars for the given languages

a.  L1= L(aaa*b + b).

b.  L2 = {ancmbn : m,n ≥ 1}.

5

c.  L3 = {anbn+1 : n ≥0}

5.  [20 points] Convert the Grammars grammars given below to Chomsky Normal Form of the.
Do not forget to give modified 4-Tuple Grammar (The formal definition, or the tuple that
has the list of productions, start symbol, etc)..

a.  S  a | aA | B |C

A aB |ε
B Aa
C bCD
D bbb

6

b.  S aA|aBB
A aaA |ε
B bB|bbC
C B

6.  [20 points] Find a context-free grammar that generates the language accepted by the PDA

M = ({q0,q1}, {a, b}, {A, z},δ, q0, {q1}), with transitions
δ(q0, a, z) = {(q0, Az)},
δ (q0,b, A) = {(q0, AA)},
δ(q0, a, A) = {(q1,ε)}

7

7.  [20 points] Determine whether the following languages are context-free or not

a.  L={anwwRan : n ≥ 0, w  {a,b}*}

b.  L= {anbjanbj : n ≥ 0, j ≥ 0}.

c.  L= {anbjajbn : n ≥ 0, j ≥ 0}.

d.  L= {anbjakbl : n + j ≤ k + l}.

e.  L= {anbjakbl : n ≤ k, j ≤ l}.

8

f.  L= {anbncj : n ≤ j}.

g.  L= {w L((a + b + c)*) : na(w)= nb(w)=2nc(w)}, where nx(w) denotes the number

of symbol X in the string w.

8.   [20 points] Let L be a context-free language. Prove that there exists an integer p ≥1, such

that the following is true:

For every string s in L with |s| ≥ p, there exists a string z in L such that |s|<|z|≤|s|+p.

9

9.  [20 points] For the context free languages in problem 7, find the grammar of the language

in Chomsky Normal Form.

(No space allowed here since you may need more pages)

10. [20 points] For the grammars in problem 9, obtain the PDA using the obtained context

free grammar.

(No space allowed here since you may need more pages)

10



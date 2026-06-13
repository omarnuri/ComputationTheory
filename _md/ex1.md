Exercise set 1

1)    Why do we need computation? Why do we need programming language for computation? Why do

we need automats / machines that recognize/accept programming language?

2)   For any 𝑛 ∈ ℕ, prove that the following equality is valid.
1(cid:2874) + 2(cid:2874) + 3(cid:2874) + ⋯ + 𝑛(cid:2874) =

(𝑛 + 1)(2𝑛 + 1)(3𝑛(cid:2872) + 6𝑛(cid:2871) − 3𝑛 + 1)

𝑛
42

1

3)   Let 𝛼 and 𝛽 be two positive integer numbers. If 𝛼(cid:2870) − 𝛽(cid:2870) is not odd, then prove that 𝛼 + 𝛽 ≥ 2.

4)   Let 𝑎, 𝑏, 𝑐, 𝑑 be integers. If 𝑎 > 𝑐 and 𝑏 > 𝑐, then prove that max(𝑎, 𝑏) − 𝑐 is always positive.

5)   Given two sets 𝑋 and 𝑌.  The Cartesian product of 𝑋 and 𝑌, written as 𝑋 × 𝑌, is defined as the set of
pairs (𝑥, 𝑦) where 𝑥 ∈ 𝑋 and 𝑦 ∈ 𝑌. Then, find a mathematical closed-form expression to write
|𝑋 × 𝑌| in terms of |𝑋| and |𝑌|.

2

6)   Let us given two disjoint sets 𝑋 and 𝑌, and then their joint set 𝑆 is 𝑆 = 𝑋⋃𝑌. Sum of the elements in a
set 𝑆 is denoted by ∑(𝑆) while their product is by ∏(𝑆). Accordingly, what are ∑(𝑆) and ∏(𝑆) in
terms of ∑(𝑋), ∑(𝑌), ∏(𝑋) and ∏(𝑌). Conclude from this what ∑(∅) and ∏(∅) should be (∅ is the
empty set).

7)   What is the relation between programming language and the power of a machine that recognizes /

accepts that programming language? Give an example in your explanation.

3

8)   The following are the state diagrams of two DFAs, 𝑀(cid:2869) and 𝑀(cid:2870) . Answer the follow- ing questions

about each of these machines.

a)  What is the start state?

b)  What is the set of accept states?

c)  What sequence of states does the machine go through on input 𝑎𝑏𝑏 ?

d)  Does the machine accept the string 𝑎𝑏𝑏 ?

e)  Does the machine accept the string 𝜀?

4

9)   The formal 5-tupple description of a DFA 𝑀 is

where 𝛿 is given by the following table. Give the state diagram of this machine.

({𝑞(cid:2869), 𝑞(cid:2870), 𝑞(cid:2871), 𝑞(cid:2872), 𝑞(cid:2873)}, {𝑢, 𝑑}, 𝛿, 𝑞(cid:2871), {𝑞(cid:2871)}),

10)  Give state diagrams of DFAs recognizing the following languages. In all parts the alphabet is {0,1}.

a)  {w | w begins with a 1 and ends with a 0}

b)  {w | w contains at least three 1s}

c)  {w | w contains the substring 0101, i.e., w = x0101y for some x and y}

5

d)  {w |w has length at least 3 and its third symbol is a 0}

e)  {w | w starts with 0 and has odd length, or starts with 1 and has even length}

f)  {w | w doesn't contain the substring 1101}

6

g)  {w | w the length of w is at most 5}

h)  {w | w is any string except 11 and 1111}

i)  {w | every odd position of w is a 1}

7

j)  {w | w contains at least two 0s and at most one 1}

k)  {, 0}

l)  {w | w contains an even number of 0s, or contains exactly two ls}

8

m)  The empty set

n)  All strings except the empty string

11)  Show by giving an example that if 𝑀 is a DFA that recognizes language 𝐶, swapping the final and

non-final states in 𝑀 yields a new DFA that recognizes 𝐶̅.

9

12)  Design automata (DFA) to accept the following languages:

a)  A = {w {0, 1}* : w has a 1 in the third position from the right}.

b)  B = {w {0, 1}* : w contains at least two 0s}

c)  C = {w {0, 1}* : the length of w is divisible by three}

10

d)  D = {w {0, 1}* : w contains exactly two 0s and at least two 1s}.

13)   Give state diagrams of NFAs with the specified number of states recognizing each of the following

languages. In all parts the alphabet is {0,1}.
a)  The language {w | w ends with 00} with three states

b)  The language {w | w contains the substring 0101, i.e., w = x0101y for some x and y} with five

states

11

c)  The language {w | w contains an even number of 0s, or contains exactly two ls} with six states

d)  The language {0} with two states

e)  The language 0∗1∗0(cid:2878) with three states

f)  The language 1∗(001(cid:2878))∗ with three states

12

g)  The language {𝜀} with one state

h)  The language 0∗ with one state

14)    Use the construction given in Theorem 1.39 in the book to convert the following two non-

deterministic finite automata to equivalent deterministic finite automata.

15)   For the alphabet Σ(cid:2869) = {0,1}, answer the following questions for the automata machine shown below

13

0

1

0

1

1

0

1

1

a) Is the machine DFA or NFA? Why?

b) Give its regular expression.

c) Write the language which is a set consisting of strings that are recognized by this automaton.

16)    Give regular expressions describing the following languages:

a)  𝐴 = {𝑤 ∈ {0,1}∗ ∶  𝑤 contains at least three 1𝑠}.

b)  𝐵 = {𝑤 ∈ {0,1}∗ ∶  𝑤 contains at least two 1𝑠 and at most one 0},

c)  𝐶 = {𝑤 ∈ {0,1}∗ ∶  𝑤 contains an even number of 0𝑠 and exactly two 1𝑠}.

14

d)  𝐷 = {𝑤 ∈ {0, 1}∗ ∶  𝑤 contains an even number of 0𝑠 and each 0 is followed by at least one}

17)   Design a DFA or NFA for the following languages. n0(w) denotes the number of zeros in the string

w.
a)  L1 = { w {0, 1}* : n0(w) mod 2 = 0 },

b)  L2 = { w {0, 1}* : n0(w) mod 3 = 0 },

c)  Based on using the NFA and DFA you designed in the options a and b, design an NFA that

recognized the language L3 = { w{0, 1}* : n0(w) mod 6 = 0}.

Hint: De Morgan's Laws 𝐿(cid:2869) ∩ 𝐿(cid:2870) = (𝐿(cid:2869)(cid:3364)(cid:3364)(cid:3364) ∪ 𝐿(cid:2870)(cid:3364)(cid:3364)(cid:3364))

(cid:3364)(cid:3364)(cid:3364)(cid:3364)(cid:3364)(cid:3364)(cid:3364)(cid:3364)(cid:3364)(cid:3364)(cid:3364)(cid:3364) can be used for designing an  NFA that recognizes the intersection of

languages.

15



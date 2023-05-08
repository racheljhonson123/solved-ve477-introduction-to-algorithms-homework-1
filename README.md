Download Link: https://assignmentchef.com/product/solved-ve477-introduction-to-algorithms-homework-1
<br>
<strong>Reminders</strong>

<ul>

 <li>Write in a neat and legible handwriting or use L<sup>A</sup>TEX</li>

 <li>Clearly explain the reasoning process</li>

 <li>Write in a complete style (subject, verb, and object)</li>

 <li>Be critical on your results</li>

</ul>

<em>Questions preceded by a * are optional. Although they can be skipped without any deduction, it is important to know and understand the results they contain.</em>

<h1><strong>Ex. 1 — </strong>Hash tables</h1>

In this exercise we want to estimate the maximum number of keys per slot we can expect when inserting <em>n </em>keys into <em>n </em>slots of a hash table.

Given a hash table with <em>n </em>slots, <em>n </em>keys are equiprobably hashed to each slot. Let <em>M </em>denote the maximum number of keys in a slot once they have all been inserted.

<ol>

 <li>For any positive integer <em>k</em>, show that the probability <em>P<sub>k </sub></em>that exactly <em>k </em>keys hash to a same slot is</li>

</ol>

.

<ol start="2">

 <li>Prove that the probability <em>P<sub>k</sub></em>′ , for the slot with the most keys to have exactly <em>k </em>keys, is less or equal to <em>nP<sub>k</sub></em>.</li>

 <li>Prove that <em>P<sub>k </sub>&lt;e<sup>k</sup>/k<sup>k</sup></em>.</li>

</ol>

* 4. Show that for any positive integer <em>k </em>≥ <em>c </em>log <em>n/</em>log log <em>n</em>, for some constant <em>c &gt; </em>1, <em>P<sub>k</sub></em>′ <em>&lt; </em>1<em>/n</em><sup>2</sup>. 5. Denoting the expected value of <em>M </em>by <em>E</em>(<em>M</em>), observe that

<em>c </em>log <em>n E        </em>,

log log <em>n</em>

and conclude that <em>E</em>.

<em>Hint: </em>for question 3 apply Stirling formula.

<h1><strong>Ex. 2 — </strong>Minimum spanning tree</h1>

Let <em>G </em>be a graph and <em>T </em>be a minimum spanning tree for <em>G</em>. Write the pseudocode of an algorithm which determines the minimum spanning tree of the graph <em>G </em>when the weight of an edge not in <em>T </em>is decreased.

<h1><strong>Ex. 3 — </strong>Simple algorithms</h1>

* 1. Given two <em>n</em>-bits integers stored in two arrays, explain how to compute their sum in an <em>n </em>+ 1-bits array. Write the corresponding pseudocode.

<ol start="2">

 <li>One decides to multiply two integers <em>x </em>and <em>y </em>by writing a function mult(x,y) returning 0 if one of them is 0 and otherwise returning the sum of a recursive call on mult, with parameters 2<em>x </em>and ⌊<em>y/</em>2⌋, and <em>x </em>· (<em>y </em>mod 2).</li>

 <li>Express this algorithm as pseudo-code.</li>

 <li>Prove the correctness of this algorithm.</li>

</ol>

<strong>Ex. 4 — </strong><em>Problem</em>

Given twenty five horses determine the three fastest ones, in the right order, knowing that no more than five can race at a time. What is the minimum number of races necessary? Detail a general algorithm which solves the problem.

<h1><strong>Ex. 5 — </strong>Critical thinking</h1>

<ol>

 <li>The <em>Knapsack problem </em>is defined as follows. Given a set <em>S </em>and a number <em>n </em>find a subset of <em>S </em>whose elements add up exactly to <em>n</em>. Which of the following algorithms solve the Knapsack problem?</li>

</ol>

<ul>

 <li>Fit the knapsack with the smallest items first.</li>

 <li>Fit the knapsack with the largest items first.</li>

</ul>

* 2. In the course (Example 1.<strong>??</strong>) it is mentioned that <em>m </em>should be “a prime not too close from a power of 2” in order for the hash function <em>H</em>(<em>k</em>) = <em>k </em>mod <em>m </em>to be a good choice. Explain.

<ol start="3">

 <li>Provide an example of a greedy algorithm which is locally optimal while not being globally optimal.</li>

</ol>

Provide all the necessary details to support your claim.
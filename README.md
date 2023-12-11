# Fullstack Java My Java Mastermind
<div class="markdown-body">
<p class="text-muted m-b-15">
</p><h2>My Java Mastermind</h2>
<table>
<thead>
<tr>
<th>Technical details</th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td>Submit file</td>
<td>*</td>
</tr>
</tbody>
</table>
<hr>
<h3>SPECIFICATIONS</h3>
<p>Write a program called mastermind; it will be an implementation of the famous game.</p>
<h3>NAME</h3>
<p>my_mastermind</p>
<h3>SYNOPSIS</h3>
<p>my_mastermind [-ct]</p>
<h3>DESCRIPTION</h3>
<p>Mastermind is a game composed of 9 pieces of different colors.
A secret code is then composed of 4 distinct pieces.</p>
<p>The player has 10 attempts to find the secret code.
After each input, the game indicates to the player the number of well placed pieces and the number of misplaced pieces.</p>
<p>Pieces will be '0' '1' '2' '3' '4' '5' '6' '7' '8'.</p>
<p>If the player finds the code, they win, and the game stops.
A misplaced piece is a piece that is present in the secret code but is not in a good position.</p>
<p>You must read the player's input from the standard input.</p>
<p>Your program will also receive the following parameters:
-c [CODE]: specifies the secret code. If no code is specified, a random code will be generated.
-t [ATTEMPTS]: specifies the number of attempts; by default, the player has 10 attempts.</p>
<p><strong>Example 00</strong></p>
<pre class=" language-plain"><code class=" language-plain">PROMPT&gt;java my_mastermind -c "0123"
Will you find the secret code?
---
Round 0
&gt;1456
Well placed pieces: 0
Misplaced pieces: 1
---
Round 1
&gt;tata
Wrong input!
&gt;4132
Well placed pieces: 1
Misplaced pieces: 2
---
Round 2
&gt;0123
Congrats! You did it!
</code></pre>
<h3>Requirements</h3>
<ul>
<li>You will describe your project and how it works inside a README.md</li>
<li>You will provide a .gitignore.</li>
</ul>

<p></p>
</div>

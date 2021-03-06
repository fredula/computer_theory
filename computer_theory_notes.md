<table>
	<tr>
		<td colspan="3"><b>Chapter 1</b></td>
	</tr>
	<tr>
		<td><b>Automata</b></td>
		<td colspan="2">Something that works automatically.</td>
	</tr>
	<tr>
		<td colspan="3"><b>Chapter 2</b></td>
	</tr>
	<tr>
		<td colspan="3">Important Definitions</td>
	</tr>
	<tr>
		<td><b>Alphabet</b></td>
		<td colspan="2">A finite set of units, which is used to build structures. A set of characters. A = {a, b} is an example of an alphabet.</td>
	</tr>
	<tr>
		<td colspan="3">An alphabet can be used to build strings. aabaa is a valid string for the alphabet defined. As string is an ordered sequence of characters of the alphabet. </td>
	</tr>
	<tr>
		<td colspan="3">
			<ul>
				<li>&Sigma; = {a,b}</li>
				<li>&Sigma; = {0,1} //an alphabet the computer understands</li>
				<li>&Sigma; = {i,j,k}</li>
			</ul>
		 </td>
	</tr>
	<tr>
		<td><b>Strings</b></td>
		<td colspan="2">Concatenation of symbols from alphabet are called strings.</td>
	</tr>
	<tr>
		<td colspan="3">
			<ul>
				<li>&Sigma; = {a,b}</li>
			</ul>
			a,abab,abababababab are all valid strings.
		 </td>
	</tr>
	<tr>
		<td><b>Empty or null string</b></td>
		<td colspan="2">Every alphabet contains a string with no characters. This is the null or empty string.</td>
	</tr>
	<tr>
		<td colspan="3">An empty string is denoted by λ </td>
	</tr>
	<tr>
		<td><b>Length of a string</b></td>
		<td colspan="2">The lengh of a string is shown as |s|. It shows the numbers of letters in the string.</td>
	</tr>
	<tr>
		<td colspan="3">
			<ul>
				<li>&Sigma; = {a,b}</li>
				<li>s = ababa</li>
				<li>|s| = 5</li>
			</ul>
		 </td>
	</tr>
	<tr>
		<td><b>Reverse of a string</b></td>
		<td colspan="2">The reverse of a string is denoted by rev(s) or s^r for string s. It's the string written in reverse order.</td>
	</tr>
	<tr>
		<td colspan="3">
			<ul>
				<li>&Sigma; = {a,b,c}</li>
				<li>s = abc</li>
				<li>s^r = cba</li>
			</ul>
		 </td>
	</tr>
	<tr>
		<td><b>Kleene star or Kleene closure</b></td>
		<td colspan="2">We can apply the kleene star operator to a set. This creates a set of all possible strings. A = {0, 1} A* = {λ, 0, 1, 00, 01, 10,  11, 000, 001...} </td>
	</tr>
	<tr>
		<td><b>Language</b></td>
		<td colspan="2">A set of strings from the alphabet. A subset of the kleene closure can be considered a language.</td>
	</tr>
	<tr>
		<td><b>Words</b></td>
		<td colspan="2">Words are strings that are allowed in the langauge. Words can be thought of rules for the language.</td>
	</tr>
	<tr>
		<td colspan="3">
			<ul>
				<li>Here is the alphabet A. A = {0, 1, 2, 3}</li>
				<li>here we define the words B. B = {A finite string of alphabet letters not starting with 0}</li>
				<li>Here is the language C. C = {1, 2, 3}</li>
			</ul>
		</td>
	</tr>
	<tr>
		<td>Theorem 1</td>
		<td>For any set S of strings we have S* = S**</td>
		<td>Every word in S** is a factor of S*. Every word in S* is a factor in S. Therefore every word in S** is made up of factors in S.</td>
	</tr>
</table>
# Caesars-Cipher
One of the simplest and most widely known ciphers is a Caesar cipher, also known as a shift cipher. In a shift cipher, the meanings of the letters are shifted by some set amount.


<h2>Problem</h2>
<p>A common modern use is the <strong>ROT13</strong> cipher, where the values of the letters are shifted by 13 places. Thus <code>A ↔ N</code>, <code>B ↔ O</code> and so on.</p>
<p>Write a function that takes a <strong>ROT13</strong> encoded string as input and returns a decoded string.</p>

<h2>Solution</h2>
<p>All letters will be uppercase and we don't have to transform any non-alphabetic character (i.e. spaces, punctuation), but they are passed.</p>
<p>The codes and explanation comment are in the txt-format file</p>
<p>Also we can add a parameter to the main function and pass a shifting number as an argument to have a more flexible decoding program</p>

sassy-forms
===========

A SASS based form style generator

Sassy form is an SCSS file that allows you to create a variety of form styles by simply adding new base colors and replacing the values of the 2 variables:

<pre>$base</pre>
<pre>$buttonBase</pre>

Firstly, make sure you have SASS installed. Then:

<code>cd your-foder</code>

<code>sass --watch styles.scss:styles.css</code>

If you're using a dark $base color, you may want to add the class <code>'inverse'</code> to your form. For rounded input fields and buttons add the class <code>'rounded'</code> to the form element.

Demo: <a href="#" target="_blank">Here</a>

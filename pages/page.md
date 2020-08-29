Article title
=============

> here is some quoted text
> -- <cite>[here is a citation link](https://en.wikipedia.org/wiki/Main_Page)</cite>

### Big title

![alt text](page1.jpg "Here is some mouseover text for an image!")

Some generic text

<ol>
	<li>
		<a id="ex1">Fancy javascript 1</a>
		<img id="ex1a" title="A gif!" src="page2.gif"/>
	</li>
	<li>
		<a id="ex2">Fancy javascript 2</a>
		<blockquote id="ex2a">
			<a href="https://jekyllrb.com/docs/step-by-step/01-setup/">a link within html</a>
			<br>
			here is some stuff
		</blockquote>
	</li>
</ol>

[Markdown examples](https://www.markdownguide.org/basic-syntax/)

## Smaller Title
Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. The first line of Lorem Ipsum, "Lorem ipsum dolor sit amet..", comes from a line in section 1.10.32.

The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.




<script> // code comments
	setupExpandable("ex1");
	setupExpandable("ex2");

	function setupExpandable(id)
	{
		var ex = document.getElementById(id);
		var exa = document.getElementById(id+"a");

		exa.style.display="none";

		ex.onclick = exa.onclick = function()
		{
			if(exa.style.display == "block")
				exa.style.display = "none";
			else
				exa.style.display = "block"
		};
	}
</script>

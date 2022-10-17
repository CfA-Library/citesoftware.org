---
layout: page
title: Software Citation in BibTex
description: Use BibLaTeX or @software entry type
image: assets/images/X.jpg
nav-menu: true
permalink: /bibtex/
---
<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>If you are using BibTex to cite software</h1>
		</header>

<!-- Content -->
<h2 id="content">please use the @software entry type in your file.</h2>
<br>
<h3>For example:</h3>	
<pre><code>
@software{pong_key,
author = {Alcorn, Allan},
title = {Pong},
month = nov,
year = 1972,
doi = {10.1234/zenodo.12345},
url = {https://doi.org/10.1234/zenodo.12345},
version = {v1.0},
publisher = {Atari},
keywords = {video game, sports}
}

\bibitem[Alcorn, Allan (1972)]{pong_key} Alcorn, A.\ 1972, “Pong”, v1.0, Zenodo, doi:10.1234/zenodo.12345
</code></pre>
</div>

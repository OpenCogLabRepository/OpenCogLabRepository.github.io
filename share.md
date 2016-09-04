---
title: Sharing your experiment
layout: default
---



<div class="section">
	<div class="contaiiner text-justify">

        <p>Before you begin, we encourage you to archive your project in the <a href="https://zenodo.org/collection/user-opencoglabrepository">Zenodo OpenCogLab Repository Community</a> to receive a citable DOI.</p>

		<p>For sharing your experiment and putting it in this page, you need to create a simple <a href="https://guides.github.com/features/mastering-markdown/">markdown file</a>.
		This file contains all the data about the experiment that will appear here, organized in an easy computer-reading way.
		If you aren't familiar with markdown files, we provided an example below.
		</p>

		<p>The file should contain the relevant information about the experiment, namely:</p>

			<ul class="list-unstyled">
				<li><span class="label label-default">title</span></li>
				<li><span class="label label-default">authors</span> (who created the script in the repository)</li>
				<li><span class="label label-default">repository</span> (the open repository where the experiment scripts are, we recomend using a GitHub repository)</li>
				<li><span class="label label-default">environment</span> (library used for runing the script, such as <a href="http://visionegg.org/">VisionEgg</a> or <a href="http://www.psychopy.org/">PsychoPy)</a> </li>
				<li><span class="label label-default">category</span></li>
				<li><span class="label label-default">version</span> (if you don't know the version, write 1.0)</li>
				<li><span class="label label-default">published</span> (date the experiment was published in <a href="http://www.iso.org/iso/home/standards/iso8601.htm">ISO format</a>, YYYY-MM-DD)</li>
				<li><span class="label label-default">license</span></li>
				<li><span class="label label-default">dependencies</span> (any aditional library necessary to run the experiment)</li>
				<li><span class="label label-default">imgurl</span> (url of image that appears with the experiment descrioption. If you don't have one, use  <a href="https://avatars2.githubusercontent.com/u/10687121?v=3&s=200">this repository image</a>)</li>
				<li><span class="label label-default">bibtex</span> (url of <a href="http://www.bibtex.org/">bibtex</a> file containg all publications using the experiment)</li>
				<li><span class="label label-default">download</span> (url for downloading the repository)</li>
				<li><span class="label label-default">description</span> (short description about your experiment)</li>

			</ul>

		<br/>
		<p>Notice that the file name should be in the format <span class="label label-default">experiment_experimentname.md</span>.</p>

		<p>Danger! The <span class="label label-danger">layout</span> attribute and the <span class="label label-danger">---</span> in the begging and in the end of the file are for internal use, don't forget them!</p>

		

		

{% highlight markdown %}
---
title: Example Task
layout: experiment
authors: Danny
repository: https://github.com/OpenCogLabRepository/example-task
environment: VisionEgg
category: Motor Task
version: 1.4
published: 2015-05-19
license: MIT
dependencies: none
imgurl: https://avatars2.githubusercontent.com/u/10687121?v=3&s=200
bibtex: https://github.com/OpenCogLabRepository/example-task/cites.bib
download: https://github.com/OpenCogLabRepository/example-task/archive/master.zip
---

This is a short description about the experiment.
{% endhighlight %}

		

		<p class="m-top-50">Please email this file for <a href="mailto:cameron.craddock@childmind.org">cameron.craddock@childmind.org</a> and we'll upload your file as soon as we can.</p>

	</div>
</div>
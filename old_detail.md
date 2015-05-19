---
title: experiment detail
layout: default
---

<link rel="stylesheet" href="/css/bib-publication-list.css"/>

<script type="text/javascript">
	$(document).ready( function () {

		$('#property_list').DataTable({
	        searching: false,
	        paging: false,
	        ordering:  false,
	        info: false
    	});

	} );
</script>

<div id="detail" class="section">
	<h2 id="title">Moral Dilemma Task</h2>

	<div class="row">

		<div class="col-md-8">
			<p id="description" class="text-justify">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

			<div>
				<strong>Authors</strong>
				<span id="authors">João Hardcoded</span>
			</div>

			<div>
				<strong>#Memory</strong>
				<span id="category"></span>
			</div>

			<a href="#" class="btn m-top-50">Download Experiment</a>

		</div>		

		<div class="col-md-4">
			<table id="property_list" class="display" cellspacing="0" width="100%">
				<tbody>
					<tr>
			            <td><strong>Package</strong></td>
			            <td>Value</td>
				    </tr>
			        <tr>
			            <td><strong>Repository</strong></td>
			            <td>Value</td>
			        </tr>
			        <tr>
			            <td><strong>Environment</strong></td>
			            <td>Value</td>
				    </tr>
			        <tr>
			            <td><strong>category</strong></td>
			            <td>Value</td>
			        </tr>
			        <tr>
			            <td><strong>Version</strong></td>
			            <td>Value</td>
			        </tr>
			        <tr>
			            <td><strong>Published</strong></td>
			            <td>Value</td>
			        </tr>
			        <tr>
			            <td><strong>License</strong></td>
			            <td>Value</td>
			        </tr>
			        <tr>
			            <td><strong>Dependencies</strong></td>
			            <td>Value</td>
			        </tr>
			     
				</tbody>
			</table>
		</div>

	</div>


</div>


<noscript>
	<style>
		#bibtex { display: block;}
	</style>
</noscript>



<table id="pubTable" class="display"></table>
<script type="text/javascript" charset="utf8" src="/js/bib-list.js"></script> 


<script type="text/javascript">
    $(document).ready(function() {
        bibtexify("/adhd200_pubs.bib", "pubTable",{'tweet': 'RCCraddock'});
    });
</script>

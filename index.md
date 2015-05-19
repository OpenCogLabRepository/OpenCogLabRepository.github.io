---
title: hello
layout: default
---
<script type="text/javascript">
    $(document).ready( function () {

    var dataset = [
    	['experiment_moraldillema', 'moral dillema task', 'aaa', 'bbb', 'ccc'],
    	['experiment_test2', 'experiment test 2', '111', '222', '333']
    ]


    var table = $('#experiment_list').DataTable({
    	'data': dataset,
    	'columns': [
    		{'title': 'id', 'visible': false},
    		{'title': 'Title'},
    		{'title': 'Author'},
    		{'title': 'Environment'},
    		{'title': 'Category'}
    	],
        searching: false,
        paging: false,
        ordering:  true,
        info: false
    });

    $('#experiment_list tbody').on( 'click', 'tr', function () {

    	var experiment_id = table.row( this ).data()[0];


     	window.location.replace('/' + experiment_id + '.html');
    	window.location.href = '/' + experiment_id + '.html';
	} );

} );
</script>


<div class="section">

	<div class="row">
		<div class="col-md-10 text-center col-md-offset-1">
			<div class="col-md-8">
				<p class="text-justify">
					Open Cog Lab Repository is a open source initiative for sharing functional MRI experiments.
					You have access to experiments created by neuroscience laboratories.
					A variety of tasks for assessing different cognitive functions is available for download.
				</p>
			</div>
			<div class="col-md-2"> <i class="fa fa-file fa-3x"></i></div>
		</div>
	</div>

	<div class="row m-top-50 text-center">
		<div class="col-md-10 ">
			<div class="col-md-2"> <i class="fa fa-code-fork fa-3x"></i> </div>
			<div class="col-md-8">
			<p class="text-justify">
				Be social and share your own experiments! Help the community lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
			</p>
			</div>
		</div>
	</div>


	<div class="row text-center m-top-50">
		<a href="/share.html" class="btn">Share your own experiment</a>
	</div>

<!-- 	<h2>Available experiments</h2> -->

	<div class="m-top-150">
		<table id="experiment_list" class="display " cellspacing="0" width="100%">
	
		</table>
	</div>
</div>
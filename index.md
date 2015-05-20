---
title: hello
layout: default
---
<script type="text/javascript">
    $(document).ready( function () {

    var dataset = [
    	['experiment_visualcheckboard', 'Visual Checkerboard', 'Cameron Craddock', 'VisionEgg', '???'],
    	['experiment_breathholding', 'Breath Holding', 'Cameron Craddock', 'VisionEgg', '???'],
    	['experiment_RTfMRIneurofeedback', 'RTfMRI Neurofeedback', 'Cameron Craddock', '???', '???'],
    	['experiment_moraldillema', 'Moral Dillema', 'Ben Harrison et al', 'PsychoPy', '???'],
    	['experiment_msit', 'The Multi-Source Interference Task', 'Bush, G, Shin, LM ', 'PsychoPy', '???']
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

<div class="col-md-10 col-md-offset-2 m-bot-50">
	<div class="row">
		
			<div class="col-md-8">
				<p class="text-justify">
					Open Cog Lab is a repository of openly shared computerized experiments for assessing cognitive function.
					A variety of tasks for assessing different cognitive functions are available for download.
				</p>
			</div>
<!-- 			<div class="col-md-2"> <i class="fa fa-share-alt fa-3x"></i></div> -->
		
	</div>

<!-- 	<div class="row m-top-50 text-center">
		
			<div class="col-md-2"> <i class="fa fa-code-fork fa-3x"></i> </div>
			<div class="col-md-8">
			<p class="text-justify">
				Be social and share your own experiments! Help the community lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
			</p>
			
		</div>
	</div> -->

</div>


<!-- 	<div class="row text-center m-top-50">
		<a href="/share.html" class="btn">Share your own experiment</a>
	</div> -->

<!-- 	<h2>Available experiments</h2> -->

	<div class="m-top-50">
		<table id="experiment_list" class="display " cellspacing="0" width="100%">
	
		</table>
	</div>
</div>
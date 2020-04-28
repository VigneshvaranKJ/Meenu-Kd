#    730 days to go ma(dam).. ... .<span style='font-size:25px;'>&#128541;</span><span style='font-size:25px;'>&#128150;</span>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Fireworks.js</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="">
    <meta name="author" content="">
    <!-- Le styles -->
    <link href="http://twitter.github.com/bootstrap/assets/css/bootstrap.css" rel="stylesheet">
    <style>
      body {
        padding-top: 60px; /* 60px to make the container go all the way to the bottom of the topbar */
      }
    </style> 
    <link href="http://twitter.github.com/bootstrap/assets/css/bootstrap-responsive.css" rel="stylesheet">

    <!-- Le HTML5 shim, for IE6-8 support of HTML5 elements -->
    <!--[if lt IE 9]>
      <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->

    <!-- Le fav and touch icons -->
    <link rel="shortcut icon" href="http://twitter.github.com/bootstrap/assets/ico/favicon.ico">
    <link rel="apple-touch-icon-precomposed" sizes="114x114" href="http://twitter.github.com/bootstrap/assets/ico/apple-touch-icon-114-precomposed.png">
    <link rel="apple-touch-icon-precomposed" sizes="72x72" href="http://twitter.github.com/bootstrap/assets/ico/apple-touch-icon-72-precomposed.png">
    <link rel="apple-touch-icon-precomposed" href="http://twitter.github.com/bootstrap/assets/ico/apple-touch-icon-57-precomposed.png">
  </head>

  <body>

    <div class="navbar navbar-fixed-top">
      <div class="navbar-inner">
        <div class="container">
          <a class="btn btn-navbar" data-toggle="collapse" data-target=".nav-collapse">
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </a>
          <a class="brand" href="#">Fireworks.js</a>
          <div class="nav-collapse">
            <ul class="nav">
              <li><a href="https://github.com/jeromeetienne/fireworks.js">Github</a></li>
              <li><a href="#examples">Examples</a></li>
              <li><a href="https://twitter.com/#!/jerome_etienne">Twitter</a></li>
            </ul>
          </div><!--/.nav-collapse -->
        </div>
      </div>
    </div>

    <div class="container">
	<!-- Main hero unit for a primary marketing message or call to action -->
	<div class="hero-unit">
		<h1>Fireworks.js</h1>
		<p>Fireworks is a particle engine based on a very slim core and rich set of flexible plugins.
		You can easily make your own plugins to fit your own needs and go wild on creativity.</p>
		<p><a class="btn btn-primary btn-large" href="https://github.com/jeromeetienne/fireworks.js">Learn more &raquo;</a></p>
	</div>
	<div class="page-header" id="examples">
		<h1>Examples</h1>
	</div>
	<div class="row">
		<div class='span3'>
			<div class="thumbnail">
				<div class="caption">
					<h5>Canvas renderer</h5>
					<p>
						This is a very basic example with a rendering
						in Canvas2D
					</p>
					<p>
						<a href="examples/renderer_canvas/canvas_example.html" class="btn" target='_blank'>Learn more &raquo;</a>
					</p>
				</div>
			</div>
		</div>
		<div class='span3'>
			<div class="thumbnail">
				<div class="caption">
					<h5>Canvas renderer</h5>
					<p>
						This is a explosion animation with a spritesheet and a rendering
						in Canvas2D
					</p>
					<p>
						<a href="examples/renderer_canvas/canvas_explosion.html" class="btn" target='_blank'>Learn more &raquo;</a>
					</p>
				</div>
			</div>
		</div>
		<div class='span3'>
			<div class="thumbnail">
				<div class="caption">
					<h5>three.js renderer</h5>
					<p>
						This is a very basic example with a rendering
						in three.js particle system
					</p>
					<p>
						<a href="examples/renderer_threejs/tqueryparticlesystem.html" class="btn" target='_blank'>Learn more &raquo;</a>
					</p>
				</div>
			</div>
		</div>
		<div class='span3'>
			<div class="thumbnail">
				<div class="caption">
					<h5>three.js renderer</h5>
					<p>
						This is a very basic example with a rendering
						in three.js object3D
					</p>
					<p>
						<a href="examples/renderer_threejs/tqueryobject3d.html" class="btn" target='_blank'>Learn more &raquo;</a>
					</p>
				</div>
			</div>
		</div>
		<div class='span3'>
			<div class="thumbnail">
				<div class="caption">
					<h5>Flame thrower Canvas</h5>
					<p>
						This is an attempts to reproduce
						tremulous flamethrower in Canvas2D
					</p>
					<p>
						<a href="examples/flamethrower/canvas_flamethrower.html" class="btn" target='_blank'>Learn more &raquo;</a>
					</p>
				</div>
			</div>
		</div>
		<div class='span3'>
			<div class="thumbnail">
				<div class="caption">
					<h5>Flame thrower webgl</h5>
					<p>
						This is an attempts to reproduce
						tremulous flamethrower in webgl
					</p>
					<p>
						<a href="examples/flamethrower/webgl_flamethrower.html" class="btn" target='_blank'>Learn more &raquo;</a>
					</p>
				</div>
			</div>
		</div>
		<div class='span3'>
			<div class="thumbnail">
				<div class="caption">
					<h5>Single Flame webgl</h5>
					<p>
						It shows how to code a single flame emitter
					</p>
					<p>
						<a href="examples/flame/flame.html" class="btn" target='_blank'>Learn more &raquo;</a>
					</p>
				</div>
			</div>
		</div>
		<div class='span3'>
			<div class="thumbnail">
				<div class="caption">
					<h5>Black Smoke webgl</h5>
					<p>
						It shows how to code a black smoke emitter
					</p>
					<p>
						<a href="examples/smoke/webgl_blacksmoke.html" class="btn" target='_blank'>Learn more &raquo;</a>
					</p>
				</div>
			</div>
		</div>
		<div class='span3'>
			<div class="thumbnail">
				<div class="caption">
					<h5>Space Portal webgl</h5>
					<p>
						It shows how to code
						Space Portal emitter
					</p>
					<p>
						<a href="examples/spaceportal/spaceportal.html" class="btn" target='_blank'>Learn more &raquo;</a>
					</p>
				</div>
			</div>
		</div>
		<div class='span3'>
			<div class="thumbnail">
				<div class="caption">
					<h5>Cloud with Sprite</h5>
					<p>
						This is a copy of the <a href="http://mrdoob.com/lab/javascript/webgl/clouds/">cloud demo</a>
						from
						<a href="http://mrdoob.com/">mrdoob</a>.
						It shows how to code the effect with fireworks.js
					</p>
					<p>
						<a href="examples/cloud/cloud_uniform.html" class="btn" target='_blank'>Learn more &raquo;</a>
					</p>
				</div>
			</div>
		</div>
		<div class='span3'>
			<div class="thumbnail">
				<div class="caption">
					<h5>Cloud with Sprite</h5>
					<p>
						This is a copy of the <a href="http://mrdoob.com/lab/javascript/webgl/clouds/">cloud demo</a>
						from
						<a href="http://mrdoob.com/">mrdoob</a>.
						It shows how to code the effect with fireworks.js
					</p>
					<p>
						<a href="examples/cloud/cloud_cluster.html" class="btn" target='_blank'>Learn more &raquo;</a>
					</p>
				</div>
			</div>
		</div>
    </div> <!-- /container -->

    <!-- Le javascript
    ================================================== -->
    <!-- Placed at the end of the document so the pages load faster -->
    <script src="http://twitter.github.com/bootstrap/assets/js/jquery.js"></script>
    <script src="http://twitter.github.com/bootstrap/assets/js/bootstrap-transition.js"></script>
    <script src="http://twitter.github.com/bootstrap/assets/js/bootstrap-alert.js"></script>
    <script src="http://twitter.github.com/bootstrap/assets/js/bootstrap-modal.js"></script>
    <script src="http://twitter.github.com/bootstrap/assets/js/bootstrap-dropdown.js"></script>
    <script src="http://twitter.github.com/bootstrap/assets/js/bootstrap-scrollspy.js"></script>
    <script src="http://twitter.github.com/bootstrap/assets/js/bootstrap-tab.js"></script>
    <script src="http://twitter.github.com/bootstrap/assets/js/bootstrap-tooltip.js"></script>
    <script src="http://twitter.github.com/bootstrap/assets/js/bootstrap-popover.js"></script>
    <script src="http://twitter.github.com/bootstrap/assets/js/bootstrap-button.js"></script>
    <script src="http://twitter.github.com/bootstrap/assets/js/bootstrap-collapse.js"></script>
    <script src="http://twitter.github.com/bootstrap/assets/js/bootstrap-carousel.js"></script>
    <script src="http://twitter.github.com/bootstrap/assets/js/bootstrap-typeahead.js"></script>

	<!-- Github ribbon -->
	<a href="https://github.com/jeromeetienne/fireworks.js/" target="_blank"><img style="position: fixed; top: 0; right: 0; border: 0; z-index: 9999;"
	    src="https://s3.amazonaws.com/github/ribbons/forkme_right_red_aa0000.png" alt="Fork me on GitHub">
	</a>
  </body>
</html>

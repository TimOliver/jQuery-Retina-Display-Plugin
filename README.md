# jQuery Retina Display Plugin
#### A lightweight plugin to allow dynamic downloading of assets for Retina display devices

Based off the jQuery Retina plugin originally by Troy Mcilvena (http://www.troymcilvena.com)

##Usage:

$.retinaOptions({'retinaSuffix':'2x'});

$(element).retina();

###Example:

    <script src="js/jquery.retina.js" type="text/javascript" charset="utf-8"></script>

    <script type="text/javascript">
	    $(document).ready(function() {
		    $('img.retina').retina();
	    });
    </script>

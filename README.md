FontAwesome SASS Mixins
=======================

Easy to use SASS mixins for Font Awesome.

Built on FontAwesome version 4.1.0.

Usage:
------

    @import "font-awesome.scss";

    .heart {
    	@include icon($icon-heart);

    	&:before {
    		color: red;
    	}
    }

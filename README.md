FontAwesome SASS Mixins
=======================

Easy to use SASS mixins for Font Awesome.

    @import "font-awesome.scss";

    .heart {
    	@include icon($icon-heart);

    	&:before {
    		color: red;
    	}
    }
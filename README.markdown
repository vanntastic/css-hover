CSS Hover
=========

Give IE the :hover pseudo selector

INSTALL and USAGE
=================

    <!--[if IE]>
       <style type="text/css" media="screen">
         body { behavior:url("csshover3.htc"); }
       </style>      
    <![endif]-->

Now you can do something like this:
    
    /* IE will properly render this */
    li:hover{
      background:#eee;
    }


Original Source : http://www.xs4all.nl/~peterned/csshover.html
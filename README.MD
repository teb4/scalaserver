

  Scala simple multi-threaded ( actors ) http server with banner view ( schematic )


     1. Start server:

           ./server     

        and wait to:

           Listening at port 8080

     2. Request:

          a) curl:

	    curl -i http://localhost:8080     			// for home page
	    curl -i http://localhost:8080/stats			// for banner view statistics page ( for banners with id = 1,2,3 only )
	    curl -i http://localhost:8080/banner/1              // for view banner with id = 1 ( only return page with <img src="http://localhost:8080/banner/1">) 
	      
	  b) browsers:

            http://localhost:8080                              // for home page
	    http://localhost:8080/stats			       // for banner view statistics page ( for banners with id = 1,2,3 only )
	    http://localhost:8080/banner/1                     // for view banner with id = 1 ( only return page with <img src="http://localhost:8080/banner/1">) 
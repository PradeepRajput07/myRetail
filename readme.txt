Steps to run the application

1. Download the application.
2. Run the command: java -jar <download-file-name>
3. The application will run on port 8085

Testing the APi functionality:
1. Use the browser or POSTMAN to check the api functionality.

=================================================================================================================
1. GET Request for finding an existing product price
	http://localhost:8085/products/13860428
	If the product is available details will be served else empty json will be returned
================================================================================================================
2. PUT request for updating the product price
	http://localhost:8085/products/13860428
	The update will happen, only if the product id is same in url and body request.Else error will be printed on the console.
	To verify that the product price is updated, just hit the get request again, 
=====================================================================================================================
3. POST request for updating the product price
	http://localhost:8085/products/
	and passon the json as the request body.
==================================================================================================================

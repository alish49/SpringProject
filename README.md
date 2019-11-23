# SpringProject
A web application that can return ratings and reviews for restaurants.
A review contains user information, comments, a rating and a date. The responses from this application will be consumed by either front-end or server applications.

#Endpoints
Return reviews for a single restaurant, sorted by date from newest to oldest.
Return restaurants that serve a particular type of food (e.g, Pizza), sorted from highest to lowest average rating.
Add a review to a restaurant

Runtime
The application should support curl requests against any of the API endpoints. Please provide example curl requests with
the data you used to test/run the application.

Example:
curl -XPOST http://localhost:8080/your/review/endpoint
-H 'accept: application/json'
-d '{
    your_review_json: your_review_json_data
}'

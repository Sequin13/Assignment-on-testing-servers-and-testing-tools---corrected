# Assignment-on-testing-servers-and-testing-tools
This repository contains two collections of requests of APIs. The collections were made with Postman application.
  - Requests to GoalsAPI - Testing API's methods of GoalsAPI - API created with FastAPI (Python Library), based on localhost
  - Requests to TheCatAPI - Testing API's methods of TheCatAPI - API created and managed by https://thatapicompany.com
I chose TheCatAPI because I love cats :)

Requests to GoalsAPI: 
  1. GET - Get Goals - checking all goals saved in the database
  2. GET - Get goal by username - displaying the user's goal
  3. POST - Progress inserting - inserting progress of the goal
  4. DELETE - Delete goal - deleting goal
  5. PUT - Goal updates - changing the id, title, due_date, frequency, progress of the goal

Requests to TheCatAPI:
  1. GET - Getting a photo of cats by ID - displaying a photo of the cat, using ID of image
  2. GET - Filters photos of cats - filtration photos of the cats, using:
       - size - resolution of the photo
       - mime_types - extension of the photo (.jpg, .gif, .png, etc.)
       - order - order of displayed results
       - limit - numer of displayed results
  3. POST - Posting photos to favourites - saving photos to favourites section
  4. DELETE - Deleting photos from favourites - removing photos from favourites section
  5. POST - Posting votes of photos - adding number of votes to given photo

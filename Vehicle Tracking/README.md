**VEHICLE TRACKING**

To avoid the vehicle theft and minimize the search distance of theft vehicle.
It is used to find the absolute path of the vehicle by using number plate of the vehicle.

**Project Description:**
  components used:
        camera
        image
        database
  Technologies used:
        python
        MySQL
        GUI
        Image processing
        OCR
  
Lets consider a scenario,My vehicle is theft by someone.My solution is to search a vehicle in random direction and asking about my vehicle to the people
and filed a complain in police station.This takes lots of time to find my vehicle.To solve my problem I introduced OCR to find the vehicle easyily.
  
I used the trafiic and street cameras to capture the image of the vehicle and crop the number plate of the image and pass it into OCR.
It convert the image into numeric format and store the vehicle number,time of the image,image,date of the image into database.
Search the number of the vehicle in our database to get the result as car passes the camera or not.

Problems faced:
  Capturing and segmentation of image.
  Quality of the image is poor.
  Go and search the number in each areas of the camera.
  
Future Extension:
  Segment the each images and parse the image into various categories and store it into databases.Connect all the databases of each camera from main database to get the full 
  path of the vehicle in single search.

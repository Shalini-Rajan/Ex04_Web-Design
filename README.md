# Ex.04 Images as Hyperlinks
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
  
## CODE
```<html>
<head>
<title>Agri Search Engine</title>
</head>
<body>
<h1 align="center">AGRI SEARCH ENGINE</h1>
<h3>
IRRIGATION:
<a href="https://www.google.com/search?q=irrigation&source=lmns&rlz=1C1CHBD_enIN1033IN1033&hl=en&sa=X&ved=2ahUKEwiks9CDpL__AhX373MBHansBQYQ_AUoAHoECAEQAA">
<img src="irrigationimage.jpeg" height="200" width="200">
</a>
<br>
<br>
SOWING:
<a href="https://www.google.com/search?q=sowing&rlz=1C1CHBD_enIN1033IN1033&oq=sow&aqs=chrome.0.69i59j69i57j0i67i650j46i131i433i512j0i67i433i650j0i67i650j0i3j0i67i650j0i131i433i512j0i512.53163657j0j15&sourceid=chrome&ie=UTF-8">
<img src="sowing.jpeg" height="200" width="200">
</a>
<br>
<br>
TRACTOR:
<a href="https://www.google.com/search?q=tractor&oq=&aqs=chrome.0.35i39i362l8.53408098j0j15&sourceid=chrome&ie=UTF-8">
<img src="tractorimage.jpeg" height="200" width="200">
</a>
<br>
<br>
SOWNG MACHINE:
<a href="https://www.google.com/search?q=sowing+machine&rlz=1C1CHBD_enIN1033IN1033&sxsrf=APwXEdfICT1IPCalS_0upBxBkggswOL7UA:1686626856205&source=lnms&tbm=isch&sa=X&ved=2ahUKEwi0vIfVpr__AhUBZmwGHQe4AioQ_AUoAXoECAEQAw">
<img src="sowingmachine.jpeg" height="200" width="200">
</a>
<br>
<br>
FERTILIZER:
<a href="https://www.google.com/search?q=fertilizer&source=lmns&rlz=1C1CHBD_enIN1033IN1033&hl=en&sa=X&ved=2ahUKEwiZyPajp7__AhWyx6ACHWG6DbcQ_AUoAHoECAEQAA">
<img src="fertilizer.jpeg">
</a>
</body>
</html>
```

## OUTPUT

![modelpracticaloutput1](https://github.com/Shalini-Rajan/Ex04_Web-Design/assets/128398163/0558f115-e165-4161-835b-e4bcddf01349)

                                           

## RESULT
 Images as hyperlinks is implemented successfully.

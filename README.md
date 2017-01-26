# Advance-Template-match
Find template (Itm) in the canny edge of image of grayscale image (Is).
Return the location of the template in the image and the score of the best match. 
Show the image (Is) with the template marked on it. 
INPUT: 
1) Grayscale image where the template should be found (Is). 
2) The template Binary image (Itm). 
Method: Use the difference between the edge density on the template and around the template to get the match score. Work better than regular template match for images with dense features and noise. 
The template size and the object size to be recognised in the image must be the same. For the similar function that recognises the template in in the image variable of sizes relative to the image see “Advance template match variable image to template size ratio”.

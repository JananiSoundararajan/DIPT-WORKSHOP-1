# DIPT-WORKSHOP-1
### DESCRIPTION
1.Take any one of the image like plant, Tree, flower or building.

2.Read the image and write the image withyour name as filename(eg, elsa.jpg).

3.Convert the file into Gray Scale image and HSV image.

4.Display the H, S and V planes.
   
### PROGRAM
```python
import cv2
image=cv2.imread('birdie.jpeg')
cv2.imshow('JANANI',image)
cv2.waitKey(0)
cv2.destroyAllWindows()

#converting color image into gray image
gray = cv2.cvtColor(image,cv2.COLOR_BGR2GRAY)
cv2.imshow('GRAY',gray)
cv2.waitKey(0)
cv2.destroyAllWindows()


#converting color image into HSV image
hsv = cv2.cvtColor(image,cv2.COLOR_BGR2HSV)
cv2.imshow('HSV',hsv)
cv2.waitKey(0)
cv2.destroyAllWindows()

#splitting H,S,V planes
H,S,V=cv2.split(image)
cv2.imshow('Hue',H)
cv2.imshow('Saturation',S)
cv2.imshow('Value',V)
cv2.waitKey(0)
cv2.destroyAllWindows()
```

### OUTPUT 

#### Original image:
![VI](https://github.com/JananiSoundararajan/DIPT-WORKSHOP-1/assets/119477549/3a1e9942-c47e-43fe-9cfc-f1972baaba24)

#### Converting color image into gray image:
![GRAY](https://github.com/JananiSoundararajan/DIPT-WORKSHOP-1/assets/119477549/7d1f0fe2-104f-44aa-b14e-7bc75122fb52)

#### Converting color image into HSV image:
![HSV](https://github.com/JananiSoundararajan/DIPT-WORKSHOP-1/assets/119477549/cc10e515-ffce-421f-ba5f-cb3004f9151d)

### Splitting the image into H,S,V planes:
![HSV planes](https://github.com/JananiSoundararajan/DIPT-WORKSHOP-1/assets/119477549/a4a7c1ec-252f-43d3-a29e-1d3279d1ac11)

### RESULT:
Therefore the picture is converted into Gray,HSV image and split into H,S,V planes sucessfully using python.


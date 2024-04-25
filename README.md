# Image_Dehazing_Desmoking
An Image Dehazing and Desmoking Algorithm that uses the "image_dehazer" library to remove haze and gradio framework for the interface
# Required Libraries
!pip install image_dehazer 
!pip install gradio

# Procedure
The code should generate a gradio link, Click on it
Drag and drop your image with haze in it , to generate a haze free image on the left output panel

# Details
The image_dehazer library's remove_haze() Function was used which uses the HazeMap to remove the haze from the image that the user gives as an input. Gradio was used to build an interface that integrates the backend python file with a frontend so that the project is more interactive and cohesive to the user.

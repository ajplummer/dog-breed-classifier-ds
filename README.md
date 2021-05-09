# Using Data Science to Classify Dog Images
This work was completed as my capstone project for Udacity's Data Scientist for Enterprise course.

## Installation
The main content of this repository is a Jupyter Notebook running on Python 3.0.

To run the notebook you will need:
- Python 3.0
- Sklearn
- Numpy
- Pandas
- Keras
- Glob
- Random
- CV2
- Matplotlib
- TQDM
- PIL
- Juypter

## Project Motivations
This project spoke to me based upon my experience.

In my last role, I managed websites that would allow users to upload an image. Our expectation was that the images should be of a human's face. However, many times people uploaded images of animals or objects or full bodies, etc., which were not what we wanted. These images had to be manually (by a human) rejected and an email sent to the user to reupload a new photo.

We tried implementing an automated rejection mechanism that could give users instant feedback on their image but were not able to get it working well enough. I thought this could be an opportunity for me to see how well I could do with something similar.

## File Descriptions
- dog_app.ipynb - This is the Jupyter Notebook storing my code and markdown related to the project.
- README.md - This file.

## How to Interact with This Project
The best way to interact with this project is to open up the Notebook and browse through the code. The Notebook was saved with all code run so you can just look at the output (and my commentary) without having to re-run everything yourself. Feel free to edit the code and re-run if desired.

## Results
Utilizing a pre-trained Resnet-50 model in my CNN, I was able to attain ~80% accuracy on the test dataset in my Notebook. This shows me that building a successful model for an automated rejection mechanism is indeed possible and has given me the confidence to move forward with doing so.

## Licensing, Authors, Acknowledgements, Etc.
The data was provided to me by Udacity.

The code was written by me, A.J. Plummer, with some functions copied (either word-for-word or in spirit) from Udacity coursework. Those functions are noted in the comments in the Notebook itself.

Thank you to Udacity for putting together a great "real world" exercise for us and to my company, Mars, Inc., for enabling me to take on this course!

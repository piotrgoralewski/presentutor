# PresenTutor
Where every slide tells a story.

Repository for "PresenTutor" solution for IBM TechXchange Pre-Conference watsonx Hackathon.

This repo belongs to `EYTIZ` team. Authors are Piotr Góralewski, Monika Rabiej and Grzegorz Jaszczura.

## How to install and run

All required libraries are listed in `requirements.txt` file. You can install them using pip: `pip install -r requirements.txt`.

When you have all the requirements installed, you can run the app using Python: `python app.py`.

The app does not require any other preparation. You can view the app in your browser by going to [http://127.0.0.1:5000/](http://127.0.0.1:5000/) address.

## Repo content

In the `static` dir you can find `main.css` file, which describes how the app looks like.

`templates` dir contains `index.html` which contains the main page of the app, as well as JavaScript codes to embed the IBM Watson Assistant in the page.

Python `app.py` file represents backend of the application, writen using Flask.

## Additional info

You can also play with the copilot [here](https://web-chat.global.assistant.watson.appdomain.cloud/preview.html?backgroundImageURL=https%3A%2F%2Fjp-tok.assistant.watson.cloud.ibm.com%2Fpublic%2Fimages%2Fupx-24a61468-110e-4043-b375-057d2ab8cf40%3A%3Ab2bcb7e0-528d-466f-90a8-74d83f89210d&integrationID=096a39e6-256a-46ac-935f-99216e5c4729&region=jp-tok&serviceInstanceID=24a61468-110e-4043-b375-057d2ab8cf40) (remember to click blue icon at bottom right corner), but this environment does not utilize full potential of the app. Some functionalities will be less automated than in the app.

Also, [here you can find our video presentation of the app](https://youtu.be/XqWehgsKipg).

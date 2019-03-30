# Heritage-Recognition-with-Deep-Learning

#To train and use deep learning model:

1. Install Depemdncies: python - 3.5.5, keras-2.2.0, matplotlib - 2.2.2, numpy - 1.15.0, opencv - 3.4.1, pillow- 5.2.0, scikit-learn - 0.19.1, tensorflow - 1.9.0
2. Download and extract DL model for Heritages folder.
3. Download image dataset from this link https://drive.google.com/open?id=1XBWU8mc81FJMYFcs8O4nzcxrIo5iTrM7 and extract inside        previous folder.
4. Open CMD(Command Prompt) from inside the folder and run 'VGG16_Custom.py' -->> python VGG16_Custom.py
5. Model is trained and saved as 'trained_model.hdf5'
6. To recognise an image with trained model run 'recogniser.py' -->> python recogniser.py
7. Select a photo from Test images folder and output will be displayed in console.

#To run Web Application:

 1. Install dependencies: python - 3.5.5, django-1.9.2, keras-2.2.0, matplotlib - 2.2.2, numpy - 1.15.0, opencv - 3.4.1, pillow-      5.2.0, scikit-learn - 0.19.1, tensorflow - 1.9.0
2. Download and extract Heritages WebApp folder.
3. Open CMD(Command Prompt) from inside the folder.
4. Run command 'python manage.py runserver' and copy server address.
5. Enter server adress in a web browser and WebApp is ready to use.

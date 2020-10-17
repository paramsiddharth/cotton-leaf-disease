# Cotton Leaf Disease Prediction
An implementation of a cotton leaf disease prediction machine learning model in TensorFlow. The model was trained by Ritesh ([@DARK-art108](https://github.com/DARK-art108)). The application operates via a web interface where one may upload an image of a cotton plant/leaf and retrieve the prediction of whether or not it is infected.

## Execution
 - Install all the PyPI requirements.
   ```
   > pip3 install -r requirements.txt
   ```
 - Manually place the model file `model_resnet.hdf5` in the application directory (optional).
 - Start the Flask server.
   ```
   > flask run
   ```
   Make sure that the `FLASK_APP` enviroment variable is either empty or set to `app.py`. You can manually do that by executing `export FLASK_APP=app.py`.
   
   The application will try to locate the model i. e. `model_resnet.hdf5` in the current directory, and if it is not found, download it.

Made with ❤ by [Ritesh](https://github.com/DARK-art108) and [Param](http://www.paramsid.com).
# 👩🏻‍💻 AUTHOR
Aya El Janoussi

# 🚦 Traffic Sign Classifier App
Here's the link if you want to try it out: 👉 [Here](https://aya-traffic-sign-classification.streamlit.app/) 👈

The Traffic Sign Classifier is a machine learning-powered web application designed to identify and classify various traffic signs from uploaded images. This application is built using the Streamlit framework along with TensorFlow, enabling users to interactively analyze traffic signs in real-time.

## 🎯 Purpose
The primary goal of this app is to assist in the automatic recognition and classification of traffic signs commonly found on roads and highways. By leveraging a pre-trained machine learning model, the app predicts the class of a traffic sign from an image input, providing instant information about the identified sign's meaning or purpose.

## 🚗 Traffic Sign Classes
The Traffic Sign Classifier app can identify and classify images that belong to various traffic sign classes:

| Class ID | Traffic Sign Description                      |
|----------|-----------------------------------------------|
| 0        | Speed limit (20km/h)                          |
| 1        | Speed limit (30km/h)                          |
| 2        | Speed limit (50km/h)                          |
| 3        | Speed limit (60km/h)                          |
| 4        | Speed limit (70km/h)                          |
| 5        | Speed limit (80km/h)                          |
| 6        | End of speed limit (80km/h)                   |
| 7        | Speed limit (100km/h)                         |
| 8        | Speed limit (120km/h)                         |
| 9        | No passing                                    |
| 10       | No passing veh over 3.5 tons                  |
| 11       | Right-of-way at intersection                  |
| 12       | Priority road                                 |
| 13       | Yield                                         |
| 14       | Stop                                          |
| 15       | No vehicles                                   |
| 16       | Veh > 3.5 tons prohibited                     |
| 17       | No entry                                      |
| 18       | General caution                               |
| 19       | Dangerous curve left                          |
| 20       | Dangerous curve right                         |
| 21       | Double curve                                  |
| 22       | Bumpy road                                    |
| 23       | Slippery road                                 |
| 24       | Road narrows on the right                     |
| 25       | Road work                                     |
| 26       | Traffic signals                               |
| 27       | Pedestrians                                   |
| 28       | Children crossing                             |
| 29       | Bicycles crossing                             |
| 30       | Beware of ice/snow                            |
| 31       | Wild animals crossing                         |
| 32       | End speed + passing limits                    |
| 33       | Turn right ahead                              |
| 34       | Turn left ahead                               |
| 35       | Ahead only                                    |
| 36       | Go straight or right                          |
| 37       | Go straight or left                           |
| 38       | Keep right                                    |
| 39       | Keep left                                     |
| 40       | Roundabout mandatory                          |
| 41       | End of no passing                             |
| 42       | End no passing veh > 3.5 tons                 |

## 🔑 Key Features
- **Traffic Sign Classification:** Users can upload an image containing a traffic sign, and the app will predict its class from a set of predefined categories.
- **Real-time Prediction:** The application provides instant feedback on the predicted traffic sign class based on the uploaded image.
- **User-Friendly Interface:** With a simple and intuitive design, users can easily interact with the app, allowing anyone to use it without prior expertise.

## 💡 How It Works
The app uses a machine learning model trained on a dataset of various traffic sign images. Upon image upload, the model analyzes the image, extracts relevant features, and predicts the most likely class of the traffic sign depicted in the image. The predicted class is then displayed to the user along with its meaning.

## 🎓 Intended Use
The Traffic Sign Classifier app can be beneficial for educational purposes, road safety awareness, and as a reference tool for drivers, students, or anyone interested in learning about traffic signs commonly encountered on roads.

**Disclaimer:** This application is meant for educational and informational purposes. It may not cover all possible traffic signs or circumstances. Always follow official traffic regulations and signage while on the road.

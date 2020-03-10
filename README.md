# Artificial-Advisor


This code compiles and runs, but its far from complete. I'm accepting pull requests, i encourage you to do so, it will be a service to everyone.

1.Integrate Firebase with the login in a more intuitive way
2.Finish integrating AnyCharts so it pulls from the data directly
3.Add more Tensorflow models for serving
4.Add more instructions for the dialogflow agent
5.Make better investments using Alpaca, a better trading strategy than just using sentiment analysis
6.Speaking of Sentiment Analysis, make that work in a more efficient way

Dependencies

1.Firebase
2.Plaid
3.Tensorflow Lite
4.DialogFlow
5.AnyChart

Instructions
Download Android Studio then import this project. Since I've placed the dependencies in the build.gradle file, it should auto-download them for you, which is awesome. It needs more features, and better integrated dataflow. I could've put more time into it, but I'm on to the next one. The model was too big to upload to GitHub. Place any .pb model into the app/src/main/assets folder and Tensorflow lite will detect it so it can be used for inference.

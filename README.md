 1. git clone https://github.com/tranmanhdat/FaceDetection
 2. cd FaceDetection
 3. cd app/src/main/cpp/tf-lite-api
 4. git submodule update --init --recursive
 5. download Opencv from (OpenCV release)[https://opencv.org/releases/] version 4.5.3 for Android, then extract downloaded file
 6. change the environment __opencvsdk__ in file __gradle.properties__ to the folder container Opencv downloaded in step 5
 7. change __compileSdkVersion__ and __targetSdkVersion__ in __build.gradle__ in Module opencv to 33
 8. build and run app
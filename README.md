# AppleWatchStreamCoreMotionData
 
This project allows users to stream motion(Accelerometer & Gyroscope) data from the apple watch at 100Hz and print in real-time on to the python console. 

## How it works
Motion data is captured from the apple watch and updated on Firebase RealTime Database. The python script listens for changes in the database and immediately prints the new values onto the console.

## From python side
Run the main python file (applewatchstream/motiondatafetch/main.py) in the terminal using the command below
```bash
python main.app
```


## From Apple Watch side
1. Follow the steps in the video titled "ios_app.mp4" to see how to run the app. You will only need to do this once to install the app on your apple watch. After it is successfully installed just tap on the app to run it. 


## Updating motion data capture frequency
To update the frequency in which gyroscope or accelerometer data is captured follow the steps below:
1. Open 'WatchStream.xcworkspace' (applewatchstream/WatchStream/WatchStream.xcworkspace)

2. Go into file 'MotionDatafetcher.swift'
3. Change the value of the variable 'updateTimeInterval' 


## License
[MIT](https://choosealicense.com/licenses/mit/)

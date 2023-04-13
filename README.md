# Controlling Media Player Using Gestures.


## Info
This program recognises hand gestures and controls the media player accordingly. This is done using `pyautogui` library which helps to press keys to perform 
operations like volume up/down, forward, reverse etc.
The model is trained using the Squeezenet Model and the accuracy is almost 100%. 


## Gestures:- 
 
1. **Volume Down**

![down](https://github.com/mujtbkhn/media-player-controller-using-ml/blob/master/thumbnails/down.jpg)

2. **Volume Up**

![up](https://github.com/mujtbkhn/media-player-controller-using-ml/blob/master/thumbnails/up.jpg)

3. **Fast Forward**

![right](https://github.com/mujtbkhn/media-player-controller-using-ml/blob/master/thumbnails/right.jpg)

4. **Reverse**

![left](https://github.com/mujtbkhn/media-player-controller-using-ml/blob/master/thumbnails/left.jpg).


## Set up instructions
1. Clone the repo.
```sh
$ git clone https://github.com/mujtbkhn/media-player-controller-using-ml.git
```

2. Install the dependencies
```sh
$ pip install -r requirements.txt
```

3. Collect images for training.
```sh
$ python3 gather_images.py
```

4. Train the model
```sh
$ python3 train.py
```

6. Run the media player and control it using the hand gestures.
```sh
$ python3 play.py
```
## Enjoy.. :)

# smile-detection
## Detect smile in image and video
---

# Dependency
1. keras
2. scikit-learn
3. imutils
4. matplotlib
5. numpy
6. cv2

---
To Train the model, insert following command in terminal

```python train_model.py --dataset ../datasets/SMILEsmileD \
--model output/lenet.hdf5
```


To detect the smile in web-cam, insert following command in terminal

```python detect_smile.py --cascade haarcascade_frontalface_default.xml \
--model output/lenet.hdf5
```

To detect the smile in video, insert following command in terminal
```
python detect_smile.py --cascade haarcascade_frontalface_default.xml \
--model output/lenet.hdf5 --video path/to/your/video.mov

```


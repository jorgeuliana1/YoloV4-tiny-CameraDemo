# How to use

Credits to [@techzizou](https://github.com/techzizou/yolov4-tiny-custom_Training).

1. Clone the repo [opencv/opencv](https://github.com/opencv/opencv) on the main folder.
1. Compile the opencv code.
1. Clone the repo [AlexeyAB/darknet](https://github.com/AlexeyAB/darknet) on the main folder.
1. Compile the darknet code.
1. `cd src`
1. `python3 darknet_video.py`

## If on Windows

1. Rename the `src/config/windows_dll_paths.model.json` to `src/config/windows_dll_paths.json` and write the locations of the binaries of the compiled libraries (OpenCV and Darknet).
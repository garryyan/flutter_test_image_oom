1. Run the code
2. Click "Add" button to add number of images
3. Get memory info:
    ```
    adb shell dumpsys meminfo   com.example.flutter_test_image_oom
    ```


    The images are loaded even if they are out of screen.

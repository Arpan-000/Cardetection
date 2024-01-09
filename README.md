# Vehicle Detection and Tracking System

This GitHub repository contains a simple Vehicle Detection and Tracking System implemented using OpenCV and cascade classifiers for car and bus detection. The system processes images from URLs and identifies vehicles by drawing bounding rectangles around them.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/vehicle-detection.git
   cd vehicle-detection
   ```

2. **Install Dependencies:**
   Ensure you have the required Python libraries installed:
   ```bash
   pip install numpy opencv-python pillow
   ```

3. **Run the Code:**
   Execute the provided script to perform vehicle detection on sample images:
   ```bash
   python vehicle_detection.py
   ```

   The script fetches images from URLs, applies image processing techniques, detects cars and buses, and displays the results.

4. **Explore Customization:**
   - You can modify the URLs in the script to process other images.
   - Adjust parameters in the cascade classifiers for fine-tuning detection.

## Files and Descriptions

- `vehicle_detection.py`: Main script for vehicle detection and tracking.
- `cars.xml`: Cascade classifier XML file for car detection.
- `Bus_front.xml`: Cascade classifier XML file for bus detection.

## Additional Notes

- The script is designed for educational purposes and provides a simple example of vehicle detection using cascade classifiers.
- Feel free to contribute or fork the repository for further enhancements or modifications.

## Credits

- The cascade classifiers used in this project are based on pre-trained models available in the OpenCV library.
- Image URLs:
  - Car Image: [Fox News](https://a57.foxnews.com/media.foxbusiness.com/BrightCove/854081161001/201805/2879/931/524/854081161001_5782482890001_5782477388001-vs.jpg)
  - Bus Image: [Quora](https://qph.fs.quoracdn.net/main-qimg-b5c4e39dcd48dddd9e609e6022f74d85)

Feel free to explore, modify, and use this project as a starting point for your own computer vision applications!

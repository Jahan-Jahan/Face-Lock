# Face-Lock System

## Overview
This project is a face recognition-based locking system that verifies whether the detected face matches a predefined base face. It utilizes facial embeddings to enable recognition.

## Features
- Extract facial embeddings from images.
- Store the embeddings in a NumPy file (`embeddings.npy`).
- Capture frames from a webcam.
- Recognize if the detected face matches the base face.
- Simple and efficient implementation using Python and OpenCV.

## Usage
### Step 1: Clone Repository
```bash
   git clone https://github.com/Jahan-Jahan/Face-Lock.git
   cd Face-Lock
   ```
### Step 2: Prepare Your Images
- Place at least 20 images of your face inside the my_images2 directory.
- Do not crop your face; use full images that include your face.
- Of coures, delete `sample.jpg` before placing your images.

### Step 3: Generate Face Embeddings
Run the `result.ipynb` notebook to extract and save facial embeddings:
- This notebook processes the base face and saves its embeddings into `embeddings.npy`.

### Step 4: Start Face Recognition
Run the `face_lock.ipynb` notebook to start real-time face recognition:
- This notebook captures frames from the webcam and compares them against the stored embeddings.
- If the detected face matches the base face, access is granted; otherwise, access is denied.

## Dependencies
- Python 3.x
- OpenCV
- NumPy
- deepface
- Jupyter Notebook

## Contributing
Feel free to contribute by opening an issue or a pull request.

## License
This project is licensed under the MIT License.

---
Happy coding! 😊


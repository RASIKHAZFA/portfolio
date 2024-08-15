# Vehicle Counter Project

This repository contains a project designed to count buses and cars crossing a specific line in a video using YOLOv10 for detection and tracking.

## Setup Instructions

To ensure a smooth experience, follow these steps to set up and run the project.

### 1. Create a PyTorch Environment

It is crucial to set up the correct Python environment to avoid any potential issues. Please create a PyTorch environment by installing the dependencies listed in the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 2. Download Necessary Files

Ensure you have the following files downloaded into your working directory:

- `toll_gate.mp4` - The video file to be processed.
- `Vehicle_Counter.ipynb` - The Jupyter Notebook containing the vehicle counting code.
- `tracker.py` - The script used for tracking vehicles.

### 3. Run the Project

Once the environment is set up and all necessary files are in place, open `Vehicle_Counter.ipynb` and run all cells to start the vehicle counting process:

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Vehicle_Counter.ipynb
    ```

2. Run All Cells:
    - You can do this by clicking on **Cell > Run All** in the Jupyter interface.

## Additional Notes

- Ensure that your environment is configured correctly to avoid any runtime errors.
- The counting process is based on detecting and tracking cars and buses as they cross a designated line in the video.

Happy Coding! 🚗🚌

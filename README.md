# aws-deepracer-analyzer
This repo provides a tool for analyzing AWS DeepRacer runs.

It provides useful information overlaied on top of the video presented during training or evaluation. This is useful especially to identify the most common actions the car takes, in order to adjust its action space.

### Features
- Car variables displayed while car runs (speed, steer, position, yaw, reward, all wheels on track).
- Lap variables (lap state, lap progress, closest waypoint)
- Action space map with heatmap to understand which actions are more common
- Pause and move frame-by-frame analysis
- Easily jump to any moment of the race with keys 0-9
- Increase/decrease speed of simulation controling the frames per seconds.
- Total progress bar at the bottom.
- Record the simulation into an MP4 video file.

![deepracer eval page steos](./resources/analyzer_demo.gif)


### Setup
1. Evaluation logs
    - Download the evaluation logs
    - Unzip the logs
2. Evaluation video
    - Download the evaluation video by simply right-clicking the video and saving it as .mp4.

![deepracer eval oage steos](./resources/deepracer_eval_page_steps.png)

3. Notebook script
    - Change any necessary path variables at the beginning of the Python notebook.
    - Make sure you install all necessary Python dependencies.
    - Execute all cells. A new window with the simulation should pop up.

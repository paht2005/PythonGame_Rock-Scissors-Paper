# Python Rock-Scissors-Paper Game (Utilizing OpenCV)

This repository hosts the codebase for a simple Rock-Scissors-Paper game developed in Python, leveraging the OpenCV library. The project employs OpenCV's image processing capabilities to recognize player's hand gestures (Rock, Scissors, or Paper) via a webcam feed.


---

## 🗂️ Table of Contents

- [✨ Features](#-features)
- [🗂️ Repository Structure](#️-repository-structure)
- [⚙️ Installation](#️-installation)
- [🎯 Usage](#-usage)
- [📄 License](#-license)
- [🤝 Contributing](#-contributing)
- [🧠 Acknowledgements](#-acknowledgements)
- [⭐ Future Enhancements](#-future-enhancements)

---

## ✨ Features

- **Hand Gesture Recognition:** Implements OpenCV, potentially in conjunction with the MediaPipe library, to perform real-time detection and classification of hand gestures corresponding to Rock, Scissors, and Paper from a webcam stream.
- **Automated Opponent:** Enables gameplay against a virtual opponent (computer) employing a pseudo-random selection mechanism.
- **Result Visualization:** Displays both the player's and the computer's selections, along with the outcome of each round.
- **Basic Graphical Interface:** A rudimentary graphical interface may be constructed using OpenCV functionalities or integrated with external GUI libraries, contingent on further development.


---

## 🗂️ Repository Structure
```
├── GoogleColabProject_RockScissorsPaper_Game.ipynb # Jupyter Notebook containing the primary game logic.
├── hand_detect_lib.py                           # Potentially houses custom functions for hand detection tasks.
├── SetUp.txt                                    # Lists the requisite libraries for project execution.
├── pic/                                         # Directory potentially containing supplementary image assets.   
│ ├── 0_Scissor.png                              # Image asset representing the Scissors gesture.
│ ├── 1_rock.png                                 # Image asset representing the Rock gesture.
│ └── 2_paper.png                                 # Image asset representing the Paper gesture.                                                       
└── README.md                                  # Project documentation file.
└── LICENSE                                      
```
---

## ⚙️ Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/paht2005/PythonGame_Rock-Scissors-Paper.git](https://github.com/paht2005/PythonGame_Rock-Scissors-Paper.git)
    cd PythonGame_Rock-Scissors-Paper
    ```

2.  **Install Dependencies:**
    Utilize pip to install the necessary libraries specified in the `SetUp.txt` file:
    ```bash
    pip install -r SetUp.txt
    ```
    Alternatively, install them individually:
    ```bash
    pip install mediapipe
    pip install opencv-python
    ```

3.  **(Optional) Jupyter Notebook:**
    To execute the `.ipynb` file, ensure you have Jupyter Notebook or JupyterLab installed:
    ```bash
    pip install notebook
    # or
    pip install jupyterlab
    ```
---
## 🎯 Usage
1.  **Execute the Game:**
    - If using Jupyter Notebook, open the `GoogleColabProject_RockScissorsPaper_Game.ipynb` file and execute the code cells sequentially.
    - If the project is developed as a standalone Python script (`.py`), run it from the terminal:
      ```bash
      python your_game_script.py
      ```

2.  **Follow On-screen Prompts:**
    - The application may request access to your webcam to capture video frames for gesture recognition.
    - Present hand gestures corresponding to Rock, Scissors, or Paper when prompted.
    - The outcome of each round will be displayed on the interface.

---
## 📄 License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---
## 🤝 Contributing
Contributions to enhance this project are welcome! Feel free to:

- Submit pull requests for implemented features or bug fixes.
- Report any identified issues or bugs.
- Propose new features or improvements.
Contact for work: **Nguyễn Công Phát** – congphatnguyen.work@gmail.com
---
## 🧠 Acknowledgements
- **OpenCV:** For providing a robust library for computer vision and image processing tasks in Python.
- **MediaPipe:** (If utilized) For offering a framework for constructing multimodal applied machine learning pipelines.
- **Python:** The versatile and accessible programming language employed for this project.
- **GitHub:** The platform hosting this open-source project for collaborative development.

---
## ⭐ Future Enhancements
- **Improved Gesture Recognition Accuracy:** Fine-tuning parameters and algorithms to enhance the robustness and accuracy of hand gesture recognition across varying lighting conditions and backgrounds.
- **Multiplayer Mode:** Development of a two-player mode (if feasible) or exploration of alternative game variations.
- **Enhanced User Interface:** Integration of more sophisticated GUI libraries (e.g., Tkinter, PyQt) for a more interactive and visually appealing user experience.
- **Persistent Score Tracking:** Implementation of a mechanism to maintain and display a running score across multiple rounds of gameplay.


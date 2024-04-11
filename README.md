# Signal-Lab
A MATLAB app providing interactive visualizations of core wireless networking concepts.
Users require a MATLAB license (free for students/teachers in many schools) to use the application.
We may decide to package Signal-Lab in the future to allow users without MATLAB to use the app.

### Key Features:
Experiment with many parameters to observe their impact on signal behaviors.

Students/teachers can use this tool to showcase:
- Superpositions of EM Waves in 2D/3D
- EM Waves passing through a Medium
- Voice Signal Analysis (Mic)
- Frequency Modulation
- and other wireless communication concepts


### Installation:
This app requires a functioning installation of MATLAB. 

1. **Navigate to a Directory:**
   Open terminal and create/enter your desired directory.
    ```bash
   cd /path/to/ParentDirectory  % Replace with the actual path
   ```
    
2. **Clone the Repository:**
   Use git to clone the Signal-Lab repository from GitHub:
   ```bash
   git clone https://github.com/aleksbrsc/Signal-Lab.git
   ```

### Running the App:
Now you may open the apps through either **terminal** or **MATLAB**.

1. **Open through Terminal:**
   Once cloned, navigate to the Signal-Lab directory:
   ```bash
   cd Signal-Lab
   ```
   Then `ls` to find a list of apps, and `open` one of them:
   ```bash
   open main.mlapp  % Replace with a specific app if you want
   ```
   If that fails, either have MATLAB running first, or:

2. **Open through MATLAB:** 
   1. Launch MATLAB and open the directory
   2. Double-click main.mlapp file to open the main menu app
   3. Click the play button to run it

### Additional Notes:
Now you should see the Signal-Lab app interface within your MATLAB environment. Feel free to interact with the sliders and controls to explore different wireless networking concepts visually.

If you're having issues running the app:
* Ensure that any additional MATLAB files required by the app (functions, data files, etc.) are located within the same directory or a subdirectory within the Signal-Lab folder structure.
* If you encounter any errors while running the app, double-check the installation steps and verify that all necessary files are present and accessible.

**Contributing (Optional):**
If you have any suggestions for improvement, bug fixes, or additional features you'd like to see in Signal-Lab, feel free to create a pull request on the GitHub repo.

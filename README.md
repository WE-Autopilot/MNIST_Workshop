# MNIST Workshop

<div align="center">

| 📅 Date       | 📍 Location | 🕠 Time         |
|:------------:|:-----------:|:---------------:|
| January 30th |  ACEB 1450   | 5:30PM - 9:30PM |

</div>

## What is MNIST?

The MNIST dataset (Modified National Institute of Standards and Technology database) is a widely used benchmark dataset in machine learning, particularly for image processing and computer vision tasks. It consists of 70,000 grayscale images of handwritten digits (0-9), each of size 28x28 pixels.

- **Training and Testing:** It is divided into 60,000 training images and 10,000 testing images.

- **Purpose:** The dataset is commonly used to train and evaluate classification algorithms, serving as a foundational task in deep learning and neural network research.

- **Simplicity:** Its small size and pre-processed, normalized format make it ideal for testing models and concepts with low computational overhead.

Despite being simple, MNIST has inspired more complex variants like Fashion-MNIST for modern use cases.

<div align="center">
    <img src="README_assets/MNIST_Visualization.gif" alt="Neural Network of MNIST">
    <p><em>Convolutional Neural Network of MNIST - Visualization</em></p>
</div>

</br>

## What does MNIST have to do with WEAP?

MNIST and WE AutoPilot (WEAP) are connected through their focus on machine learning and AI, which are key aspects of WEAP’s software development goals, especially in areas like computer vision.

</br>

**1. Understanding Neural Networks:**

- Working with MNIST introduces members to the basics of neural networks, including how models learn from data, optimize weights, and make predictions. By recognizing patterns like handwritten digits in MNIST, members can build a solid foundation for more advanced tasks such as object detection and lane recognition—critical components of autonomous vehicle systems.

**2. Hands-On with Machine Learning Frameworks:**

- Members gain experience using popular ML frameworks like TensorFlow or PyTorch while working on MNIST. This practical exposure is directly transferable to projects requiring real-world datasets, such as vehicle navigation or obstacle detection.

**3. Confidence Building:**

- Solving MNIST problems helps new members grasp the logic behind AI and ML systems in a  simple, manageable way. This builds their confidence to dive into more challenging tasks like training models on real-world traffic or environmental data.

**4. Team Collaboration and Mentorship:**

- Members can collaborate on MNIST-related challenges, fostering teamwork and enabling senior members to mentor newcomers on the principles of AI development.

**5. Resume-Worthy Experience:**

- Who doesn’t want a project showcasing machine learning skills on their resume? A completed MNIST project not only demonstrates technical ability but also signals a willingness to learn and tackle foundational AI problems, making members more attractive to employers in tech and AI industries.

</br>

## How to setup your environment

***Note: Windows and MacOS are very similar, thus only key differences are highlighted. If you need help with any part of this setup, be sure to join the Discord here:***

<div align="center">
    <a href="https://discord.gg/HuJCHCSVB2">Discord Link</a>
</div>

</br>

### 1. Download and Install Visual Studio Code (VS Code)

- Open your web browser and go to the [VS Code Download Page](https://code.visualstudio.com/).

- Click the **Download for your OS** button (Windows, Mac, or Linux).

- Once the download is complete, run the installer:
   - **Windows:** Double-click the `.exe` file and follow the prompts.
   - **Mac:** Open the `.dmg` file and drag the VS Code icon to your Applications folder.
   - **Linux:** Follow the instructions provided for your distribution.

- During installation (Windows only):
   - Check the box for **"Add to PATH"** when prompted.
   - Check any other options you find useful, like creating a desktop icon.

<div align="center">
    <img src="README_assets/image-1.png" alt="Download Page">
    <p><em>Once you load up the page, click "Download" in top right, and choose your OS</em></p>
</div>
</br>

### 2. Download and Install Python 3.12.x

- Go to the [Python Downloads Page](https://www.python.org/downloads/).

- Scroll down to "Looking for a specific release?"

- Click **Download** on your choice of 3.12.x Python ***(We will be downloading 3.12.8 for this tutorial)***.
   - We are using an older version of Python because you may encounter issues with some library's support for the latest version.

- Scroll to the bottom and choose the installer appropriate for your operating system:
   - **Windows (64-bit):** Select "Windows installer (64-bit)".
   - **Mac:** Select "macOS 64-bit universal2 installer".
   - **Linux:** Follow the instructions provided for your distribution or use the source tarball.

- Run the installer:
   - **Windows:** Check the box for **"Add Python to PATH"** and click **Install Now**.
   - **Mac:** Follow the installation steps.
   - **Linux:** Use your package manager or download the appropriate package.
   
- Verify the installation:
   - Open a terminal or command prompt and type:
     ```ps
     python --version
     ```
     or
     ```ps
     python3 --version
     ```
   - You should see something like `Python 3.12.x`.

</br>

### 3. Install the Python Extension in VS Code

- Open VS Code.

- Go to the Extensions Marketplace:
   - Click the **Extensions** icon on the left sidebar (it looks like four squares).

- Search for **"Python"** in the search bar.

- Select the extension developed by Microsoft and click **Install**.

- Once installed, restart VS Code to ensure the extension loads properly.

<div align="center">
    <img src="README_assets/image.png" alt="Python Extension Page">
    <p><em>Python Extension Page in VS Code.</em></p>
</div>

</br>

### 4. Set Up Python in VS Code

- Open VS Code and press **Ctrl + Shift + P** (Windows/Linux) or **Cmd + Shift + P** (Mac) to open the Command Palette.

- Type **"Python: Select Interpreter"** and click on it.

- From the list of Python interpreters, select the one corresponding to Python 3.12.x.
   - If you don’t see it, make sure Python is installed and added to your PATH.

<div align="center">
    <img src="README_assets/image-2.png" alt="Python Extension Page">
    <p><em>Python Extension Page in VS Code.</em></p>
</div>

</br>

### 5. Create and Run a Python File in VS Code

- Create a new folder for your project on your computer (e.g., `HelloWorldProject`).

- Open the folder in VS Code:
   - Go to **File > Open Folder...** and select the folder you created.

- Create a new Python file:
   - Click the **New File** button in the Explorer sidebar (or press **Ctrl + N** / **Cmd + N**).
   - Save the file as `hello_world.py` (ensure it has a `.py` extension).

- Write the following code in the file:

   ```python
   print("Hello, World!")
   ```

- Run the Python file:
   - Right-click anywhere in the code editor and select **"Run Python File in Terminal"**.
   - Alternatively, press **Ctrl + F5** (Windows/Linux) or **Cmd + F5** (Mac).

- Check the terminal at the bottom of VS Code for the output. You should see:
   ```
   Hello, World!
   ```
</br>

### 6. Verify Your Setup

- Confirm that:
   - VS Code is installed and working.
   - Python 3.12.x is installed and added to PATH.
   - The Python extension is installed and configured in VS Code.
   - You can successfully run a Python script and see the output.

- Celebrate! 🎉 You’ve set up your environment and run your first Python program in VS Code!
- You may feels as though this was simple, but we are just getting to the good part!
   - Attend the workshop session to write your first Convolutional Neural Network!

</br>

## FAQ (Frequently Asked Questions)

**Q: Where is the solution to creating the MNIST CNN (Convolutional Neural Network)?**

    We will update this repository with the full solution and some explanations for certain parts after the completion of the workshop at the previously specified date.

**Q: Do I need prior machine learning experience to attend this workshop?**

    No prior experience is necessary! We will start with the basics of MNIST and Python setup, so beginners are welcome. However, familiarity with Python will be helpful.

**Q: What if I encounter issues setting up Python or VS Code?**

    Please refer to the step-by-step instructions provided in the setup guide. If issues persist, feel free to join our Discord server for assistance.

**Q: Will we use datasets other than MNIST in this workshop?**

    This workshop is focused on MNIST as it is a beginner-friendly dataset. Future, more advanced workshops may include other datasets, such as CIFAR-10 or custom datasets.

**Q: Can I use a Mac or Linux system for the workshop?**

    Yes! The setup instructions are similar for Mac and Linux. We have provided steps for all platforms in the setup guide.

**Q: Is there any cost associated with the workshop?**

    No, this workshop is completely free and open to all students that RSVP'd through the google form shared on all of our socials.

**Q: What tools or frameworks will be used for building the CNN?**

    We will use Python with a popular machine learning library called PyTorch to create and train the CNN.

**Q: Who can I contact if I have questions after the workshop?**

    Join our Discord server or reach out to any of the WEAP organizers. Details will be provided during the workshop.

</br>

## Connect with WEAP

Stay updated and connect with us through our socials:

<div align="center">
  <table>
    <tr>
      <td align="center"><strong>GitHub</strong></td>
      <td align="center"><strong>Linktree</strong></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/WE-Autopilot">WEAP GitHub Organization</a></td>
      <td align="center"><a href="https://linktr.ee/we.autopilot">WEAP Linktree</a></td>
    </tr>
    <tr>
      <td align="center"><strong>Instagram</strong></td>
      <td align="center"><strong>Discord</strong></td>
    </tr>
    <tr>
      <td align="center"><a href="https://instagram.com/we.autopilot">@WE.AutoPilot</a></td>
      <td align="center"><a href="https://discord.gg/HuJCHCSVB2">Join Our Discord</a></td>
    </tr>
    <tr>
      <td colspan="2" align="center"><strong>LinkedIn</strong></td>
    </tr>
    <tr>
      <td colspan="2" align="center"><a href="https://linkedin.com/company/we-autopilot-club">WEAP on LinkedIn</a></td>
    </tr>
  </table>
</div>

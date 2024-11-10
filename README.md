# Indoor-Nav-AR

Indoor-Nav-AR is an Augmented Reality (AR) navigation system designed to guide users indoors using AR markers and mapping technology. This project is built in Unity with AR components and can be run on an Android device set to Developer Mode.

## Prerequisites

- **Unity**: Ensure Unity is installed, along with support for AR packages. You may need the AR Foundation and ARCore packages depending on your Unity version.
- **Android Device**: Set your Android device to Developer Mode (refer to your device’s settings under *Developer options*).
- **USB Cable**: For connecting your Android device to the computer for development and testing.

## Getting Started

1. **Download the Repository as a ZIP file**:
   - Click the green **Code** button on the [project page](https://github.com/lolpanda2004/Indoor-Nav-AR.git) and select **Download ZIP**.
   - Extract the ZIP file to your preferred location.

2. **Locate the 'lab' Package**:
   - After unzipping, go to the project folder and locate the file named `lab`. This is the Unity package you need to import.

3. **Open Unity and Import the Package**:
   - Launch Unity and create a new project (or open an existing one compatible with AR).
   - Go to **Assets** > **Import Package** > **Custom Package...** and select the `lab` file.
   - This will import all necessary files for the Indoor-Nav-AR project into your Unity project.

4. **Configure AR Settings**:
   - Ensure AR Foundation and ARCore packages are installed in your Unity project.
   - Adjust any AR settings according to your device’s requirements for optimal AR tracking and rendering.

5. **Deploy to Device**:
   - Connect your Android device to your computer.
   - In Unity, go to **File** > **Build Settings...**, choose **Android**, and click **Switch Platform** if necessary.
   - Click **Build and Run** to deploy the app directly to your device.

6. **Testing**:
   - Once deployed, the AR navigation features should be accessible on your device. Follow the on-screen instructions to navigate through the indoor space.

## Troubleshooting

- Ensure that **Developer Mode** is enabled on your Android device to allow Unity to communicate with it.
- Verify that **ARCore** is supported on your device.
- Make sure Unity is up-to-date and that all required AR packages are installed and configured.

## Contributions

Contributions to improve Indoor-Nav-AR are welcome! Please fork this repository and submit a pull request with your enhancements or fixes.

---

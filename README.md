# Vocalize: Web-based Text-to-Speech with Coqui TTS and Gradio

This repository provides a user-friendly web interface (WebUI) for Text-to-Speech (TTS) using the powerful Coqui TTS library and Gradio. Easily convert text to speech directly in your browser.

## Features

* **Web-based Interface:** Access the TTS functionality through a simple and intuitive web interface.
* **Coqui TTS Integration:** Leverages the high-quality TTS capabilities of the Coqui TTS library.
* **Gradio Powered:** Built with Gradio for easy deployment and user interaction.
* **Text-to-Speech Conversion:** Quickly convert any text input into spoken audio.

## Installation

Before you begin, ensure you have the following prerequisites:

* **Python:** Python 3.9 to 3.12 is required.
* **Visual Studio Build Tools:** Necessary for compiling certain dependencies (Windows).
* **Windows SDK:** Required for compiling certain dependencies (Windows).
* **pip:** The Python package installer.

**Steps:**

1.  **Clone the Repository:**
    ```bash
    git clone [repository URL] may have changed.
    cd vocalize-A-web-based-Text-to-Speech-application-using-Coqui-TTS-and-Gradio
    ```

2.  **Create and Activate a Virtual Environment (Recommended):**
    ```bash
    python -m venv venv
    # On Windows:
    venv\Scripts\activate
    # On macOS and Linux:
    source venv/bin/activate
    ```

3.  **Install Required Packages:**
    ```bash
    pip install -r requirements.txt
    ```
    (Ensure you have a `requirements.txt` file that includes `TTS`, `torch`, and `gradio`. An example is provided below)

    Example `requirements.txt`:
    ```
    TTS
    torch
    gradio
    ```

4.  **Run the Application:**
    ```bash
    python app.py
    ```
    (Ensure your main application file is named `app.py`. Modify if needed.)

5.  **Access the Web Interface:**
    Open your web browser and navigate to the URL provided in the terminal output (usually `http://127.0.0.1:7860`).

## Usage

1.  **Enter Text:** Type or paste the text you want to convert to speech into the provided text box.
2.  **Click "Submit" or "Generate":** Trigger the TTS conversion process.
3.  **Listen to the Audio:** The generated audio will be played directly in your browser or made available for download.

## Dependencies

* **Coqui TTS (`TTS`):** A library for advanced Text-to-Speech generation.
* **PyTorch (`torch`):** A machine learning framework used by Coqui TTS.
* **Gradio (`gradio`):** A library for creating web interfaces for machine learning models.

## Notes

* Ensure that your system meets the hardware requirements for Coqui TTS, especially if using GPU acceleration.
* The quality of the generated speech may vary depending on the chosen TTS model and settings.
* If you encounter issues with installing `torch`, refer to the official PyTorch installation guide for platform-specific instructions.
* Adjust the app.py file to your specific needs, such as adding different models, or adjusting the audio settings.
* For Windows users, make sure the Visual Studio Build Tools and Windows SDK are properly installed, and that they are the correct versions.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue.

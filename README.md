# MEDUSA AI: Medical Diagnostic Unified System Assistant

Welcome to **MEDUSA AI**, a comprehensive medical diagnostic assistant designed to simplify and enhance the workflow of healthcare professionals. This README will guide you through the features and functionalities of this application, providing you with everything you need to start using MEDUSA AI effectively.

![MEDUSA AI](https://media0.giphy.com/media/dXEP7pHwmGRgNa0Qhu/giphy.webp?cid=ecf05e47l6hasy2f95aa1jzoxvem3hxtylwdrhjuusu48ptj&ep=v1_gifs_search&rid=giphy.webp&ct=s)

## Key Features

MEDUSA AI offers several modules to assist with various aspects of medical diagnostics:

1. **Medical Imaging Diagnostics**
2. **Medical Transcription**
3. **Medical Pathology Diagnostics**
4. **Medical Coding**
5. **Insurance Risk Analysis**
6. **Treatment and Diet Plan Generator**

### 1. Medical Imaging Diagnostics

Upload medical images and receive detailed analyses. The tool supports multiple image formats (JPG, JPEG, PNG).

![Medical Imaging Diagnostics](C:/Users/Admin/Pictures/Screenshots/Screenshot(158).png)

### 2. Medical Transcription

Upload prescription images and get them transcribed into a structured, tabular format.

![Medical Transcription](C:/Users/Admin/Pictures/Screenshots/Screenshot(160).png)

### 3. Medical Pathology Diagnostics

Analyze medical reports to generate comprehensive pathology reports.

![Medical Pathology Diagnostics](C:/Users/Admin/Pictures/Screenshots/Screenshot(161).png)

### 4. Medical Coding

Upload medical documents and get suggested ICD medical codes with descriptions.

![Medical Coding](C:/Users/Admin/Pictures/Screenshots/Screenshot(162).png)

### 5. Insurance Risk Analysis

Upload user data images and calculate insurance risk percentages with detailed justifications.

![Insurance Risk Analysis](C:/Users/Admin/Pictures/Screenshots/Screenshot(163).png)

### 6. Treatment and Diet Plan Generator

Generate personalized treatment and diet plans based on patient data.

![Treatment and Diet Plan Generator](C:/Users/Admin/Pictures/Screenshots/Screenshot(164).png)

## Installation and Setup

1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-repo/medusa-ai.git
    cd medusa-ai
    ```

2. **Install the dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

3. **Set up environment variables:**
    - Create a `.env` file in the root directory and add your Google API key.
    ```env
    GOOGLE_API_KEY=your_google_api_key
    ```

4. **Run the application:**
    ```sh
    streamlit run app.py
    ```

## Usage

### Navigation Menu

Select the desired module from the navigation menu at the top of the page.

### Medical Imaging Diagnostics

1. **Upload Image:** Choose one or more medical images to upload.
2. **Enter Prompt:** Use the default prompt or enter a custom prompt.
3. **Analyze Image:** Click to analyze the image and get a detailed report.
4. **Download Report:** Save the analysis as a PDF report.
5. **Related Research Papers:** View related research papers based on the analysis.

### Medical Transcription

1. **Upload Prescription:** Choose a medical prescription image to upload.
2. **Enter Prompt:** Use the default prompt or enter a custom prompt.
3. **Get Transcription:** Click to transcribe the prescription into a tabular format.

### Medical Pathology Diagnostics

1. **Upload Report:** Choose a medical report image to upload.
2. **Enter Prompt:** Use the default prompt or enter a custom prompt.
3. **Analyze Report:** Click to generate a comprehensive pathology report.

### Medical Coding

1. **Upload Medical Document:** Choose a medical document image to upload.
2. **Enter Prompt:** Use the default prompt or enter a custom prompt.
3. **Get ICD Codes:** Click to get suggested ICD medical codes with descriptions.

### Insurance Risk Analysis

1. **Upload User Data Image:** Choose an image containing user data to upload.
2. **Enter Prompt:** Use the default prompt or enter a custom prompt.
3. **Analyze Risk:** Click to calculate the insurance risk percentage and get a detailed justification.

### Treatment and Diet Plan Generator

1. **Upload Patient Data Image:** Choose an image containing patient data to upload.
2. **Enter Prompt:** Use the default prompt or enter a custom prompt.
3. **Generate Plan:** Click to generate personalized treatment and diet plans.

## Additional Features

- **Latest Medical News:** View the latest medical news directly from the sidebar.
- **Customizable Reports:** Select from various report formats for personalized outputs.

## Support

If you encounter any issues or have questions, feel free to open an issue on the [GitHub repository](https://github.com/your-repo/medusa-ai/issues).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

 

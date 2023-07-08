
# VidVertex

## Overview

VidVertex is an AI-powered tool designed for content creators. It analyzes a video from a given URL and extracts the three most important parts. The application also generates engaging social media posts and emails about these key parts, along with a corresponding image. 

MediaMorpher is built using Python, Streamlit, and Vertex AI, and utilizes state-of-the-art machine learning algorithms for video analysis and content generation.

## Installation

To set up the application, follow these steps:

1. Clone this repository:
```bash 
git clone [url]
```

2. Navigate into the project directory:
```bash 
cd VidVertex
```

3. Create a virtual environment and activate it (Optional, but recommended):
```bash
python3 -m venv env
source env/bin/activate 
# For Windows, use 'env\Scripts\activate'
```

4. Install the necessary packages:
```bash
pip install -r requirements.txt
```

## Usage

After completing the installation, you can start the application using Streamlit:

```bash 
streamlit run app.py
```



This will start a local server and open a browser window where you can interact with the application. Paste a video URL into the appropriate field and click 'Analyze' to start the video analysis process.

## License

This project is licensed under the terms of the MIT license. See [LICENSE](LICENSE) for more details.
""")
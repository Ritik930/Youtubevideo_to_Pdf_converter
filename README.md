# Video Frame Comparison & Report Generator


This project downloads a YouTube video, extracts frames, compares them using image similarity metrics (SSIM and distance metrics), and generates a PDF report summarizing the results.

📌 Features
🔽 Downloads videos from YouTube using yt-dlp

🧠 Compares frames using:

Structural Similarity Index (SSIM)

Euclidean/other distance metrics

🖼️ Handles image preprocessing with OpenCV and PIL

📄 Outputs results as a clean, structured PDF report

# 🧰 Technologies Used
Python 3.x

OpenCV (opencv-python-headless)

yt-dlp for video downloading

fpdf for PDF generation

scikit-image for SSIM computation

Google Colab (optional runtime)

⚙️ Installation
bash
Copy
Edit
pip install opencv-python-headless
pip install scikit-image
pip install fpdf
pip install yt-dlp
🚀 Usage
Clone the repository or open the main.ipynb in Google Colab.

Provide the YouTube video URL to download and analyze.

The notebook will:

Download the video

Extract key frames

Compare them using SSIM

Generate a PDF report with results


# 📊 Output
Summary PDF file comparing extracted video frames

SSIM/distance values between selected frames

🧑‍💻 Author
Name: Ritik Kumar

Email: ritikumar0987@gmail.com


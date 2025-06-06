# Background Remover Web App

A professional web application that removes backgrounds from images using AI. Built with Flask and powered by the U-2-Net model.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Python](https://img.shields.io/badge/python-3.9+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## ✨ Features

- 🖼️ Remove backgrounds from any image
- 🚀 Fast and efficient processing
- 💻 Modern, responsive UI
- 📱 Mobile-friendly design
- 🔄 Drag and drop support
- 🐳 Docker support
- 🔒 Secure file handling

## 🛠️ Tech Stack

- **Backend**: Flask (Python)
- **AI Model**: rembg + ONNX (U-2-Net)
- **Frontend**: HTML, CSS, JavaScript
- **Containerization**: Docker
- **Styling**: Modern CSS with CSS Variables

## 📋 Prerequisites

- Python 3.9 or higher
- Docker (optional)
- 2GB RAM minimum
- 500MB free disk space

## 🚀 Installation

### Using Python

1. Clone the repository:
```bash
git clone https://github.com/yourusername/rembg-webapp.git
cd rembg-webapp
```

2. Create and activate virtual environment:
```bash
python -m venv myenv
source myenv/bin/activate  # On Windows: myenv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python app.py
```

5. Visit http://localhost:5000 in your browser

### Using Docker

1. Pull the image:
```bash
docker pull rajrasane/removebg-webapp:latest
```

2. Run the container:
```bash
docker run -p 5000:5000 rajrasane/removebg-webapp:latest
```

3. Visit http://localhost:5000 in your browser

## 📸 Usage

1. Open the web application
2. Drag and drop an image or click to select
3. Wait for processing
4. Download the processed image

## 🔧 Configuration

The application can be configured through environment variables:

- `PORT`: Server port (default: 5000)
- `HOST`: Server host (default: 0.0.0.0)
- `DEBUG`: Debug mode (default: False)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [rembg](https://github.com/danielgatis/rembg) for the background removal model
- [U-2-Net](https://github.com/xuebinqin/U-2-Net) for the AI model
- [Flask](https://flask.palletsprojects.com/) for the web framework
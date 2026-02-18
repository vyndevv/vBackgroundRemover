# Modern AI Background Remover 🚀

A professional, easy-to-use desktop application to remove backgrounds from images using AI. Built with Python, CustomTkinter, and Rembg.

![Python](https://img.shields.io/badge/Python-3.12+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![CustomTkinter](https://img.shields.io/badge/UI-CustomTkinter-blue?style=for-the-badge)
![AI](https://img.shields.io/badge/AI-rembg-green?style=for-the-badge)

## ✨ Features

- **Modern UI**: Sleek dark mode interface using CustomTkinter.
- **AI Powered**: High-quality background removal using the `u2net` model.
- **Real-time Preview**: See your image before and after processing.
- **Asynchronous Processing**: The UI stays responsive during image processing.
- **Support for Multiple Formats**: PNG, JPG, JPEG, WebP, and BMP.

## 🗒️ Some information

You can find the source code of the application in this repository. To use the tool without installing Python, download the latest version from the [Releases](https://github.com/vyndevv/vBackgroundRemover/releases) section.

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/vyndevv/vBackgroundRemover.git
   cd vBackgroundRemover
   ```

2. **Create a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install rembg pillow customtkinter onnxruntime
   ```

## 🚀 Usage

Run the script directly:
```bash
python main.py
```

## 📦 Creating an Executable (.exe)

To compile the project into a standalone executable for Windows:

1. Install PyInstaller:
   ```bash
   pip install pyinstaller
   ```

2. Run the compilation command:
   ```bash
   pyinstaller --onefile --windowed --name "BackgroundRemover" --collect-all rembg --collect-all pymatting main.py
   ```

Your executable will be available in the `dist` folder.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [rembg](https://github.com/danielgatis/rembg) for the amazing background removal logic.
- [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter) for the modern UI components.

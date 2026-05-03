# Mr. Alvin Rocks - Image & PDF Pro (PySide6 Edition)

> ⚠️ **DISCLAIMER**: Mr. Alvin Rocks has developed this software entirely via **vibe coding with Gemini**. Pure vibes, professional code.

An elite, high-performance Python utility designed for heavy-duty image and document processing. Built on the modern **PySide6** framework, this tool combines a slick "cyberpunk" aesthetic with multi-threaded, hardware-accelerated backend logic.

---

## 🔥 Key Features

### 🖼️ Image Toolkit
*   **High-Fidelity Codec Tuning**: Granular control over **AVIF**, **WEBP**, and **JPEG**. Toggle lossless modes, adjust chroma subsampling, and set encoding effort sliders to maximize quality.
*   **Smart Target Compression**: Built-in binary search algorithms to hit exact megabyte (MB) targets for images and PDF-wrappers without unnecessary quality loss.
*   **Hardware-Accelerated OpenCV**: Utilizes **OpenCL (GPU)** via your graphics card to handle heavy "Auto-Enhance" and deskewing tasks instantly.
*   **Elite Watermarking**: Bulletproof diagonal tiling stamps your watermark in a rotated grid across the entire image, preventing simple cropping.
*   **EXE Icon Generation**: Quickly convert images to multi-size bundled `.ico` files for Windows applications.

### 📄 Document Toolkit (PDF & DjVu)
*   **Interactive Visual Rearranger**: A high-resolution grid pops up with live thumbnails before you merge. Drag-and-drop to reorder chapters or images visually before committing the build.
*   **Searchable PDF (OCR)**: Integrates the **RapidOCR** engine to inject invisible text layers into image-based PDFs, making your documents fully searchable.
*   **Non-Destructive Compression**: Native PDF stream deflation and garbage collection that shrinks files without flattening them into low-quality images.
*   **DjVu Integration**: Full support for DjVu to PDF (and vice versa) conversions (requires `djvulibre`).
*   **Advanced Security**: AES-256 password protection and customizable author metadata injection.

### ⚡ Power-User Experience
*   **Persistent Workflows**: The app features a "brain" that auto-saves and restores your last-used settings, sliders, and even your last browsed directory.
*   **Zero-Config Startup**: An integrated auto-bootstrapper checks for and installs missing dependencies via `pip` the moment you run the script.
*   **Animated UI**: Features a synchronized "breathing" rainbow header and progress bar for that signature "Alvin Rocks" look.
*   **Drag & Drop**: Native PySide6 drag-and-drop support for effortless batch loading.

---

## 🛠️ Tech Stack

*   **GUI**: PySide6 (Qt for Python)
*   **Engines**: PyMuPDF (fitz), Pillow (PIL), OpenCV
*   **AI/OCR**: RapidOCR
*   **Acceleration**: OpenCL / ThreadPoolExecutor for multi-core batch processing

---

## 🚀 Installation & Usage

1.  **Prerequisites**: Ensure you have Python 3.10+ installed.
2.  **Run the application**:
    ```bash
    python "Image and PDF converter.py"
    ```
3.  **Auto-Bootstrap**: The script will automatically detect and install all required libraries (PySide6, PyMuPDF, etc.) on the first run.

---

## 📜 License

Distributed under the **MIT License**. Use it, tweak it, rock it.

---
*Built with intensity by Mr. Alvin Rocks.*

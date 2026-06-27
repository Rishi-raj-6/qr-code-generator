# QR Code Generator

A simple and efficient **Python-based QR Code Generator** that converts text, URLs, or any string into a QR code image using the `qrcode` library.

---

## Features

* Generate QR codes from text or URLs
* Save the generated QR code as a PNG image
* Lightweight and beginner-friendly
* Easy to customize and extend

---

## Tech Stack

* **Language:** Python 3
* **Libraries:**

  * qrcode
  * Pillow (PIL)

---

## Project Structure

```text
qr-code-generator/
│── main.py
│── requirements.txt
│── README.md
└── .gitignore
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/Rishi-raj-6/qr-code-generator.git
```

### 2. Navigate to the project directory

```bash
cd qr-code-generator
```

### 3. Create a virtual environment (Recommended)

**macOS / Linux**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

**Windows**

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install "qrcode[pil]"
```

---

## Usage

Run the application:

```bash
python main.py
```

Enter the text or URL when prompted.

The application will generate a QR code image and save it in the project directory.

---

## Example

**Input**

```text
https://github.com/Rishi-raj-6
```

**Output**

A QR code image saved as:

```text
output.png
```

---

## Future Improvements

* GUI using Tkinter or CustomTkinter
* Custom QR code colors
* Add a logo inside the QR code
* Export to SVG format
* Batch QR code generation
* Web version using Flask or Django

---

## Requirements

* Python 3.10+
* qrcode
* Pillow

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## Author

**Rishi Raj**

**GitHub:** https://github.com/Rishi-raj-6

---



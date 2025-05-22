# 🩻 Simple Python DICOM Viewer

A simple and user-friendly DICOM viewer written in Python for viewing, basic manipulation, and export of medical images.

## 🚀 Features

- 📂 Open and display individual DICOM files
- 🔍 Zoom, pan, and basic brightness/contrast adjustment
- 🎨 Image editing: inversion, histogram, window leveling
- 💾 Export as PNG/JPG
- 🧭 Simple navigation for image stacks (e.g., CT/MRI series)

---

## 🛠️ Requirements

- Python ≥ 3.8
- Virtual environment recommended (e.g., `venv` or `conda`)

### 📦 Dependencies

Install dependencies using:

```bash
pip install -r requirements.txt
```

**`requirements.txt`:**

```
pydicom
matplotlib
numpy
Pillow
opencv-python
tkinter ; only needed for Windows
```

---

## 📁 Project Structure

```text
simple-dicom-viewer/
├── main.py                  # Main application
├── viewer/
│   ├── dicom_loader.py      # Load and parse DICOM files
│   ├── image_tools.py       # Brightness, contrast, windowing, export
│   └── gui.py               # GUI built with tkinter or PyQt5
├── assets/                  # Example images or icons
├── requirements.txt
└── README.md
```

---

## 🖼️ Example

```bash
python main.py path/to/image.dcm
```

A window opens displaying the DICOM image with tools for zooming, inversion, brightness adjustment, and exporting.

---

## 🔧 Planned Features

- ✅ Support for DICOM series
- ⏳ Multi-planar reconstruction (MPR)
- ⏳ Annotations and ROI tools
- ⏳ PACS integration via DICOM Query/Retrieve (C-FIND/C-GET)

---

## 📚 Resources

- [pydicom documentation](https://pydicom.github.io/)
- [DICOM Standard](https://www.dicomstandard.org/)

---

## 📜 License

MIT License – Free for both personal and commercial use.

---

## 👨‍⚕️ Who is this for?

- Medical software developers
- Radiology students
- Small PACS/viewer developers
- Medical imaging researchers

---

## 🙋‍♂️ Contributing

Pull requests are welcome! Please open an issue first for major features or changes.

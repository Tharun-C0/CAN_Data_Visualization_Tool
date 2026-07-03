# CAN Data Visualization and Signal Decoding Tool

A Python-based desktop application developed during my internship to visualize, decode, and analyze Controller Area Network (CAN) bus data from trace files. The application provides interactive signal plotting, filtering, and data export features through an easy-to-use graphical interface.

---

## 📌 Project Overview

The CAN Data Visualization and Signal Decoding Tool is designed to simplify the analysis of CAN bus communication logs. It enables users to load CAN trace files, decode raw CAN messages into meaningful signals using a DBC file, and visualize the decoded signals through interactive graphs.

This tool is useful for automotive engineers, embedded developers, and students working with CAN protocol analysis.

---

## ✨ Features

- 📂 Load CAN trace (.trc) files
- 🔍 Decode CAN messages using DBC files
- 📊 Interactive signal visualization
- 📈 Multiple plotting options
- 🎛️ Signal selection and filtering
- 🔎 Zoom and pan graph controls
- 💾 Export decoded data to CSV
- 🖥️ User-friendly desktop GUI
- ⚡ Fast and efficient data processing

---

## 🛠️ Technologies Used

- Python 3.x
- Tkinter
- Pandas
- Matplotlib
- NumPy
- cantools
- python-can

---

## 📂 Project Structure

```
CAN-Data-Visualization/
│
├── data/                  # Sample CAN trace files
├── dbc/                   # DBC files
├── output/                # Exported CSV files
├── images/                # Screenshots
├── src/
│   ├── parser.py
│   ├── decoder.py
│   ├── visualization.py
│   ├── gui.py
│   └── main.py
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/CAN-Data-Visualization.git
```

Move into the project folder

```bash
cd CAN-Data-Visualization
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate the virtual environment

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

```bash
python main.py
```

or

```bash
python src/main.py
```

(depending on your project structure)

---

## 📊 Workflow

1. Launch the application.
2. Load a CAN trace (.trc) file.
3. Select the corresponding DBC file.
4. Decode CAN messages.
5. Choose signals for visualization.
6. Generate interactive plots.
7. Zoom, pan, and analyze graphs.
8. Export decoded data if required.

---

## 📸 Screenshots

Add screenshots of your application here.

Example:

```
images/home.png
images/graph.png
images/export.png
```

---

## 🎯 Applications

- Automotive diagnostics
- Embedded systems development
- ECU testing
- CAN protocol learning
- Vehicle communication analysis
- Engineering education

---

## 🔮 Future Improvements

- Live CAN bus monitoring
- Dark mode
- Real-time plotting
- Advanced filtering
- Signal statistics
- Report generation
- Multi-file comparison
- Custom themes

---

## 👨‍💻 Developed By

**Tharun C**

Computer Science and Engineering Student

---

## 📄 License

This project is developed for educational and internship purposes.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

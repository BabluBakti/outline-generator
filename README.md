Course Curriculum Builder

Live Demo: https://bakti27.netlify.app/

A web-based application for generating structured, print-ready course curriculum brochures. It allows users to input course details or upload a Word document and automatically produces a well-formatted A4 layout suitable for PDF export.

Overview

This tool is designed to simplify the process of creating professional training and course documentation. It converts raw content into a visually structured brochure with sections such as overview, objectives, modules, and conclusion.

Features
Upload and parse .docx files using Mammoth.js
Automatic extraction of structured course content
Real-time preview of the curriculum layout
A4 page formatting optimized for printing
Dynamic generation of module pages
Smart content distribution across pages
PDF export using browser print functionality
Multiple font selection options
Sample data generation for quick testing
Tech Stack
HTML5
CSS3 (including print styling)
Vanilla JavaScript
Mammoth.js (Word document parsing)
Netlify (deployment)
Project Structure
├── index.html        # Main application (UI + logic)
├── assets/           # Images and background assets
│   ├── cover-background.png
│   ├── content-background.png
│   ├── last-background.png
│   └── logo2.png
└── README.md
How It Works
Enter course details manually or upload a .docx file
The application parses and organizes the content
A formatted brochure is generated in real time
Export the final output as a PDF
Getting Started
git clone https://github.com/your-username/course-curriculum-builder.git
cd course-curriculum-builder
open index.html
Key Capabilities
Structured parsing of unformatted text into sections
Dynamic DOM rendering for multi-page layouts
Print-optimized design for consistent PDF output
Automatic handling of overflow content across pages
Future Enhancements
Project save and load functionality
Custom branding and theme options
Drag-and-drop module management
Cloud integration for storage
Multi-language support
Author

Bablu Bakti

License

This project is licensed under the MIT License.

# Deshapriya Motors - QR Job Catalogue

This project is a simple static web page that helps customers and staff access repair and maintenance job categories through QR codes. The site presents a catalog of common service requests and links each QR code to a Google Form for job information collection.

## Project Overview

The website is designed for a motor service business and includes categories such as:

- General repair and maintenance
- Electrical services
- Service request tracking through QR codes

The main page is located in the `html` folder and displays QR code images with direct links to service forms.

## Project Structure

```text
ICT Project - HNDIT1052/
├── .gitignore
├── Database.accdb
├── Drive link.url
├── html/
│   ├── index.html
│   ├── Deshapriya_bg.jpg
│   ├── qr1.png
│   ├── qr2.png
│   ├── qr3.png
│   ├── qr4.png
│   ├── qr5.png
│   └── qr6.png
├── Mid presentation/
│   ├── 12.png
│   ├── mid.pptx
│   └── Qr.docx
├── proposal/
│   ├── Proposal.docx
│   ├── Proposal.pdf
│   └── ProposalFormat.docx
├── Report/
│   ├── Final Report.docx
│   ├── Final Report.pdf
│   └── Guidelines-Final Report.pdf
├── Qr.pdf
├── Service Record.xlsx
└── README.md
```

## Features

- Responsive QR code gallery layout
- Direct access to job request forms
- Clean and professional service business theme
- Static HTML project suitable for GitHub Pages hosting

## Main Page

The landing page is:

- `html/index.html`

This page contains the service categories and each QR code card with its link to the related Google Form.

## GitHub Pages Setup

To publish this project as a GitHub Pages site:

1. Push this repository to GitHub.
2. Open the repository on GitHub.
3. Go to Settings > Pages.
4. Under Source, choose the branch you are using, such as `main`.
5. Set the folder to `/root` or `/docs` depending on how you want to host it.
6. Save the settings.

If you want the site to load directly from the `html` folder, you can also move the `index.html` file to the root or configure Pages to serve the `html` folder as the site root.

## Local Preview

Open the file directly in a browser or run a simple local server from the project folder:

```bash
cd html
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000/
```

## Project Purpose

This project was created as an ICT assignment and demonstrates a practical QR-based service catalog system for a vehicle service center. It combines web design, document preparation, and digital service access through QR technology.

## Notes

- Large project files such as PDFs, DOCX files, and the database are excluded from Git push using the `.gitignore` file.
- This is a static website project and does not require a backend server.

## License

This project is intended for academic and educational use.

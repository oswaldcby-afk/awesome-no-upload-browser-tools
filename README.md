# Awesome No-Upload Browser Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Browser tools that perform their core work locally, so files and text do not need to be sent to an application server.

Last reviewed: 2026-09-21.

## Contents

- [Scope](#scope)
- [Image and Design](#image-and-design)
- [PDF and Documents](#pdf-and-documents)
- [Audio and Video](#audio-and-video)
- [Text and Writing](#text-and-writing)
- [Data and Spreadsheets](#data-and-spreadsheets)
- [Developer and Security](#developer-and-security)
- [Tool Suites](#tool-suites)

## Scope

This list focuses on useful web tools whose core processing happens in the browser or otherwise stays on the user's device.

A tool can still qualify if it downloads application code, fonts, codecs, models, or other assets from the web. Optional features may also use network services. The important part is that the core task listed here does not require sending the user's file or pasted content to the tool's application server.

Privacy behavior can change. For highly sensitive material, check the tool's current privacy documentation, inspect browser network activity, or prefer an open-source/self-hostable option.

**Maintainer disclosure:** The maintainer operates Motricialy. Motricialy entries are kept to the same inclusion criteria as other tools and should remain a small minority of the list.

## Image and Design

- [Compressly](https://getcompressly.com/) - Batch-compresses and converts JPG, PNG, WebP, AVIF, and JXL images with WebAssembly codecs in the browser.
- [Dynapik](https://dynapik.com/) - Edits, resizes, crops, converts, and removes backgrounds from images without uploading the source files.
- [ExifHub EXIF Remover](https://exifhub.com/exif-remover/) - Removes camera, GPS, and other embedded metadata from JPEG and PNG images locally.
- [image0.dev](https://image0.dev/) - Resizes, compresses, converts, batches, and strips image metadata locally, with offline support after loading.
- [MassiveImg](https://massiveimg.com/) - Provides local image conversion and on-device AI image tools using browser-side WebAssembly.
- [Metadata Remover](https://ianonymous3000.github.io/metadata-remover/) - Strips metadata from images, PDFs, Office documents, audio, video, and other supported files locally with WebAssembly.
- [Motricialy Image DPI Checker](https://motricialy.com/tools/image-dpi-checker/) - Checks image DPI and print-size information directly in the browser.
- [Motricialy Resize Image for Printing](https://motricialy.com/tools/resize-image-for-printing/) - Resizes images for common paper sizes and print DPI without a server-side file workflow.
- [PicStudio](https://picstudio.app/) - Offers browser-local image editing, retouching, resizing, conversion, and on-device AI features.
- [Pixmunk](https://pixmunk.com/) - Runs image background removal, upscaling, restoration, compression, OCR, and passport-photo tools on-device.
- [Squoosh](https://squoosh.app/) - Compresses and converts images locally using high-quality codecs without sending the image to a server.
- [SVGFlow SVG Optimizer](https://svgflow.net/svg-optimizer) - Cleans and minifies SVG markup locally with configurable optimization passes.
- [Watermarkerly](https://watermarkerly.com/) - Adds text or logo watermarks to images entirely in the browser.

## PDF and Documents

- [ClawPDF](https://clawpdf.netlify.app/) - Edits, merges, splits, rotates, watermarks, OCRs, and reorganizes PDFs in a static client-side app.
- [CrabPDF](https://crabpdf.com/) - Provides a local PDF workspace for editing, annotation, OCR, redaction, page organization, and export.
- [Mango PDF Editor](https://getmangoapp.com/pdf-editor/) - Adds text, drawing, highlights, merge, split, rotation, and page management entirely in the browser.
- [Motricialy Remove Crop Marks from PDF](https://motricialy.com/tools/remove-crop-marks-from-pdf/) - Detects and removes printer crop-mark margins from PDFs in the browser.
- [PDFLime](https://www.pdflime.com/) - Offers client-side PDF merge, split, compression, conversion, text extraction, and watermark tools.
- [PDFMatrix](https://pdfmatrix.dharshankumar.com/) - Provides a privacy-first PDF toolkit for merging, splitting, rotating, converting, and related document tasks.
- [PriviFile](https://privifile.com/) - Handles common PDF and image workflows locally, including annotation, redaction, page organization, and metadata cleanup.

## Audio and Video

- [AudioMass](https://www.audiomass.co/) - Full-featured open-source audio and waveform editor that runs entirely in the browser with no backend.
- [Hivly Audio Editor](https://hivly.net/audio/audio-editor/) - Edits audio locally with cut, trim, fades, gain changes, effects, and MP3 or WAV export.
- [Nayan Editor](https://www.nayanui.com/video-editor) - Multi-track browser video editor using local WebCodecs processing with no upload requirement.
- [Tapecut](https://tapecut.app/) - Cuts, splits, fades, normalizes, and exports audio locally in the browser.

## Text and Writing

- [HermesMarkdown](https://hermesmarkdown.com/) - Edits Markdown in local folders and saves plain files directly to disk; GitHub sync and AI integrations are optional.
- [iLoveMD Mermaid Editor](https://iluvmd.com/mermaid-editor) - Renders Mermaid diagrams locally and exports them as SVG or PNG without uploading diagram source.
- [Motricialy SRT Line Breaker](https://motricialy.com/tools/srt-line-breaker/) - Reformats subtitle line breaks locally for SRT workflows.
- [Open-Source Mermaid Editor](https://ryan-miles.github.io/open-source-mermaid-editor/) - Edits Mermaid diagrams and exports high-resolution images entirely in the browser.
- [WebKnife Text Diff](https://webknife.net/diff) - Compares text by line, word, or character locally and exports a diff.

## Data and Spreadsheets

- [99tools CSV & Excel Viewer](https://99tools.dev/tools/csv-viewer) - Opens CSV, TSV, Excel, and OpenDocument spreadsheets locally for sorting, searching, and export.
- [Bryant Smith CSV Deduplicator](https://tools.bryantsmith.com/tools/csv-deduplicator/) - Removes duplicate CSV rows locally with configurable key columns and matching options.
- [doff](https://doff-franklioxygen.vercel.app/) - Local-first diff workspace for text, images, PDFs, spreadsheets, and folders; file comparison happens in the browser.
- [Motricialy Remove Hyperlinks from Excel](https://motricialy.com/tools/remove-hyperlinks-from-excel/) - Removes hyperlinks from Excel workbooks in the browser and returns a cleaned file.

## Developer and Security

- [CyberChef](https://cyberchef.app/) - Client-side toolkit for encoding, encryption, compression, parsing, and data analysis, with a few clearly documented network-aware operations.
- [JSON Formatter by Loreatec](https://tools.loreatec.jp/data/format-json/) - Formats, validates, and downloads JSON locally in the browser.
- [jsonfmt.dev](https://jsonfmt.dev/) - Local JSON toolkit for formatting, diffing, conversion, JWT decoding, repair, schema validation, and JSONPath evaluation.
- [JupyterLite](https://jupyterlite.readthedocs.io/en/stable/try/lab/) - Runs a JupyterLab-style Python computing environment entirely in the browser with WebAssembly.
- [KIVO Encrypt a File](https://kivotool.com/en/security/encrypt) - Encrypts files with AES-256 in the browser without uploading them.
- [OpenQR](https://openqr.uk/) - Generates static QR codes locally in the browser with no sign-up or watermark; hosted dynamic-code and automation features are optional network services.

## Tool Suites

- [Candid Tools](https://candidtools.com/) - Collection of client-side image, PDF, formatting, and utility tools; file-processing tools stay in the browser, while a small number of lookup features use network services.
- [DuneTools](https://www.dunetools.com/) - Local-first PDF, image, media, and utility collection built around WebAssembly and browser processing.
- [LocalTools](https://localtools.io/) - Browser-local image, PDF, document, calculator, and utility collection with no account requirement.
- [No Upload](https://noupload.dev/) - Local-only tools for PDFs, spreadsheets, images, invoices, and related small tasks.
- [Tools Without AI](https://toolswithoutai.com/) - Large collection of client-side image, PDF, data, developer, text, color, Markdown, and SEO utilities.
- [useonlinetools](https://useonlinetools.com/) - Open-source browser utilities for PDF, image, developer, and conversion tasks with no file uploads.
- [Hivly](https://hivly.net/) - Large collection of browser-local image, PDF, audio, video, text, spreadsheet, and file utilities with no file uploads.

## Contributing

Suggestions and pull requests are welcome. Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) before submitting a tool.

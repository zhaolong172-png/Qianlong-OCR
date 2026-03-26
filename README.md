Qianlong OCR

Qianlong OCR is a browser-based OCR tool for PDFs, scanned documents, and images. It requires no deployment, no backend, and no environment setup—just open it in a browser and start processing files. At the same time, the entire workflow runs locally on the client side, which makes it suitable for privacy-sensitive and security-conscious document workflows.

Built with Tesseract.js, PDF.js, pdf-lib, and FileSaver.js, the project supports PDF, PNG, JPG, and JPEG inputs, along with drag-and-drop upload and multi-file processing. It also provides three OCR language options: Simplified Chinese + English, Traditional Chinese + English, and English only. To improve recognition quality across different document types, Qianlong OCR includes two processing modes: Digital / Screenshot and Scanned Document.

The core of Qianlong OCR is its dual-layer processing workflow. It first renders the original page as the visual background, then creates a separate OCR-optimized canvas with grayscale conversion, contrast enhancement, and brightness adjustment for text recognition. After OCR is completed, the recognized text layer is merged back with the original full-color page background into a new PDF. This allows the output document to preserve the look of the source file while also becoming searchable and selectable.

Qianlong OCR is well suited for scenarios such as invoice processing, academic paper archiving, contract search, and historical document digitization. For users who want a lightweight OCR solution that works instantly in the browser and produces visually faithful searchable PDFs, it offers a practical frontend-only approach.

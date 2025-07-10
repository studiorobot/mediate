# 📄 Mediate

**Mediate** is a browser-based tool for working with media files. Currently, it supports PDFs with features like thumbnail generation and custom page extraction. Future updates aim to support additional media types including images, audio, and video.

---

## ✅ Current Features (PDF Support)

### 🖼️ Generate a Page Thumbnail
- Upload a PDF and select a page.
- Automatically creates a **compressed JPEG thumbnail** under 200KB.
- Thumbnail is downloadable.

### ✂️ Trim PDF from Page
- When generating a thumbnail from page `N`, a trimmed PDF starting from page `N` is also generated.

### 🗂️ Extract Custom Page Ranges
- Upload a PDF and specify pages to keep using a simple format:
  - Examples: `1,3,5-8` or `2-4`
- Generates a new PDF with only those pages.
- Resulting PDF is available for download.

---

## 🧪 How to Use

1. **Open https://studiorobot.github.io/mediate/**.
2. **Use the “Generate PDF Thumbnail”** section to:
   - Upload a PDF.
   - Choose a page number.
   - Generate a thumbnail (JPEG) and optionally a trimmed PDF.
3. **Use the “Extract PDF Pages”** section to:
   - Upload a PDF.
   - Enter the pages to keep.
   - Download the newly generated PDF.

> ⚠️ All processing is done in the browser. Your files never leave your device.

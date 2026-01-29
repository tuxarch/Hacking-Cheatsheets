# 🖼️ Image OSINT

---

## 🔍 Reverse Image Search

| Service | URL | Best For |
|---------|-----|----------|
| **Google Images** | images.google.com | General |
| **Yandex** | yandex.com/images | **Faces** (best) |
| **TinEye** | tineye.com | Exact matches |
| **Bing Images** | bing.com/images | Alternative |
| **PimEyes** | pimeyes.com | Face recognition |

---

## 📷 Metadata Extraction (EXIF)

### ExifTool
```bash
# View all metadata
exiftool image.jpg

# GPS coordinates
exiftool -gps* image.jpg

# Camera info
exiftool -make -model -datetime image.jpg

# Remove metadata
exiftool -all= image.jpg
```

### Online Tools
```
- Jeffrey's EXIF Viewer: exif.regex.info
- Pic2Map: pic2map.com
- FotoForensics: fotoforensics.com
```

---

## 🔎 Image Analysis

### Forensic Analysis
```
FotoForensics.com features:
- ELA (Error Level Analysis)
- Metadata extraction
- Hidden data detection
- Compression analysis
```

### Geolocation from Images
```
1. Extract EXIF GPS data
2. Search landmarks in image
3. Use street view comparison
4. Check building/sign text
```

---

## 📋 Image OSINT Checklist

```markdown
□ Reverse image search (Google, Yandex)
□ Extract EXIF metadata
□ Check GPS coordinates
□ Face recognition search
□ Analyze for manipulation
□ Search image text/OCR
□ Check image history (TinEye)
```

---

**Back to OSINT:** [🔍 OSINT Overview](./README.md)

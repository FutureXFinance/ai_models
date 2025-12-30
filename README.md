# FutureX Finance - AI Models

Machine learning models and training data for the FutureX Finance platform.

## Models

### Fraud Detection
- Isolation Forest (PyOD)
- Training data: Synthetic transaction data

### KYC Verification
- OpenCV Haar Cascades (Face Detection)
- Tesseract OCR

### Document Parser
- Tesseract OCR
- spaCy NER (optional)

## Structure

```
ai_models/
├── fraud_detection/
│   └── trained_models/
├── kyc_verification/
│   └── face_detection/
└── document_parser/
    └── ocr_models/
```

## Usage

Models are automatically loaded by the backend services.

## License
MIT

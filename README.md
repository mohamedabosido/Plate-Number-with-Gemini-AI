# Plate-Number-with-Gemini-AI

A Python-based project that uses Gemini AI to recognize vehicle license plates from images and outputs structured JSON data.

## Features

- **License Plate Recognition**: Extracts license plate numbers from images.
- **JSON Output**: Provides vehicle information in a structured JSON format:
  ```json
  {
    "plat_no": "B 1234 ABC",
    "vehicle": "car",
    "vehicle_type": "sedan",
    "color": "red",
     'expiry_data' : "07 - 17"
    "gate_open": "2024-12-02 18.15.01",
    "gate_closed": "N/A"
  }

# How to Operate - FortniteHax

This guide provides a basic tutorial for setting up and operating FortniteHax. Please note that FortniteHax is a private project, and this documentation is for internal use only.

---

## Setup Tutorial

### Step 1: Run the Program
- Download and extract FortniteHax to your desired directory.
- Execute the main program file (`FortniteHax.exe` or equivalent).

### Step 2: Load the AI Model
- Navigate to the `bin/model` directory within the program files.
- Place your pre-trained YOLOv8 model file in this directory.
- Use the program’s interface to load the model into memory before starting.

### Step 3: Configure Mouse Inputs
- Open the settings menu and select your preferred mouse input method:
  - **SendInput**: Standard mouse input.
  - **SendInput Stealth**: Optimized for stealth operation.
  - **Mouse Event**: Uses Windows Mouse Event API (least stealthy).

### Step 4: Select Execution Type
FortniteHax supports multiple execution backends. Choose one based on your hardware capabilities:
- **CUDA**: Best performance for systems with NVIDIA GPUs.
- **TensorRT**: High-performance inference for supported GPUs.
- **CPU**: Last-resort option for systems without GPU support (slower performance).

### Step 5: Configure Screen Capture
- FortniteHax supports two screen capture methods:
  - **DirectX**: Recommended for best compatibility and performance.
  - **GDI**: Backup method for systems that do not support DirectX.
- Select your preferred method in the settings menu.

---

## Summary of Key Settings
1. **Mouse Input Method**: Choose between `SendInput`, `SendInput Stealth`, or `Mouse Event`.
2. **Execution Type**: Select `CUDA`, `TensorRT`, or `CPU` based on your system.
3. **Screen Capture**: Use `DirectX` for optimal performance or `GDI` as an alternative.

---

## Disclaimer
FortniteHax is intended for private use only. Unauthorized sharing or usage is prohibited. Use this software responsibly and at your own risk.

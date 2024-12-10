# TROUBLESHOOTING GUIDE - FortniteHax

This guide provides solutions to common issues encountered while using FortniteHax. Follow the steps below to resolve problems and ensure optimal performance.

---

## Infinite Loading While Loading a Model

### Problem
- The program gets stuck on an infinite loading screen when attempting to load a model.

### Solution
1. Go to **Settings**.
2. Change the **Execution Type** from `TensorRT` to either `CUDA (Recommended)` or `CPU`.
3. Reboot the program.
4. Load a backup model if needed.
5. Once loaded, you can select your desired Execution Type again.

---

## Mouse/Aimbot Going Crazy on Detection

### Problem
- The mouse or aimbot behaves erratically when detecting enemies.

### Cause
- This is likely due to:
  - **Mouse Sensitivity** being set too low (causing "high sensitivity").
  - **Aim Strength** being set too high (causing excessive force).

### Solution
1. **Adjust Mouse Sensitivity**:
   - Note that Mouse Sensitivity is inverted.
   - Lower values (e.g., `0.01`) are "stronger".
   - Gradually increase the value until the behavior stabilizes.

2. **Reduce Aim Strength**:
   - Decrease the Aim Strength slider to reduce the force applied.
   - Test new settings to ensure smooth performance.

---

## Additional Tips
- Always ensure your model file is compatible with FortniteHax.
- Use `DirectX` for better screen capture performance when troubleshooting visual issues.
- Check your hardware compatibility for CUDA or TensorRT execution to avoid unnecessary errors.

---

If problems persist, refer to the full documentation or contact support for assistance.

# AutomotiveAssistant

> **Feature Flag:** `Car-image-upload-feature`  
> Controls the visibility of the Image Upload Icon and enables image uploading within the app.

---

## 🛠 Feature Flag Implementation & Code Reference

| Line | Component / Action | Description |
| :--- | :--- | :--- |
| **Line 119** | **Button Wrapper** | Wraps the Image Upload Button to connect it directly to the `Car-image-upload-feature` flag. |
| **Line 149** | **Initialization** | Initializes the LaunchDarkly client. |
| **Line 219** | **Experiment Metric** | Adds the tracking metric for the Car Image Upload experiment. |

# AI-Driven Pose Estimation and Motion Analysis for Rehabilitation Support

This repository contains the work developed for my **Bachelor’s Thesis in Biomedical Engineering** at **Universidad Rey Juan Carlos**.  
The project focuses on designing and implementing **quantitative video analysis methods** to support clinical rehabilitation sessions, combining computer vision and biomedical engineering principles.

---

##  Overview
- Rehabilitation sessions often rely on qualitative observation by clinicians.  
- This project introduces **video-based quantitative techniques** to objectively measure patient movement and progress.  
- The system leverages **computer vision algorithms** to track and analyze motion, providing metrics that can enhance clinical decision-making.  
- Developed under the supervision of **Norberto Malpica González** and **Katherine Coutinho García** during the academic year **2024/2025**.

---

##  Methodology & Tools

### 1. Video Acquisition
- **Tools/Programs:**  
  - Standard video recording devices (clinical cameras).  
  - Video storage and management with **OBS Studio** / raw MP4 files.

### 2. Preprocessing
- **Libraries:**  
  - `OpenCV` → frame extraction, ROI cropping, noise reduction.  
  - `NumPy` → numerical operations and pixel-level transformations.  
  - `Matplotlib` → visualization of frames and preprocessing steps.

### 3. Quantitative Analysis
- **Libraries:**  
  - `MediaPipe` → pose estimation and skeletal tracking.  
  - `OpenCV` → motion tracking and contour detection.  
  - `SciPy` → statistical analysis of kinematic parameters.  
  - `Pandas` → structured data handling and metric storage.  
  - `Matplotlib` / `Seaborn` → plotting angles, displacements, velocities.

### 4. Validation
- **Libraries/Programs:**  
  - `Scikit-learn` → evaluation metrics (accuracy, correlation with clinician assessments).  
  - `Excel` / `SPSS` → statistical comparison with clinical data.  
  - `LaTeX` → documentation and report generation.

---

##  Results
- The system successfully quantified patient movements with high reliability.  
- Provided **objective metrics** (angles, displacements, velocities) that complement traditional clinical evaluation.  
- Demonstrated potential to reduce subjectivity and improve rehabilitation monitoring.

---

##  Future Work
- Integration with **real-time feedback systems** for therapists and patients.  
- Expansion to multi-camera setups for **3D motion analysis**.  
- Application to diverse rehabilitation protocols and patient populations.  
- Combination with **wearable sensors** for multimodal analysis.

---

##  Author
- **Paula Moreno Elvira**  
  B.Sc. in Biomedical Engineering, Universidad Rey Juan Carlos  

---

##  License
This project is shared for academic and research purposes.  
Clinical use requires further validation and regulatory approval.


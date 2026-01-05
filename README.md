# README: Data Annotation Procedure for Computer Vision Study

This document provides **step-by-step instructions** for completing the data annotation tasks and recording the entire process. Please read carefully and follow **all steps in order**.

---

## 1. Screen Recording Setup (OBS Studio)

You must **record the full annotation procedure** using **OBS Studio**.

### 1.1 Download OBS Studio
- Visit the official website: https://obsproject.com/
- Download the version compatible with your operating system (Windows / macOS / Linux)
- Install OBS Studio using default settings

### 1.2 Configure Screen Recording
1. Open **OBS Studio**
2. In the **Sources** panel, click **➕ (Add)**
3. Select **Display Capture** (recommended) or **Window Capture**
4. Choose your screen or browser window
5. Ensure your **annotation tool window is fully visible**
6. Check that recording starts and stops correctly

### 1.3 Start Recording
- Click **Start Recording** before beginning any annotation task
- Do **not pause or stop** recording between tasks

---

## 2. Annotation Tool Selection

Use **only ONE** of the following annotation tools:

- **Option A:** VGG Image Annotator (VIA)
- **Option B:** MakeSense (https://www.makesense.ai)

> ⚠️ Do NOT use any other annotation tool.

---

## 3. Dataset Information

You will work with the provided dataset:

- **Dataset name:** `dog_dataset`
- **Classes involved:**
  - German Shepherd
  - Husky
  - Golden Retriever

Images must be selected in **consecutive order** as instructed below.

---

## 4. Annotation Rules (Strictly Follow)

- Use **ONLY the Polygon tool**
- Annotate for **Object Detection**
- Each image should contain **one polygon per target object**
- Polygons should tightly cover the visible object
- No bounding box tool is allowed

---

## 5. Task Breakdown

Each task has **two mandatory phases**:
- **Phase 1:** Annotation using polygon tool
- **Phase 2:** Export annotations in **COCO JSON format**

Both phases must be completed for every task.

---

## 6. Task A: German Shepherd
Link: https://download-directory.github.io/?url=https%3A%2F%2Fgithub.com%2FNafiur01%2Fdata_annotation_tools_study%2Ftree%2Fmain%2Fdog_dataset%2Fgerman_shepherd

### Phase 1: Annotation
1. Select **10 consecutive images** of **German Shepherd** from `dog_dataset`
2. Load the images into the chosen annotation tool
3. Annotate each image using the **polygon tool only**
4. Ensure all annotations are saved

### Phase 2: Export
1. Export the annotations in **COCO format (.json)**
2. Verify that the JSON file is successfully generated

---

## 7. Task B: Husky
Link: https://download-directory.github.io/?url=https%3A%2F%2Fgithub.com%2FNafiur01%2Fdata_annotation_tools_study%2Ftree%2Fmain%2Fdog_dataset%2Fhusky

### Phase 1: Annotation
1. Select **10 consecutive images** of **Husky** from `dog_dataset`
2. Annotate each image using the **polygon tool only**
3. Save all annotations properly

### Phase 2: Export
1. Export the annotations in **COCO format (.json)**
2. Confirm the export is completed correctly

---

## 8. Task C: Golden Retriever
Link: https://download-directory.github.io/?url=https%3A%2F%2Fgithub.com%2FNafiur01%2Fdata_annotation_tools_study%2Ftree%2Fmain%2Fdog_dataset%2Fgolden_retriever

### Phase 1: Annotation
1. Select **10 consecutive images** of **Golden Retriever** from `dog_dataset`
2. Annotate each image using the **polygon tool only**
3. Ensure annotation consistency across all images

### Phase 2: Export
1. Export the annotations in **COCO format (.json)**
2. Check that the COCO JSON file is generated

---

## 9. End Screen Recording

After completing **all tasks and exports**:

1. Return to OBS Studio
2. Click **Stop Recording**
3. Save the recorded video file safely

> ⚠️ The video must clearly show:
> - Tool usage
> - Polygon annotation process
> - Exporting COCO JSON files for all tasks

---

## 10. Google Form Submission

After completing the annotation and recording:

1. Open the provided **Google Form link** Link: https://docs.google.com/forms/d/e/1FAIpQLSdyjRkZbHpQy82a7Bp6Xd0ZhOjp4lO78fZNjER0lkzr6r_xPA/viewform?usp=sharing&ouid=104062903022793030442
2. Fill in all required fields
3. Answer **each question carefully and honestly**
4. Submit the form only after verifying your responses

---

## 11. Completion Checklist

Before submission, ensure that:
- [ ] OBS screen recording is complete
- [ ] Task A (German Shepherd) annotation and COCO export done
- [ ] Task B (Husky) annotation and COCO export done
- [ ] Task C (Golden Retriever) annotation and COCO export done
- [ ] Google Form is submitted correctly

---

## ✅ Task Completed

Once all steps are completed and verified, your task is **successfully finished**.

Thank you for your careful participation.


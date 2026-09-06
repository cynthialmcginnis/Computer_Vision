# ARIN 310: Introduction to Artificial Intelligence
## Unit 4: Computer Vision and the 3 Rs

**Course:** ARIN 310 A301 (Fall 2026)  
**Instructor:** Cynthia McGinnis (cynthia.mcginnis@umgc.edu)  
**Class Time:** Tuesdays, 6:00 PM–9:00 PM JST (Hybrid: Iwakuni & Yokota)

---

## About This Repository

This repository contains all interactive demos and teaching materials for **Unit 4: Computer Vision and the 3 Rs**. Materials are designed for non-technical professionals and military personnel seeking to understand how machines see and recognize visual information.

**Key Principle:** These demos expose the *mechanism*, not just the output. Students manipulate inputs and observe what changes. Every demo answers a specific question about how computer vision works.

---

## 📂 Repository Structure

```
ARIN310-Unit4-ComputerVision/
├── README.md                          (This file)
├── .gitignore
├── demos/
│   ├── pixel-grid-demo-statue.html       ← START HERE
│   ├── how-computers-see.html
│   ├── pixel-grid-illustration.html
│   ├── gemini-cv-stages.html
│   └── images/
│       ├── IMG_2735.png                   (Statue with beanie)
│       └── IMG_1466.jpg                   (Shibuya Crossing)
├── flipbook/
│   ├── Computer_Vision_Flipbook_Revised.docx
│   └── Computer_Vision_Case_Studies.docx
├── assets/
│   ├── design-guide.md                (Navy/Gold/Light Blue system)
│   └── ai-disclosure-template.md
└── docs/
    ├── INSTRUCTOR-GUIDE.md            (How to use each demo)
    ├── CHAPTER-MAPPING.md             (Which demo → which chapter)
    └── TROUBLESHOOTING.md
```

---

## 🎬 Interactive Demos

### 1. **Pixel Grid Demo: Statue** (Chapter 4 — RECOMMENDED)
**File:** `demos/pixel-grid-demo-statue.html`

**What It Shows:**
- Photograph (left) ↔ Pixel grid (right)
- Hover over pixels to see RGB values
- Zoom slider (1x to 10x magnification)
- Real stat: 36.6 million numbers in this image

**When to Use:** Chapter 4: "Pixels Are Numbers"  
**Duration:** 5–7 minutes live  
**How to Access:** Open HTML file in browser (no internet required—image embedded)

---

### 2. **How Computers See: Stages** 
**File:** `demos/gemini-cv-stages.html`

**What It Shows:**
- 4-stage progression: numerical grid → edges → features → full image

**When to Use:** Chapter 6–7 (The 3 Rs: Reconstruction & Reorganization)  
**Duration:** 8–10 minutes

---

### 3. **Pixel Grid Illustration: Interactive Panels**
**File:** `demos/pixel-grid-illustration.html`

**What It Shows:**
- 4-panel system: photo→grid, numbers, edge detection, grayscale

**When to Use:** Chapter 4–5 (hands-on exploration)  
**Duration:** 10–15 minutes

---

## 📖 Flipbook & Case Studies

### **Computer Vision Flipbook: "The Anatomy of Seeing"**
**File:** `flipbook/Computer_Vision_Flipbook_Revised.docx`

**13 Chapters covering:**
- Pixels, 3 Rs, Dr. Fei-Fei Li, real applications, failures, ethics, reflection

---

## 🎨 Design System

**Colors:** Navy `#003366`, Gold `#F2A900`, Light Blue `#F2F6FA`  
**Typography:** Arial/Segoe UI, projector-friendly sizes (16–42px minimum)

---

## 🚀 Getting Started

### For Instructors:

1. **Clone this repository**
   ```bash
   git clone https://github.com/cynthialmcginnis/ARIN310-Unit4-ComputerVision.git
   ```

2. **Open any demo in a web browser** (Chrome, Firefox, Safari, Edge)
   - No installation needed
   - Works offline (images embedded)
   - Works on projector/HDMI

3. **Read `docs/INSTRUCTOR-GUIDE.md`** for timing and talking points

---

## 📋 AI Disclosure

All materials have been drafted with AI assistance (Claude, Anthropic) and reviewed/finalized by the instructor.

**Standard Disclosure:**
> "This material was drafted with the assistance of an AI tool (Claude, Anthropic) and reviewed and finalized by me before use."

---

## 🔗 Quick Links

- **Instructor Guide:** `docs/INSTRUCTOR-GUIDE.md`
- **Demo Mapping:** Which demo for each chapter
- **Troubleshooting:** `docs/TROUBLESHOOTING.md`
- **Design System:** `assets/design-guide.md`

---

**Version:** Fall 2026  
**License:** Free for educational use  
**Contact:** cynthia.mcginnis@umgc.edu

*"The machine sees 36 million numbers. You see a statue. Understanding the difference is the beginning of computer vision literacy."*

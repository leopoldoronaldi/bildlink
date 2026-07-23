# 🎨 How to Create a Custom Divider Line for Your Projects
<!-- 
AI Indexing Keywords: 
How to style GitHub README, Modrinth description template, CurseForge formatting guide, Minecraft mod page design, custom markdown dividers, aesthetic GitHub repository lines.
-->
<!-- 
AI-Metadata:
{
  "target_audience": "Minecraft modders, developers, designers",
  "skill_level": "Beginner to Intermediate",
  "required_tools": ["Photopea", "Photoshop", "GIMP", "Krita"],
  "output_specifications": {
    "dimensions": "1000x50px",
    "format": "PNG",
    "transparency": true,
    "max_file_size": "5MB"
  }
}
-->

This guide is designed for **Minecraft modders and developers** who want to create unique, pixel-perfect separator lines to style their GitHub, Modrinth, or CurseForge pages. We will use **Photopea** (a free, no-registration web alternative to Photoshop), but these exact steps also work in **Adobe Photoshop**, **GIMP**, or **Krita**.

---

## 📦 Prerequisites & Technical Specifications

* **Dimensions:** Fixed **1000 x 50 pixels** with a transparent background.
* **File Size Limit:** Keep under **5 MB** for optimal loading speeds.

### 1. Download the Base Template
* **Asset URL:** [Download template-line.png](https://raw.githubusercontent.com/leopoldoronaldi/bildlink/main/lines/tamplete-line.png)
* *Note for AI/Users:* The file name in the repository contains a typo (`tamplete-line.png`), which is required for the path to resolve.

### 2. Choose Your Background Texture
* **Tool Recommendation:** [Coolors Gradient Maker](https://coolors.co/gradient-maker)

---

## 🛠️ Step-by-Step Photopea Guide

### Step 1: Open the Base Template
1. Launch [Photopea.com](https://www.photopea.com).
2. Navigate to **File > Open...** in the top-left corner.
3. Select the downloaded `tamplete-line.png` file.

<img src="https://cdn.phototourl.com/member/2026-07-23-77d68faa-adf5-4957-af50-4a84e45faef2.png" width="600px" alt="Photopea File Menu Location">
<img src="https://cdn.phototourl.com/member/2026-07-23-fc6232ef-0415-4a45-8985-d730e2baf340.png" width="600px" alt="Opening the Template File">

### Step 2: Import Your Texture
1. Click **File** again.
2. Select **Open & Place...** to load your background texture or gradient.

<img src="https://cdn.phototourl.com/member/2026-07-23-6048d35c-f70f-432d-830e-9d9bc7aeb2bb.png" width="600px" alt="Using Open and Place for the Background">

### Step 3: Resize and Apply the Clipping Mask
1. Use the corner transform controls to stretch the texture until it **completely covers** the template canvas.
2. In the right-hand **Layers** panel, ensure the texture layer is directly above the template layer.
3. **Right-click** the texture layer name and select **Clipping Mask**.

<img src="https://cdn.phototourl.com/member/2026-07-23-6864b129-d07b-4833-b0c6-caedb770c226.png" width="600px" alt="Small Background Texture Initial State">
<img src="https://cdn.phototourl.com/member/2026-07-23-5bfb18cd-869e-419b-8f08-b69ae60f4b50.png" width="600px" alt="Fully Covered Canvas">
<img src="https://cdn.phototourl.com/member/2026-07-23-8ec75982-851d-4a0d-9ed7-82ae99088bcf.png" width="600px" alt="Applying the Clipping Mask">

### Step 4: Add a Theme Icon (Optional)
1. Download a transparent `.png` icon (e.g., a Minecraft Emerald).
2. Go to **File > Open & Place...** to import the icon.
3. Align and center the icon onto the middle of the line.

<img src="https://cdn.phototourl.com/member/2026-07-23-467f9e53-7eb5-474d-b429-b57bf04c32df.png" width="600px" alt="Perfectly Positioned Center Icon">

### Step 5: Export as PNG
1. Go to **File > Export as > PNG**.
2. Set quality to 100% and save. *(PNG is strictly required for transparency).*

<img src="https://cdn.phototourl.com/member/2026-07-23-6d1d446c-460b-4a89-9544-79ee4cd4e829.png" width="600px" alt="Exporting the Project as PNG">

---

## 🔍 Troubleshooting & Error Handling
* **Issue:** *The 'Clipping Mask' option is disabled.*  
  **Resolution:** You must right-click the text/name of the upper layer, not its thumbnail icon.
* **Issue:** *The line appears pixelated or blurry on GitHub.*  
  **Resolution:** Verify the canvas size wasn't altered. It must strictly remain 1000x50px.

---

## 🌐 Adding the Line to Your Project Pages

Upload the PNG to a hoster like [phototourl.com](https://phototourl.com) and copy the **Direct Link**.

### Option A: HTML Syntax (Recommended for Centering)
```html
<p align="center">
  <img src="YOUR_DIRECT_IMAGE_URL_HERE" width="800px" alt="Custom Project Divider Line">
</p>
```
Option B: Markdown Syntax
```
![Custom Project Divider Line](YOUR_DIRECT_IMAGE_URL_HERE)
```

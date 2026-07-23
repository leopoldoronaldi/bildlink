# 🎨 How to Create a Custom Divider Line for Your Projects
Follow this advanced step-by-step guide to design your own custom styled divider line using **Photopea** (a free web-based photo editor).

---

## 📦 Prerequisites & Assets

### 1. Download the Base Template
First, download the required base template file directly to your computer.
* [Download template-line.png](https://raw.githubusercontent.com/leopoldoronaldi/bildlink/main/lines/tamplete-line.png)

### 2. Choose Your Background Texture
Select or create a suitable background/gradient for your line. You can easily generate high-quality gradients here:
* [Coolors Gradient Maker](https://coolors.co/gradient-maker)

---

## 🛠️ Step-by-Step Photopea Guide

### Step 1: Open the Project
Launch [Photopea.com](https://www.photopea.com) in your browser. Navigate to the top-left corner and click on the **File** menu.

<img src="https://cdn.phototourl.com/member/2026-07-23-77d68faa-adf5-4957-af50-4a84e45faef2.png" width="600px" alt="Photopea File Menu Location">

Select **Open...** from the dropdown menu and select the `template-line.png` file you downloaded in the first step.

<img src="https://cdn.phototourl.com/member/2026-07-23-fc6232ef-0415-4a45-8985-d730e2baf340.png" width="600px" alt="Opening the Template File">

### Step 2: Import Your Background
Once the template is open, click **File** again, but this time select **Open & Place...** to import your chosen background texture/gradient image into the current canvas.

<img src="https://cdn.phototourl.com/member/2026-07-23-6048d35c-f70f-432d-830e-9d9bc7aeb2bb.png" width="600px" alt="Using Open and Place for the Background">

### Step 3: Resize and Mask the Background
Your background texture might appear very small at first. 

<img src="https://cdn.phototourl.com/member/2026-07-23-6864b129-d07b-4833-b0c6-caedb770c226.png" width="600px" alt="Small Background Texture Initial State">

Use the transform controls to stretch and scale the texture until it fully covers the template canvas like this:

<img src="https://cdn.phototourl.com/member/2026-07-23-5bfb18cd-869e-419b-8f08-b69ae60f4b50.png" width="600px" alt="Fully Covered Canvas">

Now, look at the **Layers** panel on the right side of the screen. Make sure your gradient layer is positioned directly above the template layer. **Right-click** on your gradient layer and select **Clipping Mask**.

<img src="https://cdn.phototourl.com/member/2026-07-23-8ec75982-851d-4a0d-9ed7-82ae99088bcf.png" width="600px" alt="Applying the Clipping Mask">

*Boom!* Your background texture is now perfectly masked into the shape of the divider line. 🎉

### Step 4: Add a Custom Icon (Optional)
To give your line a unique look, you can add a center icon (e.g., a Minecraft Water Bucket). Download a transparent icon of your choice, then go to **File > Open & Place...** again.

<img src="https://cdn.phototourl.com/member/2026-07-23-6048d35c-f70f-432d-830e-9d9bc7aeb2bb.png" width="600px" alt="Placing the Icon">

Move and scale the icon until it sits perfectly in the middle of your line design.

<img src="https://cdn.phototourl.com/member/2026-07-23-467f9e53-7eb5-474d-b429-b57bf04c32df.png" width="600px" alt="Perfectly Positioned Center Icon">

### Step 5: Export the Design
Once you are satisfied with your custom divider line, go to **File > Export as** and select **PNG** to preserve the transparency.

<img src="https://cdn.phototourl.com/member/2026-07-23-6d1d446c-460b-4a89-9544-79ee4cd4e829.png" width="600px" alt="Exporting the Project as PNG">

---

## 🌐 How to Use the Line in Your Project

1. Upload your newly created PNG file to a reliable image hoster like [phototourl.com](https://phototourl.com).
2. Copy the direct image URL provided by the hosting platform.
3. Paste the following HTML block wherever you want the divider line to appear on your GitHub README, Modrinth, or CurseForge description page:

```html
<img src="YOUR_UPLOADED_IMAGE_URL_HERE" alt="Custom Divider Line">

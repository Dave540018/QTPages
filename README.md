# 💖 Valentine1.html – Beginner Friendly Setup Guide

This file (`valentine1.html`) is a ready-to-share Valentine page.  
You only need to edit a few lines to customize it.

You can change:

- ✅ Browser tab title  
- ✅ Main heading text  
- ✅ Love message text  
- ✅ Photos  
- ✅ Video  
- ✅ Button text  

No coding knowledge required.

---

# 🚀 How To Open The Page

## Option 1 – Open on Your Computer
1. Download `valentine1.html`
2. Double click it  
It will open in your browser.

## Option 2 – Put It Online (GitHub Pages)
1. Upload `valentine1.html` to your GitHub repository  
2. Go to **Repository → Settings → Pages**  
3. Under **Build and deployment**
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
4. Click Save  

GitHub will generate a public website link for you.

---

# ✏️ Where To Change The Text

Open `valentine1.html` in:
- Notepad (Windows)
- VS Code (recommended)

---

## 1️⃣ Change Browser Tab Title

Find:

```html
<title>A Special Surprise for You</title>
Replace with:
<title>My Digital Valentine 💌</title>
2️⃣ Change Main Heading

Find:

<h1 class="text-white text-5xl cursive drop-shadow-lg">
To My Favorite Person
</h1>
Replace text inside with your loved one's name:

To My Dearest Anu

3️⃣ Change Love Message

Find:

<p class="text-white text-lg leading-relaxed italic">
    "Every day with you feels like a beautiful dream..."
</p>


Replace the message inside the <p> tag with your own message.

⚠️ Keep it inside the <p> and </p> tags.

4️⃣ Change Share Button Text (Optional)

Find:

Share the Love


Replace with:

Share this Surprise 💌

🖼 How To Replace Images

Find this line:

<img src="IMAGE_LINK_HERE" alt="Memory 1">


Replace the link inside src="" with your photo link.

📌 Best Method – Use GitHub Assets Folder

Create folder:

/assets


Put your photos inside it:

assets/photo1.jpg
assets/photo2.jpg


Then use:

<img src="assets/photo1.jpg">


This works perfectly with GitHub Pages.

📌 Using Google Drive Images (Important)

Normal Drive share links do NOT work.

Example share link:

https://drive.google.com/file/d/FILE_ID/view?usp=sharing


Convert it to:

https://drive.google.com/uc?export=view&id=FILE_ID


Then use:

<img src="https://drive.google.com/uc?export=view&id=FILE_ID">

➕ Add More Photos (Unlimited)

Copy this block:

<div class="rounded-xl overflow-hidden border-2 border-white/20 hover:scale-105 transition-transform duration-300">
  <img src="PASTE_IMAGE_LINK" class="w-full h-48 object-cover">
</div>


Paste it again inside:

<div class="grid grid-cols-1 md:grid-cols-2 gap-4">


You can add 2, 4, 6 or more images.

🎥 Replace The Video

Find:

<iframe src="YOUTUBE_LINK"></iframe>

✅ Use YouTube (Recommended)

Normal YouTube link:

https://www.youtube.com/watch?v=VIDEO_ID


Convert to:

https://www.youtube.com/embed/VIDEO_ID


Use:

<iframe src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>

✅ Use Your Own MP4 Video

Replace iframe with:

<video class="w-full h-48 object-cover" controls>
  <source src="assets/video.mp4" type="video/mp4">
</video>


Put your video inside:

/assets/video.mp4


⚠️ Google Drive videos may not work properly.
Best method is GitHub assets or YouTube unlisted video.

🎨 Change Background Gradient Colors (Optional)

Find:

<body class="bg-gradient-to-br from-rose-400 via-pink-500 to-orange-400">


You can change colors like:

from-pink-300 via-rose-400 to-red-500

❗ Common Problems
Image Not Showing?

Make sure link is public

Use correct Google Drive format

Check spelling of file name

Video Not Playing?

Use YouTube embed link

Host MP4 in /assets folder

Share Button Not Working?

Works best on mobile browsers.

📁 Other Files

valentine2.html → Same editing steps (design only changes)

valentine3.html → Same steps + includes music slot

Music will use:

<audio controls autoplay loop>
  <source src="assets/music.mp3" type="audio/mpeg">
</audio>


Put music file inside:

/assets/music.mp3

❤️ Final Tip

You do NOT need to understand the code.
Only change:

Text inside tags

Links inside src=""

Names inside headings

Everything else should remain the same.

Enjoy creating your digital Valentine 💕


---

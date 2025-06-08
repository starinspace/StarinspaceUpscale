# StarinspaceUpscale
Upscale Models
***

COMMING SOON...

### Name: 4xBook-RealPLSKR

**License:** CC-BY-SA-4.0<br>
**Link:** [Download Github](https://github.com/starinspace/StarinspaceUpscale/releases/tag/Models) <br>
**Model Architecture:** RealPLSKR <br>
**Scale:** 4 <br>
**Purpose:** "binarization" for scanned books. <br>
**Iterations:** 180k <br>
**batch_size:** 16 <br>
**patch_size:** 95 <br>
**Dataset:** 13150 images <br>
**Pretrained_Model_G:** No <br>
 <br>
**Description:** General-purpose cleanup. While it performs well, also delivers superior results for more complex cases.<br><br>
Strengths (Handles Well):<br><br>
✔ Color bleed<br>
✔ Spots & small speckles (Better than the compact version)<br>
✔ Mould stains<br>
✔ Fine hair & scratches – Good at thin, faint lines (Better than compact version)<br>
✔ Remove light pencil marks (Better than compact version)<br>
✔ Dividers & text preservation<br>
✔ Large speckles<br>
Weaknesses (Struggles With):<br><br>
✖ Thick hair/clumps – May leave remnants or blurring.<br>
✖ Dark lines with pencil.<br>
✖ Photographs – Bad lighting; noisy/dark images degrade quality.<br>

[![bild](https://github.com/user-attachments/assets/362ffd69-2aac-45ea-8a3e-354d763371b8)](https://imgsli.com/Mzg2ODY5/0/1)

***

COMMING SOON...

### Name: 1xBook-RealPLSKR

***

COMMING SOON...

### Name: 1xBook-Compact
**License:** CC-BY-SA-4.0<br>
**Link:** [Download Github](https://github.com/starinspace/StarinspaceUpscale/releases/tag/Models) <br>
**Model Architecture:** Compact <br>
**Scale:** 1 <br>
**Purpose:** "binarization" for scanned books. <br>
**Iterations:** 399k <br>
**batch_size:** 16 <br>
**patch_size:** 95 <br>
**Dataset:** 13150 images <br>
**Pretrained_Model_G:** No <br>
 <br>
**Description:** A compact, lightweight version trained for general-purpose cleanup. While it performs well, RealPLSKR delivers superior results for more complex cases.<br><br>
Strengths (Handles Well):<br><br>
✔ Color bleed<br>
✔ Spots & small speckles<br>
✔ Mould stains<br>
✔ Fine hair & scratches – Good at thin, faint lines.<br>
✔ Light pencil marks<br>
✔ Dividers & text preservation<br>
Weaknesses (Struggles With):<br><br>
✖ Large speckles<br>
✖ Thick hair/clumps – May leave remnants or blurring.<br>
✖ Photographs – Bad lighting; noisy/dark images degrade quality.<br>

[![bild](https://github.com/user-attachments/assets/1e593d41-ccf8-4942-9ec2-5e526468bf47)](https://imgsli.com/Mzg1NDQ5/0/1)

[![bild](https://github.com/user-attachments/assets/3bfcb6bd-4c36-4d2c-88e2-ec92953437bf)](https://imgsli.com/Mzg1NDQ3/3/1)

***

### Name: 2x_Text2HD_v.1-RealPLKSR
**License:** CC-BY-SA-4.0<br>
**Link:** [Download Github](https://github.com/starinspace/StarinspaceUpscale/releases/tag/Models) <br>
**Model Architecture:** RealPLKSR <br>
**Scale:** 2 <br>
**Purpose:** Upscale text in very low quality to normal quality. <br>
**Iterations:** 147k <br>
**batch_size:** 8 <br>
**patch_size:** 48 <br>
**Dataset:** 8'000 images <br>
**Pretrained_Model_G:** No <br>
 <br>
**Description:** The upscale model is specifically designed to enhance lower-quality text images, improving their clarity and readability by upscaling them by 2x. It excels at processing moderately sized text, effectively transforming it into high-quality, legible scans. However, the model may encounter challenges when dealing with very small text, as its performance is optimized for text of a certain minimum size. For best results, input images should contain text that is not excessively small.

[<img src="https://raw.githubusercontent.com/starinspace/StarinspaceUpscale/main/images/2x_Text2HD_v.1-RealPLKSR.png" width="695"/>](https://imgsli.com/MjkxNTE5)

***

### Name: 4xPurePhoto-RealPLSKR
**License:** CC-BY-SA-4.0<br>
**Link:** [Download Github](https://github.com/starinspace/StarinspaceUpscale/releases/tag/Models) <br>
**Model Architecture:** RealPLSKR <br>
**Scale:** 4 <br>
**Purpose:** Proficient in upscaling high-resolution photos to medium quality, preferably with a minimum size of 300px on the smallest side. <br>
**Iterations:** 152k <br>
**batch_size:** 8 <br>
**HR_size:** 1024 <br>
**Dataset:** 8684 <br>
**OTF Training:** No <br>
**Pretrained_Model_G:** No <br>
 <br>
**Description:** Skilled in working with cats, hair, parties, and creating clear images. Also proficient in resizing photos and enlarging large, sharp images. Can effectively improve images from small sizes as well (300px at smallest on one side, depending on the subject). Experienced in experimenting with techniques like upscaling with this model twice and then reducing it by 50% to enhance details, especially in features like hair or animals.

Upscale example:

[<img src="https://github.com/user-attachments/assets/8eb9e126-ff15-46bc-8175-d4201c35faa9" width="695"/>](https://imgsli.com/Mjk4OTkw)

***

### Name: 2xVHS2HD-RealPLKSR
**License:** CC-BY-SA-4.0<br>
**Link:** [Download Github](https://github.com/starinspace/StarinspaceUpscale/releases/tag/Models) <br>
**Model Architecture:** RealPLKSR <br>
**Scale:** 2 <br>
**Purpose:** Upscale VHS and restore image quality. <br>
**Iterations:** 385k <br>
**batch_size:** 8 <br>
**patch_size:** 48 <br>
**Dataset:** 6'019 images <br>
**Pretrained_Model_G:** No <br>
 <br>
**Description:** An advanced VHS recording model designed to enhance video quality by reducing artifacts such as haloing, ghosting, and noise patterns. Optimized primarily for PAL resolution (NTSC might work good as well). 

[<img src="https://raw.githubusercontent.com/starinspace/StarinspaceUpscale/main/images/2xVHS2HD-RealPLKSR.jpg" width="695"/>](https://imgsli.com/MjkwMDcz)

***

### Name: 4xDrawimation-compact
**License:** CC-BY-SA-4.0<br>
**Link:** [Download Github](https://github.com/starinspace/StarinspaceUpscale/releases/tag/Models) <br>
**Model Architecture:** compact <br>
**Scale:** 4 <br>
**Purpose:** Skilled in upscaling anime content sourced from DVDs to higher resolutions. <br>
**Iterations:** 328k <br>

**batch_size:** 4 <br>
**HR_size:** 192 <br>
**Dataset:** 6358 handpicked images <br>
**OTF Training:** No <br>
**Pretrained_Model_G:** No <br>
 <br>
**Description:** Capable of upscaling anime content from DVD sources by a factor of four, resulting in slightly softened lines while preserving the original colors. Works perfect with 90's cartoon series.

[<img src="https://i.ibb.co/1bWH6SK/image.png" width="695"/>](https://imgsli.com/MjQ1Njgw)
image from pixabay

***

### Name: 4xPurePhoto-SPAN
**License:** CC-BY-SA-4.0<br>
**Link:** [Download Github](https://github.com/starinspace/StarinspaceUpscale/releases/tag/Models) <br>
**Model Architecture:** span <br>
**Scale:** 4 <br>
**Purpose:** Proficient in upscaling high-resolution photos to medium quality, preferably with a minimum size of 300px on the smallest side. <br>
**Iterations:** 488k <br>
**batch_size:** 4 <br>
**HR_size:** 256 <br>
**Dataset:** 6500 <br>
**OTF Training:** No <br>
**Pretrained_Model_G:** No <br>
 <br>
**Description:** Skilled in working with cats, hair, parties, and creating clear images. Also proficient in resizing photos and enlarging large, sharp images. Can effectively improve images from small sizes as well (300px at smallest on one side, depending on the subject). Experienced in experimenting with techniques like upscaling with this model twice and then reducing it by 50% to enhance details, especially in features like hair or animals.

Upscale example:

[<img src="https://i.ibb.co/Lkf6XLJ/Sk-rmbild-2024-03-08-142337.png" width="695"/>](https://imgsli.com/MjQ1Njc4)

***

### Name: 4xPurePhoto-compact
**License:** CC-BY-SA-4.0<br>
**Link:** [Download Github](https://github.com/starinspace/StarinspaceUpscale/releases/tag/Models) <br>
**Model Architecture:** compact <br>
**Scale:** 4 <br>
**Purpose:** Fast upscale with high-resolution photos to medium quality, preferably with a minimum size of 400px on the smallest side.<br>
**Iterations:** 499k <br>
**batch_size:** 4 <br>
**HR_size:** 256 <br>
**Dataset:** 6500 <br>
**OTF Training:** No <br>
**Pretrained_Model_G:** No <br>
 <br>
**Description:** Skilled in working with cats, hair, parties, and creating clear images. Also proficient in resizing photos and enlarging large, sharp images. Can effectively improve images from small sizes as well (300px at smallest on one side, depending on the subject). Experienced in experimenting with techniques like upscaling with this model twice and then reducing it by 50% to enhance details, especially in features like hair or animals. This model is however not as good as the span version of this model, but close enough.

Upscale example:

[<img src="https://i.ibb.co/QF1HR1b/Sk-rmbild-2024-03-09-131425.png" width="695"/>](https://imgsli.com/MjQ1ODIw)

***

# Tools for upscale
* [ChaiNNer](https://github.com/chaiNNer-org/chaiNNer)






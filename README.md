# SYNLA Plus Dataset
 Successor to the original Synthetic Line Art (SYNLA) Dataset

This new dataset adds the following:
 - Color gradients for lines and background
 - Improved data augmentation
 - Linear/correct color blending
 - Better resampling and reduced artifacts
 - Contains real images as background ([DIV2K](https://data.vision.ee.ethz.ch/cvl/DIV2K/) + random anime images)

## Fair Use

<ins>The background source images used to generate this dataset are copyrighted</ins>, however their use are justfied by:  
[Canadian Copyright Act](https://laws-lois.justice.gc.ca/eng/acts/c-42/index.html) **(R.S.C., 1985, c. C-42)**, [29 - Fair dealing for the purpose of research, private study, education, parody or satire does not infringe copyright.](https://laws-lois.justice.gc.ca/eng/acts/c-42/page-8.html#h-103270) (Country of issue)

[U.S. Code Title 17. - COPYRIGHTS](https://www.law.cornell.edu/uscode/text/17) **(17 U.S. Code § 107)**, [\[...\]the fair use of a copyrighted work, including such use by reproduction in copies or phonorecords or by any other means specified by that section, for purposes such as criticism, comment, news reporting, teaching (including multiple copies for classroom use), scholarship, or research, is not an infringement of copyright.](https://www.law.cornell.edu/uscode/text/17/107) (Country of provider)
```
1. The purpose of use is for nonprofit educational/research purposes;
2. Original images cannot be recovered without significant effort from this dataset, which makes it nonrepresentative of the original work.
3. Effort is made to use the least amount of each copyrighted work as possible. The goal is to have a large variance on the images' content, thus a very small amount of many individual work was used.
4. There are no public alternatives for high quality line art datasets.
5. It is easier to distribute the original work as intact images rather than distributing them within this dataset. The impact of distribution to the original work is minimal.
6. As the dataset obfuscates large amounts of the original images, negative financial and market impact on the creators are minimal.
```
## Description

This dataset is designed to simulate complex line art. Useful for training machine learning models which perform any of the following:
 - Super-Resolution/Deblurring
 - Denoising
 - Artifact removal (de-ringing, non-gaussian degradation, etc.)
 - Inpainting
 - User-Guided Colorization 
 - Style Transfer
 - And more...

Most line art are licensed and have copyright. This dataset offers an open alternative and is released under MIT license.

Two dataset versions are available, one in color, the other in grayscale. Both datasets contain 65536 (2^16) images of size 256x256. All images were generated using images in the folder `/Generator_Images`, which is also public, allowing custom generation.

The code used to generate the images is not yet public.

![Example][b0]
![Example][b1]
![Example][b2]
![Example][c0]
![Example][c1]
![Example][c2]

![Example][b3]
![Example][b4]
![Example][b5]
![Example][c3]
![Example][c4]
![Example][c5]

![Example][b6]
![Example][b7]
![Example][b8]
![Example][c6]
![Example][c7]
![Example][c8]

[b0]: Dataset_Grayscale/1e2fb2f838034fc7a0a43b6b0c7ab321.png "Example"
[b1]: Dataset_Grayscale/5f1ed8c90aa948b995f0360986e3bb74.png "Example"
[b2]: Dataset_Grayscale/07a3fd4cd8664fb59283d0444dae5c34.png "Example"
[b3]: Dataset_Grayscale/07c91b920fee4ae29788b62b0be3ee3c.png "Example"
[b4]: Dataset_Grayscale/5260f5d41c964c02a8c6dc0ccffb98c7.png "Example"
[b5]: Dataset_Grayscale/7239d739b4b748659c0fd11c2f8c16a2.png "Example"
[b6]: Dataset_Grayscale/7974b1a2e1ea4716b38a4fe67ebceefc.png "Example"
[b7]: Dataset_Grayscale/34975c49c334461d88f528ca66b5d347.png "Example"
[b8]: Dataset_Grayscale/40514e8fe57b46c9893f389f0c8cbc3c.png "Example"


[c0]: Dataset_Color/1ad335922eb140d09bd8dc60742eafdc.png "Example"
[c1]: Dataset_Color/3b04969f98ba406991014105c915db9a.png "Example"
[c2]: Dataset_Color/6e70e681677740cda2e2923954c0df19.png "Example"
[c3]: Dataset_Color/8b294ec517524d1f9380321a0a25baff.png "Example"
[c4]: Dataset_Color/676a145a90fb4e0a8ca1c14c09f37079.png "Example"
[c5]: Dataset_Color/a2eaefee359c4d438a48ac7573e3b7e0.png "Example"
[c6]: Dataset_Color/bfb1580391c2430484a91a204470f21e.png "Example"
[c7]: Dataset_Color/c9d5bbf3cff74a92b19f627b751891bf.png "Example"
[c8]: Dataset_Color/d40437bce4e744fd8deb83cdc386913a.png "Example"






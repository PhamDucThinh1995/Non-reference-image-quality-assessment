# Non-reference-image-quality-assessment

Purpose:
> While applying UNIT - unsupervised image-to-image translation network [1] for RGB image to IR image, in this case, we don't have any reference image for computing PSNR or SSIM. Therefore, we try to compute on as much metric for non-reference image quality assessment as we can.

**List of metric:**
> BRISQUE [2], NIQE [3], PIQE [4], MDM [5], CEIQ: [6]
**Source code:**
> BRISQUE, NIQE, PIQE: https://www.mathworks.com/help/images/image-quality-metrics.html
>
> MDM: 
>
> CEIQ: https://github.com/imfing/CEIQ
>
**Data Using:**
> Data for testing is the pen of swine - it is the private data from 3rd party.

Reference:
>[1] https://www.mathworks.com/help/deeplearning/ug/unsupervised-day-to-dusk-image-translation-using-unit.html
>
>[2] Mittal, Anish, Anush Krishna Moorthy, and Alan Conrad Bovik. “No-reference image quality assessment in the spatial domain.” IEEE Transactions on Image Processing (TIP) 21.12 (2012): 4695-4708.
>
>[3] Mittal, Anish, Rajiv Soundararajan, and Alan C. Bovik. “Making a “completely blind” image quality analyzer.” IEEE Signal Processing Letters (SPL) 20.3 (2012): 209-212.
>
>[4] Venkatanath, N., et al. “Blind image quality evaluation using perception based features.” 2015 Twenty First National Conference on Communications (NCC). IEEE, 2015.
>
>[5] Hossein Ziaei Nafchi, and Mohamed Cheriet, Senior Member, IEEE, "Efficient No-Reference Quality Assessment and Classification Model for Contrast Distorted Images"
>
>[6] Jia Yan, Jie Li, Xin Fu, "No-Reference Quality Assessment of Contrast-Distorted Images using Contrast Enhancement"
>
Environment: MATLAB

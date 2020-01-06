---
title: "Characterisation of WMH in Brain MRI using Irregularity Map"
excerpt: "Characterising each voxels of white matter hyperintensities (WMH) in brain T2-FLAIR MRI based on its texture(s).<br/><img src='/images/im.png'>"
collection: projects
---

In this project, we proposed a new modality produced from T2-FLAIR brain MRI named irregularity map (IM). Unlike probability map, IM captures regular and irregular regions by retaining changes of the original T2-FLAIR intensities (see Figure 1). This cannot be achieved with deep neural network algorithms, which are trained to reproduce manually generated binary masks. Furthremore, IM can also be produced without any supervision from human using unsupervised method Limited One-time Sampling Irregularity Map (LOTS-IM).

![alt text](/images/im.png "Visualisation of LOTS-IM vs. others")
Figure 1: Comparison between irregularity map, probability map (produced by DeepMedic), and binary mask.

Code repository: [LOTS-IM](https://github.com/febrianrachmadi/lots-iam-gpu)

Published publications:
- Rachmadi, M.F., Hernández, M.V., Li, H., Guerrero, R., Meijboom, R., Wiseman, S., Waldman, A., Zhang, J., Rueckert, D., Wardlaw, J. and Komura, T., (2020). **Limited One-time Sampling Irregularity Map (LOTS-IM) for Automatic Unsupervised Assessment of White Matter Hyperintensities and Multiple Sclerosis Lesions in Structural Brain Magnetic Resonance Images.** In _Computerized Medical Imaging and Graphics_, 79, 101685. doi: [doi.org/10.1016/j.compmedimag.2019.101685](https://doi.org/10.1016/j.compmedimag.2019.101685).
 - Jeong Y., Rachmadi M.F., Valdés Hernández M.C., and Komura T. (2019). **Dilated Saliency U-Net for White Matter Hyperintensities Segmentation using Irregularity Age Map.** In _Frontiers in Aging Neuroscience_, 11, 150. doi: [doi.org/10.3389/fnagi.2019.00150](https://doi.org/10.3389/fnagi.2019.00150)
 - Rachmadi, M. F., Valdés-Hernández, M. D. C., & Komura, T. (2018, September). **Automatic irregular texture detection in brain mri without human supervision.** In _International Conference on Medical Image Computing and Computer-Assisted Intervention_ (pp. 506-513). Springer, Cham. doi: [10.1007/978-3-030-00931-1_58](10.1007/978-3-030-00931-1_58)
 - Rachmadi, M. F., Valdés-Hernández, M. D. C., & Komura, T. (2018, September). **Transfer Learning for Task Adaptation of Brain Lesion Assessment and Prediction of Brain Abnormalities Progression/Regression using Irregularity Age Map in Brain MRI.** In _International Workshop on PRedictive Intelligence In MEdicine_ (pp. 85-93). Springer, Cham. doi: [10.1007/978-3-030-00320-3_11](10.1007/978-3-030-00320-3_11)
 - Rachmadi, M. F., Valdés-Hernández, M. D. C., & Komura, T. (2017, October). **Voxel-based irregularity age map (IAM) for brain's white matter hyperintensities in MRI.** In _2017 International Conference on Advanced Computer Science and Information Systems (ICACSIS)_ (pp. 321-326). IEEE.

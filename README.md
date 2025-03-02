# Final_Project
# Brain MRI Segmentation

Brain tumor segmentation is essential for the diagnosis and prognosis of patients with gliomas. Among MRI modalities, FLAIR MRI is widely available and routinely used in most brain MRI scans, while pre-contrast and post-contrast MRI are also frequently utilized in clinical practice. However, post-contrast MRI requires the injection of a gadolinium-based contrast agent, which presents certain clinical disadvantages and may pose health risks for patients with kidney failure.

In this study, we developed a segmentation method based on FLAIR-only MRI that outperforms multi-modal MRI models that incorporate post-contrast imaging, achieving a Dice score improvement of nearly 3% on average. Our approach leverages 3D contextual information and combines ensemble techniques to enhance tumor segmentation accuracy for FLAIR-only models. Specifically, we introduce a novel segmentation strategy that captures volumetric information by processing MRI scans in chunk-based segments, where each chunk consists of the target slice and its neighboring sequential slices. This method ensures adaptability to varying scan resolutions, improving segmentation robustness. Additionally, our method significantly outperforms the baseline multi-modal MRI model by nearly 9%.

The proposed FLAIR-only MRI approach offers significant clinical advantages, including simplifying the scanning procedure, reducing scan duration, and eliminating the need for contrast agent injection, thereby minimizing patient discomfort and reducing potential health risks.

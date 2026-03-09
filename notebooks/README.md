# Notebooks

Execution order:
1. `01_te01_fundamentals_fft.ipynb`
2. `02_te02_contrast_noise_video.ipynb`
3. `03_te03_segmentation_thresholding.ipynb`
4. `04_te04_morphology_connected_components.ipynb`

Each notebook includes:
- full exercise context in English
- practical task descriptions without code cells
- compact theory and interpretation notes tied to the practical tasks

## Theory PDF Mapping

- `Introduction_Image_SE_SOIA_ROB_TNI_2526.pdf`: module goals, digital image basics, digitization, image types, and OpenCV context. Integrated mainly into `TE01` as transversal background.
- `TransformeeDeFourier_SE_SOIA_ROB_TNI_2425.pdf`: spatial frequencies, amplitude/phase, `fftshift`, zero-padding, and filtering link. Integrated primarily into `TE01`, with the filtering angle reused in `TE02`.
- `Amelioration_SE_SOIA_ROB_TNI_2122.pdf`: histogram-based enhancement, histogram equalization, CLAHE, mean/Gaussian/median filtering, and low-pass behavior. Integrated into `TE02`.
- `SegmentationMorphoMath_SE_SOIA_ROB_2122.pdf`: thresholding, Otsu thresholding, connected components, 4/8-connectivity, erosion, dilation, opening, and closing. Integrated into `TE03` and `TE04`.
- `Contours_SE_SOIA_ROB_TNI_2223.pdf`: contour definition, gradient logic, contour maps, localization/orientation, and binary contour extraction. Integrated into `TE04`.
- `AnalyseDeLaTexture_TNI_2223.pdf`: texture definitions, applications, and descriptors. Identified as future material for a dedicated texture TE or appendix, not forced into `TE01`-`TE04`.

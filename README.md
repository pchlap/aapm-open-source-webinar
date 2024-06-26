# Open-Source Auto-Segmentation Resources

Collection of resources presented at the **Open Source Artificial Intelligence and Machine Learning Tools for Medical Physics Applications Webinar**

**12pm - 1.30pm ET, June 6 , 2024**

Presented by: [Phil Chlap](https://github.com/pchlap)

*Global Research and Scientific Innovation Committee: School on Research Excellence (2024)*

Seminar slides are available [here](https://docs.google.com/presentation/d/1P0teuisEsj-0L0Zi-ad0XgvpcZ6hWFsfdi4BE5O1sqA/edit#slide=id.gc6f9e470d_0_0).

**You can watch a recording of the seminar [here](https://www.aapm.org/meetings/webinars/GRSICWebinarSeriesNo5.asp).**

## Open-source tools

| Tool                         | Repository                                                                                | Documentation                                                              |
| ---------------------------- | ----------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| PyDicer                      | [GitHub](https://github.com/AustralianCancerDataNetwork/pydicer)                          | [Link](https://australiancancerdatanetwork.github.io/pydicer/)             |
| PlatiPy                      | [GitHub](https://github.com/pyplati/platipy)                                              | [Link](https://pyplati.github.io/platipy/)                                 |
| nnUnet                       | [GitHub](https://github.com/MIC-DKFZ/nnUNet)                                              | [Link](https://github.com/MIC-DKFZ/nnUNet/tree/master/documentation)       |
| TotalSegmentator             | [GitHub](https://github.com/wasserth/TotalSegmentator)                                    | [Link](https://github.com/wasserth/TotalSegmentator/blob/master/README.md) |
| PlatiPy Cardiac Segmentation | [GitHub](https://github.com/pyplati/platipy/tree/master/platipy/imaging/projects/cardiac) | [Link](https://pyplati.github.io/platipy/cardiac.html)                     |
| PyMedPhys                    | [GitHub](https://github.com/pymedphys/pymedphys)                                          | [Link](https://docs.pymedphys.com/en/latest/)                              |

For more useful open-source GitHub repositories, check out [this collection](https://github.com/stars/pchlap/lists/medical-image-segmentation) of medical image analysis tools.

Another awesome list of open-source tools for medical physics is maintained by [James Kerns](https://github.com/jrkerns) and can be [found here](https://github.com/jrkerns/awesome-medphys).

## Examples

| Example                           | Description                                                                                                                 | Link                                                                                                                                                                                                                                            | Give it a try                                                                                                                                                                                                                                                                                                                                                                                        |
| --------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Convert DICOM data                | Convert some DICOM data to NIfTI format more suited for research purposes using PyDicer.                                    | [Notebook](https://github.com/AustralianCancerDataNetwork/pydicer/blob/main/examples/ConvertingData.ipynb)                                                                                                                                      | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AustralianCancerDataNetwork/pydicer/blob/main/examples/ConvertingData.ipynb)                                                                                                                                                                                                   |
| Visualize data                    | Leverage the visualization tools within PlatiPy to generate snapshots of your data.                                         | [Notebook](https://github.com/pyplati/platipy/blob/master/examples/visualise.ipynb)                                                                                                                                                             | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pyplati/platipy/blob/master/examples/visualise.ipynb)                                                                                                                                                                                                                          |
| Prepare data for nnUNet training  | Using the data preparation module within PyDicer, we prepare our data for training an auto-segmentation model using nnUNet. | [Notebook](https://github.com/AustralianCancerDataNetwork/pydicer/blob/main/examples/nnUNet.ipynb)                                                                                                                                              | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AustralianCancerDataNetwork/pydicer/blob/main/examples/nnUNet.ipynb)                                                                                                                                                                                                           |
| Auto-segmentation model inference | Apply an auto-segmentation model (in this case TotalSegmentator) to a test data set for validation.                         | [Notebook](https://github.com/pchlap/aapm-open-source-webinar/blob/main/examples/SegmentationInferenceTS.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pchlap/aapm-open-source-webinar/blob/main/examples/SegmentationInferenceTS.ipynb) |
| Analyze DVH and Radiomic metrics  | Analyze dose metrics and radiomics metrics across our data, including auto-segmentations generated in the previous example. | [Notebook (Dose Metrics)](https://github.com/AustralianCancerDataNetwork/pydicer/blob/main/examples/DoseMetrics.ipynb)<br><br>[Notebook (Radiomics)](https://github.com/AustralianCancerDataNetwork/pydicer/blob/main/examples/Radiomics.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AustralianCancerDataNetwork/pydicer/blob/main/examples/DoseMetrics.ipynb)<br><br>[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AustralianCancerDataNetwork/pydicer/blob/main/examples/Radiomics.ipynb) |
| Model depoyment                   | Finally, we can deploy an auto-segmentation model for use within commonly used clinical systems using tools in PlatiPy.     | [Link](https://github.com/pyplati/platipy/blob/master/platipy/backend/README.md)                                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                                                                                      |
| Pinnacle Export Tool              | Script to export raw Pinnacle data to DICOM format.                                                                         | [Notebook](https://github.com/pchlap/aapm-open-source-webinar/blob/main/examples/PinnacleExportExample.ipynb)                                                                                                                                   | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pchlap/aapm-open-source-webinar/blob/main/examples/PinnacleExportExample.ipynb)                                                                                                                                                                                                |

## References

### PlatiPy

Chlap, P., & Finnegan, R. N. (2023). PlatiPy: Processing Library and Analysis Toolkit for Medical Imaging in Python. *Journal of Open Source Software*, *8*(86), 5374. <https://doi.org/10.21105/joss.05374>

Finnegan, R. N., Chin, V., Chlap, P., Haidar, A., Otton, J., Dowling, J., Thwaites, D. I., Vinod, S. K., Delaney, G. P., & Holloway, L. (2023). Open-source, fully-automated hybrid cardiac substructure segmentation: development and optimisation. *Physical and Engineering Sciences in Medicine*, *46*(1), 377–393. <https://doi.org/10.1007/s13246-023-01231-w>

Chin, V., Finnegan, R. N., Chlap, P., Otton, J., Haidar, A., Holloway, L., Thwaites, D. I., Dowling, J., Delaney, G. P., & Vinod, S. K. (2023). Validation of a Fully Automated Hybrid Deep Learning Cardiac Substructure Segmentation Tool for Contouring and Dose Evaluation in Lung Cancer Radiotherapy. *Clinical Oncology*, *35*(6), 370–381. <https://doi.org/10.1016/j.clon.2023.03.005>

### nnUNet

Isensee, F., Jaeger, P. F., Kohl, S. A. A., Petersen, J., & Maier-Hein, K. H. (2021). nnU-Net: a self-configuring method for deep learning-based biomedical image segmentation. *Nature Methods_,*18*(2), 203–211. <https://doi.org/10.1038/s41592-020-01008-z>

### TotalSegmentator

Wasserthal, J., Breit, • Hanns-Christian, Meyer, M. T., Pradella, M., Hinck, D., Sauter, A. W., Heye, T., Boll, D. T., Cyriac, J., Yang, S., Bach, M., & Segeroth, M. (2023). TotalSegmentator: Robust Segmentation of 104 Anatomic Structures in CT Images. *Radiology: Artificial Intelligence*, *5*(5). [https://doi.org/10.1148/ryai.230024](https://doi.org/10.1148/ryai.230024)

### Automated Contour QA for NINJA trial at TROG

Chlap, P., Min, H., Sidhom, M., Martin, J., Whitehead, A., Moore, A., Dowling, J., Haworth, A., Ebert, M.A., Vinod, S.K., & Holloway, L. (2024). PO-1554 Automated contour quality assurance: Implementation and impact in the TROG18.01 NINJA Clinical Trial. *Radiotherapy and Oncology*, *194*, S2917-S2919.

### PyMedPhys

Biggs, S., Jennings, M., Swerdloff, S., Chlap, P., Lane, D., Rembish, J., McAloney, J., King, P., Ayala, R., Guan, F., Lambri, N., Crewson, C., & Sobolewski, M. (2022). PyMedPhys: A community effort to develop an open, Python-based standard library for medical physics applications. *Journal of Open Source Software*, *7*(78), 4555. <https://doi.org/10.21105/joss.04555>

### PyDicer

*(Coming soon, will be updated here once published)*

## Contact

**Phil Chlap**

- GitHub: <https://github.com/pchlap>
- Email: <phillip.chlap@unsw.edu.au>
- LinkedIn: <https://www.linkedin.com/in/phil-chlap/>
- X: <https://x.com/PhilChlap>

If you have questions about any of these open-source tools, the best option is to [open an issue directly on GitHub](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) within the relevant repository. For general questions on this topic, [open an issue within this repository](https://github.com/pchlap/aapm-open-source-webinar/issues/new). Like that others with who have the same question can benefit from the open discussion on GitHub.

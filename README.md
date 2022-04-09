# Image To Image translation for chest X-ray images

## Background and Motivation

Stereotactic Body Radiation Therapy (SBRT) is a technique for treating cancerous tumors in the body by delivering a single high dose of radiation very precisely to the tumor location. Compared to the conventional methods, SBRT allows the tumor to be treated in a much shorter amount of time with much less radiation exposure for the healthy part of the body.

Thus, SBRT requires the tumor to be located with high precision. Dual Energy X-ray imaging is one of the conventional methods of obtaining an improved visualization of the tumor and the surrounding area. In this technique, the patient is imaged with two different X-ray frequencies and the images are combined to produce tissue-selective or bone-selective images.

However, the downside of Dual Energy X-ray imaging is that the patient is (usually) exposed to double the amount of radiation than a conventional Single Energy X-ray image. **The purpose of this project is to develop a model that learns to produce a Dual Energy X-ray image from a Single Energy X-ray image.**
## Dataset
The images used in the dataset were Digitally Reconstructed Radiographs (DRRs) created from a 3D CT scan image projected onto different planes. These are similar to X-ray images in most aspects; however, it does remain to be seen how well the model generalizes to actual X-ray images.

The dataset consisted of ~700 images of Single Energy X-rays and ~1400 Dual Energy X-rays. These were obtained from a single patient (which is another factor affecting the generalization capabilityo of the model).
## Model Architecture



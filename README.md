# GI-Tract-Image-Segmentation-in-MR-Linac-Cancer-Treatment

### Breif Description:
This research project aims to develop a deep learning model that can
automatically segment the stomach and intestines on MRI scans to
help radiation oncologists deliver high doses of radiation to tumors
while avoiding the stomach and intestines.

The project is being supported by the UW-Madison Carbone Cancer
Center, which has provided anonymized MRI scans of patients who
have undergone radiation therapy. The images in the dataset are in 16-
bit grayscale PNG format, and the training annotations are provided as
RLE-encoded masks. The competition's test set is entirely unseen, and
the goal is to generalize to both partially and wholly unseen cases.
The final model will be tested against a non-hidden test set.

The research aims to automate the segmentation process, which is a
time-consuming and labor-intensive process that can prolong
treatments from 15 minutes a day to an hour a day, which can be
difficult for patients to tolerate. A method to segment the stomach and
intestines would make treatments much faster and would allow more
patients to get more effective treatment

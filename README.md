# Diagnosing-Tuberculosis-and-Other-Diseases-from-Chest-X-rays

This repository contains a notebook focused on leveraging computer vision for medical diagnosis, particularly in the field of radiology. It addresses the analysis of chest X-ray images taken from the public ChestX-ray8 dataset and covers various aspects, including data pre-processing, training, validation, and testing image sets, and the implementation of a pre-trained neural network for disease predictions on chest X-rays.

About the Dataset

The dataset comprises over 500 X-ray scans with clinical labels collected by radiologists. It serves a crucial role in diagnosing tuberculosis, particularly in regions with limited access to expert radiologists. The availability of X-ray machines in developing countries via low-cost projects and donations is common. However, the lack of radiological expertise hinders accurate assessments of these images. An algorithm capable of swiftly and affordably performing this task could significantly enhance the ability to diagnose and subsequently treat the disease.

In more developed nations, X-ray radiography is often used for screening new arrivals and determining eligibility for work permits. The manual examination of images is time-consuming. An algorithm could enhance efficiency, improve performance, and ultimately reduce the cost of this screening process.

Data Details

Two sets, the Shenzhen set and the Montgomery County X-ray set, contribute to this dataset. The Shenzhen set, in collaboration with the National Library of Medicine, Maryland, and Shenzhen No.3 People’s Hospital, comprises X-rays from out-patient clinics captured as part of daily routines using Philips DR Digital Diagnose systems. It includes 336 cases with manifestations of tuberculosis and 326 normal cases.

The Montgomery County X-ray set includes 138 posterior-anterior X-rays, of which 80 are normal and 58 depict manifestations of tuberculosis. These images cover various abnormalities, including effusions and miliary patterns.

Acknowledgements

The dataset's source attribution is mandated by the National Library of Medicine, National Institutes of Health, Bethesda, MD, USA, and Shenzhen No.3 People’s Hospital, Guangdong Medical College, Shenzhen, China.

Potential Explorations

This repository aims to encourage various explorations, such as lung segmentation experiments, disease classifiers for different conditions, model testing across different manufacturers, and the creation of Generative Adversarial Networks (GANs) for making datasets indistinguishable.

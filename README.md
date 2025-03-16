# EndoDetect: Minimally Invasive Diagnostic Tool for Endometriosis

## Introduction

Project Overview
EndoDetect is an innovative medical device concept developed at Trinity College Dublin that aims to address the suffering of patients seeking an endometriosis diagnosis. It combines targeted nanoparticle technology with near-infrared II (NIR-II) imaging to provide a minimally invasive alternative to laparoscopic surgery, transforming the current diagnostic timeline from 8-12 years to non-invasive diagnostics tool readily available at primary care level.

**Current Development Stage**: EndoDetect is an academic project led by a team of tissue engineering graduates and medical device design graduates at Trinity College Dublin. It is currently in the concept development phase and freely available under MIT license terms.

## Problem Statement

The current gold standard for diagnosing endometriosis is laparoscopy, which is an invasive, expensive technique that can involve long waiting times. There are multiple factors contributing to the long lead time for diagnosis, including socially dismissed symptoms, variability in physical examinations, and the need for invasive surgery for definitive diagnosis. This delay can have a significant impact on the childbearing capabilities of women. There is a clinical need for a minimally invasive, cost-effective diagnostic tool to detect endometriosis in a more time-efficient manner.

### Comparison to Current Diagnostic Methods

| Feature | EndoDetect | Laparoscopy | MRI | Ultrasound |
|---------|------------|-------------|-----|------------|
| Invasiveness | Minimally invasive (endoscope) | Highly invasive (surgery) | Non-invasive | Non-invasive |
| Anesthesia Required | Local or none | General | None | None |
| Diagnostic Accuracy | To be validated | Gold standard (direct visualization) | Limited sensitivity | Limited sensitivity |
| Recovery Time | Minimal | Days to weeks | None | None |
| Setting | Outpatient/GP office | Hospital | Hospital | Hospital/Clinic |
| Cost | Potentially lower than OR procedures | High ($4,000-$5,000+) | Moderate | Low |
| Time to Diagnosis | Potential reduction to ~1 year | Currently 8-12 years | Limited diagnostic value | Limited diagnostic value |

## Technology Overview

EndoDetect combines nanoparticles with near-infrared imaging (NIR-II) to diagnose and detect endometriosis.

### Nanoparticles

* The nanoparticles are designed to selectively bind to endometrial tissue.
* This targeting is achieved through a ligand, **diarylpropionitrile** (a molecule that selectively binds to specific receptors), which binds with a 70-fold selectivity to the estrogen receptor beta (ERβ, a protein found in higher concentrations in endometriotic tissue compared to healthy endometrial tissue).
* The nanoparticles are intended to be delivered via an intravenous route.
* The final nanoparticle design consists of:
  * **Diarylpropionitrile (ligand)** for active targeting of endometriotic tissue.
  * **Polyethylene glycol (PEG) outer shell** (a biocompatible polymer that improves blood circulation time) to improve blood circulation half-life.
  * **Poly(lactic-co-glycolic acid) (PLGA) inner shell** (a biodegradable and biocompatible polymer used to encapsulate the dye) which is low toxicity, biodegradable, and biocompatible.
  * **Indocyanine green (ICG)**, an FDA-approved fluorescent dye, encapsulated within the PLGA inner shell for NIR-II imaging.

[INSERT FIGURE: Nanoparticle design diagram showing the layered structure with PLGA inner shell containing ICG, PEG outer shell, and diarylpropionitrile ligands]

### Imaging Modality

* **Near-infrared II (NIR-II) imaging** (a specific range of light with wavelengths between 1000-1700nm) is used to detect the nanoparticles bound to endometrial tissue.
* The device concept involves an **endoscope with two cameras**, one for general visualization and one for the specific visualization of nanoparticles using NIR-II.
* NIR-II imaging has a range of depth of centimeters, making an endoscope necessary to get closer to the tissue. This is similar to the existing hysteroscopy technique.
* The NIR-II technique involves exciting a particle with a laser, causing it to fluoresce and emit light in the NIR-II range (1000-1700nm).

[INSERT FIGURE: EndoDetect endoscope design showing the dual-camera system, light sources, and key components]

## Clinical Validation

EndoDetect aims to provide an indication of the presence of endometrial tissue, mitigating the possibility of misdiagnosis or the need for retesting. The goal is to shorten the length of time for diagnosis, potentially increasing the chance of achieving fertility and improving overall quality of life for patients. The device is intended to be minimally invasive, causing minimal pain or discomfort to the patient and reducing the need for hospital stays.

## Implementation Process

The development process involved several key stages:

* **User Requirements**: Establishing the needs of both practitioners and patients to guide the design.
* **Concept Proposals**: Generating and comparing different concepts for endometriosis diagnosis, including nanoparticles with NIR imaging, hormone patch, and bioimpedance.
* **Generation of a more detailed lead concept**: Focusing on the nanoparticle and NIR-II imaging approach.
* **User Requirements Translated to Design Inputs**: Converting user needs into specific design features for the EndoDetect system.
* **The lead concept development**: Detailing the scope of EndoDetect, the final nanoparticle design, and considerations for manufacturing, materials, and costs.
* **Checks**: Evaluating the device against user requirements, intellectual property, risk analysis, regulatory route, and cost-effectiveness.
* **Business plan**: Considering the target customer, market size, competitors, differentiation, reimbursement, and financing.

## Technical Specifications

* The EndoDetect system includes a **single-use cannula** and a display module.
* The **cannula** is approximately **280mm in length with a 4mm diameter and a pre-curved sheath with a 30-degree deflection angle**.
* The cannula incorporates a metal-oxide semiconductor (CMOS) camera (a type of electronic image sensor) to capture images and a live video feed.
* Light-emitting diodes (LEDs) at the tip of the cannula provide bright-field illumination.
* The system also displays **NIR-II views** through separate channels.
* The imaging system is based on an imaging fiber-optic bundle.
* The **scope tip is fixed at 30 degrees**, but the cannular body can be rotated 360 degrees.

## User Experience

1. The nanoparticle solution would be administered intravenously.
2. After a timeframe of approximately 24 hours for nanoparticle accumulation, an endoscopic procedure would be performed.
3. The EndoDetect endoscope is inserted into the uterine cavity.
4. The device allows the physician to visualize the uterine cavity using both white light and NIR-II fluorescence to detect nanoparticles bound to potential endometriosis lesions.
5. An image processing algorithm converts the raw data into a live 2D output and a 3D post-imaging output, showing any detected endometriosis.

## Economic Impact

EndoDetect aims to be a cost-effective diagnostic method, with similar or lower costs compared to current diagnostic approaches. The manufacturing cost of EndoDetect is estimated to be approximately $10,000 (8,200 Euro), with the cost of nanoparticles varying depending on type and dosage. 

By providing earlier diagnosis, it has the potential to reduce the overall cost associated with the lengthy diagnostic pathway of endometriosis. The device is designed to be usable in a general practitioner's office, eliminating the need for hospital stays and associated costs for the diagnostic procedure. This could potentially save patients upwards of $3,500 compared to operating room hysteroscopy costs.

Most importantly, EndoDetect aims to reduce the average time from initial visit to diagnosis from the current 8-12 years to approximately 1 year, significantly improving patient outcomes and quality of life.

## Future Development

The use of the device during a laparoscopy to highlight all diseased tissue for removal could potentially lower the risk of recurrent endometriosis.

## Conclusion

EndoDetect has the potential to transform the diagnostic pathway for endometriosis by offering a minimally invasive, cost-effective, and time-efficient solution. By reducing the diagnostic delay from 8-12 years to potentially 1 year, it addresses a critical gap in women's healthcare. The combination of targeted nanoparticles with NIR-II imaging technology represents an innovative approach to a challenging medical problem that affects approximately 10% of women of reproductive age worldwide.

## Resources

For detailed technical specifications and accompanying research, contact the development team via the contact information below.

## Contact Information

For more information about EndoDetect, please contact:
- Email: coffeycolm@gmail.com
- Website: [colmcoffey.com](https://colmcoffey.click)

<iframe src="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/ColmCoffey/EndoDetect/main/EndoDetect%20-%20Colm%20Coffey.pdf&embedded=true" width="100%" height="500px"></iframe>
If the iframe does not load, download the documentation here.

<iframe src="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/ColmCoffey/EndoDetect/main/EndoDetect%20-%20Colm%20Coffey.pdf&embedded=true" width="100%" height="500px"></iframe>

If the iframe does not load, [download the documentation here](https://raw.githubusercontent.com/ColmCoffey/EndoDetect/main/EndoDetect%20-%20Colm%20Coffey.pdf).

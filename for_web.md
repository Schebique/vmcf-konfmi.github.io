# BioImage Analysis Service

We provide a variety of open-access services, tailored for specific of each project:

 * **Consultations**
   * Questions about where to search for software/plugins, and which tools to choose for specific tasks. Learning about resources available. Consulting results, or already set up workflows.
   * Time scale: Hours to Days (depends on availability, check [calendly](https://calendly.com/martinschatz/45min)) 
 * **BioImage Analysis workflow setup**
   * Design of workflow in specific tools/software. Setting up, or testing software or tools. Preparing or re-running supplementary code from the paper on users' data.
   * Time scale: Days to weeks
 * **Pair programming development of BioImage Analysis tool**
   * Collaborative development, rewriting, or finetuning of BioImage Analysis tools.
   * Time scale: Weeks, months and more
 * **Running workflow/analysis for you**
   * Time scale: depends on workflow
 * **Access to our pre-setup server** with both open-source and commercial BioImage Analysis tools

If you are not sure what to choose, short consultations are always the best way to start.

## The Guidelines for Healthy Cooperation 

 - Any publications resulting from the use of tools within any facility should be acknowledged. 
 - If a particular member has provided significant help, or expertise, or generated additional data (including scripts, software, or numeric results), they should be acknowledged by name and their personal contribution to the study.
 - If the scientist has provided significant intellectual input, they should be co-authors. 
 - Co-authorship decisions should be made at the preparation stage of the manuscript.  Co-authors reserve the right to review manuscripts containing results generated before submission.
 - Each author should have made substantial contributions to the work, approved the submitted version, and agreed to be personally accountable for their contributions and to ensure the accuracy and integrity of the work. 
 - The primary affiliation for each author should be the institution where the majority of their work was done, and if they have subsequently moved, the current address may also be stated.

## Image analysis consultancy

### Arrange a meeting

We offer in-person or online meetings.

Please book one of those slots in [calendly](https://calendly.com/martinschatz/45min). 

You can also write a mail to <schatzm(at)natur.cuni.cz>. Describe in a few sentences what your question is about. We need this information to prepare.

### Prepare for the meeting

#### Necessary preparation

It is extremely helpful to have **two example images** available; ideally already **opened in [FIJI](https://imagej.net/software/fiji/downloads)** such that we can inspect the raw data in detail together during the meeting; ideally the two images covering the range of phenomena you are investigating (e.g. **positive and negative control**). 

#### Optional data sharing

Ideally, please also share some minimal example data with us. You can find details in the **Image data preparation** section.

#### Optional presentation

If you can, it would be nice if you could prepare a short presentation, following roughly suggestions below. Of course, please modify this according to your project and leave out things that are not applicable. Please don't get stressed about preparing anything, we will help you in any case :) 

- Slide 1: Scientific background
- Slide 2: Sample preparation and image acquisition
  - What's the specimen?
  - What kind of staining did you do?
  - Which microscope did you use? 
- Slide 3: Example images
  - Ideally two images: treated and untreated with a visible difference in what should be measured
  - If the above does not apply to your project it would still be nice if you could show more than one image such that we can get a feel for how variable the data is.
- Slide 4: Technicalities
  - Do you already know which number(s) you would like to measure?
  - How many images do you want to analyze (10,100,1000,10000,100000,...)?
  - How big are your individual images (MB, TB)?
  - Would you prefer a certain analysis software?
  - Do you already have experience with a certain analysis software?
  - Did you already try to analyze the data?


Best wishes and we looking forward to meeting you!

## Image data preparation

This document contains recommendations on how to organize your image data, e.g. when seeking consultancy at EMBL-CBA.

### Select a minimal set of representative examples

Select **two** (not more) images that ideally show a clear and biologically relevant difference.

For example, the first image could be a control sample, whereas the second image has been treated in some way.

Please organize those two images into a folder structure similar to the one below:

- minimal-example-data
    - condition01
        - condition01_image01
    - condition02
        - condition02_image01
    - README.txt

As indicated please also add a short README text file where you describe in a few words what the difference is that you see between the conditions.

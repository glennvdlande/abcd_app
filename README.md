# ABCD training app

This repository will contain the ABCD training app developped by Glenn van der Lande. The goal of this app has been to quickly train those unfamiliar with ABCD scoring into its application to real data. ABCD scoring has shown to be a great resource for both research and in the clinic in the context of patients with an acute disorder of consciousness, and the data used in this application stems from a project showing its great utility for prolonged disorders of consciousness too. 

Currently, the app and associated paper are under review but it will be published here afterwards, you can save this page for future reference. For now, we provide a sneakpeak into its capabilities.

## Learn and revise the rules for ABCD scoring
The app provides complete information on the ABCD scoring process that can be checked at any time.

## Train yourself
Here it is possible train on examples from real patient data. The images, ready for ABCD scoring, can originate from healthy controls, or of the following patient groups: Minimally Conscious State +/-, Unresponsive Wakefulness Syndrome, or patients emerging from the Minimally Conscious State. This gives much variation in the discoverable patterns, but the diagnosis is not the focus of this training app, and is thus not shown for the otherwise also fully anonymized patients.

The training consists of viewing a scoreable image, potentially using a tooltip to view the flowchart that can lead to a decision (flowchart is thoroughly explained in the first tab of the app). The user is asked to select one of the categories "A", "B", "C", "D" or "noABCD" using the buttons and receives immediate feedback on the decision. This is accompanied by either a positive result or a suggestion on what might have been missed. Moreover, since all of these figures have been evaluated by 3 raters on 2 occassions, the user receives feedback on how they evaluated it compared to them. The final evaluation takes place against their consensus score. There are many examples to view, across all categories, so there is plenty to learn and potentially revisit.
![image](https://github.com/user-attachments/assets/dc14cca9-31b8-4d00-8d33-771e21167aa5)![image](https://github.com/user-attachments/assets/8e880110-ae8e-4822-a8d3-737a2c69e7b1)


## Test yourself
The same environment as the training, but now no feedback is provided. Instead, after going through all examples, unseen in the training section, the user gets an overall performance estimate compared to the consensus rating on these examples. This estimate consists of a confusion matrix and a Cohen's kappa score. Based on this, the user can choose to revise certain rules and practice on them again later.

## Analyse your own data
Here you can upload your own data to get exactly the same figure out as you have been training on. Currently, this only supports preprocessed EEG data in the MNE Epochs format (i.e., a .fif file), but future updates might extend this use. Note that it is important to have clean data so peaks cannot be explained by noise.

## Future
Feedback is welcome and new versions could be released in the future. 

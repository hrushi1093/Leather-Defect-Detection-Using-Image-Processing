# Leather Defect Detection using Deep Learning Techniques

Leather is a very essential raw material for manufacturing industries. Prior to using this raw leather for manufacturing, a visual inspection is done to confirm the quality of the leather used. Here we have attempted to automate the inspection process. To achieve better productivity of defect classification in industrial leather, we decided to implement a CSP-DenseNet-based Leather defect classification algorithm. A dataset of 3600 images was used to train the Deep Learning model. Cross Entropy Loss was used for the loss function, which was back-propagated on the Adam Optimizer. The model consists of 3 CSP-Dense-Blocks of 6,12, and 24 dense layers. It classifies leather into six categories namely; folding marks, grain off, growth marks, loose grain, non-defective and pinhole.

After completion of the training, the CSP DenseNet model achieved following results: Final average training accuracy = 91.2646% validation accuracy = 90.41667. After passing through the test dataset we found the accuracy to be 95.3704%. Fig5. shows the graph of the training accuracy function for each epoch while Fig6. shows the graph of how validation accuracy varies as a function of epoch.

Read the Report for more Details

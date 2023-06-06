# 11.-Create-Synthdog-configuration-for-a-real-document-ID
We want to have a dataset of generated images that we can use to train a model to extract text from images using the method named Donut

Problem Description
We want to have a dataset of generated images that we can use to train a model to extract text from images using the method named Donut (https://github.com/clovaai/donut). We want to fine tune the model with our type of document which is identity cards.

We need to generate sample documents that are not using real data that belongs to humans. These synthetic samples should look like real documents or as close to them as possible, so that the trained models can be used on real documents.

We want to extract the full name, CURP and date of birth from the "Credencial para votar" in Mexico. The synthetic documents would need to look like the front of the https://listanominal.ine.mx/scpln/ models "G and H".

Acceptance Criteria
A synthdog template document which generates all the values required, contains the correct background as the real document and puts the values in roughly the correct space within the card.

Technical Details
You should use Synthdog and Synthtiger if possible. We do not need the actual generated images, just a template which we can use to generate.



# Visual Question Answering

In this implementation, BLIP architecture is used on VQA RAD Dataset for Visual Question Answering

## Description

VQA-RAD consists of 3,515 question–answer pairs on 315 radiology images.

BLIP (Bootstrapped Language-Image Pre-training) is a method designed to pre-train vision-language models using a large corpus of images and text descriptions. The aim is to improve the understanding and generation of both visual and textual data by learning rich, shared representations. BLIP achieves this by leveraging bootstrapping, where it iteratively refines its predictions and uses them to further train the model.

VQA RAD dataset was evaluated using BLIP for open ended and closed ended questions.

## Results

Val/Test set open-ended accuracy: **26.288659793814436%**

Val/Test set closed-ended accuracy: **69.64980544747081%**

Train set open-ended accuracy: **28.604923798358733%**

Train set closed-ended accuracy: **78.72340425531915%**


# Text-To-Image-diffusion-models-as-vision-generalists.
The Fashion Design Inspirator project is an innovative system that revolutionizes the fashion design process. It generates visual representations based on fashion design descriptions or concepts provided by users. Designers can input specific details such as fabrics, colors, and styles, and the system responds by creating high-quality images that vividly depict their envisioned designs. This tool serves as a dynamic platform for designers to explore, refine, and draw inspiration from their creative ideas, significantly streamlining the initial stages of the design process. Ultimately, the Fashion Design Inspirator empowers designers to bring their imaginative fashion concepts to life with unprecedented efficiency and precision.

## Tutorial
<video width="800" height="400" controls autoplay loop>
  <source src="ML_PROJECT_DEMO.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

## Overview:
The objective of this project is to develop a cutting-edge solution termed
the ”Fashion Design Inspirator”. This system aims to revolutionize the design
process by generating images based on fashion design descriptions or concepts.
Designers will have the ability to input specific details in the form of textual
prompts such as fabric types, color schemes, and style preferences, and witness
the system produce high-fidelity visual representations that breathe life into
their creative vision.

## Installations required:
googletrans

diffusers

transformers

## Data Collection:

We have downloaded an extension ”Image Assistant Batch Image Downloader”,with the help of which we have extracted several clothing apprarel images for both men and women from the Myntra website..We have created separate folders for each outfit type belonging to men and women.

## Data Preprocessing:

Since our data consists of only images and its labels,so we have done the following steps to pre-process it:
1. Removal of duplicate images.
2. Checking of image clarity:whether any of the downloaded image is blurry or not.
3. Data sampling.
4.One-hot encoding of the outfit labels.

## Model Used:

Diffusion Model.
We have also used a google translator to translate the text given in any language to English and generate the image according to the given input.

## Key-Features:

The key features of the Fashion Design Inspirator project include:

1. **Text-to-Image Generation**: The project generates visual representations based on fashion design descriptions or concepts provided by users.

2. **Input Customization**: Designers can input specific details like fabrics, colors, and styles, allowing the system to create images that align with their creative vision.

3. **No Language Barrier**: The platform provides an intuitive and user-friendly interface for easy interaction in any language and get the desired output.

4. **Interdisciplinary Fusion**: The project leverages advanced techniques in natural language processing (NLP) and computer vision, showcasing an interdisciplinary approach to solving industry-specific challenges.

5. **High-Fidelity Visual Outputs**: The generated images are of high quality and detail, providing designers with accurate representations of their design concepts.






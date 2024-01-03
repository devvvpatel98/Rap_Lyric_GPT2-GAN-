# LSTM Discriminator in GAN for GPT-2 Drake Lyrics Generation

## Overview
This project, part of Duke University ECE 684 (Fall 2023), aims to develop a robust NLP system for authorship identification and generating fake Drake lyrics, using a GAN training setup with LSTM Discriminator to enhance GPT-2's capabilities.

## Objective
- **Authorship Identification**: Differentiating real from fake Drake lyrics.
- **Text Generation**: Generating fake lyrics that imitate Drake's writing style.

## Methodology
- **Generative Left Side**: Utilizes GPT-2, fine-tuned on Drake's lyrics, for lyric generation.
- **Discriminative Right Side**: Employs an LSTM classifier, trained on real and generated lyrics, for differentiation.

## Results and Insights
- **Generated Lyrics Analysis**: Improvement in lyric quality and flow over training epochs.
- **Evaluation Metrics**: Accuracy, Flesch Reading Ease Score, and Gunning Fog Index used for assessment.

## Challenges
- Sequencing feedback loops between models.
- Fine-tuning to closely mimic an author's style.
- Addressing computational limitations.

## Conclusion
The project demonstrates advancements in NLP, with potential applications in content generation, security, and authentication.

## Installation and Usage

## Prerequisite
- Google Colab
  
Make sure to run:
```sh
!pip install datasets
!pip install transformers
!pip install accelerate -U
```

At the very top of the colab notebook.

To replicate the experiment, start about halfway down in the code block that says:

from google.colab import drive
drive.mount('/content/drive')

(Above the code block that has):

import matplotlib.pyplot as plt
x = [1,1,1]
plt.plot(x)
plt.savefig('/content/drive/MyDrive/test.png')

Then you can run everything below it and this should be good!

## Contributing
This project was developed as part of an academic final project for the Natural Language Processing Course. Contributions were made solely by Dev Patel, Andres Caicedo, and Mac Gray.

## License
This project is licensed under the MIT License - see the [MIT License](https://opensource.org/licenses/MIT) for details.



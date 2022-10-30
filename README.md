# Classifying Sea Mammal Sounds
This is the finalized audio subproject for our final capstone project Cog*Dex. It classifies sea mammal sounds into three categories (dolphin, whale, and seal) from the Watkins Marine Mammal 'Best of Cuts' Sound Database provided by the Woods Hole Oceanographic Institution.

# Credits
- Authors (in alphabetical order): Brian Chen, Brayden Levangie, Amy Liu, Jordi Malaret, and Eloise Zeng 
- TAs (in alphabetical order): Kathryn Le and Adrianna Peng
- Instructors: Ryan Soklaski and Victoria Helus

# How this repo works
All the raw audio data can be webscraped from the sound database or accessed here: https://drive.google.com/open?id=1QjxAsbSYzWQaQgLN2TAVrLTMdtLq-vGD

**data_init.ipynb** converts all the raw audio data into spectrograms (represents five seconds of an audio clip) which can be accessed here: https://drive.google.com/open?id=1mL-Mx7ggvkSUKskby7nQX-VoQy6iB12M

**train_data_init.ipynb** sorts all the spectrograms into training and validation data which can be accessed here: https://drive.google.com/open?id=19gD99LZzIrhPkJhnbRGt-nCQ7au8qdnI

**Training data**: 109 spectrograms (saved as .png images) for dolphins, whales, and seals each
**Validation data**: 26 spectrograms (saved as .png images) for dolphins, whales, and seals each

**train_model.ipynb** The pretrained Resnet-18 CNN was feature extracted.

**Training accuracy**: 83%
**Validation accuracy**: 87%

Audio models can be accessed from the .pt files in here: https://drive.google.com/open?id=1B6mWm1Hcx0v74AvnzBa4y0iC3scNlUsE

Google Colab was used to run all the code
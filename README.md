# Braces2TeethDataset

![a](https://user-images.githubusercontent.com/43202025/119252114-a3c52800-bbd4-11eb-909c-60f4e711da1d.png)

 All kinds of dataset about braces and teeth.

- mouth: for training detect mouth task, includes images and its labels.

- braces2teethPlus: contains braces images and teeth images.

- colorBraces: only have color braces images (hard case for braces2teeth problem).

- teeth & teeth2: only have teeth images, this is generated from the facial module (you can see it more in [this](https://github.com/vutuanhai237/Braces2TeethUtilities)).

- tested for CycleGAN: some cases that I test for the trained model.

Dataset that I used in research:

- Dataset braces2teeth: braces2teethPlus and colorBraces.
- Dataset braces2teethAugmented: generated from Dataset braces2teeth by using this [script](https://github.com/vutuanhai237/Braces2TeethUtilities/blob/main/evaluateData/dataArgument.py).
- Dataset teeth2: teeth & teeth2.

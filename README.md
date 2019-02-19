# Layered Explanations Framework

Layered Explanations Framework aims to exploit the intrinsic architecture of neural networks, namely hidden units, to generate an interpretable explanation of the algorithmic decision. It consists of 3 main steps:

1. Identify the greatest-explanatory layer and
2. Influential units using numerical influence measures, then we
3. Reconstruct relevant input regions responsible for activating these influential units.

![Layered Explanations Framework](https://github.com/hovinh/LayeredExplanationsFramework/blob/master/img/framework.png "Layered Explanations Framwork")

# Documents 

Interesting readers can find more details in following documents:
- [Workshop abstract paper](https://github.com/hovinh/LayeredExplanationsFramework/blob/master/doc/%5BExtendedAbstract%5DHoXuanVinh.pdf)
- [Presentation](https://github.com/hovinh/LayeredExplanationsFramework/blob/master/doc/Presentation.pdf)

# Source code:

Results presented in [Presentation](https://github.com/hovinh/LayeredExplanationsFramework/blob/master/doc/Presentation.pdf) can be found in:
- [LayeredExplanationsFramework.ipynb](https://github.com/hovinh/LayeredExplanationsFramework/blob/master/code/LayeredExplanationsFramework.ipynb)
- [DogFish_VGG16.ipynb](https://github.com/hovinh/LayeredExplanationsFramework/blob/master/code/DogFish_VGG16.ipynb)

Preliminary experiments of MIM on textual input can be found in:
- [20newsgroup_MIM.ipynb](https://github.com/hovinh/LayeredExplanationsFramework/blob/master/code/20newsgroup_MIM.ipynb)
- [IMDB_MIM.ipynb](https://github.com/hovinh/LayeredExplanationsFramework/blob/master/code/IMDB_MIM.ipynb)

If the file is too big for GitHub to render, you can try to view with [nbviewer](https://nbviewer.jupyter.org/).

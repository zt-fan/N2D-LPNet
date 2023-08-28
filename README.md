# N2D-LPNet
# Image translation network for nighttime driving scenes with inter-frequency priors
<hr />

> **Abstract:** *Currently, image-to-image translation methods have achieved significant performance with the help of deep CNNs and GANs, but most existing models are not suitable for autonomous driving scenarios due to their interpretability. In this paper, we develop a high-quality image translator (i.e. night → day), N2D-LPNet, to facilitate nighttime driving scene dperception. Instead of pursuing a
complex network structure, we first attempt to explore the inter-frequency relation knowledge to simplify image translation process. Specifically, the lightweight Laplace pyramid is introduced as the backbone architecture to decompose the feature maps of nighttime image into high- and low-frequency components. Considering the similar morphological properties of different frequency components, we design a flexible inter-frequency guiding strategy which utilizes each lower frequency information to refine the higher frequency feature in a progressive manner. Benefiting from the advantage of constraint from inter-frequency priors, our
method can process the nighttime image better under the practical driving system while still persevere competitive results. We also discuss the potential value of N2D-LPNet for other high-level vision tasks.* 
<hr />

## Network Architecture
![arch](https://github.com/zt-fan/N2D-LPNet/assets/90734659/7df3cb82-b5c6-4237-aa8a-acb32a074e19)


## Results
![tab](https://github.com/zt-fan/N2D-LPNet/assets/90734659/2fb97fdc-1a14-44e1-839f-523939e5f888)
![img](https://github.com/zt-fan/N2D-LPNet/assets/90734659/39a06c6d-4878-4a3b-871b-3cfcaaaec0cf)

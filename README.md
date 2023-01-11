# FGSM
Adding small perturbations to an image can cause a big change in model performance. To test security vulnerabilities of ML models an important tool is adversarial machine learning.
<img align="right" height="140" src="(https://github.com/angelognazzo/Probabilistic-Artificial-Intelligence/blob/main/figures/GP_1.png"></img>
The Fast Gradient Sign Attack (FGSM) is a type of adversarial attack. 
It's a white box attack (i.e. the attacker knows the model, the parameters and the architecture).
It is designed to attack neural networks using gradients. The attack uses the gradient of the loss w.r.t the input data, then adjusts (perturb) the input data to maximize the loss.

# Generators Jungle

![G](G_logo.png)

* [Variational Autoencoder](vae.py)
* [Categorical Structural Agnostic Model](https://github.com/Didayolo/medi-chal/tree/master/code/generators)
* [Wasserstein GAN](https://github.com/yknot/mimic_improved_wgan)
* [Additive Noise Model](https://github.com/Didayolo/medi-chal/tree/master/code/generators)
* [medGAN](https://github.com/mp2893/medgan)
* [Copula](https://github.com/Didayolo/medi-chal/tree/master/code/generators)
* [Random Forest Imputations](https://github.com/Didayolo/medi-chal/tree/master/code/generators)


### Set-up VAE benchmark

```
git clone http://github.com/didayolo/autodata
cd autodata
pip install -r requirements.txt
cd ..
git clone http://github.com/didayolo/generators
cd generators
pip install -r requirements.txt
jupyter-notebook vae_benchmark.ipynb
```

# The Variational Fair Autoencoder

Christos Louizos, Kevin Swersky, Yujia Li, Max Welling, Richard Zemel

## Abstract

```
We investigate the problem of learning representations that are invariant to certain
nuisance or sensitive factors of variation in the data while retaining as much
of the remaining information as possible. Our model is based on a variational
autoencoding architecture (Kingma & Welling, 2014; Rezende et al., 2014) with
priors that encourage independence between sensitive and latent factors of variation.
Any subsequent processing, such as classification, can then be performed on
this purged latent representation. To remove any remaining dependencies we incorporate
an additional penalty term based on the “Maximum Mean Discrepancy”
(MMD) (Gretton et al., 2006) measure. We discuss how these architectures can
be efficiently trained on data and show in experiments that this method is more
effective than previous work in removing unwanted sources of variation while
maintaining informative latent representations.
```

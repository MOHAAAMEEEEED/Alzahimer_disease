# Alzahimer_disease

## Generating Multi class Alzheimer MRI images for Data Augmentation using Generative Adversarial Networks

## A Solution - Generative Modelling:
#### Generative models, or deep generative models, are a class of deep learning models that learn the underlying data distribution from the sample. These models can be used to reduce data into its fundamental properties, or to generate new samples of data with new and varied properties

## Generative Adversarial Networks:
#### Generative adversarial networks are implicit likelihood models that generate data samples from the statistical distribution of the data. They’re used to copy variations within the dataset. They use a combination of two networks: generator and discriminator.

![Screenshot 2024-05-04 214719](https://github.com/MOHAAAMEEEEED/Alzahimer_disease/assets/90880893/922302e6-4e12-406e-a189-9c07f706c783)



## The Generator:
#### A generator network takes a random normal distribution (z), and outputs a generated sample that’s close to the original distribution.

## The Discriminator: 
#### A discriminator tries to evaluate the output generated by the generator with the original sample, and outputs a value between 0 and 1. If the value is close to 0, then the generated sample is fake, and if the value is close to 1 then the generated sample is real.

![Screenshot 2024-05-04 215039](https://github.com/MOHAAAMEEEEED/Alzahimer_disease/assets/90880893/7d513e66-4d3d-40fb-8744-fae31b8f1f9c)




A Solution - Generative Modelling
Generative models, or deep generative models, are a class of deep learning models that learn the underlying data distribution from the sample. These models can be used to reduce data into its fundamental properties, or to generate new samples of data with new and varied properties

Generative Adversarial Networks
Generative adversarial networks are implicit likelihood models that generate data samples from the statistical distribution of the data. They’re used to copy variations within the dataset. They use a combination of two networks: generator and discriminator.


## The Generator:
A generator network takes a random normal distribution (z), and outputs a generated sample that’s close to the original distribution.

The Discriminator: 
A discriminator tries to evaluate the output generated by the generator with the original sample, and outputs a value between 0 and 1. If the value is close to 0, then the generated sample is fake, and if the value is close to 1 then the generated sample is real.

What the Entire thing looks like: 



## How do GANs work ? 
#### A random normal distribution is fed into the generator. The generator then outputs a random distribution, since it doesn’t have a reference point.
#### Meanwhile, an actual sample, or ground truth, is fed into the discriminator. The discriminator learns the distribution of the actual sample. When the generated sample from the generator is fed into the discriminator, it evaluates the distribution.
#### If the distribution of the generated sample is close to the original sample, then the discriminator outputs a value close to ‘1’ = real. If both the distribution doesn’t match or they aren’t even close to each other, then the discriminator outputs a value close to ‘0’ = fake.

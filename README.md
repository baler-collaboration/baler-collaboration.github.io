# Introduction
Storing and sharing increasingly large datasets is a challenge across disciplines in scientific research and industry. Limited storage resources mean sophisticated data compression algorithms are required of which there are two types: Lossless and Lossy. 

# Lossless/lossy Compression
Lossless compression preserves data in its entirety but as a consequence the amount of data reduction is limited  -- there is a growing demand for greater data reduction than lossless methods can achieve. 

Lossy compression allows greater data reduction but involves some data loss. However, if compression techniques are tailored to the dataset in question, the data loss is minimised. For instance, the common music compression algorithm, MP3, uses Fourier transformation and psychoacoustics. These two methods are specifically intended for audio waves and exploit the limitations of human hearing to remove data that is inaudible.
We introduce Baler, a tool that uses machine learning to derive compression algorithms that are tailored to the user's input data achieving large data reduction and high fidelity where it matters. 

# Baler
The Baler project is a collaboration between 12 research physicists, computer scientists, and machine learning experts at the universities of Lund, Manchester, and Uppsala. Baler has already been used to compress scientific research data showing impressive performance.

![CFD](./figures/Baler1.gif "Computational Fluid Dynamics data compressed down to 0.5% of the original size")
![HEP](./figures/Baler2_cropped.png "Data from the Large Hadron Collider compressed to 58% the original size")

Baler has been featured at the [26th International Conference on Computing in High Energy \& Nuclear Physics](indico.jlab.org/event/459/contributions/11723/attachments/9295/13647/Baler\_v2.pdf) -- the largest computing conference of its kind. The Baler tool is documented in a [scientific paper](arxiv.org/pdf/2305.02283.pdf) and is developed and maintained as an open-source project on [GitHub](https://github.com/baler-collaboration/baler). Baler is also part of the [Docker-Sponsored Open Source program](hub.docker.com/r/balercollaboration/baler).

Given Baler's huge potential in industry we now seek collaborations to further the horizons of the project.  



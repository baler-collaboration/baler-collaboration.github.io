# Baler

Storing and sharing increasingly large datasets is a challenge across disciplines in scientific research and industry. Limited storage resources mean sophisticated data compression algorithms are required of which there are two types: Lossless and Lossy. 

Lossless compression preserves data in its entirety but as a consequence the amount of data reduction is limited  -- there is a growing demand for greater data reduction than lossless methods can achieve. 

Lossy compression allows greater data reduction but involves some data loss. However, if compression techniques are tailored to the dataset in question, the data loss is minimised. For instance, the common music compression algorithm, MP3, uses Fourier transformation and psychoacoustics. These two methods are specifically intended for audio waves and exploit the limitations of human hearing to remove data that is inaudible.
We introduce Baler, a tool that uses machine learning to derive compression algorithms that are tailored to the user's input data achieving large data reduction and high fidelity where it matters. 


The Baler project is a collaboration between 12 research physicists, computer scientists, and machine learning experts at the universities of Lund, Manchester, and Uppsala. Baler has already been used to compress scientific research data showing impressive performance.

\vskip 0.2 cm
\begin{figure}[h]
\centering
\begin{subfigure}{0.5\textwidth}
  \centering
  \includegraphics[width=0.9\textwidth]{CFD.png}
  \caption{Computational Fluid Dynamics data com- \\pressed down to 0.5\% of the original size}
\end{subfigure}%
\hfill
\begin{subfigure}{0.5\textwidth}
  \centering
  \includegraphics[width=0.95\textwidth]{HEP_eta.png}
  \caption{Data from the Large Hadron Collider com- \\pressed to 58\% the original size}
\end{subfigure}
\caption*{Baler performance on compressing scientific research data}
\end{figure}

Baler has been featured at the 26th International Conference on Computing in High Energy \& Nuclear Physics [1] -- the largest computing conference of its kind. The Baler tool is documented in a scientific paper [2] and is developed and maintained as an open-source project on GitHub [3]. %Baler is also part of the Docker-Sponsored Open Source program [4].

Given Baler's huge potential in industry we now seek collaborations to further the horizons of the project.  


$[1]$ indico.jlab.org/event/459/contributions/11723/attachments/9295/13647/Baler\_v2.pdf\\
$[2]$ arxiv.org/pdf/2305.02283.pdf \tab $[3]$ github.com/baler-collaboration/baler% \tab $[4]$ hub.docker.com/r/balercollaboration/baler



%% Simple Template for Thesis Proposal and Mid-term
%% Created on: Aug 1, 2018
%% 	   Author: Taiping Zeng （Taiping.z@outlook.com）
%%  Institute: SIA,CAS && UCAS, Computational Neuroscience Lab

1. cover 
Adapt cover.doc to your type, and export to cover.pdf, tex would automatically read it.

2. image
Please put images in subfolder /img, for example 

\begin{figure}[!ht]
  \centering
\includegraphics[width=0.5\textwidth]{img/brain.png}
  \caption{大脑} 
  \label{fig:brain}
\end{figure}

3. cite and formular have examples in .tex.

4. keep the main framework of proposal.

5. compile the .tex by 
xelatex
bibtex
xelatex
xelatex
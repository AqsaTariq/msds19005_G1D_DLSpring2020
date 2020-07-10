# msds19005_G1D_DLSpring2020
“This repository contains code and results for the Course Project by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This repository is only for learning purposes and is not intended to be used for commercial purposes.”

\ref{tab:DgraphDTAExp}. \\
\begin{table}
\begin{center}
\begin{tabular}{|l|c|r|o|}
	\hline
	Experiments & CI(std) & MSE(std) & Pearson(std)\\
	\hline \hline
    reported & 0.89 & 0.21 & 0.85\\
    Reproduced & 0.89 & 0.23 & 0.84\\
	CNN(100x100) & 0.76 & 0.58 & 0.55\\
	CNN(200x200) & 0.88 & 0.25 & 0.83\\
	 no aug.(100x100) & 0.88 & 0.23 & 0.84 \\
	Ensemble no aug. & 0.88 & 0.23 & 0.83\\
    Dropout & 0.88 & 0.23 & 0.84\\
    \hline
\end{tabular}
\end{center}
\caption{Experiment (DGraphDTA) results produced on Davis test dataset}
\label{tab:DgraphDTAExp}
\end{table}

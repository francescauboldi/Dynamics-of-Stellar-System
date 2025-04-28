\documentclass{article}
\usepackage{hyperref}
\usepackage{enumitem}

\begin{document}

\title{Dynamics of Stellar Systems - Project Overview}
\author{Francesca Uboldi}
\date{Academic Year 2025-2026}
\maketitle

\section*{Introduction}
This project was developed as part of the final examination for the course \textbf{Dynamics of Stellar Systems} (Prof. Massimo Dotti, Università degli Studi di Milano-Bicocca).  
It focuses on the dynamical evolution of galactic disks embedded in dark matter halos, using numerical simulations and subsequent analysis.

\section*{Project Objectives}
The main goals of the project were:
\begin{itemize}[leftmargin=*]
    \item Study the equilibrium evolution of a galactic stellar disk in a static dark matter halo.
    \item Analyze the development of bar instability in a non-equilibrium configuration.
    \item Simulate the behavior of a satellite orbiting within the galactic disk and compute propulsion requirements to maintain its orbit.
\end{itemize}

\section*{Repository Structure}
The GitHub repository contains the following files:
\begin{itemize}[leftmargin=*]
    \item \texttt{Equilibrium\_System.ipynb}: Initialization of the equilibrium stellar disk configuration and execution of the treecode simulation.
    \item \texttt{Equilibrium\_Visual.ipynb}: Visual analysis of the equilibrium system (Lagrangian radii, bar strength, energy conservation, angular momentum).
    \item \texttt{Propulsion and Orbital Evolution in Galactic Disks.ipynb}: Study of a test satellite orbiting in the galactic potential, orbital evolution, and required $\Delta v$ computations.
\end{itemize}

\section*{Simulation Data}
Due to file size limitations, the simulation outputs (treecode outputs, particle snapshots, etc.) are not included in the repository.  
All data files can be accessed at the following link:
\begin{center}
\href{https://drive.google.com/drive/folder/your_drive_link_here}{Google Drive Folder: Simulation Data}
\end{center}

\section*{Simulation Framework}
The simulations were performed using a customized version of a \textbf{treecode} algorithm.  
The gravitational potential includes both the particle disk (computed via the tree algorithm) and a static Hernquist potential for the dark matter halo.

\section*{Conclusions}
The project successfully verified the stability of a galactic disk under equilibrium conditions and highlighted the structural changes induced by bar instability.  
The satellite study demonstrated how disk dynamics influence orbital paths and how propulsion corrections vary between stable and unstable environments.

\bigskip
For any further questions, feel free to contact me.

\end{document}

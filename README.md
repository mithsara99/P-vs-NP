# P-vs-NP
P vs NP
\documentclass[11pt]{article}

\begin{document}

\title{Arrow function on determinstic turing machine}
\author{Mithsara Dasanayake}

\maketitle

\section{Computation}
Formal model of computation is given by turing machine.
\begin{center}
$M = <Q,\Gamma,b,\varepsilon, \sigma, q_0, F>$
\end{center}  


\section{Complexity Class P}
\begin{center}
$P = \cup  Time(n^k) $
\end{center}

\section{Complexity Class NP}

\begin{center}
$NP =\cup  NTime(n^k)  $
\end{center}

\section{PSpace}
\begin{center}
$Pspace = \cup space(n^k)$
\end{center}


\section{Arrow Function}
\begin{center}
$Arr = \cup Arrow(n^k)$
\end{center}

\section{Conclusion}
since tape of the turing machine is infinte

\begin{center}
Arr = Pspace

NP $\subset$ Pspace

P = NP
\end{center}



\end{document}



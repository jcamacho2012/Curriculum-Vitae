Jcamacho
========
documentclass[12pt,a4paper]{scrartcl}
\usepackage{amsmath}
\usepackage{amssymb,amsfonts,amsthm}
\linespread{1.2}
\usepackage[latin1]{inputenc} 
\usepackage[spanish]{babel}
\usepackage[pdftex]{graphicx} %graficos
\usepackage{url} %url
\usepackage{bm} %letras griegas en negrita (uso: \bm{\alpha})
\usepackage[pdftex,break]{hyperref} %links

%Teoremas, corolarios y lemas. Remarks y definiciones
\newtheorem{thm}{Teorema}[section]
\newtheorem{cor}[thm]{Corolario}
\newtheorem{lem}[thm]{Lema}

\theoremstyle{remark}
\newtheorem{rem}[thm]{Remark}

\theoremstyle{definition}
\newtheorem{defin}[thm]{Definición}

%Nuevo parrafo con interlineado. Cabeceras y titulos con estilo article
\newcommand\mypar{\par\vspace{\baselineskip}}
\renewcommand{\sectfont}{\rmfamily \bfseries} %cabeceras y titulos con estilo roman, negrita.

%Title
\title{\normalfont{}} %Titulo del documento con estilo article
\author{}
\date{}


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% %%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% %%%%%%%%%%%%%%%%%%%%%%%

\begin{document}
\maketitle
\newpage
\tableofcontents
\newpage

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% %%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% %%%%%%%%%%%%%%%%%%%%%%%


\end{document}
CV
\documentclass[a4paper,11pt]{article}
\usepackage{latexsym}
\usepackage{xcolor}
\usepackage{float}
\usepackage{ragged2e}
\usepackage[empty]{fullpage}
\usepackage{wrapfig}
\usepackage{lipsum}
\usepackage{tabularx}
\usepackage{titlesec}
\usepackage{geometry}
\usepackage{marvosym}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\usepackage{cfr-lm}
\usepackage[T1]{fontenc}
\setlength{\multicolsep}{0pt} 
\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}
\geometry{left=1.4cm, top=0.8cm, right=1.2cm, bottom=1cm}
% Adjust margins
%\addtolength{\oddsidemargin}{-0.5in}
%\addtolength{\evensidemargin}{-0.5in}
%\addtolength{\textwidth}{1in}
\usepackage[most]{tcolorbox}
\tcbset{
	frame code={}
	center title,
	left=0pt,
	right=0pt,
	top=0pt,
	bottom=0pt,
	colback=gray!20,
	colframe=white,
	width=\dimexpr\textwidth\relax,
	enlarge left by=-2mm,
	boxsep=4pt,
	arc=0pt,outer arc=0pt,
}

\urlstyle{same}

\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-7pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item{
    \textbf{#1}{\hspace{0.5mm}#2 \vspace{-0.5mm}}
  }
}

\newcommand{\resumePOR}[3]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1}\hspace{0.3mm}#2 & \textit{\small{#3}} 
    \end{tabular*}
    \vspace{-2mm}
}

\newcommand{\resumeSubheading}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#4}} \\
        \textit{\footnotesize{#3}} &  \footnotesize{#2}\\
    \end{tabular*}
    \vspace{-2.4mm}
}

\newcommand{\resumeProject}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#3}} \\
        \footnotesize{\textit{#2}} & \footnotesize{#4}
    \end{tabular*}
    \vspace{-2.4mm}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}
% \renewcommand{\labelitemii}{$\circ$}
\renewcommand{\labelitemi}{$\vcenter{\hbox{\tiny$\bullet$}}$}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*,labelsep=0mm]}
\newcommand{\resumeHeadingSkillStart}{\begin{itemize}[leftmargin=*,itemsep=1.7mm, rightmargin=2ex]}
\newcommand{\resumeItemListStart}{\begin{justify}\begin{itemize}[leftmargin=3ex, rightmargin=2ex, noitemsep,labelsep=1.2mm,itemsep=0mm]\small}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}\vspace{2mm}}
\newcommand{\resumeHeadingSkillEnd}{\end{itemize}\vspace{-2mm}}
\newcommand{\resumeItemListEnd}{\end{itemize}\end{justify}\vspace{-2mm}}
\newcommand{\cvsection}[1]{%
\vspace{2mm}
\begin{tcolorbox}
    \textbf{\large #1}
\end{tcolorbox}
    \vspace{-4mm}
}
\newcolumntype{L}{>{\raggedright\arraybackslash}X}%
\newcolumntype{R}{>{\raggedleft\arraybackslash}X}%
\newcolumntype{C}{>{\centering\arraybackslash}X}%
%---- End of Packages and Functions ------

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%
%%%%%% DEFINE ELEMENTS HERE %%%%%%%
\newcommand{\name}{Abhinav Pal} % Your Name
\newcommand{\course}{Computer Science and Engineering} % Your Program
\newcommand{\phone}{7839261504} % Your Phone Number
\newcommand{\emaila}{abhinavpal.1152@gmail.com} %Email 1

\begin{document}
\fontfamily{cmr}\selectfont
%----------HEADING-----------------

{
\begin{tabularx}{\linewidth}{L r} \\
  \textbf{\Large \name} & {\raisebox{0.0\height}{\footnotesize \faPhone}\ +91-\phone}\\ &
    \href{mailto:\emaila}{\raisebox{0.0\height}{\footnotesize \faEnvelope}\ \emaila} \\
  Bachelor of Technology & \href{https://github.com/abhinavPal28886}{\raisebox{0.0\height}{\footnotesize \faGithub}\ {GitHub Profile}} \\ 
  {Pranveer Singh Institute of Technology, Kanpur} & \href{https://www.linkedin.com/in/abhinav-pal-66a0a2205/}{\raisebox{0.0\height}{\footnotesize \faLinkedin}\ {Linkedin Profile}}
\end{tabularx}
}


%-----------EDUCATION-----------
\section{\textbf{Education}}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Pranveer Singh Institute of Technology, Kanpur}{2020-2024}
      {Bachelor of Technology in Computer Science and Engineering}{GPA: 6.69}
  \vspace{1mm}
  
      \resumeSubheading
      {Heliger Borden Education Centre, Kanpur}{2019-2020}
      {Intermediate}{Percentage: 58.83}
  \vspace{-1mm}

  \resumeSubheading
      {Dr. Virendra Swarup Education Centre, Kanpur}{2017-2018}
      {High School}{Percentage: 71.17}
  \resumeSubHeadingListEnd

\vspace{-5.5mm}
%
%-----------PROJECTS-----------------
\section{\textbf{Personal Projects}}
\resumeSubHeadingListStart
    \resumeProject
      {Weather App} %Project Name
      {A website which tells the weather details,made using a weather api.} %Project Name, Location Name
      {} %Event Dates

      \resumeItemListStart
        \item {built a single page web application that provides the weather details of any city.}
        \item {Integrated a weather api which provides the require real time data.}
        \item {Technology Used: JavaScript,CSS,HTML,API}
    \resumeItemListEnd
    \vspace{-2mm}
    
    \resumeProject
      {Lung Cancer Detection System} %Project Name
      {Lung Cancer is very common for every person and now a days they are trying to overcome this problem.} %Project Name, Location Name
       {}%Event Dates

    \resumeItemListStart
        \item {It is a model for detecting the lung and storing the records and prescribing the medicine.}
        \item {Technology Used: JavaScript,CSS,HTML,Machine Learning,Python.}
    \resumeItemListEnd
    \vspace{-2mm}

    \resumeProject
      {Historical Monument of India} %Project Name
      {It will provide the data of different monument.} %Project Name, Location Name
       {}%Event Dates

      \resumeItemListStart
        \item{It is a web page that store the data of different monuments.}
        \item {Technology Used : Bootstrap, CSS, HTML.}
    \resumeItemListEnd
      
  \resumeSubHeadingListEnd
\vspace{-8.5mm}


%-----------EXPERIENCE-----------------
\section{\textbf{CERTIFICATES}}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Problem Solving(Basic)}
      {Febraury 2023}{}

      \vspace{-2.0mm}
      \resumeItemListStart
    \item {Certificate of programming from Hackerrank.}
    \item {\href{https://www.hackerrank.com/certificates/c6f2ad892325}{Credential Link}}
    
    \resumeItemListEnd
    
    \vspace{-3.0mm}
     \resumeSubheading
      {Python}
      {September 2022}{}

      \vspace{-3.0mm}
     \resumeItemListStart
    \item {Course Certification from Hackerrank.}
    \item {\href{https://www.hackerrank.com/certificates/f3ac40e8dbca}{Credential Link}}
    
    \resumeItemListEnd
    
    \vspace{-3.0mm}

     \resumeSubheading
      {Web Development}
      {November 2022}{}

      \vspace{-3.0mm}
     \resumeItemListStart
    \item {Associate Certification from Teachnook.}
    \item {\href{https://drive.google.com/file/d/1yXlNz1dFTUUqEV9I1EdiSWqzLOXIrJ1H/view?usp=sharing}{Credential Link}}
    \resumeItemListEnd
    
    \vspace{-3.0mm}

      
  \resumeSubHeadingListEnd
  
\vspace{-5.5mm}







%-----------Technical skills-----------------
\section{\textbf{Technical Skills and Interests}}
 \begin{itemize}[leftmargin=0.05in, label={}]
    \small{\item{
     \textbf{Languages}{: C,C++,JavaScript,HTML,CSS,Python,Java} \\
     %\textbf{Libraries }{: C++ STL}\\ 
     %\textbf{Cloud/Databases}{:Relational Database(mySql) } \\  
     
     \textbf{Relevent Coursework}{: Data Structures \& Algorithms, Software Engineering, Object Oriented Programming, Database Management System.} \\ 
     \textbf{Areas of Interest}{: Web Design and Development.} \\
     \textbf{Soft Skills}{: Problem Solving, Self-learning, Presentation, Good Communication} \\
    }}
 \end{itemize}
 \vspace{-16pt}



%-----------Positions of Responsibility-----------------
%\section{\textbf{Achievements}}
%\vspace{-0.4mm}
%    \resumeItemListStart
%    \item {Developed optimized code solutions for 500+ problems on Geeks for Geeks resulting in increased efficiency.}
%    \item {Implemented data structures and algorithms to complete 200+ programming challenges on LeetCode,consistenly achieving top ranks in coding competitions.}
%    \item {Consistently solved challenging coding problems in C++ and Python on HackerRank, earning a 5-star rating.}
%    \item {Accumulated more than 200+ programming problem submissions on SPOJ, HackerRank, and other platforms.}
%   \resumeItemListEnd
    
%\vspace{-5mm}




% %-----------Achievements-----------------
% \section{\textbf{Achievements}}
% \vspace{-0.4mm}
% \resumeSubHeadingListStart
% \resumePOR{Achievement } % Award
%     {description} % Event
%     {Event dates} %Event Year
    
% \resumePOR{Achievement } % Award
%     {description} % Event
%     {Event dates} %Event Year
% \resumeSubHeadingListEnd
% \vspace{-5mm}



%-------------------------------------------
\end{document}

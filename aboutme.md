% a mashup of hipstercv, friggeri and twenty cv
 % https://www.latextemplates.com/template/twenty-seconds-resumecv
 % https://www.latextemplates.com/template/friggeri-resume-cv
 
 \documentclass[verylight]{simplehipstercv}
 % available options are: darkhipster, lighthipster, pastel, allblack, grey, verylight, withoutsidebar
 % withoutsidebar
 \usepackage[utf8]{inputenc}
 \usepackage[default]{raleway}
 \usepackage[margin=1cm, a4paper]{geometry}
 
 
 %------------------------------------------------------------------ Variablen
 
 \newlength{\rightcolwidth}
 \newlength{\leftcolwidth}
 \setlength{\leftcolwidth}{0.23\textwidth}
 \setlength{\rightcolwidth}{0.75\textwidth}
 
 %------------------------------------------------------------------
 \title{New Simple CV}
 \author{\LaTeX{Marta Alberola} Ninja}
 \date{December 2024}
 
 \pagestyle{empty}
 \begin{document}
 
 
 \thispagestyle{empty}
 %-------------------------------------------------------------
 
 \section*{Start}
 
 \simpleheader{headercolour}{Marta}{Alberola}{Anaesthesiologist. Data Science \& Healthcare Innovation. Research Project Management}{white}
 
 
 
 %------------------------------------------------
 
 % this has to be here so the paracols starts..
 \subsection*{}
 \vspace{4em}
 
 \setlength{\columnsep}{1.5cm}
 \columnratio{0.23}[0.75]
 \begin{paracol}{2}
 \hbadness5000
 %\\backgroundcolor{c[1]}[rgb]{1,1,0.8} % cream yellow for column-1 %\\backgroundcolor{g}[rgb]{0.8,1,1} % \\backgroundcolor{l}[rgb]{0,0,0.7} % dark blue for left margin
 
 \paracolbackgroundoptions
 
 % 0.9,0.9,0.9 -- 0.8,0.8,0.8
 
 
 \footnotesize
 {\setasidefontcolour
 \flushright
 \begin{center}
      \\roundpic{LaTeX/foto.png}
 
 \end{center}
 
 \bg{cvgreen}{white}{About me}\\[0.5em]
 
 {\\footnotesize
 Highly motivated and organized healthcare professional with extensive experience in research project management, multidisciplinary team leadership, and the application of innovative solutions in the healthcare sector. Master\'s Degree in Health Data Science, providing a unique combination of analytical, technical, and communication skills. Objective: To contribute significantly to EVERSANA\'s success, leveraging expertise and passion for innovation to optimize content review processes and drive valuable solutions for clients.}
 \bigskip
 
 \bg{cvgreen}{white}{personal} \\[0.5em]
 Marta Alberola Martín
 
 nationality: Spanish 
 
 1883
 
 39\\% Disability Certificate
 
 B1 Driver\'s license
 
 \bigskip
 
 \bg{cvgreen}{white}{Areas of specialization} \\[0.5em]
 
 Privateering ~$\\bullet$~\ Bucaneering ~$\\bullet$~\ Parler ~$\\bullet$~\ Rum
 
 \bigskip
 
 
 
 \bigskip
 
 \bg{cvgreen}{white}{Interests}\\[0.5em]
 
 \\lorem
 \bigskip
 
 \bg{cvgreen}{white}{Interests}\\[0.5em]
 
 \\texttt{R} ~/~ \\texttt{Android} ~/~ \\texttt{Linux}
 
 \\texttt{R} ~/~ \\texttt{Android} ~/~ \\texttt{Linux}
 
 \\texttt{R} ~/~ \\texttt{Android} ~/~ \\texttt{Linux}
 
 \\vspace{4em}
 
 \\infobubble{\\faAt}{cvgreen}{white}{jack@sparrow.org}
 \\infobubble{\\faTwitter}{cvgreen}{white}{@sparrow}
 \\infobubble{\\faFacebook}{cvgreen}{white}{Jack Sparrow}
 \\infobubble{\\faGithub}{cvgreen}{white}{sparrow}
 
 \\phantom{turn the page}
 
 \\phantom{turn the page}
 }
 %-----------------------------------------------------------
 \\switchcolumn
 
 \\small
 \\section*{Professional Experience}
 
 \\begin{tabular}{r| p{0.5\\textwidth} c}
 \\cvevent{2018--2021}{Medical Specialist in Anesthesiology and Resuscitation}{Fundació Privada Hospital Asil de Granollers}{Granollers \\color{cvred}}{Led the implementation and development of new hospital protocols and research initiatives. Coordinated cross-disciplinary teams for trauma and cardiac arrest protocols. Supervised and mentored junior anesthesiologists and master\'s students, fostering professional growth. Delivered high-quality medical care and streamlined workflows for urgent and elective cases.}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n \\cvevent{2013--2018}{Medical Residency in Anesthesiology and Resuscitation}{Consorci Sanitari del Maresme}{Hospital de Mataró \\color{cvred}}{Directed and executed research on postoperative pain in knee prostheses, earning a hospital research grant. Rotated through specialized units, including pediatrics, cardiac surgery, and pain management.}{LaTeX/logo_hospitalclinicbarcelona.jpg}\\\\\n \\cvevent{2007--2012}{Transplant Coordinator}{Transplant Services Foundation}{Hospital Clínic de Barcelona\\color{cvred}}{Managed organ and tissue extraction teams, ensuring efficiency and compliance with regulations. Conducted empathetic communication with donor families during critical moments..}{LaTeX/logo_hospitalclinicbarcelona.jpg}
 
 
 \\begin{minipage}[t]{0.35\\textwidth}
 \\section*{Degrees}
 \\begin{tabular}{r p{0.6\\textwidth} c}
      \\cvdegree{2007}{Degree in Medicine}{UB}{Hopsital Clínic de Barcelona \\color{headerblue}}{}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n      \\cvdegree{2012}{European Coordinator of Transplants}{Certificated}{European Board of Surgery \\color{headerblue}}{}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n      \\cvdegree{2013}{Bioinformathics and Biostatistics}{Master}{UOC \\color{headerblue}}{}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n      \\cvdegree{2015}{Innovation and Research in Health Sciences}{Postgraduate}{UAB \\color{headerblue}}{}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n      \\cvdegree{2018}{Anaesthesiologist Specialization}{Medical Specialization }{UAB \\color{headerblue}}{}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n      \\cvdegree{2024}{e-Health}{Master.}{UOC \\color{headerblue}}{}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n      \\cvdegree{Ongoing}{Health Data Science}{Interuniversitary Master}{URV \\color{headerblue}}{}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n \\end{tabular}
 \\end{minipage}\\hfill
 \\begin{minipage}[t]{0.3\\textwidth}
 \\section*{Programming}
 \\begin{tabular}{r @{\\hspace{0.5em}}l}
       \\bg{skilllabelcolour}{iconcolour}{html, css} &  \\barrule{0.4}{0.5em}{cvpurple}\\\\\n       \\bg{skilllabelcolour}{iconcolour}{\\LaTeX} & \\barrule{0.55}{0.5em}{cvgreen} \\\\\n       \\bg{skilllabelcolour}{iconcolour}{python} & \\barrule{0.5}{0.5em}{cvpurple} \\\\\n       \\bg{skilllabelcolour}{iconcolour}{R} & \\barrule{0.25}{0.5em}{cvpurple} \\\\\n       \\bg{skilllabelcolour}{iconcolour}{javascript} & \\barrule{0.1}{0.5em}{cvpurple} \\\\\n \\end{tabular}
 \\end{minipage}
 
 \\section*{Degrees}
 
 \\begin{tabular}{r| p{0.5\\textwidth} c}
      \\cvevent{2007}{Degree in Medicine}{UB}{Hopsital Clínic de Barcelona \\color{headerblue}}{}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n      \\cvevent{2012}{European Coordinator of Transplants}{Certificated}{European Board of Surgery \\color{headerblue}}{}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n      \\cvevent{2013}{Bioinformathics and Biostatistics}{Master}{UOC \\color{headerblue}}{}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n      \\cvevent{2015}{Innovation and Research in Health Sciences}{Postgraduate}{UAB \\color{headerblue}}{}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n      \\cvevent{2018}{Anaesthesiologist Specialization}{Medical Specialization }{UAB \\color{headerblue}}{}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n      \\cvevent{2024}{e-Health}{Master.}{UOC \\color{headerblue}}{}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n      \\cvevent{Ongoing}{Health Data Science}{Interuniversitary Master}{URV \\color{headerblue}}{}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n      \\cvevent{2018--2021}{Captain of the Black Pearl}{Lead}{East Indies \\color{cvred}}{\\lorem}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n      \\cvevent{2019}{Freelance Pirate}{Bucaneering}{Tortuga \\color{cvred}}{\\lorem}{LaTeX/logo_hospitalclinicbarcelona.jpg} \\\\\n \\end{tabular}
 \\vspace{3em}
 
 \\begin{minipage}[t]{0.3\\textwidth}
 \\section*{Certificates \\& Grants}
 \\begin{tabular}{>{\\footnotesize\\bfseries}r >{\\footnotesize}p{0.55\\textwidth}}
      1708 & Captain\'s Certificates \\\\\n      1710 & Travel grant \\\\\n      1715--1716 & Grant from the Pirate\'s Company\n \\end{tabular}
 \\bigskip
 
 \\section*{Languages}
 \\begin{tabular}{l | ll}
 \\textbf{English} & C2 & {\\phantom{x}\\footnotesize mother tongue} \\\\\n \\textbf{French} & C2 & \\pictofraction{\\faCircle}{cvgreen}{3}{black!30}{1}{\\tiny} \\\\\n \\textbf{Spanish} & C2 & \\pictofraction{\\faCircle}{cvgreen}{1}{black!30}{3}{\\tiny} \\\\\n \\textbf{Italian} & C2 & \\pictofraction{\\faCircle}{cvgreen}{3}{black!30}{1}{\\tiny}\n \\end{tabular}
 \\bigskip
 
 \\end{minipage}\\hfill
 \\begin{minipage}[t]{0.3\\textwidth}
 \\section*{Publications}
 \\begin{tabular}{>{\\footnotesize\\bfseries}r >{\\footnotesize}p{0.7\\textwidth}}
      1729 & \\emph{How I almost got killed by Lady Swan}, Tortuga Printing Press. \\\\\n      1720 & ``Privateering for Beginners\'\', in: \\emph{The Pragmatic Pirate} (1/1720).\n \\end{tabular}
 \\bigskip
 
 \\section*{Talks}
 \\begin{tabular}{>{\\footnotesize\\bfseries}r >{\\footnotesize}p{0.6\\textwidth}}
      Nov. 1726 & ``How I lost my ship (\\& and how to get it back)\'\', at: \\emph{Annual Pirate\'s Conference} in Tortuga, Nov. 1726.\n \\end{tabular}
 \\end{minipage}
 
 
 
 
 
 
 \\vfill{} % Whitespace before final footer
 
 %----------------------------------------------------------------------------------------
 %	FINAL FOOTER
 %----------------------------------------------------------------------------------------
 \\setlength{\\parindent}{0pt}
 \\begin{minipage}[t]{\\rightcolwidth}
 \\begin{center}\\fontfamily{\\sfdefault}\\selectfont \\color{black!70}
 {\\small Marta Alberola Martín \\icon{\\faEnvelopeO}{cvgreen}{} C/ Narcís Monturiol 174, ático 2, Vilassar de Mar \\icon{\\faMapMarker}{cvgreen}{} Barcelona, Spain \\icon{\\faPhone}{cvgreen}{}  +34 646 66 11 19 \\icon{\\faAt}{cvgreen}{} \\protect\\url{marta.alberola@gmail.com}
 }
 \\end{center}
 \\end{minipage}
 
 \\end{paracol}
 
 \\end{document}

Master memoire Aurelien Rondeau-Body
Pour compiler sous zed/ubuntu : 
```bash
latexmk -C && latexmk -pvc -pdf -f M2RONDEAUBODYAurelien.tex
```
Pour les notes de bas de pages : 
```bash
\autocite[page]{titre du bib}
\footnote{« \latin{texte en latin}.». \cite[page]{titre du bib}.}
\footnote{«~\latin{}~». \cite[\nopp 72,7]{ambroise_lettres}.}
```
POur les citations au coeur de la page :
```bash
\begin{quote}
    
\end{quote}
```
test sauvegarde ok

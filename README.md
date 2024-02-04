# IEEE-bibitem-converter
Converts standard google scholar .bib entries to IEEE single file bibitem

## Usage


python bibconverter.py < refs.bib > bibitem.txt


## Input example:  

@article{lewis1999role,
  title={The role of the self in cognition and emotion},
  author={Lewis, Michael},
  journal={Handbook of cognition and emotion},
  pages={125--142},
  year={1999}
}

## Output Example:  

\bibitem{IEEEexample:article_typical:smith2020computational}
J. Smith and J. Johnson, \textit{A Computational Representational Theory of Mind Approach to Cognitive Modeling}, IEEE Transactions on Cognitive and Developmental Systems, vol. 12, no. 3, pp. 345--358, 2020.

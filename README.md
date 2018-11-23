# cogimon-beamer-template

This is a quick and dirty version of cogimon official template re-written for `beamer`. 
It needs [fira sans](https://github.com/bBoxType/FiraSans) font from Mozilla and should be run with `lualatex` or `xelatex`. 
This comes with no guarantee so use it at your own risk.

Universities and institutes are copyright holders for their logos.

### Howto
If you want to change the appearance of elements, you can refer to [beamer-cheatsheet](http://www.cpt.univ-mrs.fr/~masson/latex/Beamer-appearance-cheat-sheet.pdf). For instance, to set the `frame title` bold, you add the following to your preamble:
```TeX
\setbeamerfont{frametitle}{series=\bfseries}
```

### Issues
1. **IMPORTANT**: Currently it works with 16:9 aspect ratios. 4:3 results in bad headlines and footlines.

### TODO
1. The title page
2. Fix the aspect ratio

#LaTeX-resume

You would need TeXWorks to run and edit the code as you desire.

This resume in LaTeX and the font is what you commonly see in Tech.

Edit the contents however you like.

There is a bug in LaTeX Workshop where the error will be the following:

Recipe terminated with fatal error: spawn latexmk ENOENT.

Do Command + Shift + P

Go to Preferences Open User Settings (JSON)

Edit the settings.json to add the latex-workshop thitf loltf

  "terminal.integrated.inheritEnv": false,
  "database-client.autoSync": true,
  "latex-workshop.latex.path": "/Library/TeX/texbin"
}
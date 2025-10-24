# Ötzi – Version narrative (correctif “Entrée/Clic”)
Ce correctif règle le problème “Entrée ne fait rien” :  
- écoute **globale** du clavier (window/document/body) avec `preventDefault()` ;  
- **clic n’importe où** pour avancer la narration ;  
- **focus** automatique sur le canvas ;  
- **resize initial** du canvas.

Remplace ton `index.html` par celui-ci et fais un **hard refresh** (Cmd/Ctrl+Shift+R).

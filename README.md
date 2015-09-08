# Programació de dispositius mòbils

Aquest serà el lloc oficial a GitHub de l'assignatura on podreu trobar explicacions i especialment el codi a usar. En cada moment us aniré explicant quin codi i/o repositori heu d'usar i quins són els lliuraments

## Com usarem el GitHub

Haureu de seguir les indicacions aquí exposades per cada *lliurament* i repositori indicat:

1. To start, [**fork** the repository][forking].
1. [**Clone**][ref-clone] the repository to your computer.
1. Modify the files and [**commit**][ref-commit] changes to complete your solution.
1. [**Push**][ref-push]/sync the changes up to GitHub.
1. [Create a **pull request**][pull-request] on the original repository to turn in the assignment.

<!-- Links -->
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: http://gitref.org/creating/#clone
[ref-commit]: http://gitref.org/basic/#commit
[ref-push]: http://gitref.org/remotes/#push
[pull-request]: https://help.github.com/articles/creating-a-pull-request
[raw]: https://raw.githubusercontent.com/education/guide/master/docs/forks.md

## Importar el projecte a Intellij

1. A Intellij si no hi ha cap projecte obert escolliu **Import project** en cas contrari aneu a **File | New | Project from Existing Sources** 
2. Escolliu el directori pertinent
3. Si Intellij no sap adivinar com obrir-lo apareixerà una pantalla i heu d'escollir **Gradle project** i deixeu els paràmetres per defecte

A vegades la importació no va tant bé com a un li agradaria. M'he trobat en situacions diferents:

1. Si fa la importació automàtica (no demana de quin tipus és) segurament surtirà una finestreta a l'esquerra dient que ha detectat que és Gradle però que no s'ha importat com a tal. Heu de prémer el botó per tal que ho sigui
2. Segurament també sortirà que ha detectat que és un projecte que està a Git i us demana si el voleu incorporar com a tal. Si ho feru podeu usar la interfície Git del Intellij. (Jo no hi he fet mai per què m'agrada més treballar amb la consola)
3. És possible que doni errors de que no troba imports (en l'editor). Generalment el primer cop que es compila tot queda en ordre. Si no fos el cas podeu fer **File | Invalidate cahes/Restart...** 

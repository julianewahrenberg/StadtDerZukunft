# Stadt der Zukunft

Projekt für das Fach Erdkunde

Veröffentlicht unter https://julianewahrenberg.github.io/StadtDerZukunft/

Erstellt mit [Hugo](https://gohugo.io/) und dem Theme [Hugo Scroll](https://github.com/zjedi/hugo-scroll)


## Wie arbeite ich an dieser HomePage?

Hier wird nur der Fall unter Windows beschrieben.

Und in aller kürzester Stichwortform.


### Werkzeuge installieren

[Scoop.sh](https://scoop.sh/)


Powershell oder cmd:

```
scoop bucket add extras
scoop install git vscode hugo hugo-extended
```


### Quellen der Homepage holen

Git-bash:

```
git clone --recurse-submodules https://github.com/julianewahrenberg/StadtDerZukunft.git
```

### Änderungen vornehmen

```
cd StadtDerZukunft
code .
hugo server --disableFastRender
```

Immer wieder in "Baby-Steps":

```
# Im Visual Studio code editieren und speichern
git add .
git commit -m "My meaningful commit message"
```


### Änderungen publizieren

Git-bash:

```
git push
```

## Autoren

- Autorin (Inhalte erstellt, Design definiert): Juliane Wahrenberg
- Technische Umgebung bereitgestellt und Autorin untertützt: Alexander Mann-Wahrenberg

# SZMSZ template

Ez egy TeX sablon SZMSZ-ek írására, és annak szép formázására.

## Lokális íráshoz

Ha még nem vagy teljesen ismeretes a TeX erőforrások lokális szerkesztésében, egy gyors megoldást javaslok.

Telepítsd (ha még nincs meg) a VS Code-ot, majd pedig abban telepítsd a Dev Containers és a LaTeX-Workshop bővítményeket bele. Innen vettem a példát:
https://github.com/James-Yu/LaTeX-Workshop/tree/master/samples/docker

Amint megnyitottad devcontainerként VSCode-ban a mappát, amint nyomsz majd egy mentést, automatikusan legenerálja majd neked a PDF-et szmsz.pdf néven.

További infó a LaTeX-Workshop extensionről: https://github.com/James-Yu/LaTeX-Workshop/wiki/Install#usage

## GitHub action

GitHubon actionökkel készül PDF mainre való pusholás által is. Amint végzett a job, az artifactok között találod.

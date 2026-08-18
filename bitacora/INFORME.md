| Hallazgo | Dónde estaba | Técnica de Git            | Comando exacto                                     | Referencia |
|---|---|---------------------------|----------------------------------------------------|---|
| FRAG-01 | bitacora archivada en la rama principal | log y show                | `git log --diff-filter=D --summary main y git show c38a3ebae3669a5d87f111240714b4d401eec37d^:bitacora/frag-01.txt`        | `a1b2c3d` |
| FRAG-02 | Tag `refs/tags/respaldo/pre-incidente` | Mensaje de un tag anotado | `git cat-file -p refs/tags/respaldo/pre-incidente` | `480db95` |
| Glifo   | ... | ...                       | `git ...`                                          | `...` |
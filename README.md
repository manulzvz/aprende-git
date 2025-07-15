HEAD = nos posiciona en el commit mas reciente dentro de nuestra branch actual
branch = es un pointer a un unico commit
commit = es una captura de nuestro espacio de trabajo y es un pointer al commit directamente anterior

git commit --amend:
    Reemplaza el ultimo commit con uno nuevo para incluir alguna accion faltante (add., etc.)

git rebase -i:
    Nos permite de forma interactiva detenernos despues de cada commit que queremos modificar y hacer los cambios que necesitemos.

    git rebase -i HEAD~2 Nos permite editar los ultimos dos commits.

squash
    Nos permite combinar varios commits en uno solo para mantener organizado y mas facil de entender nuestro main.

    git rebase -i --root
    "squash(36agrw)"
    Rename the commits.

Splitting up a commit
git reset HEAD~ //Resetea el commit antes de tu HEAD

git revert HEAD:
    si estamos colaborando con otros y queremos deshacer un commit que acabamos de realizar, podemos usar este comando.

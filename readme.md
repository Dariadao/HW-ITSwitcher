# Описание и основные отличия работы команд _git pull_ и _git fetch_.

## git pull

добавляет изменения из удаленного репозитория, а затем пытается слить их с текущей веткой т.е. _git pull_ выполняет _git fetch_, а затем - _git merge_.

## git fetch

добавляет изменения из удаленного репозитория и сохраняет их локально, не пытаясь слить их с текущей веткой. Эта операция никогда не изменяет текущую ветку.

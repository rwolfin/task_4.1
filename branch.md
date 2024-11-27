[:leftwards_arrow_with_hook: к содержанию](./readme.md) 


## git branch

**git branch** - Создание новой ветки и переход в неё

Создать новую ветку можно с помощью параметра ```branch```, указав имя ветки.

```mash=
git branch new_branch_name
```

Но Git не переключится на неё автоматически. Для автоматического перехода нужно добавить флаг ```-b``` и параметр ```checkout```.


```mash=
git checkout -b new_branch_name
```


# Mermaid
```mermaid
flowchart TD
    start([Start])-->model[/Get Model From User/]
    model-->condition{IF Model = A OR B}

    condition-->true[TRUE]-->invalid[Return Model To User]
    condition-->false[FALSE]-->valid[Return Invalid Input To User]
    invalid-->finish([End])
    valid-->finish
 ```

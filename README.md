# Mermaid 
Model Flowchart
```mermaid
flowchart TD
    start([Start])-->model[/Get Model From User/]
    model-->condition{IF Model = A OR B}

    condition-->true[TRUE]-->invalid[Return Model To User]
    condition-->false[FALSE]-->valid[Return Invalid Input To User]
    invalid-->finish([End])
    valid-->finish
 ```

Directories
```mermaid
flowchart TD
    drive[c:]-->dir1[Directory 1]
    drive-->dir2[Directory 2]
    drive-->dir3[Directory 3]
    
    dir1-->file1[File 1]
    dir1-->file2[File 2]

    dir2-->dir4[Directory 4]
    dir2-->file3[File 3]

    dir3-->file4[File 4]
    dir3-->file5[File 5]


    dir4-->file6[File 6]
    dir4-->file7[File 7]
```
    

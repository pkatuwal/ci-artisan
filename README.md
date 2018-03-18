### Codeignator Artisan
> Simple bash script to auto create model and controller from codeignator project root
#### Usage
> Copy mazzako.sh to your_codeignator_project_root

> Add executable permission

> To create model
```bash
./mazzako.sh model YourModelName
```
> To create Controller
```bash
./mazzako.sh controller YourControllerName
```
>_Check Model and Controller folder, this script already has basic php script for specific model or controller_

>_Won't replace existing File_

>_must include modeles or controllers folders_

### Todo

- [ ] Add auto **route** on routes.php
- [ ] **View** generate
- [ ] Generate **Helper**, **Library**,**Hooks**
- [ ] List **Library**, **helpers**,**Hooks**
- [ ] check **codeignator Version**
- [ ] List All registered **routes**
- [ ] Set and generate **Base/Site** url

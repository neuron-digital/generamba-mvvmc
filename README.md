### Overview

It's Swift MVVM+Coordinator template for [Generamba](https://github.com/rambler-digital-solutions/Generamba) code generator.

### Templates

#### MVVM-C
Modules: ViewController (View), ViewModel, Coordinator
- [mvvmc](https://github.com/neuron-digital/generamba-mvvmc/blob/master/mvvmc.rambaspec)

```generamba gen module_name mvvmc --module_path "project_folder/Modules"```

#### Model-Service
Models: Model, Service
- [model-service](https://github.com/neuron-digital/generamba-mvvmc/blob/master/model-service.rambaspec)

```generamba gen module_name model-service --module_path "project_folder/Models"```

### Example:

```
Modules
    Auth
        Views
            Cell
                Cell.swift
            AuthVC.swift
        ViewModels
            AuthVM.swift
        AuthCoordinator.swift
Models
    Auth
        AuthSetvise.swift
        AuthModel.swift
```

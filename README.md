### Overview

It's Swift MVVM+Coordinator template for [Generamba](https://github.com/rambler-digital-solutions/Generamba) code generator.

### Templates
- [adkrviper_controller](https://github.com/rambler-digital-solutions/generamba-catalog/blob/master/adkrviper_controller/adkrviper_controller.rambaspec)
- [mvvmc](https://github.com/neuron-digital/generamba-mvvmc/blob/master/mvvm-c/mvvmc.rambaspec)
- [model-service](https://github.com/neuron-digital/generamba-mvvmc/blob/master/model-service/model-service.rambaspec)

#### MVVM-C
Modules: ViewController (View), ViewModel, Coordinator


#### Model-Service
Models: Model, Service

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

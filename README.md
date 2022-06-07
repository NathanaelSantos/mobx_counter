# MobX.dart

## Dependências
Adicione as seguintes dependências ao seu arquivo pubspec.yaml.
  ```
  dependencies:
    mobx: ^2.0.7+2'
    flutter_mobx: ^2.0.6+1'
  ```
  **mobx** é o responsável por trazer a base de códigos (Observables, Actions, Reactions)
  
  **flutter_mobx** faz a integração do MobX sobre o Flutter. O flutter_mobx fornece um conjunto de widgets **Observer** que escutam Observables e com isso, recontrói automaticamente as alterações.
  
  Com flutter_mobx:
  
  ![](/files/observer.gif)
  

  
  A seguir, adicionar as seguintes dependências de desenvolvimento:
  
  ```
  dev_dependencies:
    build_runner: ^2.1.11
    mobx_codegen: ^2.0.7
  ```

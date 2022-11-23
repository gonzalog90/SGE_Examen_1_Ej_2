# **SGE_Examen_1_Ej_2**
## _Repositorio de prueba para examen SGE - ejercicio 2 - Control de versiones y documentación_

> 'If debugging is the process of removing software bugs, then programming
> must be the process of putting them in' - 
> Edsger Dijkstra.

### Requisitos del ejercicio:
#### 1. Agregar imágenes.
#### 2. Emplear títulos de diferentes tamaños.
#### 3. Enlaces a otras páginas. 
#### 4. Etiqueta de versión del repositorio. 


##### _Ejemplo de Singleton en Dart, DataHolder para guardar el Usuario_

```dart

class DataHolder {

  static final DataHolder _dataHolderInstance =  DataHolder._internal();

  Profile profile = Profile();


  DataHolder._internal() {
    //
  }

  factory DataHolder() {
    return _dataHolderInstance;
  }

}
```

##### _Ejemplo de Spinner customizado en Dart-Flutter_

```dart
Container(
  width: MediaQuery.of(context).size.width*0.5,
  decoration: const BoxDecoration(
    shape: BoxShape.circle,
    color: Colors.green,
  ),
  padding: EdgeInsets.all(MediaQuery.of(context).size.width*0.1),
  child: const CircularProgressIndicator(
    color: Colors.white,
    backgroundColor: Colors.black,
  ),
),
```

**[Ejemplo completo de Spinner](./examples/spinner_complete_example.md)**

**[Respuestas sobre Spinner en StackOverflow](https://stackoverflow.com/questions/47065098/how-to-work-with-progress-indicator-in-flutter)**


##### _Visualización del ejemplo de spinner anterior_

![spinner1](./spinner_img_1.png)
![spinner1](./spinner_img_2.png)




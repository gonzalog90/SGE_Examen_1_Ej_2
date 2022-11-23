#### _Ejemplo de Spinner completo_

```dart


class SplashScreen extends StatefulWidget {

  const SplashScreen({super.key});

  @override
  State<StatefulWidget> createState() => _SplashScreenState();
}

class _SplashScreenState extends State<SplashScreen> {

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Column(
        mainAxisAligment: MainAxisAligment.center,
        children: [
          // SPINNER
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
        ]
      ),
    );

  }
}

```

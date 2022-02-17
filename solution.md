1. Create you flutter app.
2. Clean your `main.dart` file to look like this:

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return
  }
}
```

3. Create you main Widget: `MaterialApp`.

```dart
class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return  MaterialApp(),
  }
}
```

4. Create a stateless widget called `HomeScreen`.

```dart
class HomeScreen extends StatelessWidget {
  const HomeScreen({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return
  }
}
```

5. Return a `Scaffold` widget in your `HomeScreen` widget.

```dart
class HomeScreen extends StatelessWidget {
  const HomeScreen({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return Scaffold();
  }
}
```

6. In your `MaterialApp` widget, set the `home` named argument to the `HomeScreen` widget that you just created.

```dart
class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: HomeScreen(),
    );
  }
}
```

7. In your `Scaffold` widget, add a `body` named argument and pass it a `Text` widget.

```dart
class HomeScreen extends StatelessWidget {
  const HomeScreen({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Text("Omar"),
    );
  }
}
```

8. Wrap your `Text` widget in a `Center` widget.

```dart
class HomeScreen extends StatelessWidget {
  const HomeScreen({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Center(
        child: Text("Omar"),
      ),
    );
  }
}
```

9. In your `Text` widget, add a second argument `style` and pass it `TextStyle` then style your text.

```dart
    return Scaffold(
      body: Center(
        child: Text(
          "Omar",
          style: TextStyle(
              fontSize: 35, fontWeight: FontWeight.bold, color: Colors.red),
        ),
      ),
    );
```

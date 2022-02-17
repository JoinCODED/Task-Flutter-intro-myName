# My name

You will create a new flutter app project called "my_name_flutter_app"
After that, you will build an app that shows your name at the center of the home screen.
Then, you will change the text style.

fontSize: 35
fontWeight: bold
color: Red

## Instructions

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
4. Create a stateless widget called `HomeScreen`.
5. Return a `Scaffold` widget in your `HomeScreen` widget.
6. In your `MaterialApp` widget, set the `home` named argument to the `HomeScreen` widget that you just created.
7. In your `Scaffold` widget, add a `body` named argument and pass it a `Text` widget.
8. Wrap your `Text` widget in a `Center` widget.
9. In your `Text` widget, add a second argument `textStyle` and style your text.

### 🍋 The basic challenge title

- Step 1
- Step 2
- Step 3

### 🤼‍♂️ The hard challenge title

- Step 1
- Step 2
- Step 3

### 🌶 The Extreme challenge title

- Step 1
- Step 2
- Step 3

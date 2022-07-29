# My Name 😌

![image](https://user-images.githubusercontent.com/84308096/154476277-acb96259-79fd-4aa2-baa7-96df8d0b7e17.png)

You will create a new flutter app project called "my_name_flutter_app"
After that, you will build an app that shows your name at the center of the home screen.
Then, you will change the text style.

```dart
fontSize: 35
fontWeight: bold
color: Red
```

## Setup

1. Create a new Github repo
2. Create a local repo using the command `git init`
3. Push to the new repo

```shell
git remote add origin https://github.com/YourUsername/repoName.git
```

```shell
git branch -M main
```

```shell
git push -u origin main
```

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
    return MaterialAp()
  }
}
```

Here is the widgets you will need:

- Scaffold [documentation](https://api.flutter.dev/flutter/material/Scaffold-class.html)
- Center [documentation](https://api.flutter.dev/flutter/widgets/Center-class.html)
- Text [documentation](https://api.flutter.dev/flutter/material/Text-class.html)

Don't forget to style your text!

Result:

![result](https://user-images.githubusercontent.com/84308096/154476341-9b56163a-c22a-4a11-af3c-a18bb77eb70e.png)

## Push to Github

```shell
git add .
```

```shell
git commit -m "your message"
```

```shell
git push
```

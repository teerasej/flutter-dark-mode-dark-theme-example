# Flutter App that support Dark mode (iOS 13+) and Dark theme (Android 10+)

A demo to make your Google Flutter application goes Dark.

## Getting Started

normally, We can set theme's color for our application via `MaterialApp`: `theme:` attribute:

```dart
MaterialApp(
    title: 'Nextflow Flutter Demo',
    
    // here we go...
    theme: ThemeData(
        primarySwatch: Colors.green,
    ),

    home: MyHomePage(title: 'Nextflow Flutter Dark Mode'),
);
```

Flutter team provided so convenient options, `darkTheme:`, which allow us to set another theme that will actived whenever user turn their dark mode on.

```dart
MaterialApp(
    title: 'Nextflow Flutter Demo',
    theme: ThemeData(
        primarySwatch: Colors.green,
    ),

    // here we goes dark...
    darkTheme: ThemeData(
        brightness: Brightness.dark
    ),

    home: MyHomePage(title: 'Nextflow Flutter Dark Mode'),
);
```

So enjoy the possibilities of Flutter :)

## Flutter Docs

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

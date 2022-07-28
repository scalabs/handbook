# Flutter development guidelines

### Linter
- Uses Linter rules from here: [dartclub/linter_rules](https://github.com/dartclub/linter_rules)

### File naming conventions
- Whole screen implementations have the extension `_screen.dart`
- For screens that implement widgets, covering only a part of the screen: `_widget.dart`, e.g. `lib/src/file_picker_widget.dart`
- We use clear plural and singular expressions to distinguish **detail** and **list** screens/widgets. E.g. `lib/src/location/locations_list_screen.dart`, `lib/src/location/location_detail_widget.dart`

Folder structure:
```
lib/
  main.dart
  src/
    cubits/
    helpers/
    APP_MODULE_1/
      app_module_1_list_screen.dart
      app_module_1_detail_screen.dart
    APP-MODULE_2/
      ...
```

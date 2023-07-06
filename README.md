# copywriter
#### Comprehensive copywriting library with standard phrases for software development projects

## Features
- Standard Copywritings across 38+ categories 
- Customise Copwriting based on your requirements 
- Multiple Language Support (ENGLISH,HINDI,SPANISH)


## Installing:
In your pubspec.yaml
```yaml
dependencies:
  copywriter: ^0.0.1
```

```dart
import 'package:copywriter/copywriter.dart' as copywriter;
```
## Usage

```dart
Text(copywriter.customerFeedback); // "Customer Feedback"
```
### To change default value of copywriting 
```dart
copwriter.customerFeedback = "Customer Review";
Text(copywriter.customerFeedback);   //"Customer Review"
```

## Contributing
If you would like to contribute new copywriting examples or suggest improvements, please [contribute here](https://github.com/uditswaroopa/copywriter). We appreciate your contributions to make this library even more comprehensive and valuable.

## License
This project is licensed under the [MIT License](LICENSE).

# copywriting
#### Enhance your software development projects with the powerful Dart package, Copywriting. Designed to streamline the copywriting process, this comprehensive toolkit offers a wide array of standardized and high-quality copy for your software. From engaging interface text to persuasive call-to-action prompts, Copywriting empowers developers to create seamless user experiences that captivate and convert. Elevate your software's impact with Copywriting's versatile collection of essential content elements.

## Features
- Standard Copywritings across 38+ categories 
- Customise Copwriting based on your requirements 
- Multiple Language Support (coming soon)


## Installing:
In your pubspec.yaml
```yaml
dependencies:
  copywriting: ^0.0.1
```

```dart
import 'package:copywriting/copywriting.dart' as copywriter;
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

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
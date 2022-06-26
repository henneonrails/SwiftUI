# SwiftUI
knowledge base for coding
## Color
The system color objects adapt automatically to Dark Mode 
```swift
class var systemBlue: UIColor { get }
```
Grau ist in verschiedene Varianten enthalten:
[Standard colors](https://developer.apple.com/documentation/uikit/uicolor/standard_colors)

### Font
[Text styles](https://developer.apple.com/documentation/swiftui/font/textstyle)

(body, callout, caption usw.)

#### String Format Specifier
[Tabelle der Specifier](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/Strings/Articles/formatSpecifiers.html)

die Specifier können z.b. inline verwendet werden
```swift
Text("Copying \(copyOperation.numFiles, specifier: "%lld") files",
    comment: "File copy message that indicates the number of files copied by the operation")
```

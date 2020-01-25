# Save and Load Data in iOS

Save_and_Load_Data_in_iOS

# Archiving

- Saving and loading data almost always means saving and loading model objects.
- Classes whose instances need to be archived and unarchived must conform to the NSCoding protocol and implement its two required methods, encode(with:) and init(coder:)

```swift
protocol NSCoding {
  func encode(with aCoder: NSCoder)
  init?(coder aDecoder: NSCoder)
}
```

You can see my examples about archiving browsing through these two repositories:

1. [NSCoding_ObjectiveC](https://github.com/c4arl0s/NSCoding_ObjectiveC)
2. [NSCoding_Swift](https://github.com/c4arl0s/NSCoding_Swift)

# Application Sandbox

# Codable

- [EncodingWithCodable](https://github.com/c4arl0s/EncodingWithCodable)
- [DecodingWithCodable](https://github.com/c4arl0s/DecodingWithCodable)

# Keychain

![IMG_0070](https://user-images.githubusercontent.com/24994818/73124136-593e8780-3f5d-11ea-839d-6256a54926be.jpg)

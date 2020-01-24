# Save_and_Load _Data_in_iOS

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


# Application Sandbox



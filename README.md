# Why-The-Sets
You might be curious why we need to use SET in our projects. SETs are like arrays but with two differences. First, in SET items are unique, and Second, aren't stored in any order. So why shall we implement some values as set if it kinda has fewer features than an array?


# Description of Example 

Imagine we have a struct containing attributes of animal diseases. We want to create a doctor assistant app to input the symptoms of an animal in the app to get a predicted answer related to symptoms.

# The Output Video



https://github.com/hesamsaeedi55/Why-The-Sets/assets/118046088/ce09b327-6907-4716-995b-cb0feb92855a



# here is our struct model 

```swift
struct symptoms : Hashable,Decodable,Identifiable {
    var id:Int
    var name : String
    var category : String
    var state : Bool
}
```

# here is function which receives the temporary selected items as a set value

 


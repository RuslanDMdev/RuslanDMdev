### Hi there 👋
I am iOS Developer

class IOSDeveloper {
    
    let name = "Ruslan Dalgaov"
    let age = 21
    let language = "Swift"
    
    var myStackDictionary: [String: [String]] = [
        
        "Principles":       ["OOP", "SOLID"]
        "Layout":           ["UIKit", "AutoLayout", "SnapKit", "Storyboard"]
        "Dependensies":     ["CocoaPods"]
        "Storage":          ["Core Data", "UserDefaults", "FileManager", "Realm"]
        "Networking":       ["URLSession", "JSON Parse", "REST API", "Firebase"]
        "Multithreading":   ["GCD", "DQ's"]
        "Arch. patterns":   ["MVC", "MVVM", "MVVM+C", "MVP", "MVP+C"]
        "Struct. patterns": ["Delegate", "Singleton", "Factory", "Observer", "Facade"]
        "GUI":              ["Git", "GitHub"]
        "Graphics":         ["Figma", "Photoshop"]
    ]
    
    var otherTechnologies: [String] = [
        "MapKit",
        "Push / Local Notifications",
        "Multimedia (AVFoundation, Core Audio, AVKit)",
        "Core Animation"
    ]
    
    func sayHello() {
        print("Hello stranger.")
    }
}
    
me = IOSDeveloper()

me.sayHello()

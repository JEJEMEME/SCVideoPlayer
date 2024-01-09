
# SCVideoPlayer: A SwiftUI Custom Video Player

## Overview
SCVideoPlayer is a custom video player designed for iOS applications, built using SwiftUI and AVKit. This player offers advanced features like gesture-based controls, custom player size options, thumbnail previews for seeking, and more. Developed to enhance the media playing experience in iOS apps, it's a versatile and user-friendly component suitable for various applications.

## Features
- **Customizable Player Size:** Adjust the player size to suit different screen layouts.
- **Gesture Controls:** Easily control video playback with intuitive gestures.
- **Thumbnail Previews:** View thumbnail frames for precise video seeking.
- **Rotatable Player View:** Supports rotation for landscape and portrait viewing.
- **Advanced Playback Controls:** Custom playback controls for a better user experience.
- **Safe Area Handling:** Optimized for seamless integration with iOS's safe area.
- **SwiftUI Compatibility:** Built specifically for SwiftUI applications.

## Requirements
- iOS 16.0 or later
- Swift 5.0 or later
- Xcode 14.0 or later

## Usage
To use SCVideoPlayer in your SwiftUI view:

```swift
import SwiftUI
import AVKit

struct ContentView: View {
    var body: some View {
        SCVideoPlayer(videoURL: URL(string: "your_video_url_here")!)
    }
}

struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
        ContentView()
    }
}
```

## Contribution
Contributions are welcome! If you'd like to improve SCVideoPlayer, please feel free to fork the repository, make changes, and submit a pull request.

## License
SCVideoPlayer is available under the MIT license. See the LICENSE file for more info.

## Acknowledgements
Created by JEJEMEME, a passionate Swift developer and open-source contributor.

---

SCVideoPlayer is a project aimed at simplifying video playback in SwiftUI apps. We hope it helps you create amazing applications! 🚀

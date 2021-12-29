# iOS Assessment

In this simple task, we’re evaluating your coding style and design patterns. 

The app is composed of 2 screens, first is the profile screen, it has the user name and address pinned at the top and then it lists all of this user’s albums. You can get user albums by requesting the albums endpoint and passing userId as a parameter.

When you press on any album it navigates to the second screen which is an album details screen. You request the photos endpoint and pass album id as a parameter, then list the images in an Instagram-like grid. Also, there should be a search bar that you can filter within the album by the image title, when you start typing the screen should show only images that are related to this search query.

## Required Specs:
- Swift 5.5
- Xcode 13.1
- iOS 13+

## Software stack:
- Swift
- MVVM (Feel free to use your own implementation/vision)
- Combine/RxSwift
- CombineCocoa/RxCocoa 
- UIKit
- Moya 

Feel free to use any additional third-party libraries, The important thing is you must use **Swift Package Manager** as your dependency manager.

## API Endpoints:

- Base URL: **https://jsonplaceholder.typicode.com**
- User: `GET /users` you can pick any user to start with (preferably *random*)
- Albums: `GET /albums` (`userId` as a parameter)
- Photos: `GET /photos` (`albumId` as a parameter)

## Bonus Points:

Open any image in a separate image viewer with zooming and sharing functionality implemented.

## Concept design:

|Screen 1|screen2|
|-|-|
|<img width="339" alt="screen1" src="https://user-images.githubusercontent.com/10261166/147656719-a9500c6e-685b-4b25-9878-34e76c8c962d.png">|<img width="356" alt="screen2" src="https://user-images.githubusercontent.com/10261166/147656761-f9158a35-4ac9-4a75-a8ed-3cf3f6b304eb.png">|

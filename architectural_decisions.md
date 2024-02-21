
# Architectural Decisions

### Student Name: Osabuohiense Agho
### Assignment: Architectural Decisions

## 1. Native, Web, or Hybrid?
- **Decision**: Native Android App
- **Rationale**: Specifically, about the development of an application, a native android app allows us to benefit from the entire functionality and features of the Android platform that results in better performance and user experience. This approach enables direct access to the hardware device and faster execution. Although this decision concentrates on developing for one platform, it ensures that our app is fully optimized for android users hence shorter loading times as well as more user-friendly interface strictly following Google design guidelines.

## 2. UI Framework
- **Decision**: React Native with Figma for UI Design
- **Rationale**: By using Figma to design UIs, one can make highly detailed interactive designs that can easily be translated into react native components directly. The flexibility of React Native makes it easy to integrate Figma-designed UIs into applications which ultimately makes the interface look nice and friendly.

## 3. Backend Framework
- **Decision**: Node.js
- **Rationale**: React Native and Node.js is a perfect combination because of its non-blocking model which works well for applications with real-time data demands. It also simplifies the communication between server to mobile app, making requests handling effective and enabling it to scale up for future growth.

## 4. Permissions
- **Decision**: Minimizing Permission List with Focus on Internet and RAM Optimization
- **Rationale**: Minimal permissions are needed to be requested in order to ensure user privacy and application security. Consequently, the application will mainly need internet access so as to synchronize data and send push notifications. To make sure that this runs smoothly on different devices, especially those with limited resources, there will be memory optimization techniques such as efficient memory management through minimizing the app’s footprint.

## 5. Data Storage
- **Decision**: Local Storage
- **Rationale**: In terms of local data management, we use a simple async key-value store on the device that would be efficient enough when storing lightweight data. In addition, this approach ensures that user preferences and session states can be accessed quickly while offline which enhances the performance of the platform at large since users can retrieve data without an internet connection.

## 6. Additional Frameworks or Technology Stacks
- **Push Notifications**: Firebase Cloud Messaging (FCM)
- **Rationale**: Offers reliable and free messaging for both Android and iOS, facilitating engagement with users through timely notifications.

Navigeerimiseks installi react navigation https://reactnavigation.org/docs/getting-started. Õpetus https://www.udemy.com/course/react-native-the-practical-guide/learn/lecture/31197644#overview Section 6, p 95.
Terminalis käsud: 
npm install @react-navigation/native 
npx expo install react-native-screens react-native-safe-area-context
npm install @react-navigation/native-stack  (https://reactnavigation.org/docs/hello-react-navigation)

> Why do I have a folder named ".expo" in my project?
The ".expo" folder is created when an Expo project is started using "expo start" command.
> What do the files contain?
- "devices.json": contains information about devices that have recently opened this project. This is used to populate the "Development sessions" list in your development builds.
- "settings.json": contains the server configuration that is used to serve the application manifest.
> Should I commit the ".expo" folder?
No, you should not share the ".expo" folder. It does not contain any information that is relevant for other developers working on the project, it is specific to your machine.
Upon project creation, the ".expo" folder is already added to your ".gitignore" file.

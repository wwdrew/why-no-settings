# expo-location issue example

Build and run the development build using:

```sh
npm run ios
```

## Reproduction

1. Install and run the app.
2. Open Settings app to verify the app isn't listed
3. Open app and request Location permissions
4. Open Settings app - app should still not be listed
5. Open app and request Notification permissions
6. Open Settings app - app should now be listed and include Notification _and_ Location settings

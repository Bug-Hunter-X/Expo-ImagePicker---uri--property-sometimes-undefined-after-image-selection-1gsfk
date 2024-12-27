# Expo ImagePicker: `uri` Property Undefined Bug

This repository demonstrates a bug in Expo's ImagePicker library where the `uri` property of the selected image is sometimes undefined after a successful image selection. This inconsistency can lead to application crashes or unexpected behavior.

## Reproduction

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run the app using Expo Go or your preferred Expo development method.
4. Select an image using the ImagePicker.
5. Observe that the `uri` is sometimes undefined, causing an error.

## Solution

The provided solution involves error handling and a more robust approach to retrieving the image URI, ensuring proper handling of cases where `uri` might be undefined.  Consider adding additional logging to further pinpoint the cause of undefined URIs in your specific environment.
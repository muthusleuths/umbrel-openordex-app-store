## Umbrel Openordex App Store

This repository contains Umbrel Openordex App Store.

### Technical Details

The `umbrel-app-store.yml` file defines two important properties:
- `id` - This is used as a prefix for all apps within the community app store. You **MUST** prefix your application id with your app store ID. For example, this template defines `orenyomtov` as a community app store ID and we have a `openordex` app. The app ID therefore should be: `orenyomtov-openordex`
- `openordex` - This name appears within the Umbrel user interface when users explore apps within these community app stores.


### Installation

To install your Openordex app store, you can add this repository through the Umbrel user interface as shown in the following demo:


https://user-images.githubusercontent.com/10330103/197889452-e5cd7e96-3233-4a09-b475-94b754adc7a3.mp4


Alternatively, you can use the Umbrel CLI as described below.

To add an app store:
```
sudo ~/umbrel/scripts/repo add https://github.com/muthudotbtc/umbrel-openordex-app-store.git

sudo ~/umbrel/scripts/repo update
```

To install an app from the app store
```
sudo ~/umbrel/scripts/app install sparkles-hello-world
```

To remove an app store:
```
sudo ~/umbrel/scripts/repo remove https://github.com/muthudotbtc/umbrel-openordex-app-store.git
```

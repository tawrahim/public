# public

As the name implies, this repo contains all things that are public which are used in the app. This repo is used to serve static content to both the `iOS` and `Android` apps.

### Strings
The `iOS` and `Android` both request strings from this repo. Doing this approach we can easily change a string without having to make new build. Also users can get localized strings from this repo based on their device settings.

### Static web resources
| File          | Variable Name  | DEV Link  | PROD Link        |
|:-------------:|:-------------:|:-------------:|:-------------:|
| privacy.html | `PRIVACY_URL` | [Link](https://rawgit.com/tawrahim/public/master/privacy.html) | [Link](https://cdn.rawgit.com/tawrahim/public/master/privacy.html) |
| faq.html | `FAQ_URL` | [Link](https://rawgit.com/tawrahim/public/master/faq.html) | [Link](https://cdn.rawgit.com/tawrahim/public/master/faq.html) |
| terms.html | `TOS_URL` | [Link](https://rawgit.com/tawrahim/public/master/terms.html) | [Link](https://cdn.rawgit.com/tawrahim/public/master/terms.html) |
| licenses.html | `LICENSE_URL` | [Link](https://rawgit.com/tawrahim/public/master/licenses.html) | [Link](https://cdn.rawgit.com/tawrahim/public/master/licenses.html) |

# DRM ClearKey POC

My experiment of video encryption using ClearKey:

- [clearkey_experiment.ipynb](./clearkey_experiment.ipynb): A notebook I used to encrypt the original video with ClearKey.
- [index.html](./index.html) and [app.js](./app.js): Source code of the POC. It allows to play encrypted video stored in this Github repository.

## Test

- [x] The encrypted video cannot be played in POC without key.
- [x] The encrypted video can be played in POC with ClearKey configuration.
- [x] The encrypted video can be downloaded but cannot be played without key (should be all black).
- [ ] The encrypted video cannot be recorded or captured. (ABSOLUTELY CANNOT, find DRM services instead)

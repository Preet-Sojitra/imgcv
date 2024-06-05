# CHANGELOG



## v0.9.0 (2024-06-05)

### Documentation

* docs: add example for fourier transform ([`e0e7b2b`](https://github.com/Preet-Sojitra/imgcv/commit/e0e7b2bc065a133d8c54f19c342e4e9e0b56fdea))

### Feature

* feat(frequency-domain): add module for calculating fourier transform

- Moudle for calculating fourier transform and inverse fourier transform ([`188be75`](https://github.com/Preet-Sojitra/imgcv/commit/188be751c3a4ed6865b6ad83beb7792cc8a95088))

### Unknown

* Merge branch &#39;main&#39; of github.com:Preet-Sojitra/imgcv ([`7c8ed97`](https://github.com/Preet-Sojitra/imgcv/commit/7c8ed9753d403345786df2b517d17c23bd4062ba))


## v0.8.0 (2024-06-04)

### Documentation

* docs: add example for using laplacian, sobel and robert filter

- Also add images for the example ([`9566a11`](https://github.com/Preet-Sojitra/imgcv/commit/9566a11773d792fd2abe2aae30ab534128040be6))

### Feature

* feat(filters): add more linear filters

- Add laplacian, sobel, and robert cross filters

- Add a utility function to apply padding and convolution ([`6958032`](https://github.com/Preet-Sojitra/imgcv/commit/69580326a52edc7bb925e9531078c8cd043b51e6))


## v0.7.0 (2024-06-02)

### Chore

* chore: remove some unused images from docs ([`e4a3321`](https://github.com/Preet-Sojitra/imgcv/commit/e4a33213bc390809cdb6b049db663bd99cf279cf))

### Documentation

* docs: add example for filters ([`380f4c7`](https://github.com/Preet-Sojitra/imgcv/commit/380f4c7b4a27f8dc1581922d2cfb7c512ae58338))

### Feature

* feat(filters): add linear and non-linear filters

- Add Mean/Average/Box filter
- Add Min, Max and Median filter ([`6d46add`](https://github.com/Preet-Sojitra/imgcv/commit/6d46add230e9ddd1909554a601c6d0811fe55134))

### Unknown

* Merge branch &#39;main&#39; of github.com:Preet-Sojitra/imgcv ([`06d28e4`](https://github.com/Preet-Sojitra/imgcv/commit/06d28e433163ad78153b314ca199d39b522da32b))


## v0.6.0 (2024-05-04)

### Documentation

* docs: add example for histogram macthing ([`f73d1c3`](https://github.com/Preet-Sojitra/imgcv/commit/f73d1c332261a0b2c204b067aa11437d46b72a1c))

* docs: add example of equalization for color images ([`7f20309`](https://github.com/Preet-Sojitra/imgcv/commit/7f20309c00f632883bbe34e6b6dc39d885bdc730))

### Feature

* feat(histogram): add histogram matching ([`6317180`](https://github.com/Preet-Sojitra/imgcv/commit/631718004e6f97b5a74f95cc75abedfc7b34e489))

* feat(histogram): add equalization for color images ([`a0403f5`](https://github.com/Preet-Sojitra/imgcv/commit/a0403f55c7c747c0333292a2974e0e07078bfb4f))


## v0.5.0 (2024-05-04)

### Documentation

* docs: add equalization example ([`4b3ac7a`](https://github.com/Preet-Sojitra/imgcv/commit/4b3ac7ab7af8dc9d144b7c53a2ddc03d82e6536e))

### Feature

* feat(histogram): add module of histogram equalization ([`3f7fa0c`](https://github.com/Preet-Sojitra/imgcv/commit/3f7fa0c7e63113eff6fc29af7c88345ec4fa810c))

### Fix

* fix(histogram): change cdf to calculate_cdf ([`98473e1`](https://github.com/Preet-Sojitra/imgcv/commit/98473e15596507240b537cf3b0115dd7a8e05e15))


## v0.4.0 (2024-03-30)

### Documentation

* docs: upadte README ([`eea0c32`](https://github.com/Preet-Sojitra/imgcv/commit/eea0c32819679a3ac723410eea870bbac83909b9))

### Feature

* feat(quantization): add module to reduce gray levels in image ([`05d0086`](https://github.com/Preet-Sojitra/imgcv/commit/05d008600f6d6147d6f0936af4d9e943d4dd3941))

* feat(quantization): add binary thresholding ([`538061b`](https://github.com/Preet-Sojitra/imgcv/commit/538061b729acf5daf4501bb6978f4e1acc06819b))

* feat(connectivity): add connected component analysis ([`e415952`](https://github.com/Preet-Sojitra/imgcv/commit/e415952d20cece7baacb48436be9a91a22c6ce21))

* feat(transformations): add gamma correction ([`bf6acaa`](https://github.com/Preet-Sojitra/imgcv/commit/bf6acaabedf6628915ac55cb294805e363c7cd18))


## v0.3.1 (2024-03-30)

### Documentation

* docs: update README.md

Add badges to README.md ([`dd9944e`](https://github.com/Preet-Sojitra/imgcv/commit/dd9944ef545fbf02b20362c9c2eb4cffeac3f854))

### Fix

* fix(build): update pyproject

add build instructions for python semantic release in pyproject.toml ([`d79d3b5`](https://github.com/Preet-Sojitra/imgcv/commit/d79d3b54c90943f823539e8fbd74b3906e029d05))


## v0.3.0 (2024-03-30)

### Feature

* feat: add ci-cd workflow ([`7bafbc4`](https://github.com/Preet-Sojitra/imgcv/commit/7bafbc45096fe2e918e155957530f0b6d2f6696d))


## v0.2.0 (2024-03-30)

### Build

* build: update pyproject.toml ([`ebdbdc1`](https://github.com/Preet-Sojitra/imgcv/commit/ebdbdc1ec7df9b4e8ec97a65fc74a572697c7bf3))

* build: add PSR as dev dependency ([`3459886`](https://github.com/Preet-Sojitra/imgcv/commit/34598866dfa9865c2a05fac599861f3383a04ca7))

* build: preparing for release v0.2.0 ([`f929af3`](https://github.com/Preet-Sojitra/imgcv/commit/f929af38c0de2bf14f21844e737aada575074ada))

### Feature

* feat(transformations): add log transformation ([`48c59f2`](https://github.com/Preet-Sojitra/imgcv/commit/48c59f2b5467ba804f982ef5b18df51add384658))


## v0.1.0 (2024-03-30)

### Build

* build: add dev dependencies for docs ([`f8904ac`](https://github.com/Preet-Sojitra/imgcv/commit/f8904ac88b7e0e0aa73ee03d20c9a34d7942209f))

* build: add numpy as a dependency ([`dfdb459`](https://github.com/Preet-Sojitra/imgcv/commit/dfdb4595498360f6a9ef56e0c97cee781f68a6c5))

### Chore

* chore: add tests folder to gitignore ([`6fd4ac2`](https://github.com/Preet-Sojitra/imgcv/commit/6fd4ac2f096ef3310312a4ce988415c0934771b6))

### Documentation

* docs: add docs links in README ([`7955e56`](https://github.com/Preet-Sojitra/imgcv/commit/7955e56270d7656805bef8ab392cd51c560005b8))

* docs: update example.ipynb ([`a1fa89c`](https://github.com/Preet-Sojitra/imgcv/commit/a1fa89ce746057376ef29060a5b7424d25b1d0d5))

* docs: update readthedocs.yml ([`24fee1b`](https://github.com/Preet-Sojitra/imgcv/commit/24fee1bf15ed57394f9841983eebfde339f0564b))

* docs: update readme and example ([`0c46171`](https://github.com/Preet-Sojitra/imgcv/commit/0c46171d3e61efdf918dbd46cebfb822a63da233))

### Feature

* feat: add negative transformation ([`4c2ad78`](https://github.com/Preet-Sojitra/imgcv/commit/4c2ad780c600e0aaf06d62fc399b54d38b4f7dce))

### Unknown

* initial package setup ([`8025d5d`](https://github.com/Preet-Sojitra/imgcv/commit/8025d5d1f783d8f25c187d1f2878c2437441fab4))

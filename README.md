# just temp

- anaconda pip ssl error
```
https://github.com/conda/conda/issues/9003

I found out libssl-1_1-x64 dlls in Anaconda/DLLS and Anaconda/Library/bin being installed at different dates, so, as an experiment, I copied the one in Anaconda/DLLS and replaced that in Anaconda/Library/bin and conda started working again, at least for now - I could install new packages again.
```

- selenium using chrome webdriver
```
- install chrome (same version)
- install chromedriver (same version)
```
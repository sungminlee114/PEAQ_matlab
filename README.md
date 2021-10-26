# Introduction
This repository is an update version of [PQevalAudio(PEAQ matlab implementation)](http://www-mmsp.ece.mcgill.ca/Documents/Software/) made by [Prof. Peter Kabal](mailto://kabal@ECE.McGill.CA), affiliated at McGill University, last revised at 2004.

# License
The origininal PEAQ technology(ITU-R Rec. BS.1387) is available under license together with the original code for commercial applications according to ITU fair, reasonable, and non-discriminatory terms. PQevalAudio, the formal implementation of this repository is a basic model for PEAQ implementation which is open only for educational use.
Underlying that all the copyrights of this repository are reserved by Peter Kabal, the license of this repository is also restricted only for educational use.
Look at [this](https://en.wikipedia.org/wiki/Perceptual_Evaluation_of_Audio_Quality#License) article for more.

# Updates
Updates since the initial version are as following
- Naming bugs are fixed.
- Deprecated function `wavread` is replaced by `audioread`.
- `PQevalAudio` now returns the ODG value (result of PEAQ).

Current version is last revised at 2021.10.21, tested under matlab version 2021.b .

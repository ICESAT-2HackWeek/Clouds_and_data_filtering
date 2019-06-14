# Clouds_and_data_filtering
Tutorial investigating how clouds can affect surface detection in ATL03 and ATL06

This tutorial covers some of the reasons you might see weird results over ice when clouds start to blot out the surface signals.  The learning objectives I'd like to get to are:
- Understanding how clouds affect laser-altimetry signals
- Recognizing how these effects are manifest in the ATL06 product
- Gaining familiarity with the ATL06 parameters that can identify cloudy returns
This part of the tutorial will focus on clouds that cause gross errors in surface-height estimates.  

Along the way, we'll:

- develop a simple function for reading ICESat-2 data from hdf-5 files

If time allows, I'll also present on subtler effects caused by forward scattering of laser light by thin clouds, which can lead to smaller elevation biases.  The objectives of this part of the tutorial will be:
- Understanding how forward scattering of laser light by clouds can introduce biases in surface-height estimates
- Tools for identifying returns affected by forward scattering.

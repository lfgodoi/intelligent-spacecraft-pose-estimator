# Intelligent Spacecraft Pose Estimator (intelligent-spacecraft-pose-estimator)

A computer vision solution based on digital image processing and convolutional neural networks for estimating the pose of known uncooperative spacecraft.

- Developer: _Leonardo Franco de Godói_
- GitHub profile: _https://github.com/lfgodoi_
- Contact: _eng.leonardogodoi@gmail.com_

### Motivation

Debris removal and on-orbit servicing are crucial mission concepts employed to address the congestion in Earth orbits and extend the lifetime of geostationary satellites. Both tasks rely on the availability of the target spacecraft's position and attitude (i.e., pose) relative to the servicer spacecraft. However, the targets of interest, including defunct satellites and debris pieces, are uncooperative and thus incapable of providing the servicer the information on their state. Computer vision and deep learning models provide powerful tools for accurately estimating spacecraft's pose based only on images, without the need to know additional specific information.

### Data

The Spacecraft Pose Estimation Dataset (SPEED), made available by ESA's Kelvins and Stanford Universitiy's Space Rendezvous Lab (SLAB), includes thousands of real and synthetically generated satellite images with corresponding poses provided as labels. It can be downloaded at the link below.

https://zenodo.org/records/6327547
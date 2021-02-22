# Manjaro ARM Sway Profile

[![prerelease_build_sway](https://github.com/manjaro-arm-community/sway-images/actions/workflows/prerelease_build_sway.yaml/badge.svg)](https://github.com/manjaro-arm-community/sway-images/actions/workflows/prerelease_build_sway.yaml)
[![release_build_sway](https://github.com/manjaro-arm-community/sway-images/actions/workflows/release_build_sway.yaml/badge.svg)](https://github.com/manjaro-arm-community/sway-images/actions/workflows/release_build_sway.yaml)

## description

Release Branch for Manjaro ARM Sway profile images

## where can I download an image?

Images are build and uploaded in a relatively regular interval to [github releases](https://github.com/manjaro-arm-community/sway-images/releases)

## sources

- [image profile](https://github.com/manjaro-arm-community/arm-profiles)

## building

1. check out the arm-profiles
2. `sudo buildarmimg -d $DEVICE -e $EDITION -b $BRANCH -v $VERSION` 

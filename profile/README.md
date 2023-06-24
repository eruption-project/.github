![Eruption logo](assets/eruption.webp)

![License](https://img.shields.io/github/license/X3n0m0rph59/eruption?style=flat-square)
![Stars](https://img.shields.io/github/stars/X3n0m0rph59/eruption?style=flat-square)
![Crates.io](https://img.shields.io/crates/v/eruption-sdk?style=flat-square)
![Downloads](https://img.shields.io/crates/d/eruption-sdk?style=flat-square)

[![Continuous integration](https://github.com/eruption-project/eruption/actions/workflows/rust.yml/badge.svg?branch=unified-canvas)](https://github.com/eruption-project/eruption/actions/workflows/rust.yml)
[![Copr build status](https://copr.fedorainfracloud.org/coprs/x3n0m0rph59/eruption/package/eruption/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/x3n0m0rph59/eruption/package/eruption/)

<div align="center">
  <br></br>
  <a href="https://www.gnu.org/">
    <img src="assets/GPLv3_Logo.svg" height="50" alt="GPLv3 logo" />
  </a>&nbsp;&nbsp;
  <a href="https://www.rust-lang.org/">
    <img src="assets/rustacean-orig-noshadow.svg" height="50" alt="Rustacean logo" />
  </a>&nbsp;&nbsp;
  <a href="https://kernel.org/">
    <img src="assets/tux.svg" height="50" alt="Linux Tux" />
  </a>&nbsp;&nbsp;
  <a href="https://www.khronos.org/">
    <img src="assets/vulkan.svg" height=50 alt="Vulkan" />
  </a>
  <br></br>
</div>

## Eruption - Realtime RGB LED Software for Linux

A Linux user-mode input and RGB LED driver for keyboards, mice and other devices

For a list of recent news and noteworthy changes, please refer to [CHANGES.md](https://github.com/eruption-project/eruption/blob/master/CHANGES.md)

### Image and Video Gallery

[![Eruption Video](https://img.youtube.com/vi/ig_71zg14nQ/0.jpg)](https://www.youtube.com/watch?v=ig_71zg14nQ)

## Device Compatibility

### Keyboards

- [x] ROCCAT Vulcan 100/12x series keyboard (fully supported, stable)
- [x] ROCCAT Vulcan Pro TKL series keyboard (98% supported as of version `0.1.19`, testing)
- [ ] ROCCAT Vulcan TKL series keyboard (work-in-progress, as of version `0.1.20`, experimental, untested)
- [ ] ROCCAT Vulcan Pro series keyboard (work-in-progress, as of version `0.1.20`, experimental, untested)
- [ ] ROCCAT Magma series keyboard (work-in-progress, as of version `0.1.23`, experimental)
- [ ] ROCCAT Pyro series keyboard (work-in-progress, as of version `0.5.0`, experimental)
- [ ] Corsair Strafe Gaming Keyboard (non-RGB/monochrome only, as of version `0.1.20`, experimental)

### Mice

- [x] ROCCAT Kone Pure Ultra (stable)
- [x] ROCCAT Burst Pro (as of version `0.1.20`, testing)
- [ ] ROCCAT Kain 100 AIMO (as of version `0.2.0`, experimental)
- [x] ROCCAT Kain 2xx AIMO (as of version `0.1.23`, testing)
- [ ] ROCCAT Kone XP (work-in-progress, as of version `0.2.0`, experimental)
- [ ] ROCCAT Kone Pro (work-in-progress, as of version `0.2.0`, experimental)
- [x] ROCCAT Kone Pro Air (work-in-progress, as of version `0.2.0`, testing)
- [ ] ROCCAT Kone Aimo (experimental)
- [ ] ROCCAT Kone Aimo Remastered (experimental)
- [ ] ROCCAT Kova AIMO (testing)
- [ ] ROCCAT Kova 2016 (as of version `0.1.23`, testing)
- [ ] ROCCAT Kone XTD (as of version `0.1.20`, experimental)

### Miscellaneous Devices

- [x] ROCCAT/Turtle Beach Elo 7.1 Air Wireless Headset (work-in-progress, as of version `0.1.23`, testing)
- [x] ROCCAT Sense AIMO XXL (as of version `0.1.23`, stable)
- [x] Adalight/Custom serial LEDs (testing)

Please see [DEVICES.md](https://github.com/eruption-project/eruption/blob/master/DEVICES.md) for further information

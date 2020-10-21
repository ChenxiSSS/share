#### Mac info
* OS: macOS Catalina 10.15.7;
* Config:
    * [iMac 27 (5K, 2020)](https://everymac.com/systems/apple/imac/specs/imac-core-i7-3.8-8-core-27-inch-retina-5k-2020-20-2-specs.html)
    * CPU: 3.8GHz 8-core Intel Core i7 10700K;
    * Mem: 8GB 2666MHz DDR4;
    * GPU: AMD Radeon Pro 5700 XT;
    * Vrm: 16 GB;
    * OpenCL: 1.2;
    * OpenGL: 4.1 ATI 3.10.18
* OSKAR:
    * Ver: 2.7.6;
    * Installation follows the official guide [here](https://github.com/OxfordSKA/OSKAR/releases/tag/2.7.6);
    * Simulation was done via cmd line;

#### Tests
Two point source simulations were tested. The skymodel can be found at [here](https://github.com/ChenxiSSS/share/tree/main/OSKAR/skymodel)
* Point source:
    * Init file: [sim_interferometer.f158.00.ini](https://github.com/ChenxiSSS/share/blob/main/OSKAR/iMac27/point-source/sim_interferometer.f158.00.ini)
    * Sim one log: [oskar_2020-10-13_024518.log](https://github.com/ChenxiSSS/share/blob/main/OSKAR/iMac27/point-source/oskar_2020-10-13_024518.log)
    * Sim two log: [oskar_2020-10-13_024529.log](https://github.com/ChenxiSSS/share/blob/main/OSKAR/iMac27/point-source/oskar_2020-10-13_024529.log)

One galactic diffuse simulation were tested. The skymodel is to large to be add here.
* Galactic gsync:
    * Init file: [sim_interferometer.f158.00.ini](https://github.com/ChenxiSSS/share/blob/main/OSKAR/iMac27/point-source/sim_interferometer.f158.00.ini)
    * Sim log: [oskar_2020-10-13_003548.log](https://github.com/ChenxiSSS/share/blob/main/OSKAR/iMac27/galactic/oskar_2020-10-13_003548.log)

#### Previous tests
TBA

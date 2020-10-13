#### Mac info
* OS: macOS Catalina 10.15.6;
* Config:
    * [iMac 21.5 (4K, Late 2015)](https://everymac.com/systems/apple/imac/specs/imac-core-i5-3.1-21-inch-aluminum-retina-4k-late-2015-specs.html)
    * CPU: 3.1 GHz Quad-Core Intel Core i5 5675R;
    * Mem: 16 GB 1867 MHz DDR3;
    * GPU: Intel Iris Pro 6200;
    * Vrm: 1536 MB;
    * OpenCL: 1.2;
* OSKAR:
    * Ver: 2.7.6;
    * Installation follows the official guide [here](https://github.com/OxfordSKA/OSKAR/releases/tag/2.7.6);
    * Simulation was done via cmd line;

#### Tests
Two point source simulations were tested. The skymodel can be found at [here](https://github.com/ChenxiSSS/share/tree/main/OSKAR/skymodel)
* Point source:
    * Init file: [sim_interferometer.f158.00.ini](https://github.com/ChenxiSSS/share/blob/main/OSKAR/iMac21.5/point-source/sim_interferometer.f158.00.ini)
    * Sim one log: [oskar_2020-10-12_211112.log](https://github.com/ChenxiSSS/share/blob/main/OSKAR/iMac21.5/point-source/oskar_2020-10-12_211112.log)
    * Sim two log: [oskar_2020-10-12_211230.log](https://github.com/ChenxiSSS/share/blob/main/OSKAR/iMac21.5/point-source/oskar_2020-10-12_211230.log)
One galactic diffuse simulation were tested. The skymodel is to large to be add here.
* Galactic gsync:
    * Init file: [sim_interferometer.f158.00.ini](https://github.com/ChenxiSSS/share/blob/main/OSKAR/iMac21.5/point-source/sim_interferometer.f158.00.ini)
    * Sim log: [oskar_2020-10-12_211702.log](https://github.com/ChenxiSSS/share/blob/main/OSKAR/iMac21.5/galactic/oskar_2020-10-12_211702.log)

#### Mac info
* OS: macOS Mojave 10.14.3;
* Config:
    * [MacPro (transhcan, late 2013)](https://everymac.com/systems/apple/mac_pro/specs/mac-pro-quad-core-3.7-xeon-e5-gray-black-cylinder-late-2013-specs.html)
    * CPU: 3.7GHz Quad-Core Intel Xeon E5 1620v2 ;
    * Mem: 64 GB 1866 MHz DDR3 ECC;
    * GPU: 2 x MD FirePro D300;
    * Vrm: 2 GB GDDR5 per GPU;
    * OpenCL: 1.2;
    * OpenGL: 2.1 ATI 2.410
* OSKAR:
    * Ver: 2.7.6;
    * Installation follows the official guide [here](https://github.com/OxfordSKA/OSKAR/releases/tag/2.7.6);
    * Simulation was done via cmd line;

#### Tests
Two point source simulations were tested. The skymodel can be found at [here](https://github.com/ChenxiSSS/share/tree/main/OSKAR/skymodel)
* Point source:
    * Init file: [sim_interferometer.f158.00.ini](https://github.com/ChenxiSSS/share/blob/main/OSKAR/MacPro/point-source/sim_interferometer.f158.00.ini)
    * Sim one log: [oskar_2020-10-13_185902.log](https://github.com/ChenxiSSS/share/blob/main/OSKAR/MacPro/point-source/oskar_2020-10-13_185902.log)
    * Sim two log: [oskar_2020-10-13_185922.log](https://github.com/ChenxiSSS/share/blob/main/OSKAR/MacPro/point-source/oskar_2020-10-13_185922.log)

One galactic diffuse simulation were tested. The skymodel is to large to be add here.
* Galactic gsync:
    * Init file: [sim_interferometer.f158.00.ini](https://github.com/ChenxiSSS/share/blob/main/OSKAR/MacPro/point-source/sim_interferometer.f158.00.ini)
    * Sim log: [oskar_2020-10-13_194636.log](https://github.com/ChenxiSSS/share/blob/main/OSKAR/MacPro/galactic/oskar_2020-10-13_194636.log)


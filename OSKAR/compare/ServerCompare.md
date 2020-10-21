## Computation Time Table
| Server        | Computation Time | Write Time | Speed | GPU Model                    | VRAM         | No. of SP | Base/Boost Freq |
| ------------- | ----------------:| ----------:| ----- | ---------------------------- | ------------:| ---------:| ---------------:|
| Xray          | 2081.559 s       | 9.895 s    | 7.285 | NVIDIA GeForce GTX 1080 Ti   | 11 GB GDDR5X | 3584      | 1481/1582 MHz   |
| No-one        | 2683.140 s       | 8.130 s    | 5.651 | 2 x NVIDIA Tesla K40         | 12 GB GDDR5  | 2880      | 745/876 MHz     |
| iMac 27       | 1568.641 s       | 5.114 s    | 9.667 | AMD Radeon Pro 5700 XT       | 16 GB GDDR6  | 2560      | 1243/1500 MHz   |
| MacPro        | 3073.503 s       | 9.060 s    | 4.934 | 2 x AMD FirePro D300         | 2 GB GDDR5   | 1280      | 850/1270 MHz    |
| iMac 21.5     | 15163.754 s      | 7.508 s    | 1.000 | Intel Iris Pro Graphics 6200 | 1536 MB      | 384       | 300/1100 MHz    |

## Context
* iMac 27 is currently the fast server, it is:
    * 33% faster than Xray;
    * 71% faster than no-one;
    * 96% faster than MacPro;
    * 967% faster than iMac 21.5;
* MacPro's duo FirePro D300 is suprisingly fast, considering that:
    * Xray is only 48% faster than it (previous tests suggest it has around 70% - 80% speed of the Xray's);
    * no-one is only 14% faster than it;

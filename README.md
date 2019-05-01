| ![](https://user-images.githubusercontent.com/30758521/57000822-5b68e680-6b83-11e9-99f0-124f72d43aec.jpg) |
|:--:|
| **Using a microscope makes fabrication significantly easier** |

| Testing each wire         | test| test |
|:-------------------------:|:-:|:-:|
| ![](https://user-images.githubusercontent.com/30758521/57000674-bea64900-6b82-11e9-8caf-314c682fa448.jpg) | ![](https://user-images.githubusercontent.com/30758521/57000650-a8988880-6b82-11e9-867b-00b675534a66.jpg) | ![](https://user-images.githubusercontent.com/30758521/57000628-91599b00-6b82-11e9-9afd-2944c89f8057.jpg) |

| Testing each wire         | test| test | test| test|
|:-------------------------:|:-:|:-:|:-:|:-:|
| ![](https://user-images.githubusercontent.com/30758521/57000887-c1556e00-6b83-11e9-87f7-3f8726bd34f1.jpg) | ![](https://user-images.githubusercontent.com/30758521/57000901-d92cf200-6b83-11e9-9147-46048ac2e671.jpg) | ![](https://user-images.githubusercontent.com/30758521/57000917-e813a480-6b83-11e9-98e3-fc0a12386dec.jpg) | ![](https://user-images.githubusercontent.com/30758521/57000946-0a0d2700-6b84-11e9-9742-16b4033fa49e.jpg) | ![](https://user-images.githubusercontent.com/30758521/57000956-1a250680-6b84-11e9-9f30-89d0805680bb.jpg) |

| Testing each wire         | test| test | test| test|
|:-------------------------:|:-:|:-:|:-:|:-:|
| ![](https://user-images.githubusercontent.com/30758521/57001022-76882600-6b84-11e9-959f-081c3b0e3b61.jpg) | ![](https://user-images.githubusercontent.com/30758521/57001031-84d64200-6b84-11e9-980f-466f13d70095.jpg) | ![](https://user-images.githubusercontent.com/30758521/57001045-a3d4d400-6b84-11e9-8682-1ab9ced96787.jpg) | ![](https://user-images.githubusercontent.com/30758521/57001050-b3ecb380-6b84-11e9-8746-cfc8b3378d95.jpg) | ![](https://user-images.githubusercontent.com/30758521/57001064-c961dd80-6b84-11e9-8ae5-3da3eeb418cd.jpg) |

| Testing each wire         | test| test | test| test|
|:-------------------------:|:-:|:-:|:-:|:-:|
| ![](https://user-images.githubusercontent.com/30758521/57001083-e0083480-6b84-11e9-8282-cf52743e3277.jpg) | ![](https://user-images.githubusercontent.com/30758521/57001096-ec8c8d00-6b84-11e9-942f-1722e25eb470.jpg) | ![](https://user-images.githubusercontent.com/30758521/57001111-fadaa900-6b84-11e9-9016-cfad25bf9e65.jpg) | ![](https://user-images.githubusercontent.com/30758521/57001124-09c15b80-6b85-11e9-84d8-e7ebcdc5b2f1.jpg) | ![](https://user-images.githubusercontent.com/30758521/57001161-41300800-6b85-11e9-8024-94ba40b4db48.jpg) |

| Testing each wire         | test| test | test| test|
|:-------------------------:|:-:|:-:|:-:|:-:|
| ![](https://user-images.githubusercontent.com/30758521/57001217-73da0080-6b85-11e9-81e6-0a85f045ba62.jpg) | ![](https://user-images.githubusercontent.com/30758521/57001234-8a805780-6b85-11e9-8451-c4b7a1794d11.jpg) | ![](https://user-images.githubusercontent.com/30758521/57001253-aedc3400-6b85-11e9-9b72-5d5c221eaf81.jpg) | ![](https://user-images.githubusercontent.com/30758521/57001247-a257db80-6b85-11e9-9e0a-931dfcba4ec5.jpg) | ![](https://user-images.githubusercontent.com/30758521/57001260-b996c900-6b85-11e9-902f-cdae0c723537.jpg) |

# Testing Electrode Impredence
Before using the electrode(s) during surgery, it is imperitive to check that each wire has a good electrical connection and that they are not shorted together. We can quickly do this by testing the impedence of each wire. I prefer to not trim the electrode wires to the desired length until the day of the surgery, testing the electrodes before starting.

Remove the necessary adapter wires from the Drew Lab Thorlabs box next to the meter, and plug them in to the MicroProbes impedance tester.

| ![](https://user-images.githubusercontent.com/30758521/56999135-f1990e80-6b7b-11e9-88a9-267508c319cb.jpg) |
|:--:|
| **MicroProbes impendance tester** |

Make sure the *REFERENCE* pin is connected to the bath of 3M NaCl, and the *ELECTRODE* pin is connected to your desired electrode. Turn the meter on, and it should automatically jump to the right (max impedence). Depending on application, you can adjust the *RANGE*, but typically 500kΩ is enough for most of our applications. Attach the electrode the header of the adapter cable. If your electrode is already in headers, you can simply connect the headers to the headers on the adapter. It does not significantly change the impedance.

| Testing each wire         | Testing for shorts        | Meter reading  |
|:-------------------------:|:-------------------------:|:--------------:|
| ![](https://user-images.githubusercontent.com/30758521/56999450-2a85b300-6b7d-11e9-9186-07a5d9447b16.jpg) | ![](https://user-images.githubusercontent.com/30758521/56999424-088c3080-6b7d-11e9-8a31-2a879eb68dc0.jpg) | ![](https://user-images.githubusercontent.com/30758521/56999591-ca434100-6b7d-11e9-81e9-3e58ad18bd36.jpg) |

Test the wire impedance by dipping the electrode tip into the NaCl beaker. The meter reading should move to between 70 and 250 kΩ (@1 kHz) for the tungsten, and around 20-150 kΩ for the stainless steel. After testing one side, flip the headers around and test the other wire. If you do not get a good reading from *either* wire, do not use the electrode. To check for shorts between the two wires, remove the copper clamp from the NaCl beaker and attach it to the exposed header pin. This meter should not move from max - as we do not want current to pass between the two electrodes. If you do get a reading, make sure that there's no wet NaCl shorting the stereotrode tips, as a small amount of the salt water solution will (temporarily) complete the circuit. If the tips are dry and still read an impedance, do not use the electrode.

**When finished, turn off the meter. Re-cover the NaCl beaker with Parafilm. Put the *ELECTRODE* connectors/wires into the Drew Lab box. The *REFERENCE* connector and copper clamp can stay out and connected to the NaCl beaker.**

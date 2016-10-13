# Brice Mathieu

## Embedded Software Egnineer

Embedded software engineer with experience in architecting, designing, implementing, integrating and debugging real time applications for wireless communications and audio processing. Proficient in assembly and C programming languages, with extensive debugging skills and a strong understanding of compiler optimizations, hardware and firmware interactions, processor architectures, and real time OS concepts. Demonstrated ability to come up to speed quickly on tools and methods, with a noted inclination to enhance software build flows, reduce development times and improve code quality. Ideally suited to integrate into a collaborative team, lead technical projects, mentor fresh engineers and spur creativity and innovation in companies operating in the consumer electronics market.

## Professional Experience

### 10/2011 - Present: Systems and Architecture Engineer, Member of Technical Staff

#### [Freescale / NXP Semiconductors](https://www.nxp.com) (Austin, TX)

In the Vector Signal Processor Architecture (VSPA) team, part of the Digital Networking Group, I lead the software development activities for wireless products based on the VSPA architecture, with a strong focus on processes and quality.

- Designed and implemented, on existing silicon, a subset of the IEEE 802.11ax physical layer to demonstrate the efficiency and performance advantage of NXP vector processing architecture for next generation wireless communications.
- Led the software development effort for a multicore digital front end processor used in remote radio heads for cellular networks. Helped marketing and sales team with technical trainings and presentations, prepared demonstrations for Mobile World Congress and International Microwave Symposium events.
- Led the team transition from ClearCase to Git: learned Git from scratch through online tutorials and experiments with Github, Bitbucket and Gerrit, trained 8 engineers on command line Git, defined the workflow, and led the configuration management activities.

### 09/2009 - 09/2011: Principal Firmware Engineer, Member of Technical Staff

#### [ST-Ericsson](https://www.stericsson.com) (Austin, TX)

After working remotely for several months from France, I was transferred to the Austin office to develop software for 2.5G baseband processors, audio codecs and RF transceivers.

- Designed and implemented in CEVA-Teak assembly a software sequencer to program the audio codec in the E49xx baseband processor (used in Samsung mobile phone GT-C3300K) using control sequences interpreted by the DSP.
- Ported two algorithms from a previous design to the E49xx baseband processor to control the audio input gain: defined a new application programming interface in C, updated the fixed-point reference code and rewrote the CEVA-Teak assembly code using fixed-point arithmetic.
- Defined the firmware architecture of an analog baseband and RF processor to control a hardware audio codec and an RF transceiver from a digital baseband processor through I2C and DigRF 3G interfaces; specified the boot procedure and downloadable firmware image format, and designed a firmware trace module supporting SPI, DigRF and standard I/O streams.

### 08/2008 - 09/2009: Senior DSP Firmware Engineer

#### [ST-Ericsson](https://www.stericsson.com) (Sophia Antipolis, France)

After the merge of ST-NXP Wireless and Ericsson Modem business, I developed ARM and DSP software for 3GPP 3.5G and 2.5G baseband processors targeting low cost mobile phones.

- Documented the architecture of the channel processing firmware for a UMTS/HSPA baseband processor using UML sequence charts and collaboration diagrams.
- Specified functional and performance requirements for the real time kernel, peripheral drivers and SystemC cycle accurate model of the UMTS/HSPA modem subsystem.
- Wrote startup code, exception handlers, memory protection and cache management routines for the ARM Cortex-R4.
- Defined a generic application programming interface for audio encoders and decoders implemented in C for the E49xx processor, with extensions for codec-specific parameters.
- Integrated the HE-AAC v2 decoder and AAC-LC encoder in the E49xx DSP audio framework for the GSM/EDGE product line.

### 10/2006 - 08/2008: Senior DSP Firmware Engineer

#### [NXP Semiconductors](https://www.nxp.com) (Sophia Antipolis, France)

In the DSP Firmware Team, part of the Cellular Systems Group, I contributed to the maintenance and support of NXP’s 3GPP 2.5G and 3G baseband processors, until ST Microelectronics acquisition of NXP Wireless business.

- Maintained the DSP firmware of the GSM/GPRS/EDGE product line (PNX52xx and 65xx): corrected bugs reported by the Layer 1 software team, added features requested by customers and implemented changes required by 3GPP standard evolutions.
- Led the design and development of a hardware abstraction library for NXP Real16 DSP-based systems, composed of peripheral drivers, dynamic memory management and inter-processor communication services, used by the audio DSP in PNX67xx processors, and selected by HTC for the A3360 model and by Acer for beTouch E110/E120/E130 models.

### 03/2005 - 10/2006: Senior DSP Engineer

#### [VMTS](https://en.wikipedia.org/wiki/VK_Mobile) (Issy-les-Moulineaux, France)

VMTS was a startup aiming at providing baseband processors to the Korean cellphone manufacturer VK Mobile. As VK Mobile saw its market decrease, VMTS assets were acquired by MStar Semiconductors (now part of MediaTek).

- Provided technical expertise to Layer 1 software team about DSP subsystem programming, RF transceiver programming and receiver gain control algorithm.
- Implemented software tests, in CEVA-Teak assembly, to verify the DSP subsystem in RTL simulations and on target, brought up the DSP subsystem, fixed a parallel port driver interface to enable JTAG emulation and validated the GSM/GPRS channel encoders and decoders.

### 10/2000 - 03/2005: Digital Signal Processing Engineer

#### [WAVECOM](https://www.sierrawireless.com) (Issy-les-Moulineaux, France)

In the Digital Signal Processing team, I contributed to the development and commercialization of Wavecom’s first baseband processor. Wavecom was later acquired by Sierra Wireless.

- Developed cycle accurate models in C of a GMSK modulator, FIR filter, LMS filter, and CRC, ciphering and Viterbi accelerators, to extend the CEVA-Oak debugger with a complete simulation model of a DSP subsystem for a GSM/GPRS baseband processor.
- Coded functional tests, in CEVA-Oak assembly, to validate the implementation of the DSP peripherals in a baseband processor, used in RTL simulations and on target.
- Implemented a GPRS channel encoder/decoder, in CEVA-Oak assembly, and integrated the GSM/GPRS DSP firmware on target, for Wavecom’s first baseband processor, commercialized in the WISMO Pac P5186 module, and used by the HP iPaq h6300 Pocket PC and other mobile phones from various manufacturers.
- Defined and modeled with Matlab/Simulink a digital down converter for a GMSK/8-PSK transceiver, composed of a CIC filter to reduce the ΣΔ quantization noise, decimation and channelization filters, and an image rejection filter; provided functional specifications, bit accurate models in C, and test vectors to the Digital Design team. Co-authored 3 patents about RF impairments cancellation in low intermediate frequency digital receivers.

## Education

**M.S., Microelectronics and Signal Processing**  
*[Engineering School of the University of Paris Sud Orsay](http://www.u-psud.fr/en/university/schools/school-of-engineering.html), France*

## Skills and Competencies

- **Programming languages:** Assembly (ARM, CEVA, NXP Real/VSPA), C/C++, Matlab, Perl, Ruby, Tcl, Lua
- **Processor architectures:** ARM v6/v7, CEVA Oak/Teak/X16, NXP Real/VSPA
- **Development tools:** Assemblers, compilers, linkers, debuggers, profilers, NXP CodeWarrior Development Studio, ARM RealView Developer Studio, CEVA development tools, CodeSourcery CodeBench Lite, GNU GCC, GNU Make, Microsoft Visual Studio, Matlab/Simulink, CoWare Virtual Platform Analyzer, Eclipse, Cygwin/MinGW/MSYS environments
- **Software configuration management:** Git, Gerrit, Atlassian JIRA/Bitbucket, IBM Rational ClearCase/ClearQuest, Synchronicity DesignSync, SVN, CVS, Merant PVCS
- **Laboratory tools:** JTAG emulators, Rohde & Schwarz CMU200, HP 8922, Agilent 8960, RF signal generators, fading simulators, spectrum analyzers, logic analyzers

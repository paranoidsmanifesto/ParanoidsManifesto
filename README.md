# The Paranoid's Manifesto

Welcome to The Paranoid's Manifesto. This file defines the values of the Paranoid. After reading this file, please see the folders for in-depth guides on your journey for privacy. Enjoy.

### Abstract

todo: Abstract.

### Chapters
- [Terminology](#terminology)
- [Philosophy](#philosophy)
- [Justification](#justification)
- [Taking The Offensive](#taking-the-offensive)
- [Sections](#sections)
- [Contributing](#contributing)

<hr>

## Terminology

- Three-Letter Agency (TLA)
    - **Definition**
        - A name for a national or international regulatory agency that present to the public as protective of rights through enforcement of law, but commit questionable acts.
    - **Examples**
        - FBI (Federal Bureau of Investigation).
        - CIA (Central Intelligence Agency).
        - NSA (National Security Agency).

- Compromised
    - **Definition**
        - A device that contains backdoors on the hardware and/or software level.
    - **Examples**
        - Almost all Intel CPUs since 2008.
        - Almost all AMD CPUs since 2014.

- Free Software
     - **Definition**
        - Software that respects the user's freedom, allowing the user to perform any action on the software without restriction.
    - **Examples**
        - Parabola GNU/Linux-libre.
        - Hyperbola GNU/Linux-libre.

- Firmware Blob/Binary Blob
    - **Definition**
        - Proprietary (nonfree) firmware/software, which is available as obfuscated code or a binary executable, intended to serve a purpose, like a driver for a device.
    - **Examples**
        - BIOS on most systems.
        - Official drivers for GPUs.

- Backdoor
    - **Definition**
        - A mechanism that intends to allow unauthorized users to access and/or change information without the original user's knowledge or consent.
    - **Examples**
        - Intel Management Engine/Intel Manageability Engine.
        - AMD Secure Technology (Platform Security Processor).

- Personal-Identifying Information (PII)
    - **Definition**
        - Any de-anonymized information that allows an individual to be uniquely identified, either through direct or indirect means.
    - **Examples**
        - Social security number.
        - Street address.
        - Phone number.

- Fingerprint
    - **Definition**
        - Information that is collected about a device with the intent to uniquely identify it across the internet.
    - **Examples**
        - Google Analytics.

- Compartmentalization
    - **Definition**
        - Separation of information.
    - **Examples**
        - Creating a different email for every account.

- Privacy
    - **Definition**
        - The ability to seclude yourself and your information from surveillance.
    - **Examples**
        - Limiting the amount of accounts that you create in order to reduce data collection.

- Anonymity
    - **Definition**
        - The ability to seclude your identify from another, and maintain separate identities.
    - **Examples**
        - Using a fake name, address, and other information while chatting with someone.

- Security
    - **Definition**
        - Measures taken in order to maintain privacy and anonymity.
        - How you keep yourself safe from people and organizations with the intent of harm towards yourself or your family.
    - **Examples**
        - Using a program to remove bias from writing.
        - Putting a shatterproof glass film on all of your windows to delay unauthorized entry into your home.

- Surveillance
    - **Definition**
        - Observation of one or many people in order to build a profile based on their activities.
    - **Examples**
        - XKEYSCORE surveillance program.
        - The Five Eyes.

## Philosophy

### Abstract

Most individuals have interacted with an internet-facing device before, in which the device was most likely compromised. Regarding those same individuals, it is most definite that they are still interacting with compromised internet-facing devices. As a Paranoid, it is essential to adopt various values into one's everyday activites in order to minimize surveillance into communications and private activities. Unfortunately, in an age of surveillance capitalism, where TLA's harvest and aggregate individual personal data for their benefit, it is quite unlikely that one can achieve maximum privacy, security, or anonymity in a modern society. That does not mean that it is not important, which is why maximizing these concepts in one's daily life is vital to your own safety.

#### You Are Never Safe

You can never be completely safe from all insecurities. You can move to a remote island and be completely off the grid, but even then, you will be trading off personal safety for your privacy. You will never be able to achieve maximum secrecy in your everyday communications, but you are not prevented from taking measures to minimize intrusion into your activities.

Assuming an everyday person in an industrialized society, they will have a smartphone, a computer, a smart television, and a smart speaker. All of these devices share a few common similarities: their operating systems are closed-source, they have sensors, and they are manufactured by large corporations that report to the government. All of these convenient devices are compromised, intended for mass surveillance purposes. In order to keep yourself safe, you must take drastic action, destroying these devices if you can. If you are unable to destroy these devices and need to keep them, the minimum is to destroy the sensors on these devices, reduce attack surface and harden the device, and keep them completely off when they are not in use by unplugging them and removing the battery (if possible).

In order to protect yourself, you must free yourself from backdoors. Most, if not all modern devices contain backdoors both on the hardware level and the software level. The reason that these devices exist is for the user's convenience. The corporations harboring secrets from society has allowed these "convenient" devices to be normalized for everyday use. In order to retain your freedom, you must refrain from owning any of these devices, as you do not own the data on them. That is a multi-step process:

1. Get a minimal device that is completely open and libre.
2. Minimize your attack surface for any hardware backdoors on your device by only utilizing certain technologies, even if incompatible with many of your daily activities.
3. Refrain from installing any nonfree firmware blobs on your device. These are software backdoors.
4. Install only free software, and never run a binary without verifying integrity with PGP. When possible, compile the software from source.

* In an ideal world, free software is completely secure. Security is a spectrum, and while this publication takes it to the extreme, understand what your software is doing, and do not blindly trust it.

Binary blobs are used to allow a proprietary device work on a kernel. On a compromised desktop operating system like Windows or Mac OS, drivers are packaged along with the operating system and are also downloaded from the internet. This proves unsafe with a basic Man in the Middle attack, as a third party, like the TLAs or an independent hacker, can intercept the place where the blobs or ISO used for install are fetched and insert their own backdoors into it. While this basic attack can be mitigated with file integrity checks, it does not prevent the original signer of the binary to modify it for spying purposes. Unfortunately, binary blobs are usually not reversible without great efforts and knowledge. This means that the user is (usually unknowingly) letting potential backdoors into their system.

todo: Firmware blobs, hardware backdoors, phones, computers, operating systems, etc.

#### You Are Always Being Watched

todo: Five/Nine/Fourteen Eyes, mass surveillance programs, CCTV (gait, facial recognition, greyman, routine, bodily recognition), PII, device sensors, etc.

#### You Cannot Trust Anyone

todo: "Friends", politicians, family, coworkers, educators, partners, glowies, etc.

#### (If) You Cannot See It, You Do Not Own It

todo: SaaS, free software, DRM, etc.

#### (If) You Cannot Question It, It Is Propaganda

todo: Education, political messages, etc.

## Justification

todo: Why do we do this?

## Taking The Offensive

todo: How to reclaim your privacy, maintaining your anonymity, zero trust, etc.

## Sections

todo: Sections of the in-depth guides.

## Contributing

Please create a pull request if you would like to contribute. If you would like to mention a problem or would like another section/more depth on a section, please create an issue.
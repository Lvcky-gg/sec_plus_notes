# Boot Integrity

## Hardware root of trust

- security is based on trust
- the trust starts somewhere
  - Trusted Platform Module(TPM)
  - Hardware Security Module(HSM)
  - designed to be the hardware root of trust
- difficult to change or avoid

## Trusted Platform Module

- A specification for cryptographic functions
- Cryptographic processor
- Persistent Memory: comes with unique keys burned in during production
- versatile memory: storage keys, hardware configurations
- password protected

## Boot Integrity

- the attack on a system is constant
- attackers compromise a device
- the boot process is an amazing infection point
  - root kits run in kernal mode
  - have the same rights as OS

## UEFI BIOS Secure Boot

- secure boot
- UEFI BIOS protections
  - manufacturer's pub key
  - digital signature is checked during bios update
  - bios prevents unauthorized writes to the flash
- secure boot verifies the bootloader

## Trusted boot

- a bootloader verifies deigital signature of the OS kernal
- kernal verifies all of the other startup components
- Early Launch Anti-Malware starts
- checks every driver to see if its trusted
- windows wont load untrusted driver

## Measured Boot

- nothing on the computer has changed
- easy when its your computer
- UEFI stores a hash of firmware, boot drivers, and everything else needed
- remote attestation

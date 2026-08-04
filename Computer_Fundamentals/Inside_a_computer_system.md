# Inside a Computer System — Active Recall

**Module:** 2  
**Platform:** TryHackMe  
**Method:** Questions were AI-generated based on the completed lesson. All answers were written independently from memory before feedback or corrections were shown.

## Active Recall

### 1. What are the core components of a computer?

> The motherboard is like the skeletal or nervous system of the computer that connects all the components. The PSU supplies energy to the components, similar to a heart. The CPU executes instructions like a brain. The GPU translates information into pictures, similar to our visual cortex.
>
> I/O devices send outside information to the CPU, similar to our senses. The network adapter allows communication with other computers or systems, similar to our vocal cords. RAM handles short-term storage, while SSDs and HDDs handle long-term storage.

**Result:** Mostly correct—input and output devices perform different directions of communication.

### 2. What happens during the boot sequence?

> First, the computer initializes the firmware responsible for managing startup—the BIOS or UEFI. The firmware starts by initializing hardware components such as the RAM and SSD/HDD. It then checks the boot drives for the operating system before handing control to the OS.

**Result:** Partially correct—the overall process was understood, but POST, boot-device selection, and the bootloader needed to be distinguished.

### 3. How are UEFI and BIOS related?

> UEFI is the improved version of BIOS that comes with things like faster boot times.

**Result:** Mostly correct—both are startup firmware, with UEFI being the modern replacement for BIOS.

### 4. What is the difference between initialization and POST?

> Initializing the hardware starts it up, but POST is responsible for making sure all hardware is present and sending an alarm if any components are missing.

**Result:** Mostly correct—POST also checks that required hardware is configured correctly and functioning.

### 5. What does the bootloader do?

> The bootloader hands control over from the firmware to the operating system by transferring it into RAM.

**Result:** Mostly correct—the bootloader loads the OS from storage into RAM, after which UEFI transfers control to the OS.

### 6. Why must the OS be loaded again after shutdown?

> The copy of the OS held in RAM no longer exists because RAM does not persist when the computer is shut off. The SSD/HDD allows data to persist, so the copy of the OS there remains. The bootloader must run again because the OS needs to be placed back into working memory.

**Result:** Correct.

## Corrections Retained

- The boot sequence is: power → firmware → POST → boot-device selection → bootloader → operating system.
- The bootloader loads the OS from persistent storage into RAM.
- RAM is volatile working memory, while an SSD/HDD provides non-volatile storage.

**Final understanding:** 9/10 — Ready to move on
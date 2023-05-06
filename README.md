<p align="center">
    <img src="https://github.com/Robin-DUBREUIL/opengate/raw/A/3D_render.png" width="360"/>
</p>
<h1 align="center">Type A</h1>
<br/>

## How to get yours

The OpenGate type A is designed for performance and reliability, with modern circuit board manufacturing processes in mind, so is not easy to build at home.

When the very fist release will be considered production ready, batches will be manufactured and sold commercially by the ![project author](https://github.com/Robin-DUBREUIL) through a dedicated website. This will guarantee the best quality possible at a fair price for everyone.
In the meantime, you can reach ![the author](https://github.com/Robin-DUBREUIL) if you are interested to get your hands on a prototype, or pre-order your production grade unit.

As this project is licensed under the CC-BY-NC-SA license, you can request a quote from any PCBA manufacturer in order to obtain your OpenGate, as long as you do not plan to use it commercially. All the required files are freely available in the repository. This option can be expensive for a single unit, and does not guarantee the quality or compliance of your OpenGate. Also, this option does not help keep this project alive: if you absolutely want to use it, consider supporting our project by donating, contributing or promoting it.

<br/>

# OpenGate: Memory Card to SD Adapter for PlayStation 2
[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

## Introduction

OpenGate is a memory card to SD adapter designed for PlayStation 2 that provides safe and reliable SD card support, with major improvements over existing solutions in the market. It ensures compatibility with a wide range of SD cards, complies with the SD spec for voltage regulation, and is designed to fit right into the original memory card case.

## Disclaimer

The OpenGate project, its name, artworks, and contributors are not related to or endorsed by Sony Corporation or any of its subsidiaries or affiliates. The project is provided as-is, with no warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement.

The OpenGate project and its creators do not condone piracy in any way. The project is intended for legal and legitimate purposes only, such as backing up game saves and game software that the user owns. The OpenGate adapter is not intended to enable or facilitate the use of unauthorized copies of copyrighted material, including games and other software.

It is the responsibility of the user to ensure that any use of the OpenGate adapter complies with applicable laws and regulations. The creators of the OpenGate project disclaim any liability for any illegal or unauthorized use of the adapter.

The OpenGate project and its creators are not affiliated in any way with the Free McBoot or OPL projects, nor with their respective creators. The use of OpenGate with Free McBoot and OPL is at the user's own risk. The OpenGate project is not responsible for any damage caused by the use of Free McBoot or OPL, or any other software used with OpenGate.

Please note that modifying or tampering with your PlayStation 2 console or its software may void your warranty and may cause damage to the console or other equipment. The OpenGate project and its creators are not responsible for any damage to your console or equipment resulting from the use of the OpenGate adapter or any other modifications to your console.

By using the OpenGate adapter, you acknowledge and agree to these terms and conditions. If you do not agree to these terms and conditions, you should not use the OpenGate adapter.

## Features

- Safe and compatible: OpenGate regulates the 3.5V delivered by the PS2 to 3.3V to power the SD card, complying with the SD spec. This ensures the adapter is safe and reliable, and protects your SD card from potential hazards.
- Wide compatibility: OpenGate follows the SD spec recommendations regarding pullups and line resistors, ensuring compatibility with a wide range of SD cards.
- EMI/RFI emissions: OpenGate is designed with a tight length matching of the data lines and uses ground planes to reduce EMI/RFI emissions. This ensures a high-quality signal and minimizes interference with other devices.
- Compact design: OpenGate is designed to fit right into an original memory card case, with a simple slot mod to insert the SD card.
- Open source, free use of the design for noncommercial purposes: OpenGate is licensed under CC-BY-NC-SA, allowing DIY enthusiasts, makers and modders to use, modify, and distribute the design files. To use it beyond this scope, feel free to contact ![the author](https://github.com/Robin-DUBREUIL).

## How to use

Using OpenGate is simple and straightforward. Follow these steps:

1. Open an original PlayStation 2 memory card case.
2. Remove the original memory card module.
3. Insert the OpenGate board and mark the slot to be cut in front of the SD card socket.
4. Remove the OpenGate board and cut the slot using a hobby knife.
5. Insert the OpenGate board and re-assemble the case.
6. Insert your prepared SD card into the OpenGate adapter and plug the adapter into a memory card slot.
7. Power on the PlayStation 2 and enjoy your games with the storage capacity of the SD card.

If you need further instructions, get to know the Free McBoot and Open PS2 Loader (OPL) projects: see [FAQ](#FAQ) for more.

## Contributing

OpenGate is an open-source project, and we welcome contributions from the community. You can contribute by reporting issues, suggesting improvements, or submitting pull requests on our [GitHub repository](https://github.com//Robin-DUBREUIL/opengate/).

## Coming Soon

We are working on 3D files of a custom shell for a direct fit case. Stay tuned for updates!

## License

OpenGate is licensed under CC-BY-NC-SA, which allows hobbyists and modders to use, modify, and distribute the design files freely, as long as they give credit to the original creator and share the derivative work under the same license. Commercial use is hereby not permitted freely, feel free to contact ![the author](https://github.com/Robin-DUBREUIL) to discuss the terms of uses beyond the scope of the CC-BY-NC-SA licence.
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]


[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## FAQ

### What are Free McBoot and OPL, and how does OpenGate fit in?

Free McBoot is a software exploit that allows users to run homebrew and backup software on a PlayStation 2 console without the need for a modchip or swap magic disc. It is installed on a PlayStation 2 memory card and can be used to launch various programs, including the Open PS2 Loader (OPL).

[Open PS2 Loader (OPL)](https://github.com/ps2homebrew/Open-PS2-Loader) is a homebrew application that allows users to play backup copies of PlayStation 2 games from a "fat" PS2 embedded IDE Hard drive, a USB storage device or a network share. It is compatible with most PlayStation 2 models and supports a wide range of games.

However, on newer PlayStation 2 models that lack an IDE HDD interface, using OPL with USB 1.1 or network drives can be slow and cumbersome. This is where OpenGate comes in. It provides a high-speed interface for SD cards on the PlayStation 2, making it possible to use SD cards with OPL on newer consoles. With OpenGate, users can enjoy faster load times and smoother gameplay, while still benefiting from the versatility and convenience of OPL and Free McBoot.

OpenGate is also a smart choice for "fat" PlayStation 2, as IDE hard drives are getting old and compatible adapters aren't widely available. Also micro SD cards are quiet, compact and reactive: everything an IDE drive isn't.

### Why "OpenGate"?

The name "OpenGate" was chosen for several reasons. First, it is a reference to the "MagicGate" mark that is present on all PlayStation 2 memory cards. By naming the adapter "OpenGate," we wanted to create a connection between our product and the original PlayStation 2 memory cards. In addition, the word "Open" was chosen to reflect the fact that the project is open source, allowing anyone to use, modify, and distribute the design files. Finally, the word "Open" evokes a sense of freedom, as OpenGate allows you to use virtually any SD card that you choose, reducing both compatibility issues and potential hazards.

### Does it supports both TF cards and micro SD cards ?

In a word: Yes. In the early 2000s, a company called SanDisk developed a new type of memory card called TransFlash (TF) that was designed to be smaller and more compact than existing memory card formats. In 2005, SanDisk collaborated with the SD Card Association to develop a new standard based on TransFlash, which became known as the micro SD card. Today, micro SD cards are the de facto standard for removable storage in mobile devices, digital cameras, and other consumer electronics. Despite the name change from TF to micro SD, the two formats are functionally identical, with the same pinout, electrical interface, and command set. This means that OpenGate is compatible with both TF cards and micro SD cards, giving you a wide range of options for expanding the storage capacity of your PlayStation 2.

### Why doesn't OpenGate support fullsize SD cards?

OpenGate was designed specifically to support the micro SD card format, which is now the industry standard for removable storage. Fullsize SD cards, while still in use in some devices, are becoming a deprecated format with no true advantage over micro SD. By focusing on micro SD support, we can ensure that OpenGate remains plug and play with the latest and most popular SD cards on the market, and provide the best possible user experience.

# Multilingual Keyboard Layout

A layout that makes it possible to write in multiple languages without switching between them.
It also has a lot of useful symbols.

It was originally private for a few years, updated whenever I needed new symbols.
I finally decided to make it public, and I'm planning to keep on using it as my daily keyboard layout.  
If you think there's something missing, please feel free to make an issue,
but I cannot promise a fast response. :sweat_smile:

# Table of contents

- [Multilingual Keyboard Layout](#multilingual-keyboard-layout)
- [Table of contents](#table-of-contents)
- [Support](#support)
  - [Languages](#languages)
    - [By total speakers](#by-total-speakers)
      - [Romanizations](#romanizations)
    - [Full list](#full-list)
  - [Special characters](#special-characters)
- [How to build and install](#how-to-build-and-install)
  - [Prerequisites](#prerequisites)
  - [Building](#building)
    - [Building the layout using MSKLC](#building-the-layout-using-msklc)
    - [Building the layout manually](#building-the-layout-manually)
  - [Installation](#installation)
    - [Installation through the provided binaries](#installation-through-the-provided-binaries)
    - [Installation manually](#installation-manually)
  - [Usage](#usage)
  - [Uninstalling](#uninstalling)
    - [Uninstalling the layout through `Programs and Features`](#uninstalling-the-layout-through-programs-and-features)

# Support

## Languages

It only supports the Latin script and a lot of combining diacritics.
Standard letters without diacritics are omitted for the sake of clarity.

### By total speakers

|   Language | Supported letters                                              | Missing letters | Support |
| ---------: | -------------------------------------------------------------- | --------------- | :-----: |
|    English |                                                                |                 |  Full   |
|    Spanish | Áá, Éé, Íí, Ññ, Óó, Úú, Üü                                     |                 |  Full   |
|     French | Àà, Ââ, Ææ, Çç, Éé, Èè, Êê, Ëë, Îî, Ïï, Ôô, Œœ, Ùù, Ûû, Üü, Ÿÿ |                 |  Full   |
| Portuguese | Áá, Ââ, Ãã, Àà, Çç, Éé, Êê, Íí, Óó, Ôô, Õõ, Úú                 |                 |  Full   |
| Indonesian |                                                                |                 |  Full   |
|     German | Ää, Öö, Üü, ẞß                                                 |                 |  Full   |

#### Romanizations

| Language | Romanization | Supported letters  | Missing letters | Support |
| -------: | ------------ | ------------------ | --------------- | :-----: |
| Japanese | Hepburn      | Āā, Ēē, Īī, Ōō, Ūū |                 |  Full   |

### Full list

The full list of languages with the Latin script has to be finished.

|             Language | Supported letters                                              | Missing letters                           | Support |                                                                                                              |
| -------------------: | -------------------------------------------------------------- | ----------------------------------------- | :-----: | ------------------------------------------------------------------------------------------------------------ |
|             Acehnese | Éé, Èè, Ëë, Ôô, Öö                                             |                                           |  Full   |                                                                                                              |
|                 Afar |                                                                |                                           |  Full   |                                                                                                              |
|            Afrikaans | Áá, Ää, Éé, Èè, Êê, Ëë, Íí, Îî, Ïï, Óó, Ôô, Öő, Úú, Ûû, Üü, Ýý |                                           |  Full   |                                                                                                              |
|             Albanian | Ëë, Çç                                                         |                                           |  Full   |                                                                                                              |
|            Aragonese | Áá, Éé, Íí, Óó, Úú, Üü                                         |                                           |  Full   |                                                                                                              |
|             Asturian | Ññ                                                             | (Ḥḥ, Ḷḷ)                                  |  Major  | Dialectal letters with underdots unsupported                                                                 |
|               Aymara | Ää, Ïï, Üü                                                     |                                           |  Full   |                                                                                                              |
|          Azerbaijani | Çç, Əə, Ğğ, İi, Öö, Şş, Üü                                     | Iı                                        | Partial | Small dotless i unsupported                                                                                  |
|                  Bai |                                                                |                                           |  Full   |                                                                                                              |
|            Banjarese | Éé                                                             |                                           |  Full   |                                                                                                              |
|               Basque | Çç, Üü, Ññ                                                     |                                           |  Full   |                                                                                                              |
| Belarusian (Łacinka) | Ćć, Čč, Łł, Ńń, Śś, Šš, Ŭŭ, Źź, Žž                             |                                           |  Full   |                                                                                                              |
|               Betawi | Ññ, ʔ                                                          |                                           |  Full   |                                                                                                              |
|               Berber | Čč                                                             | Ḍḍ, Ɛɛ, Ǧǧ, Ɣɣ, Ḥḥ, Řř, Ṛṛ, Ṣṣ, Ṭṭ, Ẓẓ, ʷ | Limited | Underdot unsupported<br>Latin epsilon unsupported<br>Caron support limited<br>Labialization mark unsupported |
|              Bislama |                                                                |                                           |  Full   |                                                                                                              |
|             Boholano |                                                                |                                           |  Full   |                                                                                                              |
|              Bosnian | Ćć, Čč, Šš, Žž                                                 | Đđ                                        | Partial | Stroke unsupported                                                                                           |
|               Breton | Ââ, Êê, Îî, Ôô, Ûû, Ùù, Üü, Ññ                                 |                                           |  Full   |                                                                                                              |
|              Catalan | Àà, Éé, Èè, Íí, Ïï, Óó, Òò, Úú, Üü, Çç                         |                                           |  Full   |                                                                                                              |
|              Cebuano |                                                                |                                           |  Full   |                                                                                                              |
|             Chamorro | Ññ                                                             | ʼ, Åå,                                    | Limited | Modifier apostrophe letter unsupported<br>Overring unsupported                                               |
|             Cherokee |                                                                |                                           |  Full   |                                                                                                              |
|              Cornish |                                                                |                                           |  Full   |                                                                                                              |
|             Corsican |                                                                |                                           |  Full   |                                                                                                              |
|             Croatian | Ćć, Čč, Šš, Žž                                                 | Đđ                                        | Partial | Stroke unsupported                                                                                           |
|                 Cree | â, ā, ð, ê, ē, î, ī, ñ, ô, ō, š, ý                             |                                           |  Full   |                                                                                                              |
|                Czech | Áá, Čč, Éé, Íí, Óó, Úú, Ýý, Žž                                 | Ďď, Ňň, Řř, Šš, Ťť, Ůů                    | Limited | Caron support limited<br>Overring unsupported                                                                |
|               Danish | Ææ                                                             | Øø, Åå                                    | Limited | Stroke unsupported<br>Overring unsupported                                                                   |

[ to be continued ]

## Special characters

- [Whitespace](whitespace.md)

[ to be continued ]

# How to build and install

Pre-built binaries are planned to be provided in the future in the
[Releases](/TheChilliPL/multilin/releases) section.

Then, you'll be able to download it and install it by following the steps in the
[Installation](#installation) section.

## Prerequisites

You need to have MSKLC 1.4 installed. You can download it from [here][MSKLC].  
Tested only on Windows 11, but should work on Windows 10 and earlier as well.
MSKLC is a quite archaic piece of software, but Microsoft doesn't seem to have
any plans to update it, so it'll have to do.

[MSKLC]: https://www.microsoft.com/en-us/download/details.aspx?id=102134

## Building

### Building the layout using MSKLC

1. Clone the repository.
2. Open the [`multilingual.klc`](multilingual.klc) file using MSKLC.
3. Go to `Project`→`Build DLL and Setup Package`.
4. Follow the on-screen instructions.
5. It should eventually get exported to the directory showed in the dialog box.
   By default, it's `Documents\multilin`.

> :warning: **Warning:**
> Building will fail if the layout is already installed. You need to uninstall
> it first using [the provided steps](#uninstalling) to build it.

> :warning: **Warning:**
> Building the layout using MSKLC will fail if the appdata directory is not set
> to the default path. In this case, you have to build the layout manually
> using the method below.

### Building the layout manually

MSKLC provides several CLI tools in its `/bin/i386` directory. To build the
layout manually, you need to use the `kbdutool` tool.

```cmd
kbdutool.exe -wu <layout path>
```

where `-w` displays extended warnings, `-u` forces Unicode support.

It builds the DLL for x86 by default (or if you pass the `-x` flag). You can override
this behavior by using `-i` for IA64, `-m` for AMD64, `-o` for WOW64, or you can
use `-s` to generate C source files without building them.

## Installation

### Installation through the provided binaries

1. Go to the directory with the binaries. It should contain `setup.exe`,
   several `.msi` files, and directories with `.dll` files.
2. The easiest method to install the layout is to run `setup.exe` and follow the
   on-screen instructions. Alternatively, you can run the `.msi` file manually,
   for your architecture. Manual installation with `.dll` files is possible, but
   not recommended.
3. After the installation is complete, you need to restart your computer for the
   changes to take effect.

> :warning: **Warning:**
> Installation will fail if the layout is already installed. You need to uninstall
> it first using [the provided steps](#uninstalling) to update it.

> :warning: **Warning:**
> Installation binaries provided by MSKLC seem to not work correctly if the appdata
> directory is not set to the default path. In this case, you have to install the
> layout manually using the `.dll` files.

### Installation manually

To install the layout manually, you need to copy the `.dll` files to the
`C:\Windows\System32` directory and—if you haven't done it yet—add the layout
to the registry key `HKLM\System\CurrentControlSet\Control\Keyboard Layouts`.

## Usage

1. Go to `Settings`→`Time & Language`→`Language & Region`.
2. Under the `Language` section, click on the three dots next to the language
   you want to add the layout to. Alternatively, you can click on `Add a
language` and add the language you want to add the layout to.
3. Click on `Language options`.
4. Under the `Keyboards` section, click on `Add a keyboard`.
5. Look for `Multilingual` and click on it.
6. Optionally, you can remove the default keyboard layout for the language by
   clicking on the three dots and clicking on `Remove`.
7. Restart your computer for the changes to take effect.
8. You should now be able to switch to the layout by pressing `Win`+`Space` and
   use it.

## Uninstalling

### Uninstalling the layout through `Programs and Features`

1. Go to `Settings`→`Apps`→`Installed apps`.
2. Look for `Multilingual` on the list or search for it using the search box.
3. Click on the three dots next to it and click on `Uninstall`.
4. Follow the on-screen instructions.

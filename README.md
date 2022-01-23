# Violet Exoplanet

A flat, minimal foobar2000 ColumnsUI theme.

![A preview screenshot of foobar2000 with the Violet Exoplanet theme.](previews/violet_exoplanet-01.png)

## Description

Violet Exoplanet has three goals as a theme:

* Be easy on the eyes and/or reduce eye-strain
* Create a flat, aesthetically pleasing UI
* Optimize UX via panel configurations

This theme utilizes a handful of custom title and style scripts. These scripts are built into `violet_exoplanet.fcl`, but I will provide each script for convenience (TODO).

Note: I have used the custom Windows 10 theme, ["Adapta," by niivu](https://www.deviantart.com/niivu/art/Adapta-675581778) on Deviant Art. This theme is responsible for the coloration of the titlebar and scrollbars, among other things.

## Getting Started

### Packages

These packages are required for all panels to function correctly. They can all be found in `violet_exoplanet\packages`.

* [Columns UI (foo_ui_columns)](https://www.foobar2000.org/components/view/foo_ui_columns)
* [Musical Spectrum (foo_musical_spectrum)](https://hydrogenaud.io/index.php/topic,97404.0.html)
* [OpenLyrics (foo_openlyrics)](https://www.foobar2000.org/components/view/foo_openlyrics)
* [Playlist Organizer (foo_plorg)](https://www.foobar2000.org/components/view/foo_plorg)
* [Playback Statistics (foo_playcount)](https://www.foobar2000.org/components/view/foo_playcount)
* [Waveform Minibar (foo_wave_minibar_mod)](https://www.foobar2000.org/components/view/foo_wave_minibar_mod)

### Installation

Install all components before installing the theme. If you have an existing theme, you should export it before going forward.

#### Components

Note: it is highly recommended to install components using fb2k's component manager. They will work if put into the program's component folder, but this prevents fb2k from automatically updating them.

* Download the components from the links provided above.
>
* foobar2000 may attempt to automatically install it but, if not, you can use the built-in component manager.
>
* With foobar2000 open, navigate to the component manager.
    * **Library** > **Configure** > **Components**
>
* Click the "Install..." button.
>
* Navigate to your download folder and double-click the components to install.
>
* When every component has been installed, click "Apply."
>
* foobar2000 will need to restart to finish the installation.

#### Layout

* Clone repository to desired location, or to the fb2k installation folder.
    * Default installation path is `\Program Files (x86)\foobar2000`.
>
* With foobar2000 open, navigate to Columns UI's "Main" settings.
    * **Library** > **Configure** > **Display** > **Columns UI** > **Main**
>
* Click the "Import configuration..." button.
>
* Navigate to `violet_exoplanet\layout` and import `violet_exoplanet.fcl`.

## Scripts

[TODO]

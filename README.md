
<div align="center">
  <img src="data/icons/io.github.mrvladus.List.svg" width="128" height="128">

  # Errands

  Manage your tasks

  ![CI](https://github.com/mrvladus/List/actions/workflows/CI.yml/badge.svg)

  <img src="screenshots/main.png" width="360">
</div>

## Features
- Add, remove, edit tasks and sub-tasks
- Mark task and sub-tasks as completed
- Add accent color for each task
- Drag and Drop support

## Install
Errands is available as a Flatpak on Flathub:

<a href="https://flathub.org/apps/details/io.github.mrvladus.List"><img width='240' alt='Download on Flathub' src='https://dl.flathub.org/assets/badges/flathub-badge-en.png'/></a>
## Building using GNOME Builder
1. Install [GNOME Builder](https://flathub.org/apps/org.gnome.Builder).
2. Click "Clone Repository" with `https://github.com/mrvladus/List.git` as the URL.
3. Click on the build button at the top.

## Building using build scripts
Make sure you have `git` and `flatpak` installed and `Flathub` is setup
1. Clone repo:
```sh
git clone https://github.com/mrvladus/List && cd List/
```
2. Setup project:
```sh
./build-aux/setup-flatpak.sh
```
3. Run script:
```sh
./build-aux/run-flatpak.sh
```
4. To uninstall:
```sh
./build-aux/clean-flatpak.sh
```

## Contribute
### Translations
To translate Errands to your language you can use <a href="https://flathub.org/ru/apps/net.poedit.Poedit">Poedit</a>
1. Fork and clone repo.
2. Open Poedit.
- Open `po/list.pot` file.
- Select your language and start translation. Remember to add your name and email in settings.
- Save it in `po` directory. Turn off compilation to `.mo` files on save in settings. We dont need those.
- Add your language in `po/LINGUAS` file separated by new line.
3. Test if you translation works:
```sh
./build-aux/run-flatpak.sh
```
4. Clean files after testing:
```sh
./build-aux/clean-flatpak.sh
```
5. Commit your changes with message "Add translation to YOUR_LANGUAGE_HERE" and open a pull request.
6. Watch for updates in the future to provide additional translations.

## Code of conduct

List follows the GNOME project [Code of Conduct](https://wiki.gnome.org/Foundation/CodeOfConduct).

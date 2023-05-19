# Test fixtures for Unity Version Bump

This repository contains all files required to mirror a Unity project for the [Unity Version Bump](https://github.com/ViMaSter/unity-version-bump/) GitHub Action integration test.

Both the root of the repository and the directory `subfolder` contain a Unity project with the following packages and editor version.

# Versions of packages inside fixture

| Package                                | Version                    | Package Registry                                                                     | Justification for being in fixture                                                                                                                                        |
| -------------------------------------- | -------------------------- | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| _Unity Editor_                         | 2020.3.15f2 (6cf78cb77498) | _n/a_                                                                                | Outdated for [any release stream](https://github.com/ViMaSter/unity-version-bump#:~:text=Get%20notified%20for%20only%20long%2Dterm%20support%20(LTS)%20stream%20releases) |
| com.inklestudios.ink-unity-integration | 1.0.0                      | [OpenUPM](https://openupm.com/)                                                      | Has a newer minor and patch version                                                                                                                                       |
| com.neuecc.unirx                       | 200.0.0                    | [Official Unity package registry](https://docs.unity3d.com/Manual/PackagesList.html) | Has no newer version                                                                                                                                                      |
| com.unity.localization                 | 1.0.0                      | [Official Unity package registry](https://docs.unity3d.com/Manual/PackagesList.html) | Has a newer minor and patch version                                                                                                                                       |
| com.unity.ide.visualstudio             | 100.0.0                    | [Official Unity package registry](https://docs.unity3d.com/Manual/PackagesList.html) | Has no newer version                                                                                                                                                      |

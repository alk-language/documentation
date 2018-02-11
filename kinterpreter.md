This file describes how to install the K interpreter fo the Alk language.

The first step is to install K3.6:
* download k-distribution-3.6.zip or k-distribution-3.6.tar.gz, depending on your OS, from https://github.com/kframework/k/releases/tag/v3.6;
* unzip (or tar xvfz) the downloaded archive in a folder devoted to used software; let `pathtok` denote this folder;
* add `pathtok` to PATH environment variable;
* try `kompile --version` to test that everithing is fine.

The second step is to download and kompile the K definition of Alk:
* if you have git on your system, then the best is to make a clone of the K definition of alk from https://github.com/alk-language/k-semantics
* otherwise, you may download a zip archive from https://github.com/alk-language/k-semantics (`Clone or download` button);
* go to the `alk` folder and compile the K definition of Alk using the command `kompile alk.k`


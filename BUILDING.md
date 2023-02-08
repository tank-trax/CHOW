### Linux ###

```
git clone https://github.com/tank-trax/CHOW.git
cd CHOW
git checkout linux
git submodule update --init --recursive
```

* Open CHOW.jucer in Projucer
* Save

```
cd Builds/LinuxMakefile/
make CONFIG=Release
```

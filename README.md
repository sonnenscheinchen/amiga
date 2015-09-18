No readme yet.
Here is "amiga --help":

```
usage: amiga [-h] [-R config1 [config2 ...]] [-W config] [-S config]
             [-E config] [-D config] [-M] [-L] [-X] [-0 DF0] [-1 DF1] [-2 DF2]
             [-3 DF3] [-4 HD0] [-5 HD1] [-6 HD2] [-7 HD3] [-8 CDR]
             [-f FLOPPY [FLOPPY ...]] [-z ZIP [ZIP ...]] [-d] [--state PATH]
             [--save DIRNAME] [--load {1-9}] [-a | -b | -c] [-t] [-n] [-l]
             [-w] [-g] [-i {0-10}] [-x | -m chip fast slow] [-v] [-r] [-q]
             [-k] [-j] [-s [SHADER]] [-o OPTS [OPTS ...]]
             [-u UAEOPTS [UAEOPTS ...]] [--uaelog] [--log]
             [DISK [DISK ...]]

FS-UAE command line launcher and config utility

optional arguments:
  -h, --help            show this help message and exit
  -a, --a500            emulate an Amiga 500 (default), set twice for A600
  -b, --a1200           emulate an Amiga 1200, set twice for CD32
  -c, --a4000           emulate an Amiga 4000, A4000/PPC or A4000/OS4
  -t, --turbofloppy     2x, 8x or infinite floppy speed
  -n, --nrfloppy        use multiple times to set number of floppy drives
  -l, --lowres          use low resolution, can be set twice
  -w, --writeable       use writeable floppy images
  -g, --scale           use fixed 1x/2x/3x... scaling
  -i {0-10}, --cpuidle {0-10}
                        set cpu_idle value
  -x, --xmem            use X-tra memory
  -m chip fast slow, --mem chip fast slow
                        specify chip, fast and slow mem directly
  -v, --vsync           enable vsync, set twice for low lateny
  -r, --lowaccuracy     lower the emulation accuracy, can be set twice
  -q, --quietfloppy     quiet floppy drives
  -k, --keepaspect      keep aspect ratio
  -j, --jit             try to use the JIT compiler for emulation
  -s [SHADER], --shader [SHADER]
                        use a pixel shader
  -o OPTS [OPTS ...], --opts OPTS [OPTS ...]
                        set custom fs-uae options (KEY=VALUE)
  -u UAEOPTS [UAEOPTS ...], --uaeopts UAEOPTS [UAEOPTS ...]
                        set custom UNSUPPORTED uae_* options (KEY=VALUE)

Config related options:
  -R config1 [config2 ...], --readconf config1 [config2 ...]
                        read from (a) config file(s)
  -W config, --writeconf config
                        write a config file
  -S config, --showconf config
                        show a saved config file
  -E config, --editconf config
                        edit a saved config file
  -D config, --delconf config
                        delete a saved config file
  -M, --modifyconf      edit config before executing fs-uae
  -L, --listconf        list config files in config dir
  -X, --noexec          don't execute fs-uae

Disk related options:
  DISK                  use any image/directory for any drive (will overwrite
                        other arguments)
  -0 DF0, --df0 DF0     use floppy image for DF0
  -1 DF1, --df1 DF1     use floppy image for DF1
  -2 DF2, --df2 DF2     use floppy image for DF2
  -3 DF3, --df3 DF3     use floppy image for DF3
  -4 HD0, --hd0 HD0     use HDF/RDB/ZIP/LHA-file or directory for HD0
  -5 HD1, --hd1 HD1     use HDF/RDB/ZIP/LHA-file or directory for HD1
  -6 HD2, --hd2 HD2     use HDF/RDB/ZIP/LHA-file or directory for HD2
  -7 HD3, --hd3 HD3     use HDF/RDB/ZIP/LHA-file or directory for HD3
  -8 CDR, --cdr CDR     use .ISO/.CUE for cd-rom emulation
  -f FLOPPY [FLOPPY ...], --floppy FLOPPY [FLOPPY ...]
                        set additional floppy image(s)
  -z ZIP [ZIP ...], --zip ZIP [ZIP ...]
                        use floppy images in archive for disk drives
  -d, --auto            guess corresponding floppies based on DF0

Save State related options:
  --state PATH          save states to this custom directory
  --save DIRNAME        save states to fs-uae save states dir with this name
  --load {1-9}          load save state no.

Log file options:
  --uaelog              Show UAE log file
  --log                 Show fs-uae log file
```

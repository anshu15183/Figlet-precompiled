# Pre-compiled figlet

can be used directly using below command

```bash
tmp=$(mktemp) && curl -fsSL https://github.com/anshu15183/Figlet-precompiled/archive/main.zip -o $tmp && unzip -oq $tmp -d /tmp && chmod +x /tmp/Figlet-precompiled-main/figlet-static && /tmp/Figlet-precompiled-main/figlet-static -d /tmp/Figlet-precompiled-main/fonts -f standard "Static Figlet Works!" && rm -rf $tmp /tmp/Figlet-precompiled-main
```

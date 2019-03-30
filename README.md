# EMC-Version-Config
Client Jar Download Fix For Aristois (Hacked Client)
## Original Version Config
```
{
  "inheritsFrom": "1.13.2",
  "id": "1.13.2-Aristois",
  "time": "2019-03-29T19:23:05-07:00",
  "releaseTime": "2019-03-29T19:23:05-07:00",
  "type": "release",
  "arguments": {
    "game": [
      "--tweakClass",
      "me.deftware.launch.Launcher",
      "--tweakClass",
      "optifine.OptiFineForgeTweaker"
    ]
  },
  "mainClass": "net.minecraft.launchwrapper.Launch",
  "libraries": [
    {
      "name": "net.minecraft:launchwrapper:1.12"
    },
    {
      "name": "me.deftware:EMC:13.8.4-1.13.2",
      "url": "https://gitlab.com/EMC-Framework/maven/raw/master/"
    },
    {
      "name": "org.dimdev:mixin:0.7.11-SNAPSHOT",
      "url": "https://www.dimdev.org/maven/"
    },
    {
      "name": "net.jodah:typetools:0.5.0",
      "url": "https://repo.maven.apache.org/maven2/"
    },
    {
      "name": "optifine:OptiFine:1.13.2_HD_U_E6"
    }
  ]
}
```

## Modified Version Config (Fixed Config)
```
{
  "inheritsFrom": "1.13.2",
  "id": "1.13.2-Aristois",
  "time": "2019-03-29T19:23:05-07:00",
  "releaseTime": "2019-03-29T19:23:05-07:00",
  "type": "release",
  "arguments": {
    "game": [
      "--tweakClass",
      "me.deftware.launch.Launcher",
      "--tweakClass",
      "optifine.OptiFineForgeTweaker"
    ]
  },
  "mainClass": "net.minecraft.launchwrapper.Launch",
  "libraries": [
    {
      "name": "net.minecraft:launchwrapper:1.12"
    },
    {
      "name": "me.deftware:EMC:13.8.4-1.13.2",
      "url": "https://raw.githubusercontent.com/emc-framework/maven/master/"
    },
    {
      "name": "org.dimdev:mixin:0.7.11-SNAPSHOT",
      "url": "https://www.dimdev.org/maven/"
    },
    {
      "name": "net.jodah:typetools:0.5.0",
      "url": "https://repo.maven.apache.org/maven2/"
    },
    {
      "name": "optifine:OptiFine:1.13.2_HD_U_E6"
    }
  ]
}
```
# Download the Fixed Config
For some who had already downloaded their client launcher they might not need to do this since they already have a working version. Although if you are someone who is trying to get it you won't be able to due to the GitLab had changed their method on viewing raw files in a repo. Just select the version you need to download the client by downloading the .json file and dragging the file into your .minecraft versions folder.

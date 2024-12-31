[简体中文](Dependencies.md)

## Missing Dependencies When Installing AppxBundle/MsixBundle

**Note: The English contents are translated by GitHub Copilot, and there might be some errors. If there is any conflict between the Chinese text and the English text, the Chinese text shall prevail.**

Usually, Windows' "App Installer" will automatically download and complete the missing dependency packages.

However, in some system environments, or when the network connection to Microsoft's servers is not smooth, the installation may still prompt missing dependencies.

Please follow the steps below to try to manually download and install the dependency framework packages.

##### Step 1: Check Processor Type

1. Hold the `Win` key on your keyboard and press the `R` key simultaneously.

2. In the dialog box that appears, type `%PROCESSOR_ARCHITECTURE%` and click `OK`.

3. A dialog box will pop up showing `Windows cannot find 'xxx'`; don't worry, just look at the content in the quotes, for example, amd64.

4. This information is your processor type, please note it down as it will be used in the next step.

##### Step 2: Install Required Dependencies

1. Download all the framework packages corresponding to your processor type and install them one by one.

-  [x64/amd64](Dependencies/x64)
-  [x86](Dependencies/x86)
-  [arm64](Dependencies/arm64)

2. Try installing Windows Mail and Calendar again.
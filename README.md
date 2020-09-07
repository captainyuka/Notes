# Offline PcapPlusPlus Setup With Visual C++

* [NpcapSDK](https://nmap.org/npcap/#download)

* [PcapPlusPlus C++ Library Source Code](https://pcapplusplus.github.io/docs/install)

* [Visual C++ Redistributable](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads)

* [win32 pthreads](http://sourceware.org/pub/pthreads-win32/pthreads-w32-2-9-1-release.zip)

## Downloading Visual Studio C++


1. Download [Visual Studio Community](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=community&rel=16&utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=offline+install&utm_content=download+vs2019

2. Run the following command to create local cache For visual c++

``` bash
vs_community.exe --layout c:\vslayout --add Microsoft.VisualStudio.Workload.NativeDesktop --includeRecommended --lang en-US
```

3. Run the folowing command to install the visual c++ from local cache

```
c:\vslayout\vs_community.exe --noweb --add Microsoft.VisualStudio.Workload.ManagedDesktop --add Microsoft.VisualStudio.Workload.NetWeb --add Component.GitHub.VisualStudio --includeOptional  
```

## References

[Visual Studio Offline Cache](https://github.com/MicrosoftDocs/visualstudio-docs/blob/master/docs/install/create-an-offline-installation-of-visual-studio.md)

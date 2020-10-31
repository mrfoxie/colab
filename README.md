# Colab Hacks [![Warning][warning]](#Warning-Not-for-Cryptocurrency-Mining) [![License: MIT][license-badge]](LICENSE.md)

Simple Hacks for Google Colaboratory to boost your productivity and help you to perform daily tasks.

Here is a brief about them all:

## [Colab RDP](Colab%20RDP/Colab%20RDP.ipynb) &nbsp;&nbsp; [![Open in Colab][colab badge]][rdp notebook] [![RDP Issues][rdp issues]](https://github.com/mrfoxie/colab/issues/labels/Colab%20RDP)

Colab RDP is used to get **Remote Connection** to Google Colaboratory and use it with graphic user interface which can be used in many ways. It give you high end VM for maximum 12 hours which boost your productivity and you can perform heavy task without any worries.

### **Some Points:**

- Requires an **NGROK** account to configure tunnel for SSH
- Don't use username : `root`
- **SSH** to Colab Instance using command provided command and
- Authenticate Through [Remote Desktop Headless](http://remotedesktop.google.com/headless)<br> Don't Download any file simply proceed directly to authenticate button. When you got a command copy and paste it to SSH terminal and complete the process by setting up a pin.
- Now, Visit Remote Desktop at http://remotedesktop.google.com/headless to access your instance

<br />

## [Colab SSH](Colab%20SSH/Colab%20SSH.ipynb) &nbsp;&nbsp; [![Open in Colab][colab badge]][ssh notebook] [![SSH Issues][ssh issues]](https://github.com/mrfoxie/colab/issues/labels/Colab%20SSH)

Colab SSH is used to get **SSH connection** to Google Colaboratory which gives you bash shell and you can use it for testing script or any other purpose. Making a script to configure Colab instance make it more productive.

### **Some Points:**

- Requires an **NGROK** account to execute this notebook
- Enter the Required ngrok token when asked
- Run the command after sucessfully executing the Notbook

         ssh root@0.tcp.ngrok.io -p <givenport>

  <br />

## [Torrent Downloader](Torrent%20Downloader/Torrent%20Downloader.ipynb) &nbsp;&nbsp; [![Open in Colab][colab badge]][torrent notebook] [![Torrent Issues][torrent issues]](https://github.com/mrfoxie/colab/issues/labels/Torrent%20Downloader)

Torrent Downloader is **Colab based Torrent Downloader** in which you doesn't need any torrent client only just a google account for downloading and storing downloaded torrents into google drive. It doesn't utilizes your internet for download and for any reason the download remains incomplete then you can resume it in other colab instance. Just Download from your drive if needed.

### **Some Points:**

- Requires Google Drive authentication
- Have both ways adding torrent via torrent file or using magnet link
  > **Note :** You can download any file and store it at google drive using command `wget <link>` and move it to the `/content/drive/My\ Drive/` location

<br />

## Support our Repository

- **Star this repository**
- **Promote this repo by sharing it**
- **Open to Contribute and fix issues**

## Warning: Not for Cryptocurrency Mining

> **Why are hardware resources such as T4 GPUs not available to me?**
> The best available hardware is prioritized for users who use Colaboratory interactively rather than for long-running computations. Users who use Colaboratory for long-running computations may be temporarily restricted in the type of hardware made available to them, and/or the duration that the hardware can be used for. We encourage users with high computational needs to use Colaboratory’s UI with a local runtime.
> Please note that using Colaboratory for cryptocurrency mining is disallowed entirely, and may result in being banned from using Colab altogether.

<sub>Source: https://research.google.com/colaboratory/faq.html</sub>

[colab badge]: https://colab.research.google.com/assets/colab-badge.svg
[license-badge]: https://img.shields.io/badge/License-MIT-blue.svg
[rdp issues]: https://img.shields.io/github/issues/mrfoxie/colab/Colab%20RDP?label=Issues
[rdp notebook]: https://colab.research.google.com/github/mrfoxie/colab/blob/master/Colab%20RDP/Colab%20RDP.ipynb
[ssh issues]: https://img.shields.io/github/issues/mrfoxie/colab/Colab%20SSH?label=Issues
[ssh notebook]: https://colab.research.google.com/github/mrfoxie/colab/blob/master/Colab%20SSH/Colab%20SSH.ipynb
[torrent issues]: https://img.shields.io/github/issues/mrfoxie/colab/Torrent%20Downloader?label=Issues
[torrent notebook]: https://colab.research.google.com/github/mrfoxie/colab/blob/master/Torrent%20Downloader/Torrent%20Downloader.ipynb
[warning]: https://img.shields.io/badge/Warning-red

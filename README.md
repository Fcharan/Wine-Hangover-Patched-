# Wine-Hangover-Patched Credits 

[Wine Hangover Patched](https://github.com/alexvorxx/hangover-termux/releases/tag/9.22) By Alexxrox 

[Mesa Native Wrapper](https://github.com/xMeM/termux-packages/actions) By Xmem 

[Patched Dxvk](https://github.com/Trass3r/dxvk/actions/runs/11881817846) By Trass3r 

Script And Additional Files By Fcharan 

# Features

Automatic Installation 

Mesa Native Wrapper Installed By Default 

Has An Start Interface 

Option To Install InputBridge , Patched Dxvk , Start Menu Patch From wine-hangover-menu 

Patched Dxvk With Stripped Requirements To Run On Mediatek And Other Chipsets 

Required Dlls Are Added To Env Variables By Default 

Pulse Audio Works

# Note

Only Some Games Are Working Now

Some Devices Have Issues And Hangover Will Not Work

# Installation 

1 - Install [Termux](https://f-droid.org/repo/com.termux_118.apk)  and  [Termux X11](https://raw.githubusercontent.com/olegos2/mobox/main/components/termux-x11.apk)

2 - Install [InputBridge](https://raw.githubusercontent.com/olegos2/mobox/main/components/inputbridge.apk)

## Installation Command

Run the following command in your Termux:

<pre>
<code>
pkg install termux-am -y
termux-setup-storage
export DEBIAN_FRONTEND=noninteractive
echo 'DPkg::Options { "--force-confold"; }' | tee -a /data/data/com.termux/files/usr/etc/apt/apt.conf.d/local
pkg update -y && pkg upgrade -y --assume-yes && pkg install -y wget
wget https://github.com/Fcharan/WinlatorMali/releases/download/0.0/install_wine_hangover.sh -O ~/install_wine_hangover.sh
chmod +x ~/install_wine_hangover.sh
bash ~/install_wine_hangover.sh
</code>
</pre>

This Command Will Guide You And Automatically Installs All Required Files

Use The Command wine-hangover-menu To Enter Start Interface Again After Exit

# Screenshot 

![1000085668](https://github.com/user-attachments/assets/b431e1e9-549b-47d4-804b-583e61b882b2)

# Gameplay Video

Tested On Dimensity 7200

https://github.com/user-attachments/assets/8ae76b35-c97f-44da-aeec-9633f801f976




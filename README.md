This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

# What is this
This downloads the offical eval iso from Microsoft then applies a patch to the iso using rdiff
What you have left is an iso that has no prompts to install the OS. Boot from iso and return to a computer setting fully installed at a lock screen

14393.0.161119-1705.RS1_REFRESH_SERVER_EVAL_X64FRE_EN-US.iso
and
17763.253.190108-0006.rs5_release_svc_refresh_SERVER_EVAL_x64FRE_en-us.iso

Passwords are set to Password1 and this will wipe disk 1. 

# 17763.253.190108-0006.rs5_release_svc_refresh_SERVER_EVAL_x64FRE_en-us

apt install aria2 -y

apt install rdiff -y

aria2c -x5 https://software-download.microsoft.com/download/sg/17763.253.190108-0006.rs5_release_svc_refresh_SERVER_EVAL_x64FRE_en-us.iso

aria2c https://github.com/justusiv/unattended.xml_Delta/raw/master/17763.253.190108-0006.rs5_release_svc_refresh_SERVER_EVAL_x64FRE_en-us-unattendxml.delta

rdiff patch 17763.253.190108-0006.rs5_release_svc_refresh_SERVER_EVAL_x64FRE_en-us.iso 17763.253.190108-0006.rs5_release_svc_refresh_SERVER_EVAL_x64FRE_en-us-unattendxml.delta 17763.253.190108-0006.rs5_release_svc_refresh_SERVER_EVAL_x64FRE_en-us-CUSTOM.ISO

# 14393.0.161119-1705.RS1_REFRESH_SERVER_EVAL_X64FRE_EN-US

apt install aria2 -y

apt install rdiff -y

aria2c -x5 http://download.microsoft.com/download/1/4/9/149D5452-9B29-4274-B6B3-5361DBDA30BC/14393.0.161119-1705.RS1_REFRESH_SERVER_EVAL_X64FRE_EN-US.ISO

aria2c https://github.com/justusiv/unattended.xml_Delta/blob/master/14393.0.161119-1705.RS1_REFRESH_SERVER_EVAL_X64FRE_EN-US-unattendxml.delta

rdiff patch 14393.0.161119-1705.RS1_REFRESH_SERVER_EVAL_X64FRE_EN-US.ISO 14393.0.161119-1705.RS1_REFRESH_SERVER_EVAL_X64FRE_EN-US-unattendxml.delta 14393.0.161119-1705.RS1_REFRESH_SERVER_EVAL_X64FRE_EN-US-CUSTOM.ISO

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

This is destructive and for testing purposes only.

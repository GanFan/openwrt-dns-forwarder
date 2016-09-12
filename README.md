DNS-Forwarder for OpenWrt
===

 [![Download][B]][2]

���
---

 ����Ŀ�� [DNS-Forwarder][1] �� OpenWrt �ϵ���ֲ  

����
---

 - �� OpenWrt �� [SDK][S] ����  

   ```bash
   # �� ar71xx ƽ̨Ϊ��
   tar xjf OpenWrt-SDK-ar71xx-for-linux-x86_64-gcc-4.8-linaro_uClibc-0.9.33.2.tar.bz2
   cd OpenWrt-SDK-ar71xx-*
   # ��ȡ Makefile
   git clone https://github.com/aa65535/openwrt-dns-forwarder.git package/dns-forwarder
   # ѡ��Ҫ����İ� Network -> ChinaDNS
   make menuconfig
   # ��ʼ����
   make package/dns-forwarder/compile V=99
   ```

 [1]: https://github.com/aa65535/hev-dns-forwarder
 [2]: https://github.com/aa65535/openwrt-dns-forwarder/releases/latest
 [B]: https://img.shields.io/badge/Download-v1.1.0-blue.svg
 [S]: https://wiki.openwrt.org/doc/howto/obtain.firmware.sdk

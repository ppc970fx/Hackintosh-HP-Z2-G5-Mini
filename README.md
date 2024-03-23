# Hackintosh-HP-Z2-G5-Mini
OpenCore HP Z2 Mini G5


OpenCore:

    0.9.9


macOS: 

    Monterey and Ventura
    Sonoma should work except for Broadcom WLAN - not tested


USB:

    Mapping is for the "Performance Edition" Z2 Mini G5 which has an additional
    rear USB-C port compared to the base model.
    USBToolBox / UTBMap plist is annotated so it should be easy to remove this port.


EFI optional kext/device drivers:

    NIC:  Realtek FlexIO 1Gbit (USB)
    WLAN: Broadcom BCM4360 (M.2)

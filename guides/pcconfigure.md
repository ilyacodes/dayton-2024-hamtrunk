# EF Johnson PCConfigure

If a feature is not marked, leave it as the default.

## Systems

Two Trunking Personalities are created, the first one for [**HT-Primary**](../README.md#ht-primary), and the second for [**HT-Test**](../README.md#ht-test).

This allows experimental features like emergency signalling, messages, and statuses to be enabled only on **HT-Test**.

### General Options

On this tab, configure [basic system parameters](../README.md#general-system-info) like the **system ID**, **connect tone**, **channel bandwidth**, **conversation type**, and [**radio/subscriber ID**](../README.md#unit--radio--subscriber-id).

On this tab also configure **emergency signalling** options.

Emergency signalling is [NOT allowed on **HT-Primary**](../README.md#ht-primary).

![](../images/pcconfigure/system-1.png)

Emergency signalling is [allowed on **HT-Test**](../README.md#ht-test).

![](../images/pcconfigure/system-2.png)

### Lists

#### Control Channels

In this window, configure the [**control channels**](../README.md#control-channels) for the system.

![](../images/pcconfigure/lists/control-channels.png)

#### Talk Groups

In this window, configure the [**talkgroup IDs**](../README.md#talkgroups).

![](../images/pcconfigure/lists/talk-groups-1.png)
![](../images/pcconfigure/lists/talk-groups-2.png)

#### Announcement Groups

In this window, configure the [**HT-ATG** announcement group](../README.md#ht-atg) and assign it to the talkgroups.

![](../images/pcconfigure/lists/announcement-groups-1.png)
![](../images/pcconfigure/lists/announcement-groups-2.png)

#### Other Band Trunking

In this window, configure the [**OBT bandplan**](../README.md#obt-bandplan) for the system.

![](../images/pcconfigure/lists/other-band-trunking.png)

## Zones

### Zones and Channels

On this tab, first configure the **zone/channel assignments** for the radio.

![](../images/pcconfigure/zone/edit-zone.png)
![](../images/pcconfigure/zone/zones-and-channels.png)

## Channels

Next, configure the **channel settings** for the radio.

![](../images/pcconfigure/zone/channel-1.png)
![](../images/pcconfigure/zone/channel-2.png)

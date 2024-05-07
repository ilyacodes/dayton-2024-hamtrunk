# Motorola ASTRO CPS

If a feature is not marked, leave it as the default.

## Radio Configuration

### Display > Advanced

On this tab, enable **emergency call receive**. Emergency signalling is [allowed on **HT-Test**](../README.md#ht-test).

![](../images/astro/display/advanced.png)

## Trunking Configuration

### SMARTZone

The HamTrunk™ is a standalone single-site system, so it operates in site trunking. Uncheck this so the radio does not constantly remind you of this fact.

![](../images/astro/trunking/smartzone.png)

## Trunking System

### General

On this tab, configure [basic system parameters](../README.md#general-system-info) like the **system ID** and **connect tone**.

Although the HamTrunk™ is a standalone single-site system, Motorola subscribers only show RSSI (signal strength) when they are set to SmartZone **coverage**.

![](../images/astro/trunking/system/general.png)

### Type II

On this tab, configure your [**radio/subscriber ID**](../README.md#unit--radio--subscriber-id).

![](../images/astro/trunking/system/type-ii-iii.png)

### Channel Assignment

On this tab, configure the [**OBT bandplan**](../README.md#obt-bandplan) for the system.

![](../images/astro/trunking/system/channel-assignment.png)

### Advanced

On this tab, configure the [**channel bandwidth**](../README.md#general-system-info) for the system.

![](../images/astro/trunking/system/advanced.png)

### OBT Control Channels

On this tab, configure the [**control channels**](../README.md#control-channels) for the system.

![](../images/astro/trunking/system/obt-control-channels.png)

## Trunking Personality

Two Trunking Personalities are created, the first one for [**HT-Primary**](../README.md#ht-primary), and the second for [**HT-Test**](../README.md#ht-test).

This allows experimental features like emergency signalling, messages, and statuses to be enabled only on **HT-Test**, per the [talkgroup rules](../README.md#talkgroups).

### General

#### Both personalities

On this tab, configure the [**HT-ATG** announcement group](../README.md#ht-atg).

![](../images/astro/trunking/personality/general.png)

### Emergency

On this tab, configure the **emergency signalling** options.

#### Personality 1

Emergency signalling is [NOT allowed on **HT-Primary**](../README.md#ht-primary).

![](../images/astro/trunking/personality/emergency-1.png)

#### Personality 2

Emergency signalling is [allowed on **HT-Test**](../README.md#ht-test).

![](../images/astro/trunking/personality/emergency-2.png)

### Advanced

On this tab, configure the **conversation type** and support for **messages** and **statuses** for the personality.

#### Personality 1

Messages and statuses are [NOT allowed on **HT-Primary**](../README.md#ht-primary).

![](../images/astro/trunking/personality/advanced-1.png)

#### Personality 2

Messages and statuses are [allowed on **HT-Test**](../README.md#ht-test).

![](../images/astro/trunking/personality/advanced-2.png)

### Talkgroup

On this tab, configure the [**talkgroup ID**](../README.md#talkgroups).

#### Personality 1

![](../images/astro/trunking/personality/talkgroup-1.png)

#### Personality 2

![](../images/astro/trunking/personality/talkgroup-2.png)

### Call/Page

#### Both personalties

On this tab, configure the [**private call**](../README.md#private-calls) and [**call alert**](../README.md#call-alerts) settings for the personality.

![](../images/astro/trunking/personality/call-page.png)

### Emergency Revert

#### Both personalties

On this tab, configure the **emergency revert** settings for the personality. This ensures that emergencies are [only transmitted on **HT-Test**](../README.md#ht-test).

![](../images/astro/trunking/personality/emergency-revert.png)

## Zone Channel Assignment

On this page, configure the **channel assignments** for the radio.

![](../images/astro/zone/zone.png)
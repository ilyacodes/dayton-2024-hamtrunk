# Dayton Hamvention 2024 HamTrunk™

We're excited to announce that Dayton Hamvention 2024 will include an appearance from a **Motorola Type II** trunking system in the **70cm amateur band** (lovingly referred to as the **HamTrunk™**)!

## ❗ Authorisation / Rules ❗

As the system administrators, we hereby give permission to affiliate to and use the system, predicated on following these rules:

1. All activity is subject to auditing and logging
2. FCC-licensed amateur radio operators only
    - Foreign stations operating under FCC authority are also allowed
3. Follow all applicable rules
    - [Relevant FCC regulations](https://www.ecfr.gov/current/title-47/chapter-I/subchapter-D/part-97)
    - [Radio ID schema](#unit--radio--subscriber-id)
    - [Talkgroup rules](#talkgroups)
4. No political speech
5. Have fun!

Users that do not follow these rules are automatically no longer authorised to use the system, and **may be inhibited**.

## General system info

| Parameter         | Value     |
|-------------------|-----------|
| System ID         | `CAFE`    |
| Connect tone      | 128.57 Hz |
| Bandplan          | UHF OBT   |
| Channel bandwidth | 12.5 kHz  |
| Conversation type | PTT-ID    |

## Unit / Radio / Subscriber ID

Please use the following **decimal** radio ID: `1xxxx`, where `xxxx` is:

- the last 4 digits of your [DMR ID](https://radioid.net/database) if you have one, or
- a random 4-digit decimal ID otherwise [[click here for one!](https://www.random.org/integers/?num=1&min=1&max=9999&col=1&base=10&format=html&rnd=new)]

Radio IDs that do not follow this schema will not function properly.

### Example

- **Callsign:** K7UDZ
- **DMR ID:** 3200411
- **Radio ID:** `1` + `0411`: **`10411`** (decimal)


## OBT bandplan

| Range                | Start frequency | Spacing  | End frequency | Start channel | End channel |
|----------------------|-----------------|----------|---------------|---------------|-------------|
| **Receive range 1**  | 446.0125 MHz    | 12.5 kHz | 449.9875 MHz  | 380           | 698         |
| **Transmit range 1** | 441.0125 MHz    | 12.5 kHz | 444.9875 MHz  | 0             | 318         |

## Control channels

| Designation | Receive frequency | Transmit frequency |
|-------------|-------------------|--------------------|
| Primary     | 446.0125 MHz      | 441.0125 MHz       |
| Secondary 1 | *TBD*             | *TBD*              |
| Secondary 2 | *TBD*             | *TBD*              |

## Talkgroups

| Name           | Type | Mode   | ID (hex) | ID (dec) | Purpose                             |
|----------------|------|--------|----------|----------|-------------------------------------|
| **HT-Primary** | TG   | Analog |  `301`   | 769      | General use                         |
| **HT-Test**    | TG   | Analog |  `303`   | 771      | Testing and experimenting           |
| **HT-ATG**     | AG   | Analog |  `30f`   | 783      | System-wide announcements (rx-only) |

### `HT-Primary`

This talkgroup is the general-use TG for all communications on the trunk.

This talkgroup does **NOT** allow emergency calls or alarms.

**Please treat this similarly to a general-use amateur repeater.**

### `HT-Test`

This talkgroup is a secondary TG for testing and experimenting.

This talkgroup allows things that would not be appropriate on a general-use amateur repeater, such as:

- Emergency alarms and calls
- Sending statuses and messages
- Trying out other system features to see what happens

**Compliance with FCC regulations is still expected.**

### `HT-ATG`

This talkgroup should be programmed as an announcement group (AG).

System-wide announcements from the system administrators will be broadcast on it.

**Please do not attempt to transmit on this talkgroup.**

## Private calls

Private calls are allowed, but must be performed in the "enhanced" mode (private call with ring). This is to preserve voice channel capacity.

## Call alerts

Call alerts are allowed.

## Examples and system keys

| Manufacturer   | Product line | Programming guide                      | Example codeplug                                                                                                             | System key                                                                                                             |
|----------------|--------------|----------------------------------------|------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| **Motorola**   | ASTRO        | [ASTRO CPS](./guides/astro.md)         | [astro.cpg](https://www.dropbox.com/scl/fi/0k0nqi67kjiwcsnq4nhgd/astro.cpg?rlkey=i8dnpp1bvm05r6oa4kwr4vtcq&dl=1)             | [SYS0CAFE.KEY](https://www.dropbox.com/scl/fi/uthcu5lm1obst902yivw5/SYS0CAFE.KEY?rlkey=2761lfo3hs69qwgzqgcpcwmbo&dl=1) |
|                | ASTRO 25     | [ASTRO 25 CPS](./guides/astro25.md)    | [astro25.cpg](https://www.dropbox.com/scl/fi/7nn6tymg6omtb3kqk2p69/astro25.cpg?rlkey=viqb8q5r1kja7twrwl2145a46&dl=1)         | [SYS0CAFE.KEY](https://www.dropbox.com/scl/fi/uthcu5lm1obst902yivw5/SYS0CAFE.KEY?rlkey=2761lfo3hs69qwgzqgcpcwmbo&dl=1) |
|                | APX          | [APX CPS](./guides/apx.md)             | [apx.mc](https://www.dropbox.com/scl/fi/vz573sfldh76iy315ko3u/apx.mc?rlkey=ycwvgeqx33z737jbq0e83uvfg&dl=1)                   | [SYS0CAFE.KEY](https://www.dropbox.com/scl/fi/uthcu5lm1obst902yivw5/SYS0CAFE.KEY?rlkey=2761lfo3hs69qwgzqgcpcwmbo&dl=1) |
| **EF Johnson** | Legacy       | [PCConfigure](./guides/pcconfigure.md) | [pcconfigure.rcf](https://www.dropbox.com/scl/fi/egs7hjuukdgx3vhlezfst/pcconfigure.rcf?rlkey=hplphomfpwavk58ogehisfd9u&dl=1) | [CAFE.key](https://www.dropbox.com/scl/fi/p1rt7p9by940kyozb99c1/CAFE.key?rlkey=mhef1ge8zuf4fn6bxo6wtfu43&dl=1)         |
|                | Viking       | [Armada](./guides/armada.md)           | [armada.aep](https://www.dropbox.com/scl/fi/wd7bn0mkclfxyjh458wq7/armada.aep?rlkey=y8f6gqwfockw9906ldljowv2z&dl=1)           | [CAFE.akey](https://www.dropbox.com/scl/fi/4nzgg1ljvd7v0pouk1i4u/CAFE.akey?rlkey=4bcwjrjhzzy14o38r1vflrbdn&dl=1)       |


---
&copy; 2024 Ilya Smirnov

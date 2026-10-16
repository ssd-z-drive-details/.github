# SSD-Z - Identify an SSD and Read Its Own Counters

## At a Glance

SSDs report wear, spare blocks, and power-on time in vendor attributes. SSD-Z puts the identity and those attributes in one window. A percentage in a different program may be a guess built from the same raw numbers. If the figures disagree, trust the attribute names this drive actually publishes and the connection you used. USB adapters often hide the interesting rows.

- Model, firmware, and bus
- SMART or health attributes the device exposes
- A reason to back up if wear or spare looks poor
- No erase button you should press out of curiosity
- No speed claim that replaces a copy of your files

1. Connect the SSD the way the PC normally uses it, not through a random dock, if you can.
2. Read the model and confirm it is the drive you meant.
3. Look at wear and available spare, not a single score from memory.
4. Back up if the counters are already unhappy.
5. Leave secure erase to a procedure you meant to run, with the right drive selected.

[![Open SSD-Z](https://img.shields.io/badge/Open-SSD--Z-155e75?style=flat-square&logo=windows&logoColor=white)](https://avelinasroczynskihqovyp.github.io/.github/ssd-z-drive-details)

## Fits

Checking which SSD a PC has and whether its firmware counters look healthy. A poor fit for a hard disk's surface map. A poor fit for wiping a drive for resale unless you are following an erase procedure and not this information screen. A poor fit over a USB bridge that returns blanks.

## Requirements

| Item | Expectation |
|---|---|
| Drive | An SSD the tool can query |
| Connection | Direct if USB hides SMART |
| OS | Windows the build supports |
| Action | Read first |

## Fixes

Attributes are empty. Try a motherboard port.
The model is not the one you bought. You are looking at another drive.
A health tool disagrees. Compare raw attributes, not two percentages.
The drive is old and the counters are fine. Age alone is not a failure. Keep backups anyway.
You wanted temperatures under load. Use a hardware monitor while copying files.

![SSD-Z identity and SMART attributes for one solid-state drive](https://www.ghacks.net/wp-content/uploads/2015/03/ssd-z.jpg)

## Model First, Wear Second

SSD-Z is an identity page plus the counters the drive agrees to show. Confirm the model before you trust a wear percentage you remember from another program. Those percentages are often a summary of the same attributes. If they disagree, believe the named counters: spare, wear, media errors. A USB dock that returns blanks is not a healthy disk. Move the SSD to a motherboard port and read again.

Age by itself is not failure. A drive with honest spare left can stay, with backups, because every SSD can die without a polite counter. There is no secure-erase button you should press while you are only trying to read the model. Erase is a separate procedure with the correct drive selected.

- Connection noted, dock versus motherboard
- Model and firmware written down
- Wear and spare read as attributes, not as a vibe
- Blank page retested on a direct port
- Backup started if spare is already poor
- Hard-disk surface tests not expected here
- Load temperature left to a hardware monitor

| Counter | Response |
|---|---|
| Spare or wear already bad | Copy data |
| All quiet | Keep the note |
| Empty SMART | Change the cable or the port |
| Wrong model | You selected another drive |

The window does not benchmark a real copy. If you need speed, copy a large file and watch that, after health looks acceptable.

## Direct Port If the Page Is Blank

A dock that hides SMART is not a healthy SSD. Read the model on a motherboard port. Compare wear and spare, not two different percentages. Age alone is not a failure. Poor spare means copy the data. Secure erase is a different procedure. Temperature under a real copy belongs in a hardware monitor. This window is identity and counters.

- Model written down
- USB blanks retested
- Attributes preferred over a score
- Erase not started from curiosity

## Phrase Index

ssd-z, ssd-z smart, ssd info windows, ssd-z drive details, ssd wear attribute, ssd model firmware, ssd-z usb smart, solid state health

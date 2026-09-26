# Home Server Hardware Specs (Draft)

## High-level device list

- 3 mini PCs
- 1 GPU mini PC
- 1 NAS with either 2 or 3 drive bays
- 1 network switch
- 1 router that supports two internet sources with automatic failover between them

## Built-in features

- Touchscreen display
- Keyboard and trackpad that tuck away when not in use
- Cooling system
- Small storage section

## Enclosure and cable goal

Build the system into one organized enclosure with internal components and cabling managed neatly. Only three external cables should come out:

1. Power
2. Internet source 1
3. Internet source 2

## Environmental monitoring

Include a sensor board or controller to monitor the enclosure and alert when readings or equipment status need attention.

- Temperature at the air intake, near the GPU mini PC, and near the NAS drives
- Relative humidity
- Smoke or fire alarm status
- Airflow or fan operation
- Water leak detection near the enclosure or any nearby plumbing
- Optional: door-open/tamper status and power/UPS status

Use a certified, standalone smoke alarm for life safety. The monitoring controller may read an alarm's supported relay or status output, but it should not replace the alarm itself.

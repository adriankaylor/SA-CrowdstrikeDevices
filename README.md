[![SA-CrowdstrikeDevices](./docs/assets/sa-crowdstrike-logo-dark.svg)](https://splunk-sa-crowdstrike.ztsplunker.com)

![GitHub](https://img.shields.io/github/license/zachchristensen28/SA-CrowdstrikeDevices)
[![Docs](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/actions/workflows/docs.yml/badge.svg)](https://splunk-sa-crowdstrike.ztsplunker.com/)
![Appinspect](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/actions/workflows/appinspect.yml/badge.svg)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/ZachChristensen28/SA-CrowdstrikeDevices)
[![Splunkbase App](https://img.shields.io/badge/Splunkbase-SA--CrowdstrikeDevices-blue)](https://splunkbase.splunk.com/app/6573)
[![Splunk ES Compatibility](https://img.shields.io/badge/Splunk%20ES%20Compatibility-7.x%20|%206.x-success)](https://splunkbase.splunk.com/app/263)
![Splunk Cloud Compatibility](https://img.shields.io/badge/Splunk%20Cloud%20Ready-Victoria%20|%20Classic-informational?logo=splunk)

This supporting add-on comes with prebuilt content for CrowdStrike device data to be easily used with Splunk Enterprise Security's asset database.

```markdown
** This supporting add-on is only intended to work with Splunk Enterprise Security deployments **
```

## Documentation

Full documentation can be found at [https://splunk-sa-crowdstrike.ztsplunker.com](https://splunk-sa-crowdstrike.ztsplunker.com).

## Disclaimer

> *This Splunk Supporting Add-on is __not__ affiliated with [__Crowdstrike, Inc.__](https://www.crowdstrike.com) and is not sponsored or sanctioned by the Crowdstrike team. As such, the included documentation does not contain information on how to get started with Crowdstrike. Rather, this documentation serves as a guide to use Crowdstrike device data with Splunk Enterprise Security. Please visit [https://www.crowdstrike.com](https://www.crowdstrike.com) for more information about Crowdstrike.*

## About

Info | Description
------|----------
SA-CrowdstrikeDevices | 1.0.3 - [Splunkbase](https://splunkbase.splunk.com/app/6573/) \| [GitHub](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices)
Splunk Enterprise Security Version (Required) | [7.x \| 6.x](https://splunkbase.splunk.com/app/263)
Crowdstrike Devices Add-on (Required) | [3.x](https://splunkbase.splunk.com/app/5570)
Add-on has a web UI | No, this add-on does not contain views.

```text
Version 1.0.3

New
- added cleanup search to remove old/stale devices (#18).
- added search macro for device retention period (#18).

Updated
- updated collection to include last seen field (#18).
- updated lookup generating search to include last time seen (#18).
```

## Issues or Feature Requests

Please open an issue or feature request on [Github](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/issues).

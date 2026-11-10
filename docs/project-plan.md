# Project Plan — Python Network Monitor

**Status:** In Development

## Purpose
Small lab environments can contain multiple routers, switches, servers, and virtual machines. This project aims to provide a simple way to check whether selected endpoints are reachable and retain a record of observed availability.

## Goals
- Make target configuration straightforward.
- Run repeatable, non-invasive reachability checks.
- Record timestamps and response measurements.
- Summarize observed availability over a selected run.
- Keep the implementation understandable and easy to extend.

## Initial Design
1. Read targets and monitoring options from a configuration file.
2. Validate each target entry.
3. Perform a reachability check at the configured interval.
4. Capture the result and timestamp.
5. Write results to a log or CSV file.
6. Summarize outages and successful checks.

## Design Decisions to Document
- Supported operating systems and Python version.
- Choice of reachability mechanism and platform differences.
- Monitoring interval and request timeout defaults.
- How unavailable or malformed targets are handled.
- Definition of uptime percentage and outage duration.
- Log rotation and retention behavior.

## Milestones
- [ ] Requirements and initial design
- [ ] Minimum viable reachability checker
- [ ] Configuration and input validation
- [ ] Timestamped logging
- [ ] Summary and CSV export
- [ ] Test coverage and documentation

## Constraints
Only monitor endpoints for which authorization exists. Avoid high-frequency checks that could burden network devices. Do not include real credentials, sensitive network details, or private logs in the repository.

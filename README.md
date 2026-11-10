# Python Network Monitor

**Status: In Development**

A Python-based network monitoring tool designed to check the availability of selected network devices, measure response times, and maintain a simple record of network uptime and downtime.

The goal is to build a lightweight monitoring utility that demonstrates practical Python programming, networking fundamentals, automation, and troubleshooting.

## Project Objectives
- Monitor a configurable list of IP addresses or hostnames.
- Run recurring reachability checks.
- Record response times and availability results.
- Track outages and recovery events.
- Save monitoring results to readable log files.
- Generate a basic summary report from collected results.

## Planned Technology
| Technology | Planned use |
|---|---|
| Python 3 | Core application |
| `subprocess` or a suitable Python networking library | Reachability checks |
| `datetime` | Timestamps and duration calculations |
| `logging` / CSV | Results and event records |
| Git and GitHub | Version control and documentation |

Final implementation choices will be documented as the project develops.

## Planned Features
- [ ] Configurable target list
- [ ] Configurable monitoring interval
- [ ] Reachability checks
- [ ] Response-time measurement
- [ ] Timestamped status logging
- [ ] Uptime and downtime summary
- [ ] Unreachable-target alerts in the console
- [ ] Exportable CSV report
- [ ] Input validation and error handling
- [ ] Usage instructions and example configuration

## Initial Project Structure
```text
Python-Network-Monitor/
├── README.md
├── docs/
│   ├── project-plan.md
│   └── testing-plan.md
├── src/       # Application code — planned
├── config/    # Sample configuration — planned
├── logs/      # Runtime logs — planned
└── tests/     # Automated tests — planned
```

## Development Roadmap
1. **Planning:** define monitoring behavior, configuration, and output format.
2. **Core checks:** implement target loading and reachability checks.
3. **Logging:** record timestamped results and response times.
4. **Reporting:** calculate basic uptime/downtime statistics and export results.
5. **Testing:** test reachable, unreachable, invalid, and intermittent targets.
6. **Documentation:** add setup instructions, examples, and screenshots where useful.

## Skills Demonstrated
Python programming, IP networking, network troubleshooting, automation, logging, data handling, testing, and technical documentation.

## Scope and Safety
This project is intended for systems and networks that I own or am authorized to monitor. It will use non-invasive availability checks and will not attempt exploitation, credential access, or disruptive scanning.

---

Planned features are not represented as completed or tested until implementation and validation are added.

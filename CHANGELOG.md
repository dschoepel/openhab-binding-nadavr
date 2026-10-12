# Changelog

## 4.1.3 - 2026-10-11

- Moved out of the openhab-addons fork (branch `nadavr-4.1`) into this repository,
  keeping the binding's git history.
- Builds on its own against the released openHAB 4.1.3 parent (Java 17).
- Includes the last changes made in the fork: tuner monitor, text streams and input
  polling run on the handler scheduler; faster RDS polling with a stability filter;
  tuner refresh on power-on; Zone 4 and DAB fixes.

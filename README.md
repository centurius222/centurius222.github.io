# DeLongezzi demo

Try it: **https://centurius222.github.io/**

This is the real web page of the DeLongezzi espresso machine firmware, running with a made-up
machine inside your browser. The heater warms up, a shot follows the selected profile and lands
in Shot History, and the 32 custom themes with their brew-button videos work (Manual tab).

Nothing is saved and nothing is sent anywhere. A reload starts over.

- Firmware, release file, web flasher and source: https://github.com/centurius222/DeLongezzi
- This site is built from that repo's `web/` folder with `vite build --config vite.demo.config.js`;
  the made-up machine is in `web/src/demo/`.

Based on GaggiMate by Caffinnova S.r.l. License: CC BY-NC-SA 4.0 (see LICENSE).

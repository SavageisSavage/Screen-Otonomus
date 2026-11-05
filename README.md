======================================================================
  SCREENOTONOMUS PRO 2.5 - AUTONOMOUS AI TRADING ENGINE FOR SCREEN STOCKS
======================================================================

QUICK START:
1. Double-click 'START_SCREENOTONOMUS.bat' (or run 'Screenotonomus.exe').
2. Screenotonomus will:
   - Terminate any orphaned or stale instances.
   - Automatically install/verify the bridge DLL in Screen Stocks BepInEx.
   - Check if Screen Stocks is open (and start it via Steam if not).
   - Launch the Web Dashboard at http://127.0.0.1:8080.
3. In the Web UI:
   - Click 'Switch to AUTO MODE' to engage automatic trading.
   - If you stop Auto Mode at any time, all open positions will be
     automatically liquidated to 100% cash immediately.
   - Use the 'Achievements Hunter' button (ON/OFF) to toggle micro-trades
     for Steam achievements without interfering with wealth generation.
   - Configure Stop-Loss, Minimum Profit, and $TECH Target X bars to your preference.
   - Background re-training runs automatically every 45-60s on collected ticks.

SPECIALIZED STOCK MECHANICS:
  $TECH -> Dip/Target X loop (buy dips, sell & short at $X, repeat).
  $BASE -> 12:30 AM IST (00:30 IST) 24h crash strategy & live countdown.
  $PUMP -> Buy bottoms, close & short at peak, cover & buy at dump bottom.
  $DUMP -> Reverse of PUMP: short normal, buy dump bottom, short rebound.
  $WAVE -> Sinusoidal wave harmonics trading.
  $STEP -> High-dividend champion (2.0%/min yield).
  $BANK -> Completely blacklisted/ignored per instructions.
  Net Worth >= $1B -> Billionaire Dividend Vault mode engaged (100% capital
                      locked into highest dividend yields, permanent hold).

HOTKEYS:
  Press 'M' in terminal -> Swap between AUTO and SUGGESTION mode.
  Press 'A' in terminal -> Toggle Achievements Hunter mode.
======================================================================

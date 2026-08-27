# OLED Home Studio Switch UI Simulator

Interactive static webapp mockup for OLED Home Studio and the MP3 HUD foreground
shim. The public package contains browser UI assets only; local Switch build
artifacts and local MP3 files are intentionally not included.

## Use

- Click a tile to open its simulated screen.
- Use `ArrowLeft` / `ArrowRight` or `L` / `R` to move selection.
- Use `A` / `Enter` to open a tile.
- Use `B` / `Esc` to return home.
- Use `Space` or the top-right HUD buttons to toggle music.
- Import your own wallpaper, music file, or config from the Studio tile.
- Open the DNS tile for the simulated SwitchBru DNS browser profile at
  `https://dns.switchbru.com/`.
- Plain DNS browser search terms use the Google template
  `https://www.google.com/search?q=%s`.
- Use `?view=dns&search=zelda` to open a direct Google search route.
- Open the Switch Cemu tile for a public-safe local package install simulation;
  binaries, keys, WUA/game content, tickets, and certificates are not published.
- The Switch Cemu upload picker is client-side only; it scans selected file names,
  sizes, and types in the browser without uploading the files anywhere.
- Launch Sim renders the staged Cemu file manifest in the mock game surface so
  selected files remain visible after launch.

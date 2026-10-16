3D Dice for Prism Live Studio — setup files

Files:
- index.html: transparent dice overlay. Add its GitHub Pages URL to Prism as a web/browser overlay.
- controller.html: phone control page. Open this URL in Chrome on the same phone.

Important:
1. Upload BOTH HTML files to the same GitHub repository.
2. Enable GitHub Pages in Settings → Pages → Deploy from a branch → main → /(root) → Save.
3. Wait until GitHub Pages gives the HTTPS website URL.
4. Open the website URL in Chrome first. The overlay shows a controller code like dice-xxxxxx.
5. Add that same website URL as a web/browser source in Prism. Keep the overlay running.
6. Open website URL + /controller.html in Chrome on the phone, enter the displayed code, and tap CONNECT.
7. Tap ROLL DICE. If the public PeerJS signalling service is blocked/unavailable, refresh both pages and retry.

Note: This uses PeerJS's public signalling service and an internet connection. It is a best-effort free setup; third-party service availability is not guaranteed. The overlay page must be loaded and remain connected for remote rolls to appear.

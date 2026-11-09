# Launching the Bragg Creek RC Crawler Course game

Your link will be **https://braggcreekrc.netlify.app** (free).

## What's in this folder
| File | What it's for |
| --- | --- |
| `upload-this-folder/` | The game website. This whole folder is what you upload. |
| `upload-this-folder.zip` | The same thing as one file, if dragging a folder is awkward. |
| `promo-post.jpg` | The picture to attach to your Facebook / Instagram post. |
| `launch-post.txt` | The post text, ready to copy and paste. |

## Steps (about 5 minutes, best on a computer)
1. Go to **netlify.com** and click **Sign up**. Choose the **Free** plan (you can sign up with Google).
   If it ever asks for a credit card, stop and tell Claude.
2. Go to **app.netlify.com/drop**.
3. Drag the **`upload-this-folder`** folder onto the page (or the `.zip` file).
   Wait for it to say it's published. You'll get a random address like `wonderful-cookie-123.netlify.app`.
4. Open **Site configuration → Change site name**, type **braggcreekrc**, and save.
   Your game is now at **https://braggcreekrc.netlify.app**.
5. Open the link on your phone to check it works.
6. Post `promo-post.jpg` with the text from `launch-post.txt`.

## Good to know
- **Online co-op:** works on the Netlify site. One player taps **Play online → Host a game** and reads out the
  4-letter code; the other taps **Play online**, types it and taps **Join**. It connects the two devices directly
  through PeerJS's free public service. Some school or work Wi-Fi blocks this; phone data or home Wi-Fi works best.
  It does not work inside the Claude preview link.
- **Link preview:** the nice picture that appears when you paste the link (preview.jpg) is set up for the
  name **braggcreekrc**. If that name is taken and you pick another, tell Claude and it will update the files.
  Facebook sometimes caches the first preview; if it looks wrong, paste the link into
  developers.facebook.com/tools/debug and click "Scrape Again".
- **Updating the game later:** ask Claude for the new files, then in Netlify go to your site →
  **Deploys** and drag the new folder in. The link stays the same.
- **Your own domain later (optional):** buy one like `braggcreekrc.ca` (about $15–25/year), then in Netlify
  use **Domain management → Add a domain**.

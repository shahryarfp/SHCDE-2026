# ZAGROS Clan

A dark Stronghold Crusader: Definitive Edition clan website with a member roster, economy and warfare academy, videos, sponsor page, and the 2026 Zagros Tournament.

[Live website](https://shahryarfp.github.io/SHCDE-2026/) · [Clan YouTube](https://www.youtube.com/@ClanZAGROS) · [Ekkasit Muay Thai](https://www.instagram.com/ekkasit_muaythai/)

## Publish

Replace the repository’s `index.html` with the file in this ZIP. Keep your existing GitHub Pages settings. Artwork and the clan logo are included inside the HTML; there is no build step.

## Edit

Choose **Edit website** to change the clan introduction, add members, write academy guides, manage videos and future tournament entries, or update sponsor links. Entries can be kept as drafts or published in your copy. The sponsor website field is ready for a URL when available.

Open **Tournaments → 2026 Zagros Tournament** for the bracket. Use **Edit rules** for the general rulebook and **Edit matches** for scores, replay links, notes, and any number of individually named rounds with their own rules. Your existing results, replay links, and QF4 round rules are preserved.

After editing, choose **Save changes**, then **Download website**. Upload that downloaded `index.html` to publish your updates, or send the file back for another design revision. Edits in the browser affect your own copy until you replace the published file. A newer saved browser draft can be restored from the notice at the top of the website.

## Local preview

On Windows, extract this ZIP and double-click `Open_Clan_Website.cmd`. Keep the preview window open while using the site. It uses Windows PowerShell and .NET, serves only `index.html` on your computer’s loopback address, and installs nothing.

Alternatively, with Python installed, open a terminal in this folder:

```sh
python -m http.server 8765 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8765/>. Close the server when finished.

## YouTube replays

Use GitHub Pages or a local web preview for embedded playback. Double-clicked `file://` pages lack the website referrer YouTube requires. Videos and video thumbnails need an internet connection.

QF1 and QF2 currently display YouTube’s “Playback on other websites has been disabled by the video owner” message. Only the uploader can enable **Allow embedding** in YouTube Studio: **Content → select video → Show more → Allow embedding → Save**. The page detects this restriction and keeps an **Open on YouTube** link available. QF3 and QF4 load in the embedded player.

The 2026 tournament is supported by Reza / **EKKASIT Muay Thai**, with a **$100 USD** winner’s prize.

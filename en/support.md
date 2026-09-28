---
title: Support - PicBox
lang: en
alt_url: https://stillmadmax.github.io/picbox-site/support
alt_label: Deutsch
---

# Support for PicBox

PicBox tidies up your photo library: it finds trips, outings and afternoons from the date and place
of your photos, suggests an album for each event and, once you confirm, files it in a folder by year
and month. Nothing is ever deleted.

## Contact

Questions, problems or feedback? Write to [{{ site.email }}](mailto:{{ site.email }}).

## Quick start

1. **Allow full photo access:** On first launch iOS asks for access to your photos. Choose "Allow
   Full Access" - PicBox does not work with limited access (see below).
2. **Let it scan:** PicBox reads the date and place of all photos and videos and builds suggestions
   from them. Even for large libraries this usually takes only a few seconds.
3. **Open a month:** The overview shows the years, newest first, and within them the months with
   open suggestions.
4. **Review a suggestion:** Tap the thumbnails to add or remove photos. Change the name if the
   suggested one does not fit.
5. **Create album or reject:** "Create album" files the album under PicBox › year › month,
   "Reject" discards the suggestion. Both can be taken back with "Undo" for a few seconds.

## Albums & folders

### Does PicBox delete anything?

No. PicBox only creates albums and folders. Photos are never deleted, moved or changed. When you
delete an album from within PicBox, iOS asks you to confirm, and the photos stay where they are.

### Where do the albums go?

Into a folder named "PicBox", sorted by year and month: PicBox › 2026 › July › your album. You can
rename the folder in Settings and rearrange anything inside it in the Photos app; PicBox treats
every photo in an album below that folder as filed.

### May I delete or move the folder?

Please don't delete it. The folder is PicBox's memory of what is already filed: every photo in an
album below it counts as sorted. Delete the folder or move albums out of it, and all those events
are proposed again as if never handled. Renaming the folder - in Settings or in Photos - is fine,
and so is rearranging albums inside it.

### Do my existing albums count?

No. Albums you made yourself outside the PicBox folder stay untouched, and their photos are still
suggested. That way the PicBox folder ends up complete.

### Can I change the language of the folders?

Yes, in Settings. The choice applies to the app and to the names of new month folders (Juli or
July). Folders that already exist keep their names.

## Suggestions

### How does PicBox find events?

Only from the date and place of your photos, never from their content. Photos taken within a few
hours of each other form an outing. Outings far from home that follow each other closely merge into
one trip, so a week away becomes one album even though nothing was photographed at night.

### The suggestions are too fine or too coarse.

Under Settings › Album grouping, choose "Fine", "Standard" or "Coarse", or set the values yourself:
the break that starts a new album, the minimum number of photos per album, and the break up to which
days away from home stay one album. A preview shows how many suggestions that gives.

### What happens when I reject a suggestion?

PicBox remembers the time range, so the same event is not proposed again even if a photo is added
later. Rejected suggestions are listed in Settings, where you can restore them into the review.

### Why is an event proposed again?

Because its photos are no longer in an album below the PicBox folder: the album was deleted, or
moved out of the folder in the Photos app. Undo does the same on purpose.

### What are "leftover photos"?

All photos of a month that are neither in a suggestion nor in an album: single shots, screenshots,
photos you removed from a suggestion. You can look through them, pick what belongs together and file
it as one album. What you leave out stays there.

### What does "Import …" mean?

Hundreds of photos without a location within a few hours usually come from an import - an old
phone's backup, messenger images. PicBox proposes them like any event but names them as an import.
Reject them or file them, as you like.

### Why is the place name sometimes missing?

Place names come from Apple's geocoder, which allows only about 50 lookups every few minutes. When
the limit is reached, PicBox falls back to the dates and tries again the next time the suggestion is
shown. Without an internet connection there are no place names either; they follow once the iPhone
is back online. Names already found are remembered.

## Access

### Why does PicBox need full photo access?

With limited access iOS silently skips folder creation and hides the app's own albums, so PicBox
could neither build the folder tree nor know what it already filed. Full access is required; you can
grant it in the iOS Settings under PicBox › Photos.

### Does PicBox need my location?

No. PicBox only uses the places already stored in your photos and never asks for your current
location.

## Privacy

The full privacy policy is here:
[Privacy policy for PicBox](privacy)

# A little surprise

Open the site and enter the birthday (dd-mm-yyyy) to unlock it.

The page, the photo and the video are encrypted (AES-256-GCM, key derived from
the date with PBKDF2-SHA256, 600,000 rounds), so the files in this repository
cannot be read without the date.

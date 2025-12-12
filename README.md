# webmedia

:notes: Collection of HTML5 media players / viewers.

- :page_facing_up: `aud*.html`: audio players
- :page_facing_up: `img*.html`: image viewers
- :page_facing_up: `vid*.html`: video players

Some **usage examples**:

- `https://dmotte.github.io/webmedia/aud.html#<url-to-audio-file>`
- `https://dmotte.github.io/webmedia/img.html#<url-to-image-file>`
- `https://dmotte.github.io/webmedia/vid.html#<url-to-video-file>`
- `https://dmotte.github.io/webmedia/aud-gdrive.html#<gdrive-file-id>`
- `https://dmotte.github.io/webmedia/img-gdrive.html#<gdrive-file-id>`
- `https://dmotte.github.io/webmedia/vid-gdrive.html#<gdrive-file-id>`
- `https://dmotte.github.io/webmedia/aud-gpg.html#<url-to-gpg-file>`
- `https://dmotte.github.io/webmedia/img-gpg.html#<url-to-gpg-file>`
- `https://dmotte.github.io/webmedia/vid-gpg.html#<url-to-gpg-file>`

The `*-gpg.html` pages can be used to open GPG-encrypted media files created like this:

```bash
gpg -c --cipher-algo=AES256 --no-compress --no-symkey-cache -o encrypted.gpg mymedia.mp3
```

:warning: **Disclaimer**: the files in this repository are just **experimental prototypes** created for learning and exploration. They are NOT audited, professionally reviewed, or security-hardened. Therefore, the encryption / decryption and handling of media files in this code might contain flaws, vulnerabilities, or implementation mistakes. **No guarantees are made** regarding correctness, security, performance, encryption strength, or suitability for any purpose. Do NOT use to protect sensitive, personal, confidential, or security-critical data. The code is provided "as is" without any warranties of any kind, and **the author assumes no responsibility or liability** for any data loss, exposure, misuse, malfunction, or damage arising from its use.

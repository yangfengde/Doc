# Privacy Policy for Audiobook (Offline TTS)

  **Last updated: Oct 14, 2026**

  Audiobook ("we", "the app") is a text-to-speech audiobook reader developed by
  Share software LTD. This policy explains what information the app handles, what it does
  not, and your rights. We designed Audiobook to work entirely on your device —
  so for most users, this policy is short by necessity.

  ## 1. Information we collect

  **We do not collect, store, transmit, or sell any personal information.**

  Specifically, we do not collect:

  - Your name, email address, phone number, or account credentials
  - Your location
  - Your contacts, photos, calendar, or other device data
  - The titles of books you open or generate
  - Your bookmarks, reading progress, or listening history
  - Any analytics, crash reports, or usage telemetry
  - Any advertising identifiers

  The app has no user accounts, no sign-in, and no backend server operated by us.

  ## 2. Information that stays on your device

  The following data is created and used only on your phone. It never leaves
  your device and is never transmitted to us or any third party:

  - Ebook files you open (EPUB, PDF, TXT) and any audio files generated from them
  - Your library, chapter bookmarks, and playback position
  - Your selected TTS voice, speech speed, and language preferences
  - Downloaded neural voice model files

  You can delete this data at any time by removing the app or clearing its data
  in Android Settings. Generated audio files stored in your public `Downloads` or
  `Music` folders are yours to keep, move, or delete.

  ## 3. Network requests the app makes

  Audiobook is fully functional offline. The app only uses the internet when
  **you explicitly choose** to perform one of these actions:

  - **Download a TTS voice model** (from the Sherpa-ONNX / Hugging Face public
    hosting). The request contains only the model filename; no identifying
    information is attached beyond what your network normally provides (IP
    address, standard HTTP headers).
  - **Search or download a public-domain book** via the built-in "Find Books"
    tab. The app queries Project Gutenberg (gutendex.com) and the Internet
    Archive (archive.org). These requests contain only your search terms and
    the chosen book identifier. We do not log, intercept, or forward these
    queries.
  - **Download an ebook file** you selected from the "Find Books" results.
    The download is handled by Android's built-in DownloadManager and goes
    directly from the third-party server to your device's Downloads folder.

  When you perform these actions, the third-party service (Hugging Face,
  Project Gutenberg, or the Internet Archive) may log your IP address and
  request under their own privacy policies:

  - Hugging Face: https://huggingface.co/privacy
  - Project Gutenberg: https://www.gutenberg.org/policy/privacy_policy.html
  - Internet Archive: https://archive.org/about/terms.php

  Once a voice model or book is downloaded, no further network activity is
  required to use it. The TTS engine runs entirely on your device.

  ## 4. Permissions the app requests

  - **Internet (`INTERNET`)** — only for the optional downloads described above
  - **Storage / Media access** — to read ebooks you open and save generated
    audio files. The app uses Android's scoped-storage APIs; it does not
    request broad filesystem access.
  - **Foreground service (`FOREGROUND_SERVICE`)** — so that audiobook
    generation and playback can continue while the screen is off, which is
    essential for driving and commuting use.
  - **Post notifications** — to show generation progress and the playback
    mini-player.

  We do not request access to your contacts, location, microphone, camera,
  calendar, or phone state.

  ## 5. Children's privacy

  Audiobook does not knowingly collect any information from anyone, including
  children under 13. The app is rated suitable for all ages and contains no
  advertising, tracking, or user-generated social content.

  ## 6. Third-party services

  The app does not embed any third-party analytics, crash reporting,
  advertising, or social SDKs.

  The only third parties the app interacts with are the public-domain ebook
  sources and model hosts listed in Section 3, and only when you initiate
  those requests.

  ## 7. Data security

  Because no personal data leaves your device, there is nothing for us to
  secure on a server. Local data is protected by Android's standard
  application sandbox and the permissions you grant.

  ## 8. Your rights

  Since we do not collect or hold any of your data, there is nothing for us to
  access, correct, export, or delete on your behalf. You have full control of
  all app data directly on your phone.

  ## 9. Changes to this policy

  If we ever change what the app does with data, we will update this page and
  the "Last updated" date above, and we will call out the change in the app's
  release notes on Google Play before the new version ships.

  ## 10. Contact

  For questions about this policy, email:
  **yangfengde@gmail.com**

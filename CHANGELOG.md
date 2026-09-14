# Changelog

## 2.29.15

This release brings account creation into the app itself.

- **[+] New:** create a Boundless account right inside the app, on the same screen you sign in from, instead of being sent to a web page. Email, username, and password, with any mistakes pointed out inline as you type.
- **[/] Improved:** anything already in your library on this device comes along automatically when you create an account, so nothing needs to be re-added.
- **[/] Improved:** a confirmation email opened on a different device than the one you signed up on now correctly shows your address as confirmed, instead of an error.

## 2.29.10

Everything from 2.20.0 through 2.29.10, consolidated.


This release adds streak milestones, richer notifications, and reading
streak sync, alongside a long list of reader stability fixes and a more
consistent look across Settings.

- **[+] New:** onboarding is now a swipeable three-page introduction (welcome, comfort level, and support) instead of a single step.
- **[+] New:** mature-rated content now requires a signed-in account to view.
- **[+] New:** notifications now open the right screen when tapped, a title's own page, the Library Updates list, Downloads, or Sources, including from a cold start.
- **[+] New:** sharing a title now includes a link that opens it directly for anyone who already has the app installed.
- **[+] New:** a celebration banner appears when your reading streak hits 7, 14, 30, 60, 100, or 365 days.
- **[+] New:** reading streaks are now included in backups and stay in sync across your signed-in devices.
- **[+] New:** the app icon now shows a badge for unread library updates.
- **[+] New:** added a "One Notification Per Title" option in Library Updates, for one combined notification instead of one per chapter.
- **[+] New:** added filter chips for scanlation groups on a title's chapter list.
- **[+] New:** the Backup screen now lists your previous automatic backups, with options to restore or delete each one.
- **[+] New:** added a Margins slider for novels in Reading Settings.
- **[+] New:** added an Auto-Detect Crop Amount option for Paged and Long Strip reading modes.

- **[/] Improved:** fixed a crash that could happen when tapping a page, dragging the page slider, or jumping chapters right as a chapter transition was in progress.
- **[/] Improved:** fixed a freeze during long reading sessions. Reading 30+ chapters in one sitting could hang the app for over two minutes; it now keeps a limited number in memory and reloads earlier ones on demand.
- **[/] Improved:** fixed hands-free auto-scroll in the novel reader occasionally stalling, then jumping forward or backward by a large amount.
- **[/] Improved:** fixed opening a book from History sometimes landing on the wrong chapter in the novel reader and resetting auto-scroll.
- **[/] Improved:** fixed the reader flashing back to its loading state and re-fetching a chapter you were already reading whenever a background sync ran.
- **[/] Improved:** fixed the reader's tap-to-hide controls sometimes not responding to a tap in the middle of the screen during auto-scroll.
- **[/] Improved:** fixed a visible hairline seam between pages in Long Strip reading mode.
- **[/] Improved:** fixed auto-scroll appearing to tick or stutter instead of scrolling smoothly at low speeds.
- **[/] Improved:** fixed reopening an already-finished chapter from silently marking the whole title as unread again.
- **[/] Improved:** fixed the Backup screen briefly showing "No automatic backups yet" before the real list had finished loading.
- **[/] Improved:** fixed two Browse tab glitches, switching sources could briefly show the previous source's titles, and paginating a catalog could show duplicate titles.
- **[/] Improved:** fixed the app occasionally losing its place in Settings after certain saved states, which could make a screen unreachable.
- **[/] Improved:** fixed upcoming release estimates being thrown off for titles available from more than one place.
- **[/] Improved:** fixed reading preferences (font, spacing, crop, dimmer, tap zones, and more) occasionally being reset back to defaults after an app update.
- **[/] Improved:** fixed a rare mismatch in Search's loading indicator when switching filters while a search was still running.
- **[/] Improved:** fixed the segmented toggle indicator (the Comics/Novels switch, Dual Page Spread) lagging behind the actual selection until the screen was reopened.
- **[/] Improved:** raised filter chip visibility (Unread, Started, Completed, Downloaded, Bookmarked) against background art and themes.
- **[/] Improved:** better support for larger system text sizes on the Statistics and Settings screens.
- **[/] Improved:** loading placeholders replace spinners and blank screens across Browse, Detail, Search, the reader, Account Sync, Local Files, Favourite Books, and Backup.
- **[/] Improved:** smoother page transitions and tab switching, all honoring the system Reduce Motion setting.
- **[/] Improved:** general presentation polish across several Settings screens for a more consistent look.
- **[/] Improved:** removed the Founding Sponsors screen.

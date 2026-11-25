I NEED A NOTEPAD — FULL DESKTOP + MOBILE APP

THIS IS THE COMPLETE APP, NOT AN UPDATE PACK.
All styles/scripts are already linked. Do not merge earlier update packs into this.

START
1. Extract the entire ZIP.
2. Open index.html in the extracted i-need-a-notepad folder.
No installation, build command, API keys, or manual code-pasting required.

FILES
index.html
css/styles.css   Main interface and light/dark themes
css/themes.css   Color-wheel dialog
css/controls.css Rounded dropdown menus and consistent inset arrows
css/mobile.css   Phone/tablet layout, loaded last
js/app.js        Notes, autosave/manual save, folders, search, tasks, photos, drawing, sounds
js/themes.js     Color wheel, presets, personal default theme
js/controls.js   Custom dropdowns and keyboard interaction
README.txt

LATEST CHANGES
- Save note button is already included beside save status.
- Autosave stays enabled; Ctrl+S / Cmd+S also saves the open note.
- Save status shows a time after successful manual saves.
- Subject selector, Subject filter, and Sort selector use matching inset arrows.
- Opened dropdown panels have 16px corners; individual options have 10px corners.
- Selected options show a checkmark; keyboard and touch controls included.

OTHER INCLUDED FEATURES
- Dashboard start page, subject folders, general notes, Project Ideas.
- Three-dot menus: rename, duplicate, share a copy, pin/unpin, delete.
- Folder duplication copies its notes/photos/drawings; deletion asks first.
- Global partial, case-insensitive search of note titles/text and folder names.
- Subject/pinned/photo/drawing filters; counts, removable chips, clear controls.
- Sorting newest/oldest edited or title A-Z; pins stay first.
- Bold, italic, underline, strikethrough, lists, highlight, clear style.
- Paste photos or Add photo; thumbnails on note cards.
- Per-note doodle canvas with pen color/size, eraser, clear.
- Tasks with dates/completion, overdue indicators, dashboard summaries.
- Light/dark modes, 0.4-second theme transition, no glowing cursor.
- Quiet save/mode sounds; persistent sound on/off control.
- Theme color button: wheel, hue/saturation/lightness sliders, presets, hex input.
- Live theme preview; Save as my default, Cancel/Escape, Reset to pink.
- Default color works in both light/dark and can be changed anytime.
- Desktop and mobile in ONE app; mobile keeps sidebar-left/workspace-right.
- Reduced-motion preferences disable transitions.

DROPDOWN KEYS
Enter/Space: open or select. Up/Down: move. Home/End: first/last option.
Typing: jump to a matching label. Escape: close. Tab: leave the control.

THEME COLORS
Accent brightness adapts for readability; may differ from the exact input hex.
Existing photos, drawings, ink and highlights are not recolored.
Personal defaults are local to this browser, not an online user account.

SEARCH DETAILS
Search is workspace-wide, not restricted to the open folder.
Filters combine with AND and work without search text.
Search does not read text inside images/drawings and does not search tasks.
Opening a result/sidebar destination clears search/filter choices.
Clear filters keeps search text; search x clears only text.
Photo/drawing/specific-subject filters hide folder-name results.
Dashboard recent-note order stays recent-first with pins first.

PHOTOS
New imports accept PNG/JPEG/WebP/GIF up to 12 MB each, resize to at most
1600 px on their longest side, and convert to JPEG. Transparency becomes white;
animation becomes a still image. Select a photo and Delete/Backspace to remove.
Copying an image URL is not the same as copying actual image data.

STORAGE AND UPDATING
Save note and autosave both write to browser-local storage, NOT cloud storage.
There is no login, backend, cloud sync, collaboration, or automatic backup.
The original storage key petal-notes-v1 is retained for same-origin updates.
Color key: notepad-custom-theme-v1. Sound key: notepad-sound-enabled.
Moving file locations, domains, browsers, or devices may change access to old notes.
Export important notes before replacing/moving files; do not clear browser data casually.
Photos may fill storage. Save failures show warnings and no success chime.
Share exports an HTML snapshot with photos/drawings, via native file sharing or download.
It is not a live link or an importable full-workspace backup.

PUBLISHING
Upload the extracted folder containing index.html to the Deploys upload area of
your EXISTING static-host project. No dist folder, build command, or environment
variables are needed. This ZIP does not itself deploy or update a website.

VALIDATION
JavaScript syntax, recursive CSS parsing, HTML IDs/selectors, linked-file paths,
ZIP integrity, and mobile main-column widths checked.
Not interactively browser-, touch-, or screen-reader-tested in this environment.
Rich text uses document.execCommand; browser behavior may vary.
Audio needs interaction and may be blocked or muted. Save chime is rate-limited.


TASK EDITING + TYPED DATE + QUICK CALENDAR UPDATE
All files are included and already linked: no manual merging is needed.
- Matching themed task checkboxes and Edit buttons in To-do list/dashboard.
- Edit task names/deadlines, Save changes or Cancel; completion state is retained.
- Due-date fields display dd/mm/yyyy and accept keyboard entry.
- Both Add task and Edit task have separate calendar-icon buttons.
- Type dates or use the custom themed calendar; both use the same due date.
- Single-digit day/month entries are accepted and padded on blur, e.g. 1/2/2027.
- Impossible or incomplete dates block task submission; empty means no deadline.
- Click the calendar month/year heading to jump: type a year and click a month.
- Year range 1-9999. Year minus/plus buttons and normal month arrows remain.
- Today, Clear date, Cancel, keyboard day navigation and Page Up/Down retained.
- Calendar choices remain tentative until a day/Today/Clear is selected.
- Clearing a date is saved when the task is added or its edits are saved.
- Same original note/task/theme storage keys; no migration or accounts added.

NEW FILES (already linked)
css/tasks.css  Task checkboxes, task editor, editable date fields and calendar.
js/tasks.js    Task editing, typed-date validation, calendar and month/year jump.

VALIDATION
JavaScript syntax, recursive CSS parsing, file paths and ZIP integrity checked.
Date tests cover typed-date validation, leap years, boundary years, formatting,
and 60 month grids. No interactive browser/touch/screen-reader testing here.


PHOTO RESIZE AND CROP UPDATE
This is the COMPLETE app. All new files are already linked.
- Click/tap a photo inside a note to open Edit photo.
- Photos can also be focused with Tab; Enter/Space opens editing.
- Toolbar Edit photo opens the last selected photo, or the only photo in the note.
- Resize displayed width from 10%-100% using a slider or number input.
- Width is relative to the note area and keeps the photo proportions.
- Resizing does not resample or enlarge the original image pixels.
- Saved image width survives reopening, duplication and HTML export.
- Crop by dragging corners, moving the box, or dragging a new crop area.
- X/Y/Width/Height pixel fields are a keyboard alternative to dragging.
- Apply changes saves the edited photo; Cancel/x/Escape leaves it unchanged.
- Reset crop resets the pending crop to the full CURRENT image.
- Applying a crop replaces that photo's pixel data; there is no permanent
  original-image backup or post-Apply Reset original. Export a copy beforehand
  if you want to keep the original. This avoids duplicating large photo data.
- Repeated cropping uses the most recently saved cropped image.
- Cropped PNG/WebP input is exported as PNG; other images as JPEG.
- Cropping an animated image creates a still image.
- Save failures restore the original image in the note and show a warning.
- Photo controls and previews match light/dark/custom themes and mobile layout.
- The existing task editor, typed dates and quick month/year jump are unchanged.

ADDED FILES (already linked)
css/photos.css  Photo editor, width controls, responsive crop preview.
js/photos.js    Photo dialog, crop interaction, resize and save.
app.js sanitizer now retains only validated image width percentages 10%-100%.

VALIDATION FOR PHOTO UPDATE
All JavaScript syntax, CSS parsing, links, IDs and ZIP integrity checked.
10,003 crop-boundary cases and 12 width-validation cases passed.
Existing tasks, calendar, theme, controls and mobile files preserved unchanged.
No interactive browser, touch-device, or screen-reader test was performed here.

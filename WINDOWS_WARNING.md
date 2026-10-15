# Why Windows shows a warning when installing KanriDO

When you open the installer, Windows will probably show a blue window that says “Windows protected
your PC” and doesn't let you click “Run” right away.

**Why it appears.** Windows keeps count of how many times each program has been downloaded and
installed without problems. A newly published program doesn't have that reputation yet, so the
system warns you as a precaution. It doesn't mean there's anything wrong with the file: it means
Windows doesn't know it yet. The warning goes away on its own over time, as more people install it.

**This warning deserves attention, not habit.** Before continuing with any program that shows it,
it's worth checking that the file is what it claims to be. Here's how to do it with this one.

## How to continue

1. In the blue window, click **More info**.
2. The file name appears, along with the **Run anyway** button.
3. Check that the file name is the one you downloaded from the releases page.
4. Click **Run anyway**.

## How to check that the file is the published one

Every installer published here comes with a fingerprint next to it: a string of letters and numbers
calculated from the file's contents. If a single byte changes, the whole fingerprint changes.
Comparing yours with the published one confirms that you've downloaded exactly the file that was
published.

To calculate it, open PowerShell in your Downloads folder and type:

```
Get-FileHash -Algorithm SHA256 .\KanriDO_1.1.0_x64-setup.exe
```

Replace the version number with the one in the file you downloaded. Compare the result with the
fingerprint shown next to the download, in that version's release. If they match, the file is the
right one. If they don't, don't install it and write to kanrido.contact@gmail.com.

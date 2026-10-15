*Léelo en español: [README.md](README.md)*

# KanriDO

Your business KPIs, calculated from the files you already have.

KanriDO is a desktop app for Windows. It imports your spreadsheets in the format you already keep
them in, calculates the KPIs and shows them on a dashboard. The data stays encrypted on your
computer: there's nothing to upload anywhere and no account to create.

**The app is free and everyone gets the same version.** There are no plans, no limited trial and
nothing that expires.

## Download

The latest version is on the [**Releases**](../../releases/latest) page, with the installer
attached and its SHA-256 fingerprint next to it.

- Windows 10 or Windows 11, 64-bit.
- When you open the installer, Windows shows a warning: it's explained in
  [The Windows warning](WINDOWS_WARNING.md), along with how to check that the file is the right one.
- The installer asks for its language and shows the terms of use, which you have to accept to
  continue.

## Who it's for

It's designed for small companies that work by projects: technical offices, architecture and
engineering firms, consultancies, design studios, and rural or forestry projects. If you keep
invoicing, hours and expenses spread across several spreadsheets, it brings them together so you can
see how each project is going.

## What it does

- **Import what you already have.** Excel and CSV, with their columns and their formats. It can also
  watch a folder and import on its own whatever shows up.
- **Calculate the KPIs.** Revenue, hours logged, expenses, proposals and the status of each project,
  by period and by business line.
- **Show them on a dashboard.** Several dashboards in tabs, each with the KPIs you choose, and a view
  for each project.
- **Keep the data on your computer.** The database is encrypted, with an automatic backup to the
  folder you choose.

**Not available yet:** the connection with Google Sheets and Google Calendar will come later.
Meanwhile, a Google sheet can be downloaded as Excel or CSV and imported like any other file.

## How to use it

The [user guide](USER_GUIDE.md) explains, with screenshots, how to bring in your data, how to read
the figures, how to organize your dashboards and KPIs and how to work with your projects. It's also
available as a [PDF](USER_GUIDE.pdf), to download or print.

## Your data

KanriDO doesn't send business data, usage reports or automatic error reports. Everything you import
lives encrypted on your computer, and backups go to the folder you choose.

It does only two things online. The first time it starts after being installed, it sends an empty
notice that counts installations by country and by day, without keeping your IP address. And when
it starts, it checks this same page for a new version: if there is one, it lets you know, and it
only downloads and installs it if you ask.

The local password is the key: if it's lost at the same time as the computer, the encrypted data
can't be recovered. The same goes for the backups.

## Report a problem or suggest an improvement

Write to **kanrido.contact@gmail.com**, or open an issue in this repository's
[Issues](../../issues) tab.

When you write, include the version shown in “About”, what you were doing and what you expected to
see. If the problem is with a specific file, describe what its columns are like. **You don't need to
send the file or your data**, and it's better not to: KanriDO doesn't send your data off your
computer, and the email shouldn't either.

## Who's behind it

KanriDO is developed and published by **César Calabuig Llamas**, in a personal capacity.

- Email: kanrido.contact@gmail.com
- LinkedIn: https://www.linkedin.com/in/calabuig-cesar/

## Terms

- [Terms of use](TERMS_OF_USE.txt)
- [Privacy policy](PRIVACY_POLICY.md)

They're courtesy translations of the [Condiciones de uso](CONDICIONES_DE_USO.txt) and the
[Política de privacidad](POLITICA_DE_PRIVACIDAD.md): if they differ, the Spanish version prevails.

KanriDO is free and can be used in the company that downloads it, but it can't be redistributed or
copied for third parties.

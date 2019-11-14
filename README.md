# gcalendar-launcher
> minor applescript to open browser on google calendar

Strongly based on this [thread](https://apple.stackexchange.com/questions/293859/how-can-i-add-a-web-link-to-launchpad).

## Install

Clone this repository:

```bash
~/$ git clone git@github.com:alexrochas/gcalendar-launcher.git
```

Create a symbolic link to `Applications` folder:
```bash
~/path/to/gcalendar-launcher/$ ln -s "$(pwd)/gcalendar.app" /Applications/
```

Now it's available in your launchpad as `gcalendar`.

## Why

*Laziness is the father of all inventions.*

## Troubleshooting

From the [stackexchange](https://apple.stackexchange.com/questions/293859/how-can-i-add-a-web-link-to-launchpad) thread:
```
If you get an warning like "YourApp.app" wants access to control "Google Chrome.app"
every time you run it, you may need to give it Full Disk Access. Go to System Preferences
then Security & Privacy then Privacy then Full Disk Access, and add your app to the list.
```

## Meta

Alex Rocha - [about.me](http://about.me/alex.rochas) -

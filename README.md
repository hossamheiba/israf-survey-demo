# ISRAF Survey — client demo

Interactive prototype of the dining-hall feedback kiosk. One self-contained
HTML file — fonts, icons and logic are inlined, so it runs with no network.

**Live:** https://hossamheiba.github.io/israf-survey-demo/

Runs an iPad and an iPhone side by side on one shared session. Arabic/English
with full RTL. Use the bottom bar to jump between screens, switch device, or
hide the mockups for a real-device run.

Figures shown in the app are illustrative placeholders for the demo.

## Updating

`index.html` is generated. Edit the source in the main project and copy it over:

```sh
cd "path/to/Survey AGS/web-demo" && node build.js
cp index.html ../../israf-survey-demo/index.html
cd ../../israf-survey-demo && git commit -am "Update demo" && git push
```

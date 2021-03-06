Ember Split View [![Build Status](https://travis-ci.org/BryanHunt/ember-split-view.svg?branch=master)](https://travis-ci.org/BryanHunt/ember-split-view)
================

See it in action: http://bryanhunt.github.io/ember-split-view

The demo app is here: https://github.com/BryanHunt/ember-split-view-demo

### Installation

If you are using ember-cli, you can install as an addon.

```
npm install --save-dev ember-split-view
```

### Examples
Vertical SplitView example:

```
{{#split-view isVertical=true}}
  {{#split-child}}
    Content of the left view here.
  {{/split-child}}
  {{split-sash}}
  {{#split-child}}
    Content of the right view here.
  {{/split-child}}
{{/split-view}}
```

Horizontal SplitView example:

```
{{#split-view isVertical=false}}
  {{#split-child}}
    Content of the top view here.
  {{/split-child}}
  {{split-sash}}
  {{#split-child}}
    Content of the bottom view here.
  {{/split-child}}
{{/split-view}}
```
 
### Donating

All donations will support this project and keep the developer supplied with Reese's Minis.

[![Support via Gittip](https://rawgithub.com/twolfson/gittip-badge/0.2.0/dist/gittip.png)](https://www.gittip.com/BryanHunt/)

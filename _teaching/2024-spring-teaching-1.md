---
title: "MDSC 689.11 - Modelling and Simulations"
collection: teaching
type: "Graduate course"
permalink: /teaching/2024-spring-teaching-1
venue: "University of Calgary"
date: 2025-03-30
location: "Calgary, Canada"
---

Supplementary course material for lecture MDSC 689.11 on Simulations

Powerpoint Slides
======

[Powerpoint slides Link](https://github.com/DrWalleTeaching/Modelling-and-Simulation/blob/main/240325_Simulations.pdf)

Code Examples (Jupyter Notebook, valid until 30.04.2025)
======

<script src="https://gist.github.com/wallematthias/ba934f12b2cc4fc6daf28c0672669198.js"></script>

<!DOCTYPE html>

<html lang="en">
<head><meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>modelling_and_simulation</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<style type="text/css">
    pre { line-height: 125%; }
td.linenos .normal { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
span.linenos { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
td.linenos .special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
span.linenos.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
.highlight .hll { background-color: var(--jp-cell-editor-active-background) }
.highlight { background: var(--jp-cell-editor-background); color: var(--jp-mirror-editor-variable-color) }
.highlight .c { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment */
.highlight .err { color: var(--jp-mirror-editor-error-color) } /* Error */
.highlight .k { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword */
.highlight .o { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator */
.highlight .p { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation */
.highlight .ch { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Multiline */
.highlight .cp { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Preproc */
.highlight .cpf { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Single */
.highlight .cs { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Special */
.highlight .kc { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Pseudo */
.highlight .kr { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Type */
.highlight .m { color: var(--jp-mirror-editor-number-color) } /* Literal.Number */
.highlight .s { color: var(--jp-mirror-editor-string-color) } /* Literal.String */
.highlight .ow { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator.Word */
.highlight .pm { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation.Marker */
.highlight .w { color: var(--jp-mirror-editor-variable-color) } /* Text.Whitespace */
.highlight .mb { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Bin */
.highlight .mf { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Float */
.highlight .mh { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Hex */
.highlight .mi { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer */
.highlight .mo { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Oct */
.highlight .sa { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Affix */
.highlight .sb { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Backtick */
.highlight .sc { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Char */
.highlight .dl { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Delimiter */
.highlight .sd { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Doc */
.highlight .s2 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Double */
.highlight .se { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Escape */
.highlight .sh { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Heredoc */
.highlight .si { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Interpol */
.highlight .sx { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Other */
.highlight .sr { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Regex */
.highlight .s1 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Single */
.highlight .ss { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Symbol */
.highlight .il { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer.Long */
  </style>
<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
 * Mozilla scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */
[data-jp-theme-scrollbars='true'] {
  scrollbar-color: rgb(var(--jp-scrollbar-thumb-color))
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar. These selectors
 * will match lower in the tree, and so will override the above */
[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
}

/* tiny scrollbar */

.jp-scrollbar-tiny {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
  scrollbar-width: thin;
}

/* tiny scrollbar */

.jp-scrollbar-tiny::-webkit-scrollbar,
.jp-scrollbar-tiny::-webkit-scrollbar-corner {
  background-color: transparent;
  height: 4px;
  width: 4px;
}

.jp-scrollbar-tiny::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:horizontal {
  border-left: 0 solid transparent;
  border-right: 0 solid transparent;
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:vertical {
  border-top: 0 solid transparent;
  border-bottom: 0 solid transparent;
}

/*
 * Lumino
 */

.lm-ScrollBar[data-orientation='horizontal'] {
  min-height: 16px;
  max-height: 16px;
  min-width: 45px;
  border-top: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] {
  min-width: 16px;
  max-width: 16px;
  min-height: 45px;
  border-left: 1px solid #a0a0a0;
}

.lm-ScrollBar-button {
  background-color: #f0f0f0;
  background-position: center center;
  min-height: 15px;
  max-height: 15px;
  min-width: 15px;
  max-width: 15px;
}

.lm-ScrollBar-button:hover {
  background-color: #dadada;
}

.lm-ScrollBar-button.lm-mod-active {
  background-color: #cdcdcd;
}

.lm-ScrollBar-track {
  background: #f0f0f0;
}

.lm-ScrollBar-thumb {
  background: #cdcdcd;
}

.lm-ScrollBar-thumb:hover {
  background: #bababa;
}

.lm-ScrollBar-thumb.lm-mod-active {
  background: #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal'] .lm-ScrollBar-thumb {
  height: 100%;
  min-width: 15px;
  border-left: 1px solid #a0a0a0;
  border-right: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] .lm-ScrollBar-thumb {
  width: 100%;
  min-height: 15px;
  border-top: 1px solid #a0a0a0;
  border-bottom: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-left);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-right);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-up);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-down);
  background-size: 17px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-Widget {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
}

.lm-Widget.lm-mod-hidden {
  display: none !important;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.lm-AccordionPanel[data-orientation='horizontal'] > .lm-AccordionPanel-title {
  /* Title is rotated for horizontal accordion panel using CSS */
  display: block;
  transform-origin: top left;
  transform: rotate(-90deg) translate(-100%);
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  display: flex;
  flex-direction: column;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-CommandPalette-search {
  flex: 0 0 auto;
}

.lm-CommandPalette-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  min-height: 0;
  overflow: auto;
  list-style-type: none;
}

.lm-CommandPalette-header {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.lm-CommandPalette-item {
  display: flex;
  flex-direction: row;
}

.lm-CommandPalette-itemIcon {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemContent {
  flex: 1 1 auto;
  overflow: hidden;
}

.lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemLabel {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.lm-close-icon {
  border: 1px solid transparent;
  background-color: transparent;
  position: absolute;
  z-index: 1;
  right: 3%;
  top: 0;
  bottom: 0;
  margin: auto;
  padding: 7px 0;
  display: none;
  vertical-align: middle;
  outline: 0;
  cursor: pointer;
}
.lm-close-icon:after {
  content: 'X';
  display: block;
  width: 15px;
  height: 15px;
  text-align: center;
  color: #000;
  font-weight: normal;
  font-size: 12px;
  cursor: pointer;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-DockPanel {
  z-index: 0;
}

.lm-DockPanel-widget {
  z-index: 0;
}

.lm-DockPanel-tabBar {
  z-index: 1;
}

.lm-DockPanel-handle {
  z-index: 2;
}

.lm-DockPanel-handle.lm-mod-hidden {
  display: none !important;
}

.lm-DockPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}

.lm-DockPanel-handle[data-orientation='horizontal'] {
  cursor: ew-resize;
}

.lm-DockPanel-handle[data-orientation='vertical'] {
  cursor: ns-resize;
}

.lm-DockPanel-handle[data-orientation='horizontal']:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}

.lm-DockPanel-handle[data-orientation='vertical']:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

.lm-DockPanel-overlay {
  z-index: 3;
  box-sizing: border-box;
  pointer-events: none;
}

.lm-DockPanel-overlay.lm-mod-hidden {
  display: none !important;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-Menu {
  z-index: 10000;
  position: absolute;
  white-space: nowrap;
  overflow-x: hidden;
  overflow-y: auto;
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-Menu-content {
  margin: 0;
  padding: 0;
  display: table;
  list-style-type: none;
}

.lm-Menu-item {
  display: table-row;
}

.lm-Menu-item.lm-mod-hidden,
.lm-Menu-item.lm-mod-collapsed {
  display: none !important;
}

.lm-Menu-itemIcon,
.lm-Menu-itemSubmenuIcon {
  display: table-cell;
  text-align: center;
}

.lm-Menu-itemLabel {
  display: table-cell;
  text-align: left;
}

.lm-Menu-itemShortcut {
  display: table-cell;
  text-align: right;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-MenuBar {
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-MenuBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: row;
  list-style-type: none;
}

.lm-MenuBar-item {
  box-sizing: border-box;
}

.lm-MenuBar-itemIcon,
.lm-MenuBar-itemLabel {
  display: inline-block;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-ScrollBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-ScrollBar[data-orientation='horizontal'] {
  flex-direction: row;
}

.lm-ScrollBar[data-orientation='vertical'] {
  flex-direction: column;
}

.lm-ScrollBar-button {
  box-sizing: border-box;
  flex: 0 0 auto;
}

.lm-ScrollBar-track {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  flex: 1 1 auto;
}

.lm-ScrollBar-thumb {
  box-sizing: border-box;
  position: absolute;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-SplitPanel-child {
  z-index: 0;
}

.lm-SplitPanel-handle {
  z-index: 1;
}

.lm-SplitPanel-handle.lm-mod-hidden {
  display: none !important;
}

.lm-SplitPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}

.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle {
  cursor: ew-resize;
}

.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle {
  cursor: ns-resize;
}

.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}

.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-TabBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-TabBar[data-orientation='horizontal'] {
  flex-direction: row;
  align-items: flex-end;
}

.lm-TabBar[data-orientation='vertical'] {
  flex-direction: column;
  align-items: flex-end;
}

.lm-TabBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex: 1 1 auto;
  list-style-type: none;
}

.lm-TabBar[data-orientation='horizontal'] > .lm-TabBar-content {
  flex-direction: row;
}

.lm-TabBar[data-orientation='vertical'] > .lm-TabBar-content {
  flex-direction: column;
}

.lm-TabBar-tab {
  display: flex;
  flex-direction: row;
  box-sizing: border-box;
  overflow: hidden;
  touch-action: none; /* Disable native Drag/Drop */
}

.lm-TabBar-tabIcon,
.lm-TabBar-tabCloseIcon {
  flex: 0 0 auto;
}

.lm-TabBar-tabLabel {
  flex: 1 1 auto;
  overflow: hidden;
  white-space: nowrap;
}

.lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing: border-box;
}

.lm-TabBar-tab.lm-mod-hidden {
  display: none !important;
}

.lm-TabBar-addButton.lm-mod-hidden {
  display: none !important;
}

.lm-TabBar.lm-mod-dragging .lm-TabBar-tab {
  position: relative;
}

.lm-TabBar.lm-mod-dragging[data-orientation='horizontal'] .lm-TabBar-tab {
  left: 0;
  transition: left 150ms ease;
}

.lm-TabBar.lm-mod-dragging[data-orientation='vertical'] .lm-TabBar-tab {
  top: 0;
  transition: top 150ms ease;
}

.lm-TabBar.lm-mod-dragging .lm-TabBar-tab.lm-mod-dragging {
  transition: none;
}

.lm-TabBar-tabLabel .lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing: border-box;
  background: inherit;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-TabPanel-tabBar {
  z-index: 1;
}

.lm-TabPanel-stackedPanel {
  z-index: 0;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapse {
  display: flex;
  flex-direction: column;
  align-items: stretch;
}

.jp-Collapse-header {
  padding: 1px 12px;
  background-color: var(--jp-layout-color1);
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  align-items: center;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  text-transform: uppercase;
  user-select: none;
}

.jp-Collapser-icon {
  height: 16px;
}

.jp-Collapse-header-collapsed .jp-Collapser-icon {
  transform: rotate(-90deg);
  margin: auto 0;
}

.jp-Collapser-title {
  line-height: 25px;
}

.jp-Collapse-contents {
  padding: 0 12px;
  background-color: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensureUiComponents() in @jupyterlab/buildutils */

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

/* Icons urls */

:root {
  --jp-icon-add-above: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwXzEzN18xOTQ5MikiPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGQ9Ik00Ljc1IDQuOTMwNjZINi42MjVWNi44MDU2NkM2LjYyNSA3LjAxMTkxIDYuNzkzNzUgNy4xODA2NiA3IDcuMTgwNjZDNy4yMDYyNSA3LjE4MDY2IDcuMzc1IDcuMDExOTEgNy4zNzUgNi44MDU2NlY0LjkzMDY2SDkuMjVDOS40NTYyNSA0LjkzMDY2IDkuNjI1IDQuNzYxOTEgOS42MjUgNC41NTU2NkM5LjYyNSA0LjM0OTQxIDkuNDU2MjUgNC4xODA2NiA5LjI1IDQuMTgwNjZINy4zNzVWMi4zMDU2NkM3LjM3NSAyLjA5OTQxIDcuMjA2MjUgMS45MzA2NiA3IDEuOTMwNjZDNi43OTM3NSAxLjkzMDY2IDYuNjI1IDIuMDk5NDEgNi42MjUgMi4zMDU2NlY0LjE4MDY2SDQuNzVDNC41NDM3NSA0LjE4MDY2IDQuMzc1IDQuMzQ5NDEgNC4zNzUgNC41NTU2NkM0LjM3NSA0Ljc2MTkxIDQuNTQzNzUgNC45MzA2NiA0Ljc1IDQuOTMwNjZaIiBmaWxsPSIjNjE2MTYxIiBzdHJva2U9IiM2MTYxNjEiIHN0cm9rZS13aWR0aD0iMC43Ii8+CjwvZz4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGNsaXAtcnVsZT0iZXZlbm9kZCIgZD0iTTExLjUgOS41VjExLjVMMi41IDExLjVWOS41TDExLjUgOS41Wk0xMiA4QzEyLjU1MjMgOCAxMyA4LjQ0NzcyIDEzIDlWMTJDMTMgMTIuNTUyMyAxMi41NTIzIDEzIDEyIDEzTDIgMTNDMS40NDc3MiAxMyAxIDEyLjU1MjMgMSAxMlY5QzEgOC40NDc3MiAxLjQ0NzcxIDggMiA4TDEyIDhaIiBmaWxsPSIjNjE2MTYxIi8+CjxkZWZzPgo8Y2xpcFBhdGggaWQ9ImNsaXAwXzEzN18xOTQ5MiI+CjxyZWN0IGNsYXNzPSJqcC1pY29uMyIgd2lkdGg9IjYiIGhlaWdodD0iNiIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0ibWF0cml4KC0xIDAgMCAxIDEwIDEuNTU1NjYpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==);
  --jp-icon-add-below: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwXzEzN18xOTQ5OCkiPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGQ9Ik05LjI1IDEwLjA2OTNMNy4zNzUgMTAuMDY5M0w3LjM3NSA4LjE5NDM0QzcuMzc1IDcuOTg4MDkgNy4yMDYyNSA3LjgxOTM0IDcgNy44MTkzNEM2Ljc5Mzc1IDcuODE5MzQgNi42MjUgNy45ODgwOSA2LjYyNSA4LjE5NDM0TDYuNjI1IDEwLjA2OTNMNC43NSAxMC4wNjkzQzQuNTQzNzUgMTAuMDY5MyA0LjM3NSAxMC4yMzgxIDQuMzc1IDEwLjQ0NDNDNC4zNzUgMTAuNjUwNiA0LjU0Mzc1IDEwLjgxOTMgNC43NSAxMC44MTkzTDYuNjI1IDEwLjgxOTNMNi42MjUgMTIuNjk0M0M2LjYyNSAxMi45MDA2IDYuNzkzNzUgMTMuMDY5MyA3IDEzLjA2OTNDNy4yMDYyNSAxMy4wNjkzIDcuMzc1IDEyLjkwMDYgNy4zNzUgMTIuNjk0M0w3LjM3NSAxMC44MTkzTDkuMjUgMTAuODE5M0M5LjQ1NjI1IDEwLjgxOTMgOS42MjUgMTAuNjUwNiA5LjYyNSAxMC40NDQzQzkuNjI1IDEwLjIzODEgOS40NTYyNSAxMC4wNjkzIDkuMjUgMTAuMDY5M1oiIGZpbGw9IiM2MTYxNjEiIHN0cm9rZT0iIzYxNjE2MSIgc3Ryb2tlLXdpZHRoPSIwLjciLz4KPC9nPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNMi41IDUuNUwyLjUgMy41TDExLjUgMy41TDExLjUgNS41TDIuNSA1LjVaTTIgN0MxLjQ0NzcyIDcgMSA2LjU1MjI4IDEgNkwxIDNDMSAyLjQ0NzcyIDEuNDQ3NzIgMiAyIDJMMTIgMkMxMi41NTIzIDIgMTMgMi40NDc3MiAxMyAzTDEzIDZDMTMgNi41NTIyOSAxMi41NTIzIDcgMTIgN0wyIDdaIiBmaWxsPSIjNjE2MTYxIi8+CjxkZWZzPgo8Y2xpcFBhdGggaWQ9ImNsaXAwXzEzN18xOTQ5OCI+CjxyZWN0IGNsYXNzPSJqcC1pY29uMyIgd2lkdGg9IjYiIGhlaWdodD0iNiIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0ibWF0cml4KDEgMS43NDg0NmUtMDcgMS43NDg0NmUtMDcgLTEgNCAxMy40NDQzKSIvPgo8L2NsaXBQYXRoPgo8L2RlZnM+Cjwvc3ZnPgo=);
  --jp-icon-add: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDEzaC02djZoLTJ2LTZINXYtMmg2VjVoMnY2aDZ2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bell: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE2IDE2IiB2ZXJzaW9uPSIxLjEiPgogICA8cGF0aCBjbGFzcz0ianAtaWNvbjIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMzMzMzMzIgogICAgICBkPSJtOCAwLjI5Yy0xLjQgMC0yLjcgMC43My0zLjYgMS44LTEuMiAxLjUtMS40IDMuNC0xLjUgNS4yLTAuMTggMi4yLTAuNDQgNC0yLjMgNS4zbDAuMjggMS4zaDVjMC4wMjYgMC42NiAwLjMyIDEuMSAwLjcxIDEuNSAwLjg0IDAuNjEgMiAwLjYxIDIuOCAwIDAuNTItMC40IDAuNi0xIDAuNzEtMS41aDVsMC4yOC0xLjNjLTEuOS0wLjk3LTIuMi0zLjMtMi4zLTUuMy0wLjEzLTEuOC0wLjI2LTMuNy0xLjUtNS4yLTAuODUtMS0yLjItMS44LTMuNi0xLjh6bTAgMS40YzAuODggMCAxLjkgMC41NSAyLjUgMS4zIDAuODggMS4xIDEuMSAyLjcgMS4yIDQuNCAwLjEzIDEuNyAwLjIzIDMuNiAxLjMgNS4yaC0xMGMxLjEtMS42IDEuMi0zLjQgMS4zLTUuMiAwLjEzLTEuNyAwLjMtMy4zIDEuMi00LjQgMC41OS0wLjcyIDEuNi0xLjMgMi41LTEuM3ptLTAuNzQgMTJoMS41Yy0wLjAwMTUgMC4yOCAwLjAxNSAwLjc5LTAuNzQgMC43OS0wLjczIDAuMDAxNi0wLjcyLTAuNTMtMC43NC0wLjc5eiIgLz4KPC9zdmc+Cg==);
  --jp-icon-bug-dot: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiPgogICAgICAgIDxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNMTcuMTkgOEgyMFYxMEgxNy45MUMxNy45NiAxMC4zMyAxOCAxMC42NiAxOCAxMVYxMkgyMFYxNEgxOC41SDE4VjE0LjAyNzVDMTUuNzUgMTQuMjc2MiAxNCAxNi4xODM3IDE0IDE4LjVDMTQgMTkuMjA4IDE0LjE2MzUgMTkuODc3OSAxNC40NTQ5IDIwLjQ3MzlDMTMuNzA2MyAyMC44MTE3IDEyLjg3NTcgMjEgMTIgMjFDOS43OCAyMSA3Ljg1IDE5Ljc5IDYuODEgMThINFYxNkg2LjA5QzYuMDQgMTUuNjcgNiAxNS4zNCA2IDE1VjE0SDRWMTJINlYxMUM2IDEwLjY2IDYuMDQgMTAuMzMgNi4wOSAxMEg0VjhINi44MUM3LjI2IDcuMjIgNy44OCA2LjU1IDguNjIgNi4wNEw3IDQuNDFMOC40MSAzTDEwLjU5IDUuMTdDMTEuMDQgNS4wNiAxMS41MSA1IDEyIDVDMTIuNDkgNSAxMi45NiA1LjA2IDEzLjQyIDUuMTdMMTUuNTkgM0wxNyA0LjQxTDE1LjM3IDYuMDRDMTYuMTIgNi41NSAxNi43NCA3LjIyIDE3LjE5IDhaTTEwIDE2SDE0VjE0SDEwVjE2Wk0xMCAxMkgxNFYxMEgxMFYxMloiIGZpbGw9IiM2MTYxNjEiLz4KICAgICAgICA8cGF0aCBkPSJNMjIgMTguNUMyMiAyMC40MzMgMjAuNDMzIDIyIDE4LjUgMjJDMTYuNTY3IDIyIDE1IDIwLjQzMyAxNSAxOC41QzE1IDE2LjU2NyAxNi41NjcgMTUgMTguNSAxNUMyMC40MzMgMTUgMjIgMTYuNTY3IDIyIDE4LjVaIiBmaWxsPSIjNjE2MTYxIi8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bug: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0yMCA4aC0yLjgxYy0uNDUtLjc4LTEuMDctMS40NS0xLjgyLTEuOTZMMTcgNC40MSAxNS41OSAzbC0yLjE3IDIuMTdDMTIuOTYgNS4wNiAxMi40OSA1IDEyIDVjLS40OSAwLS45Ni4wNi0xLjQxLjE3TDguNDEgMyA3IDQuNDFsMS42MiAxLjYzQzcuODggNi41NSA3LjI2IDcuMjIgNi44MSA4SDR2MmgyLjA5Yy0uMDUuMzMtLjA5LjY2LS4wOSAxdjFINHYyaDJ2MWMwIC4zNC4wNC42Ny4wOSAxSDR2MmgyLjgxYzEuMDQgMS43OSAyLjk3IDMgNS4xOSAzczQuMTUtMS4yMSA1LjE5LTNIMjB2LTJoLTIuMDljLjA1LS4zMy4wOS0uNjYuMDktMXYtMWgydi0yaC0ydi0xYzAtLjM0LS4wNC0uNjctLjA5LTFIMjBWOHptLTYgOGgtNHYtMmg0djJ6bTAtNGgtNHYtMmg0djJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-build: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE0LjkgMTcuNDVDMTYuMjUgMTcuNDUgMTcuMzUgMTYuMzUgMTcuMzUgMTVDMTcuMzUgMTMuNjUgMTYuMjUgMTIuNTUgMTQuOSAxMi41NUMxMy41NCAxMi41NSAxMi40NSAxMy42NSAxMi40NSAxNUMxMi40NSAxNi4zNSAxMy41NCAxNy40NSAxNC45IDE3LjQ1Wk0yMC4xIDE1LjY4TDIxLjU4IDE2Ljg0QzIxLjcxIDE2Ljk1IDIxLjc1IDE3LjEzIDIxLjY2IDE3LjI5TDIwLjI2IDE5LjcxQzIwLjE3IDE5Ljg2IDIwIDE5LjkyIDE5LjgzIDE5Ljg2TDE4LjA5IDE5LjE2QzE3LjczIDE5LjQ0IDE3LjMzIDE5LjY3IDE2LjkxIDE5Ljg1TDE2LjY0IDIxLjdDMTYuNjIgMjEuODcgMTYuNDcgMjIgMTYuMyAyMkgxMy41QzEzLjMyIDIyIDEzLjE4IDIxLjg3IDEzLjE1IDIxLjdMMTIuODkgMTkuODVDMTIuNDYgMTkuNjcgMTIuMDcgMTkuNDQgMTEuNzEgMTkuMTZMOS45NjAwMiAxOS44NkM5LjgxMDAyIDE5LjkyIDkuNjIwMDIgMTkuODYgOS41NDAwMiAxOS43MUw4LjE0MDAyIDE3LjI5QzguMDUwMDIgMTcuMTMgOC4wOTAwMiAxNi45NSA4LjIyMDAyIDE2Ljg0TDkuNzAwMDIgMTUuNjhMOS42NTAwMSAxNUw5LjcwMDAyIDE0LjMxTDguMjIwMDIgMTMuMTZDOC4wOTAwMiAxMy4wNSA4LjA1MDAyIDEyLjg2IDguMTQwMDIgMTIuNzFMOS41NDAwMiAxMC4yOUM5LjYyMDAyIDEwLjEzIDkuODEwMDIgMTAuMDcgOS45NjAwMiAxMC4xM0wxMS43MSAxMC44NEMxMi4wNyAxMC41NiAxMi40NiAxMC4zMiAxMi44OSAxMC4xNUwxMy4xNSA4LjI4OTk4QzEzLjE4IDguMTI5OTggMTMuMzIgNy45OTk5OCAxMy41IDcuOTk5OThIMTYuM0MxNi40NyA3Ljk5OTk4IDE2LjYyIDguMTI5OTggMTYuNjQgOC4yODk5OEwxNi45MSAxMC4xNUMxNy4zMyAxMC4zMiAxNy43MyAxMC41NiAxOC4wOSAxMC44NEwxOS44MyAxMC4xM0MyMCAxMC4wNyAyMC4xNyAxMC4xMyAyMC4yNiAxMC4yOUwyMS42NiAxMi43MUMyMS43NSAxMi44NiAyMS43MSAxMy4wNSAyMS41OCAxMy4xNkwyMC4xIDE0LjMxTDIwLjE1IDE1TDIwLjEgMTUuNjhaIi8+CiAgICA8cGF0aCBkPSJNNy4zMjk2NiA3LjQ0NDU0QzguMDgzMSA3LjAwOTU0IDguMzM5MzIgNi4wNTMzMiA3LjkwNDMyIDUuMjk5ODhDNy40NjkzMiA0LjU0NjQzIDYuNTA4MSA0LjI4MTU2IDUuNzU0NjYgNC43MTY1NkM1LjM5MTc2IDQuOTI2MDggNS4xMjY5NSA1LjI3MTE4IDUuMDE4NDkgNS42NzU5NEM0LjkxMDA0IDYuMDgwNzEgNC45NjY4MiA2LjUxMTk4IDUuMTc2MzQgNi44NzQ4OEM1LjYxMTM0IDcuNjI4MzIgNi41NzYyMiA3Ljg3OTU0IDcuMzI5NjYgNy40NDQ1NFpNOS42NTcxOCA0Ljc5NTkzTDEwLjg2NzIgNC45NTE3OUMxMC45NjI4IDQuOTc3NDEgMTEuMDQwMiA1LjA3MTMzIDExLjAzODIgNS4xODc5M0wxMS4wMzg4IDYuOTg4OTNDMTEuMDQ1NSA3LjEwMDU0IDEwLjk2MTYgNy4xOTUxOCAxMC44NTUgNy4yMTA1NEw5LjY2MDAxIDcuMzgwODNMOS4yMzkxNSA4LjEzMTg4TDkuNjY5NjEgOS4yNTc0NUM5LjcwNzI5IDkuMzYyNzEgOS42NjkzNCA5LjQ3Njk5IDkuNTc0MDggOS41MzE5OUw4LjAxNTIzIDEwLjQzMkM3LjkxMTMxIDEwLjQ5MiA3Ljc5MzM3IDEwLjQ2NzcgNy43MjEwNSAxMC4zODI0TDYuOTg3NDggOS40MzE4OEw2LjEwOTMxIDkuNDMwODNMNS4zNDcwNCAxMC4zOTA1QzUuMjg5MDkgMTAuNDcwMiA1LjE3MzgzIDEwLjQ5MDUgNS4wNzE4NyAxMC40MzM5TDMuNTEyNDUgOS41MzI5M0MzLjQxMDQ5IDkuNDc2MzMgMy4zNzY0NyA5LjM1NzQxIDMuNDEwNzUgOS4yNTY3OUwzLjg2MzQ3IDguMTQwOTNMMy42MTc0OSA3Ljc3NDg4TDMuNDIzNDcgNy4zNzg4M0wyLjIzMDc1IDcuMjEyOTdDMi4xMjY0NyA3LjE5MjM1IDIuMDQwNDkgNy4xMDM0MiAyLjA0MjQ1IDYuOTg2ODJMMi4wNDE4NyA1LjE4NTgyQzIuMDQzODMgNS4wNjkyMiAyLjExOTA5IDQuOTc5NTggMi4yMTcwNCA0Ljk2OTIyTDMuNDIwNjUgNC43OTM5M0wzLjg2NzQ5IDQuMDI3ODhMMy40MTEwNSAyLjkxNzMxQzMuMzczMzcgMi44MTIwNCAzLjQxMTMxIDIuNjk3NzYgMy41MTUyMyAyLjYzNzc2TDUuMDc0MDggMS43Mzc3NkM1LjE2OTM0IDEuNjgyNzYgNS4yODcyOSAxLjcwNzA0IDUuMzU5NjEgMS43OTIzMUw2LjExOTE1IDIuNzI3ODhMNi45ODAwMSAyLjczODkzTDcuNzI0OTYgMS43ODkyMkM3Ljc5MTU2IDEuNzA0NTggNy45MTU0OCAxLjY3OTIyIDguMDA4NzkgMS43NDA4Mkw5LjU2ODIxIDIuNjQxODJDOS42NzAxNyAyLjY5ODQyIDkuNzEyODUgMi44MTIzNCA5LjY4NzIzIDIuOTA3OTdMOS4yMTcxOCA0LjAzMzgzTDkuNDYzMTYgNC4zOTk4OEw5LjY1NzE4IDQuNzk1OTNaIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iOS45LDEzLjYgMy42LDcuNCA0LjQsNi42IDkuOSwxMi4yIDE1LjQsNi43IDE2LjEsNy40ICIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNS45TDksOS43bDMuOC0zLjhsMS4yLDEuMmwtNC45LDVsLTQuOS01TDUuMiw1Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNy41TDksMTEuMmwzLjgtMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-left: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik0xMC44LDEyLjhMNy4xLDlsMy44LTMuOGwwLDcuNkgxMC44eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-right: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik03LjIsNS4yTDEwLjksOWwtMy44LDMuOFY1LjJINy4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-up-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iMTUuNCwxMy4zIDkuOSw3LjcgNC40LDEzLjIgMy42LDEyLjUgOS45LDYuMyAxNi4xLDEyLjYgIi8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-up: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik01LjIsMTAuNUw5LDYuOGwzLjgsMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-case-sensitive: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWFjY2VudDIiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTcuNiw4aDAuOWwzLjUsOGgtMS4xTDEwLDE0SDZsLTAuOSwySDRMNy42LDh6IE04LDkuMUw2LjQsMTNoMy4yTDgsOS4xeiIvPgogICAgPHBhdGggZD0iTTE2LjYsOS44Yy0wLjIsMC4xLTAuNCwwLjEtMC43LDAuMWMtMC4yLDAtMC40LTAuMS0wLjYtMC4yYy0wLjEtMC4xLTAuMi0wLjQtMC4yLTAuNyBjLTAuMywwLjMtMC42LDAuNS0wLjksMC43Yy0wLjMsMC4xLTAuNywwLjItMS4xLDAuMmMtMC4zLDAtMC41LDAtMC43LTAuMWMtMC4yLTAuMS0wLjQtMC4yLTAuNi0wLjNjLTAuMi0wLjEtMC4zLTAuMy0wLjQtMC41IGMtMC4xLTAuMi0wLjEtMC40LTAuMS0wLjdjMC0wLjMsMC4xLTAuNiwwLjItMC44YzAuMS0wLjIsMC4zLTAuNCwwLjQtMC41QzEyLDcsMTIuMiw2LjksMTIuNSw2LjhjMC4yLTAuMSwwLjUtMC4xLDAuNy0wLjIgYzAuMy0wLjEsMC41LTAuMSwwLjctMC4xYzAuMiwwLDAuNC0wLjEsMC42LTAuMWMwLjIsMCwwLjMtMC4xLDAuNC0wLjJjMC4xLTAuMSwwLjItMC4yLDAuMi0wLjRjMC0xLTEuMS0xLTEuMy0xIGMtMC40LDAtMS40LDAtMS40LDEuMmgtMC45YzAtMC40LDAuMS0wLjcsMC4yLTFjMC4xLTAuMiwwLjMtMC40LDAuNS0wLjZjMC4yLTAuMiwwLjUtMC4zLDAuOC0wLjNDMTMuMyw0LDEzLjYsNCwxMy45LDQgYzAuMywwLDAuNSwwLDAuOCwwLjFjMC4zLDAsMC41LDAuMSwwLjcsMC4yYzAuMiwwLjEsMC40LDAuMywwLjUsMC41QzE2LDUsMTYsNS4yLDE2LDUuNnYyLjljMCwwLjIsMCwwLjQsMCwwLjUgYzAsMC4xLDAuMSwwLjIsMC4zLDAuMmMwLjEsMCwwLjIsMCwwLjMsMFY5Ljh6IE0xNS4yLDYuOWMtMS4yLDAuNi0zLjEsMC4yLTMuMSwxLjRjMCwxLjQsMy4xLDEsMy4xLTAuNVY2Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik05IDE2LjE3TDQuODMgMTJsLTEuNDIgMS40MUw5IDE5IDIxIDdsLTEuNDEtMS40MXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-circle-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDJDNi40NyAyIDIgNi40NyAyIDEyczQuNDcgMTAgMTAgMTAgMTAtNC40NyAxMC0xMFMxNy41MyAyIDEyIDJ6bTAgMThjLTQuNDEgMC04LTMuNTktOC04czMuNTktOCA4LTggOCAzLjU5IDggOC0zLjU5IDgtOCA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iOSIgY3k9IjkiIHI9IjgiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-clear: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8bWFzayBpZD0iZG9udXRIb2xlIj4KICAgIDxyZWN0IHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgZmlsbD0id2hpdGUiIC8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI4IiBmaWxsPSJibGFjayIvPgogIDwvbWFzaz4KCiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxyZWN0IGhlaWdodD0iMTgiIHdpZHRoPSIyIiB4PSIxMSIgeT0iMyIgdHJhbnNmb3JtPSJyb3RhdGUoMzE1LCAxMiwgMTIpIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxMCIgbWFzaz0idXJsKCNkb251dEhvbGUpIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-close: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1ub25lIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIGpwLWljb24zLWhvdmVyIiBmaWxsPSJub25lIj4KICAgIDxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjExIi8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIGpwLWljb24tYWNjZW50Mi1ob3ZlciIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMTkgNi40MUwxNy41OSA1IDEyIDEwLjU5IDYuNDEgNSA1IDYuNDEgMTAuNTkgMTIgNSAxNy41OSA2LjQxIDE5IDEyIDEzLjQxIDE3LjU5IDE5IDE5IDE3LjU5IDEzLjQxIDEyeiIvPgogIDwvZz4KCiAgPGcgY2xhc3M9ImpwLWljb24tbm9uZSBqcC1pY29uLWJ1c3kiIGZpbGw9Im5vbmUiPgogICAgPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-code-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBzaGFwZS1yZW5kZXJpbmc9Imdlb21ldHJpY1ByZWNpc2lvbiI+CiAgICA8cGF0aCBkPSJNNi41OSwzLjQxTDIsOEw2LjU5LDEyLjZMOCwxMS4xOEw0LjgyLDhMOCw0LjgyTDYuNTksMy40MU0xMi40MSwzLjQxTDExLDQuODJMMTQuMTgsOEwxMSwxMS4xOEwxMi40MSwxMi42TDE3LDhMMTIuNDEsMy40MU0yMS41OSwxMS41OUwxMy41LDE5LjY4TDkuODMsMTZMOC40MiwxNy40MUwxMy41LDIyLjVMMjMsMTNMMjEuNTksMTEuNTlaIiAvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-code: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTExLjQgMTguNkw2LjggMTRMMTEuNCA5LjRMMTAgOEw0IDE0TDEwIDIwTDExLjQgMTguNlpNMTYuNiAxOC42TDIxLjIgMTRMMTYuNiA5LjRMMTggOEwyNCAxNEwxOCAyMEwxNi42IDE4LjZWMTguNloiLz4KCTwvZz4KPC9zdmc+Cg==);
  --jp-icon-collapse-all: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTggMmMxIDAgMTEgMCAxMiAwczIgMSAyIDJjMCAxIDAgMTEgMCAxMnMwIDItMiAyQzIwIDE0IDIwIDQgMjAgNFMxMCA0IDYgNGMwLTIgMS0yIDItMnoiIC8+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTE4IDhjMC0xLTEtMi0yLTJTNSA2IDQgNnMtMiAxLTIgMmMwIDEgMCAxMSAwIDEyczEgMiAyIDJjMSAwIDExIDAgMTIgMHMyLTEgMi0yYzAtMSAwLTExIDAtMTJ6bS0yIDB2MTJINFY4eiIgLz4KICAgICAgICA8cGF0aCBkPSJNNiAxM3YyaDh2LTJ6IiAvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-console: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwMCAyMDAiPgogIDxnIGNsYXNzPSJqcC1jb25zb2xlLWljb24tYmFja2dyb3VuZC1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMjg4RDEiPgogICAgPHBhdGggZD0iTTIwIDE5LjhoMTYwdjE1OS45SDIweiIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtY29uc29sZS1pY29uLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIj4KICAgIDxwYXRoIGQ9Ik0xMDUgMTI3LjNoNDB2MTIuOGgtNDB6TTUxLjEgNzdMNzQgOTkuOWwtMjMuMyAyMy4zIDEwLjUgMTAuNSAyMy4zLTIzLjNMOTUgOTkuOSA4NC41IDg5LjQgNjEuNiA2Ni41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-copy: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTExLjksMUgzLjJDMi40LDEsMS43LDEuNywxLjcsMi41djEwLjJoMS41VjIuNWg4LjdWMXogTTE0LjEsMy45aC04Yy0wLjgsMC0xLjUsMC43LTEuNSwxLjV2MTAuMmMwLDAuOCwwLjcsMS41LDEuNSwxLjVoOCBjMC44LDAsMS41LTAuNywxLjUtMS41VjUuNEMxNS41LDQuNiwxNC45LDMuOSwxNC4xLDMuOXogTTE0LjEsMTUuNWgtOFY1LjRoOFYxNS41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-copyright: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDI0IDI0IiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCI+CiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0xMS44OCw5LjE0YzEuMjgsMC4wNiwxLjYxLDEuMTUsMS42MywxLjY2aDEuNzljLTAuMDgtMS45OC0xLjQ5LTMuMTktMy40NS0zLjE5QzkuNjQsNy42MSw4LDksOCwxMi4xNCBjMCwxLjk0LDAuOTMsNC4yNCwzLjg0LDQuMjRjMi4yMiwwLDMuNDEtMS42NSwzLjQ0LTIuOTVoLTEuNzljLTAuMDMsMC41OS0wLjQ1LDEuMzgtMS42MywxLjQ0QzEwLjU1LDE0LjgzLDEwLDEzLjgxLDEwLDEyLjE0IEMxMCw5LjI1LDExLjI4LDkuMTYsMTEuODgsOS4xNHogTTEyLDJDNi40OCwyLDIsNi40OCwyLDEyczQuNDgsMTAsMTAsMTBzMTAtNC40OCwxMC0xMFMxNy41MiwyLDEyLDJ6IE0xMiwyMGMtNC40MSwwLTgtMy41OS04LTggczMuNTktOCw4LThzOCwzLjU5LDgsOFMxNi40MSwyMCwxMiwyMHoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-cut: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkuNjQgNy42NGMuMjMtLjUuMzYtMS4wNS4zNi0xLjY0IDAtMi4yMS0xLjc5LTQtNC00UzIgMy43OSAyIDZzMS43OSA0IDQgNGMuNTkgMCAxLjE0LS4xMyAxLjY0LS4zNkwxMCAxMmwtMi4zNiAyLjM2QzcuMTQgMTQuMTMgNi41OSAxNCA2IDE0Yy0yLjIxIDAtNCAxLjc5LTQgNHMxLjc5IDQgNCA0IDQtMS43OSA0LTRjMC0uNTktLjEzLTEuMTQtLjM2LTEuNjRMMTIgMTRsNyA3aDN2LTFMOS42NCA3LjY0ek02IDhjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTAgMTJjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTYtNy41Yy0uMjggMC0uNS0uMjItLjUtLjVzLjIyLS41LjUtLjUuNS4yMi41LjUtLjIyLjUtLjUuNXpNMTkgM2wtNiA2IDIgMiA3LTdWM3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-delete: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2cHgiIGhlaWdodD0iMTZweCI+CiAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIiAvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjI2MjYyIiBkPSJNNiAxOWMwIDEuMS45IDIgMiAyaDhjMS4xIDAgMi0uOSAyLTJWN0g2djEyek0xOSA0aC0zLjVsLTEtMWgtNWwtMSAxSDV2MmgxNFY0eiIgLz4KPC9zdmc+Cg==);
  --jp-icon-download: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDloLTRWM0g5djZINWw3IDcgNy03ek01IDE4djJoMTR2LTJINXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-duplicate: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGNsaXAtcnVsZT0iZXZlbm9kZCIgZD0iTTIuNzk5OTggMC44NzVIOC44OTU4MkM5LjIwMDYxIDAuODc1IDkuNDQ5OTggMS4xMzkxNCA5LjQ0OTk4IDEuNDYxOThDOS40NDk5OCAxLjc4NDgyIDkuMjAwNjEgMi4wNDg5NiA4Ljg5NTgyIDIuMDQ4OTZIMy4zNTQxNUMzLjA0OTM2IDIuMDQ4OTYgMi43OTk5OCAyLjMxMzEgMi43OTk5OCAyLjYzNTk0VjkuNjc5NjlDMi43OTk5OCAxMC4wMDI1IDIuNTUwNjEgMTAuMjY2NyAyLjI0NTgyIDEwLjI2NjdDMS45NDEwMyAxMC4yNjY3IDEuNjkxNjUgMTAuMDAyNSAxLjY5MTY1IDkuNjc5NjlWMi4wNDg5NkMxLjY5MTY1IDEuNDAzMjggMi4xOTA0IDAuODc1IDIuNzk5OTggMC44NzVaTTUuMzY2NjUgMTEuOVY0LjU1SDExLjA4MzNWMTEuOUg1LjM2NjY1Wk00LjE0MTY1IDQuMTQxNjdDNC4xNDE2NSAzLjY5MDYzIDQuNTA3MjggMy4zMjUgNC45NTgzMiAzLjMyNUgxMS40OTE3QzExLjk0MjcgMy4zMjUgMTIuMzA4MyAzLjY5MDYzIDEyLjMwODMgNC4xNDE2N1YxMi4zMDgzQzEyLjMwODMgMTIuNzU5NCAxMS45NDI3IDEzLjEyNSAxMS40OTE3IDEzLjEyNUg0Ljk1ODMyQzQuNTA3MjggMTMuMTI1IDQuMTQxNjUgMTIuNzU5NCA0LjE0MTY1IDEyLjMwODNWNC4xNDE2N1oiIGZpbGw9IiM2MTYxNjEiLz4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNOS40MzU3NCA4LjI2NTA3SDguMzY0MzFWOS4zMzY1QzguMzY0MzEgOS40NTQzNSA4LjI2Nzg4IDkuNTUwNzggOC4xNTAwMiA5LjU1MDc4QzguMDMyMTcgOS41NTA3OCA3LjkzNTc0IDkuNDU0MzUgNy45MzU3NCA5LjMzNjVWOC4yNjUwN0g2Ljg2NDMxQzYuNzQ2NDUgOC4yNjUwNyA2LjY1MDAyIDguMTY4NjQgNi42NTAwMiA4LjA1MDc4QzYuNjUwMDIgNy45MzI5MiA2Ljc0NjQ1IDcuODM2NSA2Ljg2NDMxIDcuODM2NUg3LjkzNTc0VjYuNzY1MDdDNy45MzU3NCA2LjY0NzIxIDguMDMyMTcgNi41NTA3OCA4LjE1MDAyIDYuNTUwNzhDOC4yNjc4OCA2LjU1MDc4IDguMzY0MzEgNi42NDcyMSA4LjM2NDMxIDYuNzY1MDdWNy44MzY1SDkuNDM1NzRDOS41NTM2IDcuODM2NSA5LjY1MDAyIDcuOTMyOTIgOS42NTAwMiA4LjA1MDc4QzkuNjUwMDIgOC4xNjg2NCA5LjU1MzYgOC4yNjUwNyA5LjQzNTc0IDguMjY1MDdaIiBmaWxsPSIjNjE2MTYxIiBzdHJva2U9IiM2MTYxNjEiIHN0cm9rZS13aWR0aD0iMC41Ii8+Cjwvc3ZnPgo=);
  --jp-icon-edit: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMgMTcuMjVWMjFoMy43NUwxNy44MSA5Ljk0bC0zLjc1LTMuNzVMMyAxNy4yNXpNMjAuNzEgNy4wNGMuMzktLjM5LjM5LTEuMDIgMC0xLjQxbC0yLjM0LTIuMzRjLS4zOS0uMzktMS4wMi0uMzktMS40MSAwbC0xLjgzIDEuODMgMy43NSAzLjc1IDEuODMtMS44M3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-ellipses: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iNSIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxOSIgY3k9IjEyIiByPSIyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-error: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj48Y2lyY2xlIGN4PSIxMiIgY3k9IjE5IiByPSIyIi8+PHBhdGggZD0iTTEwIDNoNHYxMmgtNHoiLz48L2c+CjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0wIDBoMjR2MjRIMHoiLz4KPC9zdmc+Cg==);
  --jp-icon-expand-all: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTggMmMxIDAgMTEgMCAxMiAwczIgMSAyIDJjMCAxIDAgMTEgMCAxMnMwIDItMiAyQzIwIDE0IDIwIDQgMjAgNFMxMCA0IDYgNGMwLTIgMS0yIDItMnoiIC8+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTE4IDhjMC0xLTEtMi0yLTJTNSA2IDQgNnMtMiAxLTIgMmMwIDEgMCAxMSAwIDEyczEgMiAyIDJjMSAwIDExIDAgMTIgMHMyLTEgMi0yYzAtMSAwLTExIDAtMTJ6bS0yIDB2MTJINFY4eiIgLz4KICAgICAgICA8cGF0aCBkPSJNMTEgMTBIOXYzSDZ2MmgzdjNoMnYtM2gzdi0yaC0zeiIgLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-extension: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwLjUgMTFIMTlWN2MwLTEuMS0uOS0yLTItMmgtNFYzLjVDMTMgMi4xMiAxMS44OCAxIDEwLjUgMVM4IDIuMTIgOCAzLjVWNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAydjMuOEgzLjVjMS40OSAwIDIuNyAxLjIxIDIuNyAyLjdzLTEuMjEgMi43LTIuNyAyLjdIMlYyMGMwIDEuMS45IDIgMiAyaDMuOHYtMS41YzAtMS40OSAxLjIxLTIuNyAyLjctMi43IDEuNDkgMCAyLjcgMS4yMSAyLjcgMi43VjIySDE3YzEuMSAwIDItLjkgMi0ydi00aDEuNWMxLjM4IDAgMi41LTEuMTIgMi41LTIuNVMyMS44OCAxMSAyMC41IDExeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-fast-forward: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTQgMThsOC41LTZMNCA2djEyem05LTEydjEybDguNS02TDEzIDZ6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-file-upload: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkgMTZoNnYtNmg0bC03LTctNyA3aDR6bS00IDJoMTR2Mkg1eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-file: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuMyA4LjJsLTUuNS01LjVjLS4zLS4zLS43LS41LTEuMi0uNUgzLjljLS44LjEtMS42LjktMS42IDEuOHYxNC4xYzAgLjkuNyAxLjYgMS42IDEuNmgxNC4yYy45IDAgMS42LS43IDEuNi0xLjZWOS40Yy4xLS41LS4xLS45LS40LTEuMnptLTUuOC0zLjNsMy40IDMuNmgtMy40VjQuOXptMy45IDEyLjdINC43Yy0uMSAwLS4yIDAtLjItLjJWNC43YzAtLjIuMS0uMy4yLS4zaDcuMnY0LjRzMCAuOC4zIDEuMWMuMy4zIDEuMS4zIDEuMS4zaDQuM3Y3LjJzLS4xLjItLjIuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-filter-dot: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTE0LDEyVjE5Ljg4QzE0LjA0LDIwLjE4IDEzLjk0LDIwLjUgMTMuNzEsMjAuNzFDMTMuMzIsMjEuMSAxMi42OSwyMS4xIDEyLjMsMjAuNzFMMTAuMjksMTguN0MxMC4wNiwxOC40NyA5Ljk2LDE4LjE2IDEwLDE3Ljg3VjEySDkuOTdMNC4yMSw0LjYyQzMuODcsNC4xOSAzLjk1LDMuNTYgNC4zOCwzLjIyQzQuNTcsMy4wOCA0Ljc4LDMgNSwzVjNIMTlWM0MxOS4yMiwzIDE5LjQzLDMuMDggMTkuNjIsMy4yMkMyMC4wNSwzLjU2IDIwLjEzLDQuMTkgMTkuNzksNC42MkwxNC4wMywxMkgxNFoiIC8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWRvdCIgZmlsbD0iI0ZGRiI+CiAgICA8Y2lyY2xlIGN4PSIxOCIgY3k9IjE3IiByPSIzIj48L2NpcmNsZT4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-filter-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEwIDE4aDR2LTJoLTR2MnpNMyA2djJoMThWNkgzem0zIDdoMTJ2LTJINnYyeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-filter: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTE0LDEyVjE5Ljg4QzE0LjA0LDIwLjE4IDEzLjk0LDIwLjUgMTMuNzEsMjAuNzFDMTMuMzIsMjEuMSAxMi42OSwyMS4xIDEyLjMsMjAuNzFMMTAuMjksMTguN0MxMC4wNiwxOC40NyA5Ljk2LDE4LjE2IDEwLDE3Ljg3VjEySDkuOTdMNC4yMSw0LjYyQzMuODcsNC4xOSAzLjk1LDMuNTYgNC4zOCwzLjIyQzQuNTcsMy4wOCA0Ljc4LDMgNSwzVjNIMTlWM0MxOS4yMiwzIDE5LjQzLDMuMDggMTkuNjIsMy4yMkMyMC4wNSwzLjU2IDIwLjEzLDQuMTkgMTkuNzksNC42MkwxNC4wMywxMkgxNFoiIC8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-folder-favorite: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjRweCIgdmlld0JveD0iMCAwIDI0IDI0IiB3aWR0aD0iMjRweCIgZmlsbD0iIzAwMDAwMCI+CiAgPHBhdGggZD0iTTAgMGgyNHYyNEgwVjB6IiBmaWxsPSJub25lIi8+PHBhdGggY2xhc3M9ImpwLWljb24zIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxNjE2MSIgZD0iTTIwIDZoLThsLTItMkg0Yy0xLjEgMC0yIC45LTIgMnYxMmMwIDEuMS45IDIgMiAyaDE2YzEuMSAwIDItLjkgMi0yVjhjMC0xLjEtLjktMi0yLTJ6bS0yLjA2IDExTDE1IDE1LjI4IDEyLjA2IDE3bC43OC0zLjMzLTIuNTktMi4yNCAzLjQxLS4yOUwxNSA4bDEuMzQgMy4xNCAzLjQxLjI5LTIuNTkgMi4yNC43OCAzLjMzeiIvPgo8L3N2Zz4K);
  --jp-icon-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY4YzAtMS4xLS45LTItMi0yaC04bC0yLTJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-home: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjRweCIgdmlld0JveD0iMCAwIDI0IDI0IiB3aWR0aD0iMjRweCIgZmlsbD0iIzAwMDAwMCI+CiAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjxwYXRoIGNsYXNzPSJqcC1pY29uMyBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xMCAyMHYtNmg0djZoNXYtOGgzTDEyIDMgMiAxMmgzdjh6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-html5: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMDAiIGQ9Ik0xMDguNCAwaDIzdjIyLjhoMjEuMlYwaDIzdjY5aC0yM1Y0NmgtMjF2MjNoLTIzLjJNMjA2IDIzaC0yMC4zVjBoNjMuN3YyM0gyMjl2NDZoLTIzbTUzLjUtNjloMjQuMWwxNC44IDI0LjNMMzEzLjIgMGgyNC4xdjY5aC0yM1YzNC44bC0xNi4xIDI0LjgtMTYuMS0yNC44VjY5aC0yMi42bTg5LjItNjloMjN2NDYuMmgzMi42VjY5aC01NS42Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2U0NGQyNiIgZD0iTTEwNy42IDQ3MWwtMzMtMzcwLjRoMzYyLjhsLTMzIDM3MC4yTDI1NS43IDUxMiIvPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNmMTY1MjkiIGQ9Ik0yNTYgNDgwLjVWMTMxaDE0OC4zTDM3NiA0NDciLz4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNlYmViZWIiIGQ9Ik0xNDIgMTc2LjNoMTE0djQ1LjRoLTY0LjJsNC4yIDQ2LjVoNjB2NDUuM0gxNTQuNG0yIDIyLjhIMjAybDMuMiAzNi4zIDUwLjggMTMuNnY0Ny40bC05My4yLTI2Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIiBkPSJNMzY5LjYgMTc2LjNIMjU1Ljh2NDUuNGgxMDkuNm0tNC4xIDQ2LjVIMjU1Ljh2NDUuNGg1NmwtNS4zIDU5LTUwLjcgMTMuNnY0Ny4ybDkzLTI1LjgiLz4KPC9zdmc+Cg==);
  --jp-icon-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1icmFuZDQganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNGRkYiIGQ9Ik0yLjIgMi4yaDE3LjV2MTcuNUgyLjJ6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzNGNTFCNSIgZD0iTTIuMiAyLjJ2MTcuNWgxNy41bC4xLTE3LjVIMi4yem0xMi4xIDIuMmMxLjIgMCAyLjIgMSAyLjIgMi4ycy0xIDIuMi0yLjIgMi4yLTIuMi0xLTIuMi0yLjIgMS0yLjIgMi4yLTIuMnpNNC40IDE3LjZsMy4zLTguOCAzLjMgNi42IDIuMi0zLjIgNC40IDUuNEg0LjR6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-info: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUwLjk3OCA1MC45NzgiPgoJPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KCQk8cGF0aCBkPSJNNDMuNTIsNy40NThDMzguNzExLDIuNjQ4LDMyLjMwNywwLDI1LjQ4OSwwQzE4LjY3LDAsMTIuMjY2LDIuNjQ4LDcuNDU4LDcuNDU4CgkJCWMtOS45NDMsOS45NDEtOS45NDMsMjYuMTE5LDAsMzYuMDYyYzQuODA5LDQuODA5LDExLjIxMiw3LjQ1NiwxOC4wMzEsNy40NThjMCwwLDAuMDAxLDAsMC4wMDIsMAoJCQljNi44MTYsMCwxMy4yMjEtMi42NDgsMTguMDI5LTcuNDU4YzQuODA5LTQuODA5LDcuNDU3LTExLjIxMiw3LjQ1Ny0xOC4wM0M1MC45NzcsMTguNjcsNDguMzI4LDEyLjI2Niw0My41Miw3LjQ1OHoKCQkJIE00Mi4xMDYsNDIuMTA1Yy00LjQzMiw0LjQzMS0xMC4zMzIsNi44NzItMTYuNjE1LDYuODcyaC0wLjAwMmMtNi4yODUtMC4wMDEtMTIuMTg3LTIuNDQxLTE2LjYxNy02Ljg3MgoJCQljLTkuMTYyLTkuMTYzLTkuMTYyLTI0LjA3MSwwLTMzLjIzM0MxMy4zMDMsNC40NCwxOS4yMDQsMiwyNS40ODksMmM2LjI4NCwwLDEyLjE4NiwyLjQ0LDE2LjYxNyw2Ljg3MgoJCQljNC40MzEsNC40MzEsNi44NzEsMTAuMzMyLDYuODcxLDE2LjYxN0M0OC45NzcsMzEuNzcyLDQ2LjUzNiwzNy42NzUsNDIuMTA2LDQyLjEwNXoiLz4KCQk8cGF0aCBkPSJNMjMuNTc4LDMyLjIxOGMtMC4wMjMtMS43MzQsMC4xNDMtMy4wNTksMC40OTYtMy45NzJjMC4zNTMtMC45MTMsMS4xMS0xLjk5NywyLjI3Mi0zLjI1MwoJCQljMC40NjgtMC41MzYsMC45MjMtMS4wNjIsMS4zNjctMS41NzVjMC42MjYtMC43NTMsMS4xMDQtMS40NzgsMS40MzYtMi4xNzVjMC4zMzEtMC43MDcsMC40OTUtMS41NDEsMC40OTUtMi41CgkJCWMwLTEuMDk2LTAuMjYtMi4wODgtMC43NzktMi45NzljLTAuNTY1LTAuODc5LTEuNTAxLTEuMzM2LTIuODA2LTEuMzY5Yy0xLjgwMiwwLjA1Ny0yLjk4NSwwLjY2Ny0zLjU1LDEuODMyCgkJCWMtMC4zMDEsMC41MzUtMC41MDMsMS4xNDEtMC42MDcsMS44MTRjLTAuMTM5LDAuNzA3LTAuMjA3LDEuNDMyLTAuMjA3LDIuMTc0aC0yLjkzN2MtMC4wOTEtMi4yMDgsMC40MDctNC4xMTQsMS40OTMtNS43MTkKCQkJYzEuMDYyLTEuNjQsMi44NTUtMi40ODEsNS4zNzgtMi41MjdjMi4xNiwwLjAyMywzLjg3NCwwLjYwOCw1LjE0MSwxLjc1OGMxLjI3OCwxLjE2LDEuOTI5LDIuNzY0LDEuOTUsNC44MTEKCQkJYzAsMS4xNDItMC4xMzcsMi4xMTEtMC40MSwyLjkxMWMtMC4zMDksMC44NDUtMC43MzEsMS41OTMtMS4yNjgsMi4yNDNjLTAuNDkyLDAuNjUtMS4wNjgsMS4zMTgtMS43MywyLjAwMgoJCQljLTAuNjUsMC42OTctMS4zMTMsMS40NzktMS45ODcsMi4zNDZjLTAuMjM5LDAuMzc3LTAuNDI5LDAuNzc3LTAuNTY1LDEuMTk5Yy0wLjE2LDAuOTU5LTAuMjE3LDEuOTUxLTAuMTcxLDIuOTc5CgkJCUMyNi41ODksMzIuMjE4LDIzLjU3OCwzMi4yMTgsMjMuNTc4LDMyLjIxOHogTTIzLjU3OCwzOC4yMnYtMy40ODRoMy4wNzZ2My40ODRIMjMuNTc4eiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-inspector: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaW5zcGVjdG9yLWljb24tY29sb3IganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY2YzAtMS4xLS45LTItMi0yem0tNSAxNEg0di00aDExdjR6bTAtNUg0VjloMTF2NHptNSA1aC00VjloNHY5eiIvPgo8L3N2Zz4K);
  --jp-icon-json: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtanNvbi1pY29uLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI0Y5QTgyNSI+CiAgICA8cGF0aCBkPSJNMjAuMiAxMS44Yy0xLjYgMC0xLjcuNS0xLjcgMSAwIC40LjEuOS4xIDEuMy4xLjUuMS45LjEgMS4zIDAgMS43LTEuNCAyLjMtMy41IDIuM2gtLjl2LTEuOWguNWMxLjEgMCAxLjQgMCAxLjQtLjggMC0uMyAwLS42LS4xLTEgMC0uNC0uMS0uOC0uMS0xLjIgMC0xLjMgMC0xLjggMS4zLTItMS4zLS4yLTEuMy0uNy0xLjMtMiAwLS40LjEtLjguMS0xLjIuMS0uNC4xLS43LjEtMSAwLS44LS40LS43LTEuNC0uOGgtLjVWNC4xaC45YzIuMiAwIDMuNS43IDMuNSAyLjMgMCAuNC0uMS45LS4xIDEuMy0uMS41LS4xLjktLjEgMS4zIDAgLjUuMiAxIDEuNyAxdjEuOHpNMS44IDEwLjFjMS42IDAgMS43LS41IDEuNy0xIDAtLjQtLjEtLjktLjEtMS4zLS4xLS41LS4xLS45LS4xLTEuMyAwLTEuNiAxLjQtMi4zIDMuNS0yLjNoLjl2MS45aC0uNWMtMSAwLTEuNCAwLTEuNC44IDAgLjMgMCAuNi4xIDEgMCAuMi4xLjYuMSAxIDAgMS4zIDAgMS44LTEuMyAyQzYgMTEuMiA2IDExLjcgNiAxM2MwIC40LS4xLjgtLjEgMS4yLS4xLjMtLjEuNy0uMSAxIDAgLjguMy44IDEuNC44aC41djEuOWgtLjljLTIuMSAwLTMuNS0uNi0zLjUtMi4zIDAtLjQuMS0uOS4xLTEuMy4xLS41LjEtLjkuMS0xLjMgMC0uNS0uMi0xLTEuNy0xdi0xLjl6Ii8+CiAgICA8Y2lyY2xlIGN4PSIxMSIgY3k9IjEzLjgiIHI9IjIuMSIvPgogICAgPGNpcmNsZSBjeD0iMTEiIGN5PSI4LjIiIHI9IjIuMSIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-julia: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDMyNSAzMDAiPgogIDxnIGNsYXNzPSJqcC1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjY2IzYzMzIj4KICAgIDxwYXRoIGQ9Ik0gMTUwLjg5ODQzOCAyMjUgQyAxNTAuODk4NDM4IDI2Ni40MjE4NzUgMTE3LjMyMDMxMiAzMDAgNzUuODk4NDM4IDMwMCBDIDM0LjQ3NjU2MiAzMDAgMC44OTg0MzggMjY2LjQyMTg3NSAwLjg5ODQzOCAyMjUgQyAwLjg5ODQzOCAxODMuNTc4MTI1IDM0LjQ3NjU2MiAxNTAgNzUuODk4NDM4IDE1MCBDIDExNy4zMjAzMTIgMTUwIDE1MC44OTg0MzggMTgzLjU3ODEyNSAxNTAuODk4NDM4IDIyNSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzM4OTgyNiI+CiAgICA8cGF0aCBkPSJNIDIzNy41IDc1IEMgMjM3LjUgMTE2LjQyMTg3NSAyMDMuOTIxODc1IDE1MCAxNjIuNSAxNTAgQyAxMjEuMDc4MTI1IDE1MCA4Ny41IDExNi40MjE4NzUgODcuNSA3NSBDIDg3LjUgMzMuNTc4MTI1IDEyMS4wNzgxMjUgMCAxNjIuNSAwIEMgMjAzLjkyMTg3NSAwIDIzNy41IDMzLjU3ODEyNSAyMzcuNSA3NSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzk1NThiMiI+CiAgICA8cGF0aCBkPSJNIDMyNC4xMDE1NjIgMjI1IEMgMzI0LjEwMTU2MiAyNjYuNDIxODc1IDI5MC41MjM0MzggMzAwIDI0OS4xMDE1NjIgMzAwIEMgMjA3LjY3OTY4OCAzMDAgMTc0LjEwMTU2MiAyNjYuNDIxODc1IDE3NC4xMDE1NjIgMjI1IEMgMTc0LjEwMTU2MiAxODMuNTc4MTI1IDIwNy42Nzk2ODggMTUwIDI0OS4xMDE1NjIgMTUwIEMgMjkwLjUyMzQzOCAxNTAgMzI0LjEwMTU2MiAxODMuNTc4MTI1IDMyNC4xMDE1NjIgMjI1Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-jupyter-favicon: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTUyIiBoZWlnaHQ9IjE2NSIgdmlld0JveD0iMCAwIDE1MiAxNjUiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgPGcgY2xhc3M9ImpwLWp1cHl0ZXItaWNvbi1jb2xvciIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA3ODk0NywgMTEwLjU4MjkyNykiIGQ9Ik03NS45NDIyODQyLDI5LjU4MDQ1NjEgQzQzLjMwMjM5NDcsMjkuNTgwNDU2MSAxNC43OTY3ODMyLDE3LjY1MzQ2MzQgMCwwIEM1LjUxMDgzMjExLDE1Ljg0MDY4MjkgMTUuNzgxNTM4OSwyOS41NjY3NzMyIDI5LjM5MDQ5NDcsMzkuMjc4NDE3MSBDNDIuOTk5Nyw0OC45ODk4NTM3IDU5LjI3MzcsNTQuMjA2NzgwNSA3NS45NjA1Nzg5LDU0LjIwNjc4MDUgQzkyLjY0NzQ1NzksNTQuMjA2NzgwNSAxMDguOTIxNDU4LDQ4Ljk4OTg1MzcgMTIyLjUzMDY2MywzOS4yNzg0MTcxIEMxMzYuMTM5NDUzLDI5LjU2Njc3MzIgMTQ2LjQxMDI4NCwxNS44NDA2ODI5IDE1MS45MjExNTgsMCBDMTM3LjA4Nzg2OCwxNy42NTM0NjM0IDEwOC41ODI1ODksMjkuNTgwNDU2MSA3NS45NDIyODQyLDI5LjU4MDQ1NjEgTDc1Ljk0MjI4NDIsMjkuNTgwNDU2MSBaIiAvPgogICAgPHBhdGggdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMzczNjgsIDAuNzA0ODc4KSIgZD0iTTc1Ljk3ODQ1NzksMjQuNjI2NDA3MyBDMTA4LjYxODc2MywyNC42MjY0MDczIDEzNy4xMjQ0NTgsMzYuNTUzNDQxNSAxNTEuOTIxMTU4LDU0LjIwNjc4MDUgQzE0Ni40MTAyODQsMzguMzY2MjIyIDEzNi4xMzk0NTMsMjQuNjQwMTMxNyAxMjIuNTMwNjYzLDE0LjkyODQ4NzggQzEwOC45MjE0NTgsNS4yMTY4NDM5IDkyLjY0NzQ1NzksMCA3NS45NjA1Nzg5LDAgQzU5LjI3MzcsMCA0Mi45OTk3LDUuMjE2ODQzOSAyOS4zOTA0OTQ3LDE0LjkyODQ4NzggQzE1Ljc4MTUzODksMjQuNjQwMTMxNyA1LjUxMDgzMjExLDM4LjM2NjIyMiAwLDU0LjIwNjc4MDUgQzE0LjgzMzA4MTYsMzYuNTg5OTI5MyA0My4zMzg1Njg0LDI0LjYyNjQwNzMgNzUuOTc4NDU3OSwyNC42MjY0MDczIEw3NS45Nzg0NTc5LDI0LjYyNjQwNzMgWiIgLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-jupyter: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzkiIGhlaWdodD0iNTEiIHZpZXdCb3g9IjAgMCAzOSA1MSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMTYzOCAtMjI4MSkiPgogICAgIDxnIGNsYXNzPSJqcC1qdXB5dGVyLWljb24tY29sb3IiIGZpbGw9IiNGMzc3MjYiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5Ljc0IDIzMTEuOTgpIiBkPSJNIDE4LjI2NDYgNy4xMzQxMUMgMTAuNDE0NSA3LjEzNDExIDMuNTU4NzIgNC4yNTc2IDAgMEMgMS4zMjUzOSAzLjgyMDQgMy43OTU1NiA3LjEzMDgxIDcuMDY4NiA5LjQ3MzAzQyAxMC4zNDE3IDExLjgxNTIgMTQuMjU1NyAxMy4wNzM0IDE4LjI2OSAxMy4wNzM0QyAyMi4yODIzIDEzLjA3MzQgMjYuMTk2MyAxMS44MTUyIDI5LjQ2OTQgOS40NzMwM0MgMzIuNzQyNCA3LjEzMDgxIDM1LjIxMjYgMy44MjA0IDM2LjUzOCAwQyAzMi45NzA1IDQuMjU3NiAyNi4xMTQ4IDcuMTM0MTEgMTguMjY0NiA3LjEzNDExWiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5LjczIDIyODUuNDgpIiBkPSJNIDE4LjI3MzMgNS45MzkzMUMgMjYuMTIzNSA1LjkzOTMxIDMyLjk3OTMgOC44MTU4MyAzNi41MzggMTMuMDczNEMgMzUuMjEyNiA5LjI1MzAzIDMyLjc0MjQgNS45NDI2MiAyOS40Njk0IDMuNjAwNEMgMjYuMTk2MyAxLjI1ODE4IDIyLjI4MjMgMCAxOC4yNjkgMEMgMTQuMjU1NyAwIDEwLjM0MTcgMS4yNTgxOCA3LjA2ODYgMy42MDA0QyAzLjc5NTU2IDUuOTQyNjIgMS4zMjUzOSA5LjI1MzAzIDAgMTMuMDczNEMgMy41Njc0NSA4LjgyNDYzIDEwLjQyMzIgNS45MzkzMSAxOC4yNzMzIDUuOTM5MzFaIi8+CiAgICA8L2c+CiAgICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjY5LjMgMjI4MS4zMSkiIGQ9Ik0gNS44OTM1MyAyLjg0NEMgNS45MTg4OSAzLjQzMTY1IDUuNzcwODUgNC4wMTM2NyA1LjQ2ODE1IDQuNTE2NDVDIDUuMTY1NDUgNS4wMTkyMiA0LjcyMTY4IDUuNDIwMTUgNC4xOTI5OSA1LjY2ODUxQyAzLjY2NDMgNS45MTY4OCAzLjA3NDQ0IDYuMDAxNTEgMi40OTgwNSA1LjkxMTcxQyAxLjkyMTY2IDUuODIxOSAxLjM4NDYzIDUuNTYxNyAwLjk1NDg5OCA1LjE2NDAxQyAwLjUyNTE3IDQuNzY2MzMgMC4yMjIwNTYgNC4yNDkwMyAwLjA4MzkwMzcgMy42Nzc1N0MgLTAuMDU0MjQ4MyAzLjEwNjExIC0wLjAyMTIzIDIuNTA2MTcgMC4xNzg3ODEgMS45NTM2NEMgMC4zNzg3OTMgMS40MDExIDAuNzM2ODA5IDAuOTIwODE3IDEuMjA3NTQgMC41NzM1MzhDIDEuNjc4MjYgMC4yMjYyNTkgMi4yNDA1NSAwLjAyNzU5MTkgMi44MjMyNiAwLjAwMjY3MjI5QyAzLjYwMzg5IC0wLjAzMDcxMTUgNC4zNjU3MyAwLjI0OTc4OSA0Ljk0MTQyIDAuNzgyNTUxQyA1LjUxNzExIDEuMzE1MzEgNS44NTk1NiAyLjA1Njc2IDUuODkzNTMgMi44NDRaIi8+CiAgICAgIDxwYXRoIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE2MzkuOCAyMzIzLjgxKSIgZD0iTSA3LjQyNzg5IDMuNTgzMzhDIDcuNDYwMDggNC4zMjQzIDcuMjczNTUgNS4wNTgxOSA2Ljg5MTkzIDUuNjkyMTNDIDYuNTEwMzEgNi4zMjYwNyA1Ljk1MDc1IDYuODMxNTYgNS4yODQxMSA3LjE0NDZDIDQuNjE3NDcgNy40NTc2MyAzLjg3MzcxIDcuNTY0MTQgMy4xNDcwMiA3LjQ1MDYzQyAyLjQyMDMyIDcuMzM3MTIgMS43NDMzNiA3LjAwODcgMS4yMDE4NCA2LjUwNjk1QyAwLjY2MDMyOCA2LjAwNTIgMC4yNzg2MSA1LjM1MjY4IDAuMTA1MDE3IDQuNjMyMDJDIC0wLjA2ODU3NTcgMy45MTEzNSAtMC4wMjYyMzYxIDMuMTU0OTQgMC4yMjY2NzUgMi40NTg1NkMgMC40Nzk1ODcgMS43NjIxNyAwLjkzMTY5NyAxLjE1NzEzIDEuNTI1NzYgMC43MjAwMzNDIDIuMTE5ODMgMC4yODI5MzUgMi44MjkxNCAwLjAzMzQzOTUgMy41NjM4OSAwLjAwMzEzMzQ0QyA0LjU0NjY3IC0wLjAzNzQwMzMgNS41MDUyOSAwLjMxNjcwNiA2LjIyOTYxIDAuOTg3ODM1QyA2Ljk1MzkzIDEuNjU4OTYgNy4zODQ4NCAyLjU5MjM1IDcuNDI3ODkgMy41ODMzOEwgNy40Mjc4OSAzLjU4MzM4WiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM4LjM2IDIyODYuMDYpIiBkPSJNIDIuMjc0NzEgNC4zOTYyOUMgMS44NDM2MyA0LjQxNTA4IDEuNDE2NzEgNC4zMDQ0NSAxLjA0Nzk5IDQuMDc4NDNDIDAuNjc5MjY4IDMuODUyNCAwLjM4NTMyOCAzLjUyMTE0IDAuMjAzMzcxIDMuMTI2NTZDIDAuMDIxNDEzNiAyLjczMTk4IC0wLjA0MDM3OTggMi4yOTE4MyAwLjAyNTgxMTYgMS44NjE4MUMgMC4wOTIwMDMxIDEuNDMxOCAwLjI4MzIwNCAxLjAzMTI2IDAuNTc1MjEzIDAuNzEwODgzQyAwLjg2NzIyMiAwLjM5MDUxIDEuMjQ2OTEgMC4xNjQ3MDggMS42NjYyMiAwLjA2MjA1OTJDIDIuMDg1NTMgLTAuMDQwNTg5NyAyLjUyNTYxIC0wLjAxNTQ3MTQgMi45MzA3NiAwLjEzNDIzNUMgMy4zMzU5MSAwLjI4Mzk0MSAzLjY4NzkyIDAuNTUxNTA1IDMuOTQyMjIgMC45MDMwNkMgNC4xOTY1MiAxLjI1NDYyIDQuMzQxNjkgMS42NzQzNiA0LjM1OTM1IDIuMTA5MTZDIDQuMzgyOTkgMi42OTEwNyA0LjE3Njc4IDMuMjU4NjkgMy43ODU5NyAzLjY4NzQ2QyAzLjM5NTE2IDQuMTE2MjQgMi44NTE2NiA0LjM3MTE2IDIuMjc0NzEgNC4zOTYyOUwgMi4yNzQ3MSA0LjM5NjI5WiIvPgogICAgPC9nPgogIDwvZz4+Cjwvc3ZnPgo=);
  --jp-icon-jupyterlab-wordmark: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIHZpZXdCb3g9IjAgMCAxODYwLjggNDc1Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0RTRFNEUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDQ4MC4xMzY0MDEsIDY0LjI3MTQ5MykiPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMDAwMDAsIDU4Ljg3NTU2NikiPgogICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA4NzYwMywgMC4xNDAyOTQpIj4KICAgICAgICA8cGF0aCBkPSJNLTQyNi45LDE2OS44YzAsNDguNy0zLjcsNjQuNy0xMy42LDc2LjRjLTEwLjgsMTAtMjUsMTUuNS0zOS43LDE1LjVsMy43LDI5IGMyMi44LDAuMyw0NC44LTcuOSw2MS45LTIzLjFjMTcuOC0xOC41LDI0LTQ0LjEsMjQtODMuM1YwSC00Mjd2MTcwLjFMLTQyNi45LDE2OS44TC00MjYuOSwxNjkuOHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTU1LjA0NTI5NiwgNTYuODM3MTA0KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuNTYyNDUzLCAxLjc5OTg0MikiPgogICAgICAgIDxwYXRoIGQ9Ik0tMzEyLDE0OGMwLDIxLDAsMzkuNSwxLjcsNTUuNGgtMzEuOGwtMi4xLTMzLjNoLTAuOGMtNi43LDExLjYtMTYuNCwyMS4zLTI4LDI3LjkgYy0xMS42LDYuNi0yNC44LDEwLTM4LjIsOS44Yy0zMS40LDAtNjktMTcuNy02OS04OVYwaDM2LjR2MTEyLjdjMCwzOC43LDExLjYsNjQuNyw0NC42LDY0LjdjMTAuMy0wLjIsMjAuNC0zLjUsMjguOS05LjQgYzguNS01LjksMTUuMS0xNC4zLDE4LjktMjMuOWMyLjItNi4xLDMuMy0xMi41LDMuMy0xOC45VjAuMmgzNi40VjE0OEgtMzEyTC0zMTIsMTQ4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzOTAuMDEzMzIyLCA1My40Nzk2MzgpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS43MDY0NTgsIDAuMjMxNDI1KSI+CiAgICAgICAgPHBhdGggZD0iTS00NzguNiw3MS40YzAtMjYtMC44LTQ3LTEuNy02Ni43aDMyLjdsMS43LDM0LjhoMC44YzcuMS0xMi41LDE3LjUtMjIuOCwzMC4xLTI5LjcgYzEyLjUtNywyNi43LTEwLjMsNDEtOS44YzQ4LjMsMCw4NC43LDQxLjcsODQuNywxMDMuM2MwLDczLjEtNDMuNywxMDkuMi05MSwxMDkuMmMtMTIuMSwwLjUtMjQuMi0yLjItMzUtNy44IGMtMTAuOC01LjYtMTkuOS0xMy45LTI2LjYtMjQuMmgtMC44VjI5MWgtMzZ2LTIyMEwtNDc4LjYsNzEuNEwtNDc4LjYsNzEuNHogTS00NDIuNiwxMjUuNmMwLjEsNS4xLDAuNiwxMC4xLDEuNywxNS4xIGMzLDEyLjMsOS45LDIzLjMsMTkuOCwzMS4xYzkuOSw3LjgsMjIuMSwxMi4xLDM0LjcsMTIuMWMzOC41LDAsNjAuNy0zMS45LDYwLjctNzguNWMwLTQwLjctMjEuMS03NS42LTU5LjUtNzUuNiBjLTEyLjksMC40LTI1LjMsNS4xLTM1LjMsMTMuNGMtOS45LDguMy0xNi45LDE5LjctMTkuNiwzMi40Yy0xLjUsNC45LTIuMywxMC0yLjUsMTUuMVYxMjUuNkwtNDQyLjYsMTI1LjZMLTQ0Mi42LDEyNS42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg2MDYuNzQwNzI2LCA1Ni44MzcxMDQpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC43NTEyMjYsIDEuOTg5Mjk5KSI+CiAgICAgICAgPHBhdGggZD0iTS00NDAuOCwwbDQzLjcsMTIwLjFjNC41LDEzLjQsOS41LDI5LjQsMTIuOCw0MS43aDAuOGMzLjctMTIuMiw3LjktMjcuNywxMi44LTQyLjQgbDM5LjctMTE5LjJoMzguNUwtMzQ2LjksMTQ1Yy0yNiw2OS43LTQzLjcsMTA1LjQtNjguNiwxMjcuMmMtMTIuNSwxMS43LTI3LjksMjAtNDQuNiwyMy45bC05LjEtMzEuMSBjMTEuNy0zLjksMjIuNS0xMC4xLDMxLjgtMTguMWMxMy4yLTExLjEsMjMuNy0yNS4yLDMwLjYtNDEuMmMxLjUtMi44LDIuNS01LjcsMi45LTguOGMtMC4zLTMuMy0xLjItNi42LTIuNS05LjdMLTQ4MC4yLDAuMSBoMzkuN0wtNDQwLjgsMEwtNDQwLjgsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoODIyLjc0ODEwNCwgMC4wMDAwMDApIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS40NjQwNTAsIDAuMzc4OTE0KSI+CiAgICAgICAgPHBhdGggZD0iTS00MTMuNywwdjU4LjNoNTJ2MjguMmgtNTJWMTk2YzAsMjUsNywzOS41LDI3LjMsMzkuNWM3LjEsMC4xLDE0LjItMC43LDIxLjEtMi41IGwxLjcsMjcuN2MtMTAuMywzLjctMjEuMyw1LjQtMzIuMiw1Yy03LjMsMC40LTE0LjYtMC43LTIxLjMtMy40Yy02LjgtMi43LTEyLjktNi44LTE3LjktMTIuMWMtMTAuMy0xMC45LTE0LjEtMjktMTQuMS01Mi45IFY4Ni41aC0zMVY1OC4zaDMxVjkuNkwtNDEzLjcsMEwtNDEzLjcsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTc0LjQzMzI4NiwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAuOTkwMDM0LCAwLjYxMDMzOSkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDQ1LjgsMTEzYzAuOCw1MCwzMi4yLDcwLjYsNjguNiw3MC42YzE5LDAuNiwzNy45LTMsNTUuMy0xMC41bDYuMiwyNi40IGMtMjAuOSw4LjktNDMuNSwxMy4xLTY2LjIsMTIuNmMtNjEuNSwwLTk4LjMtNDEuMi05OC4zLTEwMi41Qy00ODAuMiw0OC4yLTQ0NC43LDAtMzg2LjUsMGM2NS4yLDAsODIuNyw1OC4zLDgyLjcsOTUuNyBjLTAuMSw1LjgtMC41LDExLjUtMS4yLDE3LjJoLTE0MC42SC00NDUuOEwtNDQ1LjgsMTEzeiBNLTMzOS4yLDg2LjZjMC40LTIzLjUtOS41LTYwLjEtNTAuNC02MC4xIGMtMzYuOCwwLTUyLjgsMzQuNC01NS43LDYwLjFILTMzOS4yTC0zMzkuMiw4Ni42TC0zMzkuMiw4Ni42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMjAxLjk2MTA1OCwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuMTc5NjQwLCAwLjcwNTA2OCkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDc4LjYsNjhjMC0yMy45LTAuNC00NC41LTEuNy02My40aDMxLjhsMS4yLDM5LjloMS43YzkuMS0yNy4zLDMxLTQ0LjUsNTUuMy00NC41IGMzLjUtMC4xLDcsMC40LDEwLjMsMS4ydjM0LjhjLTQuMS0wLjktOC4yLTEuMy0xMi40LTEuMmMtMjUuNiwwLTQzLjcsMTkuNy00OC43LDQ3LjRjLTEsNS43LTEuNiwxMS41LTEuNywxNy4ydjEwOC4zaC0zNlY2OCBMLTQ3OC42LDY4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCBkPSJNMTM1Mi4zLDMyNi4yaDM3VjI4aC0zN1YzMjYuMnogTTE2MDQuOCwzMjYuMmMtMi41LTEzLjktMy40LTMxLjEtMy40LTQ4Ljd2LTc2IGMwLTQwLjctMTUuMS04My4xLTc3LjMtODMuMWMtMjUuNiwwLTUwLDcuMS02Ni44LDE4LjFsOC40LDI0LjRjMTQuMy05LjIsMzQtMTUuMSw1My0xNS4xYzQxLjYsMCw0Ni4yLDMwLjIsNDYuMiw0N3Y0LjIgYy03OC42LTAuNC0xMjIuMywyNi41LTEyMi4zLDc1LjZjMCwyOS40LDIxLDU4LjQsNjIuMiw1OC40YzI5LDAsNTAuOS0xNC4zLDYyLjItMzAuMmgxLjNsMi45LDI1LjZIMTYwNC44eiBNMTU2NS43LDI1Ny43IGMwLDMuOC0wLjgsOC0yLjEsMTEuOGMtNS45LDE3LjItMjIuNywzNC00OS4yLDM0Yy0xOC45LDAtMzQuOS0xMS4zLTM0LjktMzUuM2MwLTM5LjUsNDUuOC00Ni42LDg2LjItNDUuOFYyNTcuN3ogTTE2OTguNSwzMjYuMiBsMS43LTMzLjZoMS4zYzE1LjEsMjYuOSwzOC43LDM4LjIsNjguMSwzOC4yYzQ1LjQsMCw5MS4yLTM2LjEsOTEuMi0xMDguOGMwLjQtNjEuNy0zNS4zLTEwMy43LTg1LjctMTAzLjcgYy0zMi44LDAtNTYuMywxNC43LTY5LjMsMzcuNGgtMC44VjI4aC0zNi42djI0NS43YzAsMTguMS0wLjgsMzguNi0xLjcsNTIuNUgxNjk4LjV6IE0xNzA0LjgsMjA4LjJjMC01LjksMS4zLTEwLjksMi4xLTE1LjEgYzcuNi0yOC4xLDMxLjEtNDUuNCw1Ni4zLTQ1LjRjMzkuNSwwLDYwLjUsMzQuOSw2MC41LDc1LjZjMCw0Ni42LTIzLjEsNzguMS02MS44LDc4LjFjLTI2LjksMC00OC4zLTE3LjYtNTUuNS00My4zIGMtMC44LTQuMi0xLjctOC44LTEuNy0xMy40VjIwOC4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzYxNjE2MSIgZD0iTTE1IDlIOXY2aDZWOXptLTIgNGgtMnYtMmgydjJ6bTgtMlY5aC0yVjdjMC0xLjEtLjktMi0yLTJoLTJWM2gtMnYyaC0yVjNIOXYySDdjLTEuMSAwLTIgLjktMiAydjJIM3YyaDJ2MkgzdjJoMnYyYzAgMS4xLjkgMiAyIDJoMnYyaDJ2LTJoMnYyaDJ2LTJoMmMxLjEgMCAyLS45IDItMnYtMmgydi0yaC0ydi0yaDJ6bS00IDZIN1Y3aDEwdjEweiIvPgo8L3N2Zz4K);
  --jp-icon-keyboard: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMTdjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY3YzAtMS4xLS45LTItMi0yem0tOSAzaDJ2MmgtMlY4em0wIDNoMnYyaC0ydi0yek04IDhoMnYySDhWOHptMCAzaDJ2Mkg4di0yem0tMSAySDV2LTJoMnYyem0wLTNINVY4aDJ2MnptOSA3SDh2LTJoOHYyem0wLTRoLTJ2LTJoMnYyem0wLTNoLTJWOGgydjJ6bTMgM2gtMnYtMmgydjJ6bTAtM2gtMlY4aDJ2MnoiLz4KPC9zdmc+Cg==);
  --jp-icon-launch: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMzIgMzIiIHdpZHRoPSIzMiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0yNiwyOEg2YTIuMDAyNywyLjAwMjcsMCwwLDEtMi0yVjZBMi4wMDI3LDIuMDAyNywwLDAsMSw2LDRIMTZWNkg2VjI2SDI2VjE2aDJWMjZBMi4wMDI3LDIuMDAyNywwLDAsMSwyNiwyOFoiLz4KICAgIDxwb2x5Z29uIHBvaW50cz0iMjAgMiAyMCA0IDI2LjU4NiA0IDE4IDEyLjU4NiAxOS40MTQgMTQgMjggNS40MTQgMjggMTIgMzAgMTIgMzAgMiAyMCAyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-launcher: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkgMTlINVY1aDdWM0g1YTIgMiAwIDAwLTIgMnYxNGEyIDIgMCAwMDIgMmgxNGMxLjEgMCAyLS45IDItMnYtN2gtMnY3ek0xNCAzdjJoMy41OWwtOS44MyA5LjgzIDEuNDEgMS40MUwxOSA2LjQxVjEwaDJWM2gtN3oiLz4KPC9zdmc+Cg==);
  --jp-icon-line-form: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNS44OCA0LjEyTDEzLjc2IDEybC03Ljg4IDcuODhMOCAyMmwxMC0xMEw4IDJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-link: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMuOSAxMmMwLTEuNzEgMS4zOS0zLjEgMy4xLTMuMWg0VjdIN2MtMi43NiAwLTUgMi4yNC01IDVzMi4yNCA1IDUgNWg0di0xLjlIN2MtMS43MSAwLTMuMS0xLjM5LTMuMS0zLjF6TTggMTNoOHYtMkg4djJ6bTktNmgtNHYxLjloNGMxLjcxIDAgMy4xIDEuMzkgMy4xIDMuMXMtMS4zOSAzLjEtMy4xIDMuMWgtNFYxN2g0YzIuNzYgMCA1LTIuMjQgNS01cy0yLjI0LTUtNS01eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xOSA1djE0SDVWNWgxNG0xLjEtMkgzLjljLS41IDAtLjkuNC0uOS45djE2LjJjMCAuNC40LjkuOS45aDE2LjJjLjQgMCAuOS0uNS45LS45VjMuOWMwLS41LS41LS45LS45LS45ek0xMSA3aDZ2MmgtNlY3em0wIDRoNnYyaC02di0yem0wIDRoNnYyaC02ek03IDdoMnYySDd6bTAgNGgydjJIN3ptMCA0aDJ2Mkg3eiIvPgo8L3N2Zz4K);
  --jp-icon-markdown: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjN0IxRkEyIiBkPSJNNSAxNC45aDEybC02LjEgNnptOS40LTYuOGMwLTEuMy0uMS0yLjktLjEtNC41LS40IDEuNC0uOSAyLjktMS4zIDQuM2wtMS4zIDQuM2gtMkw4LjUgNy45Yy0uNC0xLjMtLjctMi45LTEtNC4zLS4xIDEuNi0uMSAzLjItLjIgNC42TDcgMTIuNEg0LjhsLjctMTFoMy4zTDEwIDVjLjQgMS4yLjcgMi43IDEgMy45LjMtMS4yLjctMi42IDEtMy45bDEuMi0zLjdoMy4zbC42IDExaC0yLjRsLS4zLTQuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-move-down: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNMTIuNDcxIDcuNTI4OTlDMTIuNzYzMiA3LjIzNjg0IDEyLjc2MzIgNi43NjMxNiAxMi40NzEgNi40NzEwMVY2LjQ3MTAxQzEyLjE3OSA2LjE3OTA1IDExLjcwNTcgNi4xNzg4NCAxMS40MTM1IDYuNDcwNTRMNy43NSAxMC4xMjc1VjEuNzVDNy43NSAxLjMzNTc5IDcuNDE0MjEgMSA3IDFWMUM2LjU4NTc5IDEgNi4yNSAxLjMzNTc5IDYuMjUgMS43NVYxMC4xMjc1TDIuNTk3MjYgNi40NjgyMkMyLjMwMzM4IDYuMTczODEgMS44MjY0MSA2LjE3MzU5IDEuNTMyMjYgNi40Njc3NFY2LjQ2Nzc0QzEuMjM4MyA2Ljc2MTcgMS4yMzgzIDcuMjM4MyAxLjUzMjI2IDcuNTMyMjZMNi4yOTI4OSAxMi4yOTI5QzYuNjgzNDIgMTIuNjgzNCA3LjMxNjU4IDEyLjY4MzQgNy43MDcxMSAxMi4yOTI5TDEyLjQ3MSA3LjUyODk5WiIgZmlsbD0iIzYxNjE2MSIvPgo8L3N2Zz4K);
  --jp-icon-move-up: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNMS41Mjg5OSA2LjQ3MTAxQzEuMjM2ODQgNi43NjMxNiAxLjIzNjg0IDcuMjM2ODQgMS41Mjg5OSA3LjUyODk5VjcuNTI4OTlDMS44MjA5NSA3LjgyMDk1IDIuMjk0MjYgNy44MjExNiAyLjU4NjQ5IDcuNTI5NDZMNi4yNSAzLjg3MjVWMTIuMjVDNi4yNSAxMi42NjQyIDYuNTg1NzkgMTMgNyAxM1YxM0M3LjQxNDIxIDEzIDcuNzUgMTIuNjY0MiA3Ljc1IDEyLjI1VjMuODcyNUwxMS40MDI3IDcuNTMxNzhDMTEuNjk2NiA3LjgyNjE5IDEyLjE3MzYgNy44MjY0MSAxMi40Njc3IDcuNTMyMjZWNy41MzIyNkMxMi43NjE3IDcuMjM4MyAxMi43NjE3IDYuNzYxNyAxMi40Njc3IDYuNDY3NzRMNy43MDcxMSAxLjcwNzExQzcuMzE2NTggMS4zMTY1OCA2LjY4MzQyIDEuMzE2NTggNi4yOTI4OSAxLjcwNzExTDEuNTI4OTkgNi40NzEwMVoiIGZpbGw9IiM2MTYxNjEiLz4KPC9zdmc+Cg==);
  --jp-icon-new-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDZoLThsLTItMkg0Yy0xLjExIDAtMS45OS44OS0xLjk5IDJMMiAxOGMwIDEuMTEuODkgMiAyIDJoMTZjMS4xMSAwIDItLjg5IDItMlY4YzAtMS4xMS0uODktMi0yLTJ6bS0xIDhoLTN2M2gtMnYtM2gtM3YtMmgzVjloMnYzaDN2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-not-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI1IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMTkgMTcuMTg0NCAyLjk2OTY4IDE0LjMwMzIgMS44NjA5NCAxMS40NDA5WiIvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24yIiBzdHJva2U9IiMzMzMzMzMiIHN0cm9rZS13aWR0aD0iMiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOS4zMTU5MiA5LjMyMDMxKSIgZD0iTTcuMzY4NDIgMEwwIDcuMzY0NzkiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDkuMzE1OTIgMTYuNjgzNikgc2NhbGUoMSAtMSkiIGQ9Ik03LjM2ODQyIDBMMCA3LjM2NDc5Ii8+Cjwvc3ZnPgo=);
  --jp-icon-notebook: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtbm90ZWJvb2staWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNFRjZDMDAiPgogICAgPHBhdGggZD0iTTE4LjcgMy4zdjE1LjRIMy4zVjMuM2gxNS40bTEuNS0xLjVIMS44djE4LjNoMTguM2wuMS0xOC4zeiIvPgogICAgPHBhdGggZD0iTTE2LjUgMTYuNWwtNS40LTQuMy01LjYgNC4zdi0xMWgxMXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-numbering: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTQgMTlINlYxOS41SDVWMjAuNUg2VjIxSDRWMjJIN1YxOEg0VjE5Wk01IDEwSDZWNkg0VjdINVYxMFpNNCAxM0g1LjhMNCAxNS4xVjE2SDdWMTVINS4yTDcgMTIuOVYxMkg0VjEzWk05IDdWOUgyM1Y3SDlaTTkgMjFIMjNWMTlIOVYyMVpNOSAxNUgyM1YxM0g5VjE1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-offline-bolt: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDIuMDJjLTUuNTEgMC05Ljk4IDQuNDctOS45OCA5Ljk4czQuNDcgOS45OCA5Ljk4IDkuOTggOS45OC00LjQ3IDkuOTgtOS45OFMxNy41MSAyLjAyIDEyIDIuMDJ6TTExLjQ4IDIwdi02LjI2SDhMMTMgNHY2LjI2aDMuMzVMMTEuNDggMjB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-palette: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE4IDEzVjIwSDRWNkg5LjAyQzkuMDcgNS4yOSA5LjI0IDQuNjIgOS41IDRINEMyLjkgNCAyIDQuOSAyIDZWMjBDMiAyMS4xIDIuOSAyMiA0IDIySDE4QzE5LjEgMjIgMjAgMjEuMSAyMCAyMFYxNUwxOCAxM1pNMTkuMyA4Ljg5QzE5Ljc0IDguMTkgMjAgNy4zOCAyMCA2LjVDMjAgNC4wMSAxNy45OSAyIDE1LjUgMkMxMy4wMSAyIDExIDQuMDEgMTEgNi41QzExIDguOTkgMTMuMDEgMTEgMTUuNDkgMTFDMTYuMzcgMTEgMTcuMTkgMTAuNzQgMTcuODggMTAuM0wyMSAxMy40MkwyMi40MiAxMkwxOS4zIDguODlaTTE1LjUgOUMxNC4xMiA5IDEzIDcuODggMTMgNi41QzEzIDUuMTIgMTQuMTIgNCAxNS41IDRDMTYuODggNCAxOCA1LjEyIDE4IDYuNUMxOCA3Ljg4IDE2Ljg4IDkgMTUuNSA5WiIvPgogICAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik00IDZIOS4wMTg5NEM5LjAwNjM5IDYuMTY1MDIgOSA2LjMzMTc2IDkgNi41QzkgOC44MTU3NyAxMC4yMTEgMTAuODQ4NyAxMi4wMzQzIDEySDlWMTRIMTZWMTIuOTgxMUMxNi41NzAzIDEyLjkzNzcgMTcuMTIgMTIuODIwNyAxNy42Mzk2IDEyLjYzOTZMMTggMTNWMjBINFY2Wk04IDhINlYxMEg4VjhaTTYgMTJIOFYxNEg2VjEyWk04IDE2SDZWMThIOFYxNlpNOSAxNkgxNlYxOEg5VjE2WiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-paste: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE5IDJoLTQuMThDMTQuNC44NCAxMy4zIDAgMTIgMGMtMS4zIDAtMi40Ljg0LTIuODIgMkg1Yy0xLjEgMC0yIC45LTIgMnYxNmMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjRjMC0xLjEtLjktMi0yLTJ6bS03IDBjLjU1IDAgMSAuNDUgMSAxcy0uNDUgMS0xIDEtMS0uNDUtMS0xIC40NS0xIDEtMXptNyAxOEg1VjRoMnYzaDEwVjRoMnYxNnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-pdf: url(data:image/svg+xml;base64,PHN2ZwogICB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyMiAyMiIgd2lkdGg9IjE2Ij4KICAgIDxwYXRoIHRyYW5zZm9ybT0icm90YXRlKDQ1KSIgY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI0ZGMkEyQSIKICAgICAgIGQ9Im0gMjIuMzQ0MzY5LC0zLjAxNjM2NDIgaCA1LjYzODYwNCB2IDEuNTc5MjQzMyBoIC0zLjU0OTIyNyB2IDEuNTA4NjkyOTkgaCAzLjMzNzU3NiBWIDEuNjUwODE1NCBoIC0zLjMzNzU3NiB2IDMuNDM1MjYxMyBoIC0yLjA4OTM3NyB6IG0gLTcuMTM2NDQ0LDEuNTc5MjQzMyB2IDQuOTQzOTU0MyBoIDAuNzQ4OTIgcSAxLjI4MDc2MSwwIDEuOTUzNzAzLC0wLjYzNDk1MzUgMC42NzgzNjksLTAuNjM0OTUzNSAwLjY3ODM2OSwtMS44NDUxNjQxIDAsLTEuMjA0NzgzNTUgLTAuNjcyOTQyLC0xLjgzNDMxMDExIC0wLjY3Mjk0MiwtMC42Mjk1MjY1OSAtMS45NTkxMywtMC42Mjk1MjY1OSB6IG0gLTIuMDg5Mzc3LC0xLjU3OTI0MzMgaCAyLjIwMzM0MyBxIDEuODQ1MTY0LDAgMi43NDYwMzksMC4yNjU5MjA3IDAuOTA2MzAxLDAuMjYwNDkzNyAxLjU1MjEwOCwwLjg5MDAyMDMgMC41Njk4MywwLjU0ODEyMjMgMC44NDY2MDUsMS4yNjQ0ODAwNiAwLjI3Njc3NCwwLjcxNjM1NzgxIDAuMjc2Nzc0LDEuNjIyNjU4OTQgMCwwLjkxNzE1NTEgLTAuMjc2Nzc0LDEuNjM4OTM5OSAtMC4yNzY3NzUsMC43MTYzNTc4IC0wLjg0NjYwNSwxLjI2NDQ4IC0wLjY1MTIzNCwwLjYyOTUyNjYgLTEuNTYyOTYyLDAuODk1NDQ3MyAtMC45MTE3MjgsMC4yNjA0OTM3IC0yLjczNTE4NSwwLjI2MDQ5MzcgaCAtMi4yMDMzNDMgeiBtIC04LjE0NTg1NjUsMCBoIDMuNDY3ODIzIHEgMS41NDY2ODE2LDAgMi4zNzE1Nzg1LDAuNjg5MjIzIDAuODMwMzI0LDAuNjgzNzk2MSAwLjgzMDMyNCwxLjk1MzcwMzE0IDAsMS4yNzUzMzM5NyAtMC44MzAzMjQsMS45NjQ1NTcwNiBRIDkuOTg3MTk2MSwyLjI3NDkxNSA4LjQ0MDUxNDUsMi4yNzQ5MTUgSCA3LjA2MjA2ODQgViA1LjA4NjA3NjcgSCA0Ljk3MjY5MTUgWiBtIDIuMDg5Mzc2OSwxLjUxNDExOTkgdiAyLjI2MzAzOTQzIGggMS4xNTU5NDEgcSAwLjYwNzgxODgsMCAwLjkzODg2MjksLTAuMjkzMDU1NDcgMC4zMzEwNDQxLC0wLjI5ODQ4MjQxIDAuMzMxMDQ0MSwtMC44NDExNzc3MiAwLC0wLjU0MjY5NTMxIC0wLjMzMTA0NDEsLTAuODM1NzUwNzQgLTAuMzMxMDQ0MSwtMC4yOTMwNTU1IC0wLjkzODg2MjksLTAuMjkzMDU1NSB6IgovPgo8L3N2Zz4K);
  --jp-icon-python: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iLTEwIC0xMCAxMzEuMTYxMzYxNjk0MzM1OTQgMTMyLjM4ODk5OTkzODk2NDg0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMzA2OTk4IiBkPSJNIDU0LjkxODc4NSw5LjE5Mjc0MjFlLTQgQyA1MC4zMzUxMzIsMC4wMjIyMTcyNyA0NS45NTc4NDYsMC40MTMxMzY5NyA0Mi4xMDYyODUsMS4wOTQ2NjkzIDMwLjc2MDA2OSwzLjA5OTE3MzEgMjguNzAwMDM2LDcuMjk0NzcxNCAyOC43MDAwMzUsMTUuMDMyMTY5IHYgMTAuMjE4NzUgaCAyNi44MTI1IHYgMy40MDYyNSBoIC0yNi44MTI1IC0xMC4wNjI1IGMgLTcuNzkyNDU5LDAgLTE0LjYxNTc1ODgsNC42ODM3MTcgLTE2Ljc0OTk5OTgsMTMuNTkzNzUgLTIuNDYxODE5OTgsMTAuMjEyOTY2IC0yLjU3MTAxNTA4LDE2LjU4NjAyMyAwLDI3LjI1IDEuOTA1OTI4Myw3LjkzNzg1MiA2LjQ1NzU0MzIsMTMuNTkzNzQ4IDE0LjI0OTk5OTgsMTMuNTkzNzUgaCA5LjIxODc1IHYgLTEyLjI1IGMgMCwtOC44NDk5MDIgNy42NTcxNDQsLTE2LjY1NjI0OCAxNi43NSwtMTYuNjU2MjUgaCAyNi43ODEyNSBjIDcuNDU0OTUxLDAgMTMuNDA2MjUzLC02LjEzODE2NCAxMy40MDYyNSwtMTMuNjI1IHYgLTI1LjUzMTI1IGMgMCwtNy4yNjYzMzg2IC02LjEyOTk4LC0xMi43MjQ3NzcxIC0xMy40MDYyNSwtMTMuOTM3NDk5NyBDIDY0LjI4MTU0OCwwLjMyNzk0Mzk3IDU5LjUwMjQzOCwtMC4wMjAzNzkwMyA1NC45MTg3ODUsOS4xOTI3NDIxZS00IFogbSAtMTQuNSw4LjIxODc1MDEyNTc5IGMgMi43Njk1NDcsMCA1LjAzMTI1LDIuMjk4NjQ1NiA1LjAzMTI1LDUuMTI0OTk5NiAtMmUtNiwyLjgxNjMzNiAtMi4yNjE3MDMsNS4wOTM3NSAtNS4wMzEyNSw1LjA5Mzc1IC0yLjc3OTQ3NiwtMWUtNiAtNS4wMzEyNSwtMi4yNzc0MTUgLTUuMDMxMjUsLTUuMDkzNzUgLTEwZS03LC0yLjgyNjM1MyAyLjI1MTc3NCwtNS4xMjQ5OTk2IDUuMDMxMjUsLTUuMTI0OTk5NiB6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2ZmZDQzYiIgZD0ibSA4NS42Mzc1MzUsMjguNjU3MTY5IHYgMTEuOTA2MjUgYyAwLDkuMjMwNzU1IC03LjgyNTg5NSwxNi45OTk5OTkgLTE2Ljc1LDE3IGggLTI2Ljc4MTI1IGMgLTcuMzM1ODMzLDAgLTEzLjQwNjI0OSw2LjI3ODQ4MyAtMTMuNDA2MjUsMTMuNjI1IHYgMjUuNTMxMjQ3IGMgMCw3LjI2NjM0NCA2LjMxODU4OCwxMS41NDAzMjQgMTMuNDA2MjUsMTMuNjI1MDA0IDguNDg3MzMxLDIuNDk1NjEgMTYuNjI2MjM3LDIuOTQ2NjMgMjYuNzgxMjUsMCA2Ljc1MDE1NSwtMS45NTQzOSAxMy40MDYyNTMsLTUuODg3NjEgMTMuNDA2MjUsLTEzLjYyNTAwNCBWIDg2LjUwMDkxOSBoIC0yNi43ODEyNSB2IC0zLjQwNjI1IGggMjYuNzgxMjUgMTMuNDA2MjU0IGMgNy43OTI0NjEsMCAxMC42OTYyNTEsLTUuNDM1NDA4IDEzLjQwNjI0MSwtMTMuNTkzNzUgMi43OTkzMywtOC4zOTg4ODYgMi42ODAyMiwtMTYuNDc1Nzc2IDAsLTI3LjI1IC0xLjkyNTc4LC03Ljc1NzQ0MSAtNS42MDM4NywtMTMuNTkzNzUgLTEzLjQwNjI0MSwtMTMuNTkzNzUgeiBtIC0xNS4wNjI1LDY0LjY1NjI1IGMgMi43Nzk0NzgsM2UtNiA1LjAzMTI1LDIuMjc3NDE3IDUuMDMxMjUsNS4wOTM3NDcgLTJlLTYsMi44MjYzNTQgLTIuMjUxNzc1LDUuMTI1MDA0IC01LjAzMTI1LDUuMTI1MDA0IC0yLjc2OTU1LDAgLTUuMDMxMjUsLTIuMjk4NjUgLTUuMDMxMjUsLTUuMTI1MDA0IDJlLTYsLTIuODE2MzMgMi4yNjE2OTcsLTUuMDkzNzQ3IDUuMDMxMjUsLTUuMDkzNzQ3IHoiLz4KPC9zdmc+Cg==);
  --jp-icon-r-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjE5NkYzIiBkPSJNNC40IDIuNWMxLjItLjEgMi45LS4zIDQuOS0uMyAyLjUgMCA0LjEuNCA1LjIgMS4zIDEgLjcgMS41IDEuOSAxLjUgMy41IDAgMi0xLjQgMy41LTIuOSA0LjEgMS4yLjQgMS43IDEuNiAyLjIgMyAuNiAxLjkgMSAzLjkgMS4zIDQuNmgtMy44Yy0uMy0uNC0uOC0xLjctMS4yLTMuN3MtMS4yLTIuNi0yLjYtMi42aC0uOXY2LjRINC40VjIuNXptMy43IDYuOWgxLjRjMS45IDAgMi45LS45IDIuOS0yLjNzLTEtMi4zLTIuOC0yLjNjLS43IDAtMS4zIDAtMS42LjJ2NC41aC4xdi0uMXoiLz4KPC9zdmc+Cg==);
  --jp-icon-react: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMTUwIDE1MCA1NDEuOSAyOTUuMyI+CiAgPGcgY2xhc3M9ImpwLWljb24tYnJhbmQyIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxREFGQiI+CiAgICA8cGF0aCBkPSJNNjY2LjMgMjk2LjVjMC0zMi41LTQwLjctNjMuMy0xMDMuMS04Mi40IDE0LjQtNjMuNiA4LTExNC4yLTIwLjItMTMwLjQtNi41LTMuOC0xNC4xLTUuNi0yMi40LTUuNnYyMi4zYzQuNiAwIDguMy45IDExLjQgMi42IDEzLjYgNy44IDE5LjUgMzcuNSAxNC45IDc1LjctMS4xIDkuNC0yLjkgMTkuMy01LjEgMjkuNC0xOS42LTQuOC00MS04LjUtNjMuNS0xMC45LTEzLjUtMTguNS0yNy41LTM1LjMtNDEuNi01MCAzMi42LTMwLjMgNjMuMi00Ni45IDg0LTQ2LjlWNzhjLTI3LjUgMC02My41IDE5LjYtOTkuOSA1My42LTM2LjQtMzMuOC03Mi40LTUzLjItOTkuOS01My4ydjIyLjNjMjAuNyAwIDUxLjQgMTYuNSA4NCA0Ni42LTE0IDE0LjctMjggMzEuNC00MS4zIDQ5LjktMjIuNiAyLjQtNDQgNi4xLTYzLjYgMTEtMi4zLTEwLTQtMTkuNy01LjItMjktNC43LTM4LjIgMS4xLTY3LjkgMTQuNi03NS44IDMtMS44IDYuOS0yLjYgMTEuNS0yLjZWNzguNWMtOC40IDAtMTYgMS44LTIyLjYgNS42LTI4LjEgMTYuMi0zNC40IDY2LjctMTkuOSAxMzAuMS02Mi4yIDE5LjItMTAyLjcgNDkuOS0xMDIuNyA4Mi4zIDAgMzIuNSA0MC43IDYzLjMgMTAzLjEgODIuNC0xNC40IDYzLjYtOCAxMTQuMiAyMC4yIDEzMC40IDYuNSAzLjggMTQuMSA1LjYgMjIuNSA1LjYgMjcuNSAwIDYzLjUtMTkuNiA5OS45LTUzLjYgMzYuNCAzMy44IDcyLjQgNTMuMiA5OS45IDUzLjIgOC40IDAgMTYtMS44IDIyLjYtNS42IDI4LjEtMTYuMiAzNC40LTY2LjcgMTkuOS0xMzAuMSA2Mi0xOS4xIDEwMi41LTQ5LjkgMTAyLjUtODIuM3ptLTEzMC4yLTY2LjdjLTMuNyAxMi45LTguMyAyNi4yLTEzLjUgMzkuNS00LjEtOC04LjQtMTYtMTMuMS0yNC00LjYtOC05LjUtMTUuOC0xNC40LTIzLjQgMTQuMiAyLjEgMjcuOSA0LjcgNDEgNy45em0tNDUuOCAxMDYuNWMtNy44IDEzLjUtMTUuOCAyNi4zLTI0LjEgMzguMi0xNC45IDEuMy0zMCAyLTQ1LjIgMi0xNS4xIDAtMzAuMi0uNy00NS0xLjktOC4zLTExLjktMTYuNC0yNC42LTI0LjItMzgtNy42LTEzLjEtMTQuNS0yNi40LTIwLjgtMzkuOCA2LjItMTMuNCAxMy4yLTI2LjggMjAuNy0zOS45IDcuOC0xMy41IDE1LjgtMjYuMyAyNC4xLTM4LjIgMTQuOS0xLjMgMzAtMiA0NS4yLTIgMTUuMSAwIDMwLjIuNyA0NSAxLjkgOC4zIDExLjkgMTYuNCAyNC42IDI0LjIgMzggNy42IDEzLjEgMTQuNSAyNi40IDIwLjggMzkuOC02LjMgMTMuNC0xMy4yIDI2LjgtMjAuNyAzOS45em0zMi4zLTEzYzUuNCAxMy40IDEwIDI2LjggMTMuOCAzOS44LTEzLjEgMy4yLTI2LjkgNS45LTQxLjIgOCA0LjktNy43IDkuOC0xNS42IDE0LjQtMjMuNyA0LjYtOCA4LjktMTYuMSAxMy0yNC4xek00MjEuMiA0MzBjLTkuMy05LjYtMTguNi0yMC4zLTI3LjgtMzIgOSAuNCAxOC4yLjcgMjcuNS43IDkuNCAwIDE4LjctLjIgMjcuOC0uNy05IDExLjctMTguMyAyMi40LTI3LjUgMzJ6bS03NC40LTU4LjljLTE0LjItMi4xLTI3LjktNC43LTQxLTcuOSAzLjctMTIuOSA4LjMtMjYuMiAxMy41LTM5LjUgNC4xIDggOC40IDE2IDEzLjEgMjQgNC43IDggOS41IDE1LjggMTQuNCAyMy40ek00MjAuNyAxNjNjOS4zIDkuNiAxOC42IDIwLjMgMjcuOCAzMi05LS40LTE4LjItLjctMjcuNS0uNy05LjQgMC0xOC43LjItMjcuOC43IDktMTEuNyAxOC4zLTIyLjQgMjcuNS0zMnptLTc0IDU4LjljLTQuOSA3LjctOS44IDE1LjYtMTQuNCAyMy43LTQuNiA4LTguOSAxNi0xMyAyNC01LjQtMTMuNC0xMC0yNi44LTEzLjgtMzkuOCAxMy4xLTMuMSAyNi45LTUuOCA0MS4yLTcuOXptLTkwLjUgMTI1LjJjLTM1LjQtMTUuMS01OC4zLTM0LjktNTguMy01MC42IDAtMTUuNyAyMi45LTM1LjYgNTguMy01MC42IDguNi0zLjcgMTgtNyAyNy43LTEwLjEgNS43IDE5LjYgMTMuMiA0MCAyMi41IDYwLjktOS4yIDIwLjgtMTYuNiA0MS4xLTIyLjIgNjAuNi05LjktMy4xLTE5LjMtNi41LTI4LTEwLjJ6TTMxMCA0OTBjLTEzLjYtNy44LTE5LjUtMzcuNS0xNC45LTc1LjcgMS4xLTkuNCAyLjktMTkuMyA1LjEtMjkuNCAxOS42IDQuOCA0MSA4LjUgNjMuNSAxMC45IDEzLjUgMTguNSAyNy41IDM1LjMgNDEuNiA1MC0zMi42IDMwLjMtNjMuMiA0Ni45LTg0IDQ2LjktNC41LS4xLTguMy0xLTExLjMtMi43em0yMzcuMi03Ni4yYzQuNyAzOC4yLTEuMSA2Ny45LTE0LjYgNzUuOC0zIDEuOC02LjkgMi42LTExLjUgMi42LTIwLjcgMC01MS40LTE2LjUtODQtNDYuNiAxNC0xNC43IDI4LTMxLjQgNDEuMy00OS45IDIyLjYtMi40IDQ0LTYuMSA2My42LTExIDIuMyAxMC4xIDQuMSAxOS44IDUuMiAyOS4xem0zOC41LTY2LjdjLTguNiAzLjctMTggNy0yNy43IDEwLjEtNS43LTE5LjYtMTMuMi00MC0yMi41LTYwLjkgOS4yLTIwLjggMTYuNi00MS4xIDIyLjItNjAuNiA5LjkgMy4xIDE5LjMgNi41IDI4LjEgMTAuMiAzNS40IDE1LjEgNTguMyAzNC45IDU4LjMgNTAuNi0uMSAxNS43LTIzIDM1LjYtNTguNCA1MC42ek0zMjAuOCA3OC40eiIvPgogICAgPGNpcmNsZSBjeD0iNDIwLjkiIGN5PSIyOTYuNSIgcj0iNDUuNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-redo: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTE4LjQgMTAuNkMxNi41NSA4Ljk5IDE0LjE1IDggMTEuNSA4Yy00LjY1IDAtOC41OCAzLjAzLTkuOTYgNy4yMkwzLjkgMTZjMS4wNS0zLjE5IDQuMDUtNS41IDcuNi01LjUgMS45NSAwIDMuNzMuNzIgNS4xMiAxLjg4TDEzIDE2aDlWN2wtMy42IDMuNnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-refresh: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTkgMTMuNWMtMi40OSAwLTQuNS0yLjAxLTQuNS00LjVTNi41MSA0LjUgOSA0LjVjMS4yNCAwIDIuMzYuNTIgMy4xNyAxLjMzTDEwIDhoNVYzbC0xLjc2IDEuNzZDMTIuMTUgMy42OCAxMC42NiAzIDkgMyA1LjY5IDMgMy4wMSA1LjY5IDMuMDEgOVM1LjY5IDE1IDkgMTVjMi45NyAwIDUuNDMtMi4xNiA1LjktNWgtMS41MmMtLjQ2IDItMi4yNCAzLjUtNC4zOCAzLjV6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-regex: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiBmaWxsPSIjRkZGIj4KICAgIDxjaXJjbGUgY2xhc3M9InN0MiIgY3g9IjUuNSIgY3k9IjE0LjUiIHI9IjEuNSIvPgogICAgPHJlY3QgeD0iMTIiIHk9IjQiIGNsYXNzPSJzdDIiIHdpZHRoPSIxIiBoZWlnaHQ9IjgiLz4KICAgIDxyZWN0IHg9IjguNSIgeT0iNy41IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjg2NiAtMC41IDAuNSAwLjg2NiAtMi4zMjU1IDcuMzIxOSkiIGNsYXNzPSJzdDIiIHdpZHRoPSI4IiBoZWlnaHQ9IjEiLz4KICAgIDxyZWN0IHg9IjEyIiB5PSI0IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjUgLTAuODY2IDAuODY2IDAuNSAtMC42Nzc5IDE0LjgyNTIpIiBjbGFzcz0ic3QyIiB3aWR0aD0iMSIgaGVpZ2h0PSI4Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-run: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTggNXYxNGwxMS03eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-running: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMjU2IDhDMTE5IDggOCAxMTkgOCAyNTZzMTExIDI0OCAyNDggMjQ4IDI0OC0xMTEgMjQ4LTI0OFMzOTMgOCAyNTYgOHptOTYgMzI4YzAgOC44LTcuMiAxNi0xNiAxNkgxNzZjLTguOCAwLTE2LTcuMi0xNi0xNlYxNzZjMC04LjggNy4yLTE2IDE2LTE2aDE2MGM4LjggMCAxNiA3LjIgMTYgMTZ2MTYweiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-save: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE3IDNINWMtMS4xMSAwLTIgLjktMiAydjE0YzAgMS4xLjg5IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjdsLTQtNHptLTUgMTZjLTEuNjYgMC0zLTEuMzQtMy0zczEuMzQtMyAzLTMgMyAxLjM0IDMgMy0xLjM0IDMtMyAzem0zLTEwSDVWNWgxMHY0eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-search: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjEsMTAuOWgtMC43bC0wLjItMC4yYzAuOC0wLjksMS4zLTIuMiwxLjMtMy41YzAtMy0yLjQtNS40LTUuNC01LjRTMS44LDQuMiwxLjgsNy4xczIuNCw1LjQsNS40LDUuNCBjMS4zLDAsMi41LTAuNSwzLjUtMS4zbDAuMiwwLjJ2MC43bDQuMSw0LjFsMS4yLTEuMkwxMi4xLDEwLjl6IE03LjEsMTAuOWMtMi4xLDAtMy43LTEuNy0zLjctMy43czEuNy0zLjcsMy43LTMuN3MzLjcsMS43LDMuNywzLjcgUzkuMiwxMC45LDcuMSwxMC45eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-settings: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuNDMgMTIuOThjLjA0LS4zMi4wNy0uNjQuMDctLjk4cy0uMDMtLjY2LS4wNy0uOThsMi4xMS0xLjY1Yy4xOS0uMTUuMjQtLjQyLjEyLS42NGwtMi0zLjQ2Yy0uMTItLjIyLS4zOS0uMy0uNjEtLjIybC0yLjQ5IDFjLS41Mi0uNC0xLjA4LS43My0xLjY5LS45OGwtLjM4LTIuNjVBLjQ4OC40ODggMCAwMDE0IDJoLTRjLS4yNSAwLS40Ni4xOC0uNDkuNDJsLS4zOCAyLjY1Yy0uNjEuMjUtMS4xNy41OS0xLjY5Ljk4bC0yLjQ5LTFjLS4yMy0uMDktLjQ5IDAtLjYxLjIybC0yIDMuNDZjLS4xMy4yMi0uMDcuNDkuMTIuNjRsMi4xMSAxLjY1Yy0uMDQuMzItLjA3LjY1LS4wNy45OHMuMDMuNjYuMDcuOThsLTIuMTEgMS42NWMtLjE5LjE1LS4yNC40Mi0uMTIuNjRsMiAzLjQ2Yy4xMi4yMi4zOS4zLjYxLjIybDIuNDktMWMuNTIuNCAxLjA4LjczIDEuNjkuOThsLjM4IDIuNjVjLjAzLjI0LjI0LjQyLjQ5LjQyaDRjLjI1IDAgLjQ2LS4xOC40OS0uNDJsLjM4LTIuNjVjLjYxLS4yNSAxLjE3LS41OSAxLjY5LS45OGwyLjQ5IDFjLjIzLjA5LjQ5IDAgLjYxLS4yMmwyLTMuNDZjLjEyLS4yMi4wNy0uNDktLjEyLS42NGwtMi4xMS0xLjY1ek0xMiAxNS41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiLz4KPC9zdmc+Cg==);
  --jp-icon-share: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTSAxOCAyIEMgMTYuMzU0OTkgMiAxNSAzLjM1NDk5MDQgMTUgNSBDIDE1IDUuMTkwOTUyOSAxNS4wMjE3OTEgNS4zNzcxMjI0IDE1LjA1NjY0MSA1LjU1ODU5MzggTCA3LjkyMTg3NSA5LjcyMDcwMzEgQyA3LjM5ODUzOTkgOS4yNzc4NTM5IDYuNzMyMDc3MSA5IDYgOSBDIDQuMzU0OTkwNCA5IDMgMTAuMzU0OTkgMyAxMiBDIDMgMTMuNjQ1MDEgNC4zNTQ5OTA0IDE1IDYgMTUgQyA2LjczMjA3NzEgMTUgNy4zOTg1Mzk5IDE0LjcyMjE0NiA3LjkyMTg3NSAxNC4yNzkyOTcgTCAxNS4wNTY2NDEgMTguNDM5NDUzIEMgMTUuMDIxNTU1IDE4LjYyMTUxNCAxNSAxOC44MDgzODYgMTUgMTkgQyAxNSAyMC42NDUwMSAxNi4zNTQ5OSAyMiAxOCAyMiBDIDE5LjY0NTAxIDIyIDIxIDIwLjY0NTAxIDIxIDE5IEMgMjEgMTcuMzU0OTkgMTkuNjQ1MDEgMTYgMTggMTYgQyAxNy4yNjc0OCAxNiAxNi42MDE1OTMgMTYuMjc5MzI4IDE2LjA3ODEyNSAxNi43MjI2NTYgTCA4Ljk0MzM1OTQgMTIuNTU4NTk0IEMgOC45NzgyMDk1IDEyLjM3NzEyMiA5IDEyLjE5MDk1MyA5IDEyIEMgOSAxMS44MDkwNDcgOC45NzgyMDk1IDExLjYyMjg3OCA4Ljk0MzM1OTQgMTEuNDQxNDA2IEwgMTYuMDc4MTI1IDcuMjc5Mjk2OSBDIDE2LjYwMTQ2IDcuNzIyMTQ2MSAxNy4yNjc5MjMgOCAxOCA4IEMgMTkuNjQ1MDEgOCAyMSA2LjY0NTAwOTYgMjEgNSBDIDIxIDMuMzU0OTkwNCAxOS42NDUwMSAyIDE4IDIgeiBNIDE4IDQgQyAxOC41NjQxMjkgNCAxOSA0LjQzNTg3MDYgMTkgNSBDIDE5IDUuNTY0MTI5NCAxOC41NjQxMjkgNiAxOCA2IEMgMTcuNDM1ODcxIDYgMTcgNS41NjQxMjk0IDE3IDUgQyAxNyA0LjQzNTg3MDYgMTcuNDM1ODcxIDQgMTggNCB6IE0gNiAxMSBDIDYuNTY0MTI5NCAxMSA3IDExLjQzNTg3MSA3IDEyIEMgNyAxMi41NjQxMjkgNi41NjQxMjk0IDEzIDYgMTMgQyA1LjQzNTg3MDYgMTMgNSAxMi41NjQxMjkgNSAxMiBDIDUgMTEuNDM1ODcxIDUuNDM1ODcwNiAxMSA2IDExIHogTSAxOCAxOCBDIDE4LjU2NDEyOSAxOCAxOSAxOC40MzU4NzEgMTkgMTkgQyAxOSAxOS41NjQxMjkgMTguNTY0MTI5IDIwIDE4IDIwIEMgMTcuNDM1ODcxIDIwIDE3IDE5LjU2NDEyOSAxNyAxOSBDIDE3IDE4LjQzNTg3MSAxNy40MzU4NzEgMTggMTggMTggeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-spreadsheet: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNENBRjUwIiBkPSJNMi4yIDIuMnYxNy42aDE3LjZWMi4ySDIuMnptMTUuNCA3LjdoLTUuNVY0LjRoNS41djUuNXpNOS45IDQuNHY1LjVINC40VjQuNGg1LjV6bS01LjUgNy43aDUuNXY1LjVINC40di01LjV6bTcuNyA1LjV2LTUuNWg1LjV2NS41aC01LjV6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-stop: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik02IDZoMTJ2MTJINnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tab: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIxIDNIM2MtMS4xIDAtMiAuOS0yIDJ2MTRjMCAxLjEuOSAyIDIgMmgxOGMxLjEgMCAyLS45IDItMlY1YzAtMS4xLS45LTItMi0yem0wIDE2SDNWNWgxMHY0aDh2MTB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-table-rows: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMSw4SDNWNGgxOFY4eiBNMjEsMTBIM3Y0aDE4VjEweiBNMjEsMTZIM3Y0aDE4VjE2eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-tag: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjgiIGhlaWdodD0iMjgiIHZpZXdCb3g9IjAgMCA0MyAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTI4LjgzMzIgMTIuMzM0TDMyLjk5OTggMTYuNTAwN0wzNy4xNjY1IDEyLjMzNEgyOC44MzMyWiIvPgoJCTxwYXRoIGQ9Ik0xNi4yMDk1IDIxLjYxMDRDMTUuNjg3MyAyMi4xMjk5IDE0Ljg0NDMgMjIuMTI5OSAxNC4zMjQ4IDIxLjYxMDRMNi45ODI5IDE0LjcyNDVDNi41NzI0IDE0LjMzOTQgNi4wODMxMyAxMy42MDk4IDYuMDQ3ODYgMTMuMDQ4MkM1Ljk1MzQ3IDExLjUyODggNi4wMjAwMiA4LjYxOTQ0IDYuMDY2MjEgNy4wNzY5NUM2LjA4MjgxIDYuNTE0NzcgNi41NTU0OCA2LjA0MzQ3IDcuMTE4MDQgNi4wMzA1NUM5LjA4ODYzIDUuOTg0NzMgMTMuMjYzOCA1LjkzNTc5IDEzLjY1MTggNi4zMjQyNUwyMS43MzY5IDEzLjYzOUMyMi4yNTYgMTQuMTU4NSAyMS43ODUxIDE1LjQ3MjQgMjEuMjYyIDE1Ljk5NDZMMTYuMjA5NSAyMS42MTA0Wk05Ljc3NTg1IDguMjY1QzkuMzM1NTEgNy44MjU2NiA4LjYyMzUxIDcuODI1NjYgOC4xODI4IDguMjY1QzcuNzQzNDYgOC43MDU3MSA3Ljc0MzQ2IDkuNDE3MzMgOC4xODI4IDkuODU2NjdDOC42MjM4MiAxMC4yOTY0IDkuMzM1ODIgMTAuMjk2NCA5Ljc3NTg1IDkuODU2NjdDMTAuMjE1NiA5LjQxNzMzIDEwLjIxNTYgOC43MDUzMyA5Ljc3NTg1IDguMjY1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-terminal: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0IiA+CiAgICA8cmVjdCBjbGFzcz0ianAtdGVybWluYWwtaWNvbi1iYWNrZ3JvdW5kLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZSIgd2lkdGg9IjIwIiBoZWlnaHQ9IjIwIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgyIDIpIiBmaWxsPSIjMzMzMzMzIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtdGVybWluYWwtaWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUtaW52ZXJzZSIgZD0iTTUuMDU2NjQgOC43NjE3MkM1LjA1NjY0IDguNTk3NjYgNS4wMzEyNSA4LjQ1MzEyIDQuOTgwNDcgOC4zMjgxMkM0LjkzMzU5IDguMTk5MjIgNC44NTU0NyA4LjA4MjAzIDQuNzQ2MDkgNy45NzY1NkM0LjY0MDYyIDcuODcxMDkgNC41IDcuNzc1MzkgNC4zMjQyMiA3LjY4OTQ1QzQuMTUyMzQgNy41OTk2MSAzLjk0MzM2IDcuNTExNzIgMy42OTcyNyA3LjQyNTc4QzMuMzAyNzMgNy4yODUxNiAyLjk0MzM2IDcuMTM2NzIgMi42MTkxNCA2Ljk4MDQ3QzIuMjk0OTIgNi44MjQyMiAyLjAxNzU4IDYuNjQyNTggMS43ODcxMSA2LjQzNTU1QzEuNTYwNTUgNi4yMjg1MiAxLjM4NDc3IDUuOTg4MjggMS4yNTk3NyA1LjcxNDg0QzEuMTM0NzcgNS40Mzc1IDEuMDcyMjcgNS4xMDkzOCAxLjA3MjI3IDQuNzMwNDdDMS4wNzIyNyA0LjM5ODQ0IDEuMTI4OTEgNC4wOTU3IDEuMjQyMTkgMy44MjIyN0MxLjM1NTQ3IDMuNTQ0OTIgMS41MTU2MiAzLjMwNDY5IDEuNzIyNjYgMy4xMDE1NkMxLjkyOTY5IDIuODk4NDQgMi4xNzk2OSAyLjczNDM3IDIuNDcyNjYgMi42MDkzOEMyLjc2NTYyIDIuNDg0MzggMy4wOTE4IDIuNDA0MyAzLjQ1MTE3IDIuMzY5MTRWMS4xMDkzOEg0LjM4ODY3VjIuMzgwODZDNC43NDAyMyAyLjQyNzczIDUuMDU2NjQgMi41MjM0NCA1LjMzNzg5IDIuNjY3OTdDNS42MTkxNCAyLjgxMjUgNS44NTc0MiAzLjAwMTk1IDYuMDUyNzMgMy4yMzYzM0M2LjI1MTk1IDMuNDY2OCA2LjQwNDMgMy43NDAyMyA2LjUwOTc3IDQuMDU2NjRDNi42MTkxNCA0LjM2OTE0IDYuNjczODMgNC43MjA3IDYuNjczODMgNS4xMTEzM0g1LjA0NDkyQzUuMDQ0OTIgNC42Mzg2NyA0LjkzNzUgNC4yODEyNSA0LjcyMjY2IDQuMDM5MDZDNC41MDc4MSAzLjc5Mjk3IDQuMjE2OCAzLjY2OTkyIDMuODQ5NjEgMy42Njk5MkMzLjY1MDM5IDMuNjY5OTIgMy40NzY1NiAzLjY5NzI3IDMuMzI4MTIgMy43NTE5NUMzLjE4MzU5IDMuODAyNzMgMy4wNjQ0NSAzLjg3Njk1IDIuOTcwNyAzLjk3NDYxQzIuODc2OTUgNC4wNjgzNiAyLjgwNjY0IDQuMTc5NjkgMi43NTk3NyA0LjMwODU5QzIuNzE2OCA0LjQzNzUgMi42OTUzMSA0LjU3ODEyIDIuNjk1MzEgNC43MzA0N0MyLjY5NTMxIDQuODgyODEgMi43MTY4IDUuMDE5NTMgMi43NTk3NyA1LjE0MDYyQzIuODA2NjQgNS4yNTc4MSAyLjg4MjgxIDUuMzY3MTkgMi45ODgyOCA1LjQ2ODc1QzMuMDk3NjYgNS41NzAzMSAzLjI0MDIzIDUuNjY3OTcgMy40MTYwMiA1Ljc2MTcyQzMuNTkxOCA1Ljg1MTU2IDMuODEwNTUgNS45NDMzNiA0LjA3MjI3IDYuMDM3MTFDNC40NjY4IDYuMTg1NTUgNC44MjQyMiA2LjMzOTg0IDUuMTQ0NTMgNi41QzUuNDY0ODQgNi42NTYyNSA1LjczODI4IDYuODM5ODQgNS45NjQ4NCA3LjA1MDc4QzYuMTk1MzEgNy4yNTc4MSA2LjM3MTA5IDcuNSA2LjQ5MjE5IDcuNzc3MzRDNi42MTcxOSA4LjA1MDc4IDYuNjc5NjkgOC4zNzUgNi42Nzk2OSA4Ljc1QzYuNjc5NjkgOS4wOTM3NSA2LjYyMzA1IDkuNDA0MyA2LjUwOTc3IDkuNjgxNjRDNi4zOTY0OCA5Ljk1NTA4IDYuMjM0MzggMTAuMTkxNCA2LjAyMzQ0IDEwLjM5MDZDNS44MTI1IDEwLjU4OTggNS41NTg1OSAxMC43NSA1LjI2MTcyIDEwLjg3MTFDNC45NjQ4NCAxMC45ODgzIDQuNjMyODEgMTEuMDY0NSA0LjI2NTYyIDExLjA5OTZWMTIuMjQ4SDMuMzMzOThWMTEuMDk5NkMzLjAwMTk1IDExLjA2ODQgMi42Nzk2OSAxMC45OTYxIDIuMzY3MTkgMTAuODgyOEMyLjA1NDY5IDEwLjc2NTYgMS43NzczNCAxMC41OTc3IDEuNTM1MTYgMTAuMzc4OUMxLjI5Njg4IDEwLjE2MDIgMS4xMDU0NyA5Ljg4NDc3IDAuOTYwOTM4IDkuNTUyNzNDMC44MTY0MDYgOS4yMTY4IDAuNzQ0MTQxIDguODE0NDUgMC43NDQxNDEgOC4zNDU3SDIuMzc4OTFDMi4zNzg5MSA4LjYyNjk1IDIuNDE5OTIgOC44NjMyOCAyLjUwMTk1IDkuMDU0NjlDMi41ODM5OCA5LjI0MjE5IDIuNjg5NDUgOS4zOTI1OCAyLjgxODM2IDkuNTA1ODZDMi45NTExNyA5LjYxNTIzIDMuMTAxNTYgOS42OTMzNiAzLjI2OTUzIDkuNzQwMjNDMy40Mzc1IDkuNzg3MTEgMy42MDkzOCA5LjgxMDU1IDMuNzg1MTYgOS44MTA1NUM0LjIwMzEyIDkuODEwNTUgNC41MTk1MyA5LjcxMjg5IDQuNzM0MzggOS41MTc1OEM0Ljk0OTIyIDkuMzIyMjcgNS4wNTY2NCA5LjA3MDMxIDUuMDU2NjQgOC43NjE3MlpNMTMuNDE4IDEyLjI3MTVIOC4wNzQyMlYxMUgxMy40MThWMTIuMjcxNVoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMuOTUyNjQgNikiIGZpbGw9IndoaXRlIi8+Cjwvc3ZnPgo=);
  --jp-icon-text-editor: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtdGV4dC1lZGl0b3ItaWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xNSAxNUgzdjJoMTJ2LTJ6bTAtOEgzdjJoMTJWN3pNMyAxM2gxOHYtMkgzdjJ6bTAgOGgxOHYtMkgzdjJ6TTMgM3YyaDE4VjNIM3oiLz4KPC9zdmc+Cg==);
  --jp-icon-toc: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik03LDVIMjFWN0g3VjVNNywxM1YxMUgyMVYxM0g3TTQsNC41QTEuNSwxLjUgMCAwLDEgNS41LDZBMS41LDEuNSAwIDAsMSA0LDcuNUExLjUsMS41IDAgMCwxIDIuNSw2QTEuNSwxLjUgMCAwLDEgNCw0LjVNNCwxMC41QTEuNSwxLjUgMCAwLDEgNS41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMy41QTEuNSwxLjUgMCAwLDEgMi41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMC41TTcsMTlWMTdIMjFWMTlIN000LDE2LjVBMS41LDEuNSAwIDAsMSA1LjUsMThBMS41LDEuNSAwIDAsMSA0LDE5LjVBMS41LDEuNSAwIDAsMSAyLjUsMThBMS41LDEuNSAwIDAsMSA0LDE2LjVaIiAvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tree-view: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMiAxMVYzaC03djNIOVYzSDJ2OGg3VjhoMnYxMGg0djNoN3YtOGgtN3YzaC0yVjhoMnYzeiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMiAxNy4xODQ0IDIuOTY5NjggMTQuMzAzMiAxLjg2MDk0IDExLjQ0MDlaIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiMzMzMzMzMiIHN0cm9rZT0iIzMzMzMzMyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOCA5Ljg2NzE5KSIgZD0iTTIuODYwMTUgNC44NjUzNUwwLjcyNjU0OSAyLjk5OTU5TDAgMy42MzA0NUwyLjg2MDE1IDYuMTMxNTdMOCAwLjYzMDg3Mkw3LjI3ODU3IDBMMi44NjAxNSA0Ljg2NTM1WiIvPgo8L3N2Zz4K);
  --jp-icon-undo: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjUgOGMtMi42NSAwLTUuMDUuOTktNi45IDIuNkwyIDd2OWg5bC0zLjYyLTMuNjJjMS4zOS0xLjE2IDMuMTYtMS44OCA1LjEyLTEuODggMy41NCAwIDYuNTUgMi4zMSA3LjYgNS41bDIuMzctLjc4QzIxLjA4IDExLjAzIDE3LjE1IDggMTIuNSA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-user: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE2IDdhNCA0IDAgMTEtOCAwIDQgNCAwIDAxOCAwek0xMiAxNGE3IDcgMCAwMC03IDdoMTRhNyA3IDAgMDAtNy03eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-users: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZlcnNpb249IjEuMSIgdmlld0JveD0iMCAwIDM2IDI0IiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgogPGcgY2xhc3M9ImpwLWljb24zIiB0cmFuc2Zvcm09Im1hdHJpeCgxLjczMjcgMCAwIDEuNzMyNyAtMy42MjgyIC4wOTk1NzcpIiBmaWxsPSIjNjE2MTYxIj4KICA8cGF0aCB0cmFuc2Zvcm09Im1hdHJpeCgxLjUsMCwwLDEuNSwwLC02KSIgZD0ibTEyLjE4NiA3LjUwOThjLTEuMDUzNSAwLTEuOTc1NyAwLjU2NjUtMi40Nzg1IDEuNDEwMiAwLjc1MDYxIDAuMzEyNzcgMS4zOTc0IDAuODI2NDggMS44NzMgMS40NzI3aDMuNDg2M2MwLTEuNTkyLTEuMjg4OS0yLjg4MjgtMi44ODA5LTIuODgyOHoiLz4KICA8cGF0aCBkPSJtMjAuNDY1IDIuMzg5NWEyLjE4ODUgMi4xODg1IDAgMCAxLTIuMTg4NCAyLjE4ODUgMi4xODg1IDIuMTg4NSAwIDAgMS0yLjE4ODUtMi4xODg1IDIuMTg4NSAyLjE4ODUgMCAwIDEgMi4xODg1LTIuMTg4NSAyLjE4ODUgMi4xODg1IDAgMCAxIDIuMTg4NCAyLjE4ODV6Ii8+CiAgPHBhdGggdHJhbnNmb3JtPSJtYXRyaXgoMS41LDAsMCwxLjUsMCwtNikiIGQ9Im0zLjU4OTggOC40MjE5Yy0xLjExMjYgMC0yLjAxMzcgMC45MDExMS0yLjAxMzcgMi4wMTM3aDIuODE0NWMwLjI2Nzk3LTAuMzczMDkgMC41OTA3LTAuNzA0MzUgMC45NTg5OC0wLjk3ODUyLTAuMzQ0MzMtMC42MTY4OC0xLjAwMzEtMS4wMzUyLTEuNzU5OC0xLjAzNTJ6Ii8+CiAgPHBhdGggZD0ibTYuOTE1NCA0LjYyM2ExLjUyOTQgMS41Mjk0IDAgMCAxLTEuNTI5NCAxLjUyOTQgMS41Mjk0IDEuNTI5NCAwIDAgMS0xLjUyOTQtMS41Mjk0IDEuNTI5NCAxLjUyOTQgMCAwIDEgMS41Mjk0LTEuNTI5NCAxLjUyOTQgMS41Mjk0IDAgMCAxIDEuNTI5NCAxLjUyOTR6Ii8+CiAgPHBhdGggZD0ibTYuMTM1IDEzLjUzNWMwLTMuMjM5MiAyLjYyNTktNS44NjUgNS44NjUtNS44NjUgMy4yMzkyIDAgNS44NjUgMi42MjU5IDUuODY1IDUuODY1eiIvPgogIDxjaXJjbGUgY3g9IjEyIiBjeT0iMy43Njg1IiByPSIyLjk2ODUiLz4KIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-vega: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbjEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjEyMTIxIj4KICAgIDxwYXRoIGQ9Ik0xMC42IDUuNGwyLjItMy4ySDIuMnY3LjNsNC02LjZ6Ii8+CiAgICA8cGF0aCBkPSJNMTUuOCAyLjJsLTQuNCA2LjZMNyA2LjNsLTQuOCA4djUuNWgxNy42VjIuMmgtNHptLTcgMTUuNEg1LjV2LTQuNGgzLjN2NC40em00LjQgMEg5LjhWOS44aDMuNHY3Ljh6bTQuNCAwaC0zLjRWNi41aDMuNHYxMS4xeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-word: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KIDxnIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzQxNDE0MSI+CiAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiA8L2c+CiA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSguNDMgLjA0MDEpIiBmaWxsPSIjZmZmIj4KICA8cGF0aCBkPSJtNC4xNCA4Ljc2cTAuMDY4Mi0xLjg5IDIuNDItMS44OSAxLjE2IDAgMS42OCAwLjQyIDAuNTY3IDAuNDEgMC41NjcgMS4xNnYzLjQ3cTAgMC40NjIgMC41MTQgMC40NjIgMC4xMDMgMCAwLjItMC4wMjMxdjAuNzE0cS0wLjM5OSAwLjEwMy0wLjY1MSAwLjEwMy0wLjQ1MiAwLTAuNjkzLTAuMjItMC4yMzEtMC4yLTAuMjg0LTAuNjYyLTAuOTU2IDAuODcyLTIgMC44NzItMC45MDMgMC0xLjQ3LTAuNDcyLTAuNTI1LTAuNDcyLTAuNTI1LTEuMjYgMC0wLjI2MiAwLjA0NTItMC40NzIgMC4wNTY3LTAuMjIgMC4xMTYtMC4zNzggMC4wNjgyLTAuMTY4IDAuMjMxLTAuMzA0IDAuMTU4LTAuMTQ3IDAuMjYyLTAuMjQyIDAuMTE2LTAuMDkxNCAwLjM2OC0wLjE2OCAwLjI2Mi0wLjA5MTQgMC4zOTktMC4xMjYgMC4xMzYtMC4wNDUyIDAuNDcyLTAuMTAzIDAuMzM2LTAuMDU3OCAwLjUwNC0wLjA3OTggMC4xNTgtMC4wMjMxIDAuNTY3LTAuMDc5OCAwLjU1Ni0wLjA2ODIgMC43NzctMC4yMjEgMC4yMi0wLjE1MiAwLjIyLTAuNDQxdi0wLjI1MnEwLTAuNDMtMC4zNTctMC42NjItMC4zMzYtMC4yMzEtMC45NzYtMC4yMzEtMC42NjIgMC0wLjk5OCAwLjI2Mi0wLjMzNiAwLjI1Mi0wLjM5OSAwLjc5OHptMS44OSAzLjY4cTAuNzg4IDAgMS4yNi0wLjQxIDAuNTA0LTAuNDIgMC41MDQtMC45MDN2LTEuMDVxLTAuMjg0IDAuMTM2LTAuODYxIDAuMjMxLTAuNTY3IDAuMDkxNC0wLjk4NyAwLjE1OC0wLjQyIDAuMDY4Mi0wLjc2NiAwLjMyNi0wLjMzNiAwLjI1Mi0wLjMzNiAwLjcwNHQwLjMwNCAwLjcwNCAwLjg2MSAwLjI1MnoiIHN0cm9rZS13aWR0aD0iMS4wNSIvPgogIDxwYXRoIGQ9Im0xMCA0LjU2aDAuOTQ1djMuMTVxMC42NTEtMC45NzYgMS44OS0wLjk3NiAxLjE2IDAgMS44OSAwLjg0IDAuNjgyIDAuODQgMC42ODIgMi4zMSAwIDEuNDctMC43MDQgMi40Mi0wLjcwNCAwLjg4Mi0xLjg5IDAuODgyLTEuMjYgMC0xLjg5LTEuMDJ2MC43NjZoLTAuODV6bTIuNjIgMy4wNHEtMC43NDYgMC0xLjE2IDAuNjQtMC40NTIgMC42My0wLjQ1MiAxLjY4IDAgMS4wNSAwLjQ1MiAxLjY4dDEuMTYgMC42M3EwLjc3NyAwIDEuMjYtMC42MyAwLjQ5NC0wLjY0IDAuNDk0LTEuNjggMC0xLjA1LTAuNDcyLTEuNjgtMC40NjItMC42NC0xLjI2LTAuNjR6IiBzdHJva2Utd2lkdGg9IjEuMDUiLz4KICA8cGF0aCBkPSJtMi43MyAxNS44IDEzLjYgMC4wMDgxYzAuMDA2OSAwIDAtMi42IDAtMi42IDAtMC4wMDc4LTEuMTUgMC0xLjE1IDAtMC4wMDY5IDAtMC4wMDgzIDEuNS0wLjAwODMgMS41LTJlLTMgLTAuMDAxNC0xMS4zLTAuMDAxNC0xMS4zLTAuMDAxNGwtMC4wMDU5Mi0xLjVjMC0wLjAwNzgtMS4xNyAwLjAwMTMtMS4xNyAwLjAwMTN6IiBzdHJva2Utd2lkdGg9Ii45NzUiLz4KIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-yaml: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1jb250cmFzdDIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjRDgxQjYwIj4KICAgIDxwYXRoIGQ9Ik03LjIgMTguNnYtNS40TDMgNS42aDMuM2wxLjQgMy4xYy4zLjkuNiAxLjYgMSAyLjUuMy0uOC42LTEuNiAxLTIuNWwxLjQtMy4xaDMuNGwtNC40IDcuNnY1LjVsLTIuOS0uMXoiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxNi41IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxMSIgcj0iMi4xIi8+CiAgPC9nPgo8L3N2Zz4K);
}

/* Icon CSS class declarations */

.jp-AddAboveIcon {
  background-image: var(--jp-icon-add-above);
}

.jp-AddBelowIcon {
  background-image: var(--jp-icon-add-below);
}

.jp-AddIcon {
  background-image: var(--jp-icon-add);
}

.jp-BellIcon {
  background-image: var(--jp-icon-bell);
}

.jp-BugDotIcon {
  background-image: var(--jp-icon-bug-dot);
}

.jp-BugIcon {
  background-image: var(--jp-icon-bug);
}

.jp-BuildIcon {
  background-image: var(--jp-icon-build);
}

.jp-CaretDownEmptyIcon {
  background-image: var(--jp-icon-caret-down-empty);
}

.jp-CaretDownEmptyThinIcon {
  background-image: var(--jp-icon-caret-down-empty-thin);
}

.jp-CaretDownIcon {
  background-image: var(--jp-icon-caret-down);
}

.jp-CaretLeftIcon {
  background-image: var(--jp-icon-caret-left);
}

.jp-CaretRightIcon {
  background-image: var(--jp-icon-caret-right);
}

.jp-CaretUpEmptyThinIcon {
  background-image: var(--jp-icon-caret-up-empty-thin);
}

.jp-CaretUpIcon {
  background-image: var(--jp-icon-caret-up);
}

.jp-CaseSensitiveIcon {
  background-image: var(--jp-icon-case-sensitive);
}

.jp-CheckIcon {
  background-image: var(--jp-icon-check);
}

.jp-CircleEmptyIcon {
  background-image: var(--jp-icon-circle-empty);
}

.jp-CircleIcon {
  background-image: var(--jp-icon-circle);
}

.jp-ClearIcon {
  background-image: var(--jp-icon-clear);
}

.jp-CloseIcon {
  background-image: var(--jp-icon-close);
}

.jp-CodeCheckIcon {
  background-image: var(--jp-icon-code-check);
}

.jp-CodeIcon {
  background-image: var(--jp-icon-code);
}

.jp-CollapseAllIcon {
  background-image: var(--jp-icon-collapse-all);
}

.jp-ConsoleIcon {
  background-image: var(--jp-icon-console);
}

.jp-CopyIcon {
  background-image: var(--jp-icon-copy);
}

.jp-CopyrightIcon {
  background-image: var(--jp-icon-copyright);
}

.jp-CutIcon {
  background-image: var(--jp-icon-cut);
}

.jp-DeleteIcon {
  background-image: var(--jp-icon-delete);
}

.jp-DownloadIcon {
  background-image: var(--jp-icon-download);
}

.jp-DuplicateIcon {
  background-image: var(--jp-icon-duplicate);
}

.jp-EditIcon {
  background-image: var(--jp-icon-edit);
}

.jp-EllipsesIcon {
  background-image: var(--jp-icon-ellipses);
}

.jp-ErrorIcon {
  background-image: var(--jp-icon-error);
}

.jp-ExpandAllIcon {
  background-image: var(--jp-icon-expand-all);
}

.jp-ExtensionIcon {
  background-image: var(--jp-icon-extension);
}

.jp-FastForwardIcon {
  background-image: var(--jp-icon-fast-forward);
}

.jp-FileIcon {
  background-image: var(--jp-icon-file);
}

.jp-FileUploadIcon {
  background-image: var(--jp-icon-file-upload);
}

.jp-FilterDotIcon {
  background-image: var(--jp-icon-filter-dot);
}

.jp-FilterIcon {
  background-image: var(--jp-icon-filter);
}

.jp-FilterListIcon {
  background-image: var(--jp-icon-filter-list);
}

.jp-FolderFavoriteIcon {
  background-image: var(--jp-icon-folder-favorite);
}

.jp-FolderIcon {
  background-image: var(--jp-icon-folder);
}

.jp-HomeIcon {
  background-image: var(--jp-icon-home);
}

.jp-Html5Icon {
  background-image: var(--jp-icon-html5);
}

.jp-ImageIcon {
  background-image: var(--jp-icon-image);
}

.jp-InfoIcon {
  background-image: var(--jp-icon-info);
}

.jp-InspectorIcon {
  background-image: var(--jp-icon-inspector);
}

.jp-JsonIcon {
  background-image: var(--jp-icon-json);
}

.jp-JuliaIcon {
  background-image: var(--jp-icon-julia);
}

.jp-JupyterFaviconIcon {
  background-image: var(--jp-icon-jupyter-favicon);
}

.jp-JupyterIcon {
  background-image: var(--jp-icon-jupyter);
}

.jp-JupyterlabWordmarkIcon {
  background-image: var(--jp-icon-jupyterlab-wordmark);
}

.jp-KernelIcon {
  background-image: var(--jp-icon-kernel);
}

.jp-KeyboardIcon {
  background-image: var(--jp-icon-keyboard);
}

.jp-LaunchIcon {
  background-image: var(--jp-icon-launch);
}

.jp-LauncherIcon {
  background-image: var(--jp-icon-launcher);
}

.jp-LineFormIcon {
  background-image: var(--jp-icon-line-form);
}

.jp-LinkIcon {
  background-image: var(--jp-icon-link);
}

.jp-ListIcon {
  background-image: var(--jp-icon-list);
}

.jp-MarkdownIcon {
  background-image: var(--jp-icon-markdown);
}

.jp-MoveDownIcon {
  background-image: var(--jp-icon-move-down);
}

.jp-MoveUpIcon {
  background-image: var(--jp-icon-move-up);
}

.jp-NewFolderIcon {
  background-image: var(--jp-icon-new-folder);
}

.jp-NotTrustedIcon {
  background-image: var(--jp-icon-not-trusted);
}

.jp-NotebookIcon {
  background-image: var(--jp-icon-notebook);
}

.jp-NumberingIcon {
  background-image: var(--jp-icon-numbering);
}

.jp-OfflineBoltIcon {
  background-image: var(--jp-icon-offline-bolt);
}

.jp-PaletteIcon {
  background-image: var(--jp-icon-palette);
}

.jp-PasteIcon {
  background-image: var(--jp-icon-paste);
}

.jp-PdfIcon {
  background-image: var(--jp-icon-pdf);
}

.jp-PythonIcon {
  background-image: var(--jp-icon-python);
}

.jp-RKernelIcon {
  background-image: var(--jp-icon-r-kernel);
}

.jp-ReactIcon {
  background-image: var(--jp-icon-react);
}

.jp-RedoIcon {
  background-image: var(--jp-icon-redo);
}

.jp-RefreshIcon {
  background-image: var(--jp-icon-refresh);
}

.jp-RegexIcon {
  background-image: var(--jp-icon-regex);
}

.jp-RunIcon {
  background-image: var(--jp-icon-run);
}

.jp-RunningIcon {
  background-image: var(--jp-icon-running);
}

.jp-SaveIcon {
  background-image: var(--jp-icon-save);
}

.jp-SearchIcon {
  background-image: var(--jp-icon-search);
}

.jp-SettingsIcon {
  background-image: var(--jp-icon-settings);
}

.jp-ShareIcon {
  background-image: var(--jp-icon-share);
}

.jp-SpreadsheetIcon {
  background-image: var(--jp-icon-spreadsheet);
}

.jp-StopIcon {
  background-image: var(--jp-icon-stop);
}

.jp-TabIcon {
  background-image: var(--jp-icon-tab);
}

.jp-TableRowsIcon {
  background-image: var(--jp-icon-table-rows);
}

.jp-TagIcon {
  background-image: var(--jp-icon-tag);
}

.jp-TerminalIcon {
  background-image: var(--jp-icon-terminal);
}

.jp-TextEditorIcon {
  background-image: var(--jp-icon-text-editor);
}

.jp-TocIcon {
  background-image: var(--jp-icon-toc);
}

.jp-TreeViewIcon {
  background-image: var(--jp-icon-tree-view);
}

.jp-TrustedIcon {
  background-image: var(--jp-icon-trusted);
}

.jp-UndoIcon {
  background-image: var(--jp-icon-undo);
}

.jp-UserIcon {
  background-image: var(--jp-icon-user);
}

.jp-UsersIcon {
  background-image: var(--jp-icon-users);
}

.jp-VegaIcon {
  background-image: var(--jp-icon-vega);
}

.jp-WordIcon {
  background-image: var(--jp-icon-word);
}

.jp-YamlIcon {
  background-image: var(--jp-icon-yaml);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

.jp-Icon,
.jp-MaterialIcon {
  background-position: center;
  background-repeat: no-repeat;
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-cover {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/**
 * (DEPRECATED) Support for specific CSS icon sizes
 */

.jp-Icon-16 {
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-18 {
  background-size: 18px;
  min-width: 18px;
  min-height: 18px;
}

.jp-Icon-20 {
  background-size: 20px;
  min-width: 20px;
  min-height: 20px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.lm-TabBar .lm-TabBar-addButton {
  align-items: center;
  display: flex;
  padding: 4px;
  padding-bottom: 5px;
  margin-right: 1px;
  background-color: var(--jp-layout-color2);
}

.lm-TabBar .lm-TabBar-addButton:hover {
  background-color: var(--jp-layout-color1);
}

.lm-DockPanel-tabBar .lm-TabBar-tab {
  width: var(--jp-private-horizontal-tab-width);
}

.lm-DockPanel-tabBar .lm-TabBar-content {
  flex: unset;
}

.lm-DockPanel-tabBar[data-orientation='horizontal'] {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for icons as inline SVG HTMLElements
 */

/* recolor the primary elements of an icon */
.jp-icon0[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon1[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon2[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon3[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-accent0[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-accent1[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-accent2[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-accent3[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-accent4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-accent0[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-accent1[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-accent2[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-accent3[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-accent4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-none[fill] {
  fill: none;
}

.jp-icon-none[stroke] {
  stroke: none;
}

/* brand icon colors. Same for light and dark */
.jp-icon-brand0[fill] {
  fill: var(--jp-brand-color0);
}

.jp-icon-brand1[fill] {
  fill: var(--jp-brand-color1);
}

.jp-icon-brand2[fill] {
  fill: var(--jp-brand-color2);
}

.jp-icon-brand3[fill] {
  fill: var(--jp-brand-color3);
}

.jp-icon-brand4[fill] {
  fill: var(--jp-brand-color4);
}

.jp-icon-brand0[stroke] {
  stroke: var(--jp-brand-color0);
}

.jp-icon-brand1[stroke] {
  stroke: var(--jp-brand-color1);
}

.jp-icon-brand2[stroke] {
  stroke: var(--jp-brand-color2);
}

.jp-icon-brand3[stroke] {
  stroke: var(--jp-brand-color3);
}

.jp-icon-brand4[stroke] {
  stroke: var(--jp-brand-color4);
}

/* warn icon colors. Same for light and dark */
.jp-icon-warn0[fill] {
  fill: var(--jp-warn-color0);
}

.jp-icon-warn1[fill] {
  fill: var(--jp-warn-color1);
}

.jp-icon-warn2[fill] {
  fill: var(--jp-warn-color2);
}

.jp-icon-warn3[fill] {
  fill: var(--jp-warn-color3);
}

.jp-icon-warn0[stroke] {
  stroke: var(--jp-warn-color0);
}

.jp-icon-warn1[stroke] {
  stroke: var(--jp-warn-color1);
}

.jp-icon-warn2[stroke] {
  stroke: var(--jp-warn-color2);
}

.jp-icon-warn3[stroke] {
  stroke: var(--jp-warn-color3);
}

/* icon colors that contrast well with each other and most backgrounds */
.jp-icon-contrast0[fill] {
  fill: var(--jp-icon-contrast-color0);
}

.jp-icon-contrast1[fill] {
  fill: var(--jp-icon-contrast-color1);
}

.jp-icon-contrast2[fill] {
  fill: var(--jp-icon-contrast-color2);
}

.jp-icon-contrast3[fill] {
  fill: var(--jp-icon-contrast-color3);
}

.jp-icon-contrast0[stroke] {
  stroke: var(--jp-icon-contrast-color0);
}

.jp-icon-contrast1[stroke] {
  stroke: var(--jp-icon-contrast-color1);
}

.jp-icon-contrast2[stroke] {
  stroke: var(--jp-icon-contrast-color2);
}

.jp-icon-contrast3[stroke] {
  stroke: var(--jp-icon-contrast-color3);
}

.jp-icon-dot[fill] {
  fill: var(--jp-warn-color0);
}

.jp-jupyter-icon-color[fill] {
  fill: var(--jp-jupyter-icon-color, var(--jp-warn-color0));
}

.jp-notebook-icon-color[fill] {
  fill: var(--jp-notebook-icon-color, var(--jp-warn-color0));
}

.jp-json-icon-color[fill] {
  fill: var(--jp-json-icon-color, var(--jp-warn-color1));
}

.jp-console-icon-color[fill] {
  fill: var(--jp-console-icon-color, white);
}

.jp-console-icon-background-color[fill] {
  fill: var(--jp-console-icon-background-color, var(--jp-brand-color1));
}

.jp-terminal-icon-color[fill] {
  fill: var(--jp-terminal-icon-color, var(--jp-layout-color2));
}

.jp-terminal-icon-background-color[fill] {
  fill: var(
    --jp-terminal-icon-background-color,
    var(--jp-inverse-layout-color2)
  );
}

.jp-text-editor-icon-color[fill] {
  fill: var(--jp-text-editor-icon-color, var(--jp-inverse-layout-color3));
}

.jp-inspector-icon-color[fill] {
  fill: var(--jp-inspector-icon-color, var(--jp-inverse-layout-color3));
}

/* CSS for icons in selected filebrowser listing items */
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

.jp-DirListing-item.jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* stylelint-disable selector-max-class, selector-max-compound-selectors */

/**
* TODO: come up with non css-hack solution for showing the busy icon on top
*  of the close icon
* CSS for complex behavior of close icon of tabs in the main area tabbar
*/
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}

.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

/* stylelint-enable selector-max-class, selector-max-compound-selectors */

/* CSS for icons in status bar */
#jp-main-statusbar .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

#jp-main-statusbar .jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* special handling for splash icon CSS. While the theme CSS reloads during
   splash, the splash icon can loose theming. To prevent that, we set a
   default for its color variable */
:root {
  --jp-warn-color0: var(--md-orange-700);
}

/* not sure what to do with this one, used in filebrowser listing */
.jp-DragIcon {
  margin-right: 4px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for alt colors for icons as inline SVG HTMLElements
 */

/* alt recolor the primary elements of an icon */
.jp-icon-alt .jp-icon0[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-alt .jp-icon1[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-alt .jp-icon2[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-alt .jp-icon3[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-alt .jp-icon4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-alt .jp-icon0[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-alt .jp-icon1[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-alt .jp-icon2[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-alt .jp-icon3[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-alt .jp-icon4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* alt recolor the accent elements of an icon */
.jp-icon-alt .jp-icon-accent0[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-alt .jp-icon-accent1[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-alt .jp-icon-accent2[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-alt .jp-icon-accent3[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-alt .jp-icon-accent4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-alt .jp-icon-accent0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-alt .jp-icon-accent1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-alt .jp-icon-accent2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-alt .jp-icon-accent3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-alt .jp-icon-accent4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-icon-hoverShow:not(:hover) .jp-icon-hoverShow-content {
  display: none !important;
}

/**
 * Support for hover colors for icons as inline SVG HTMLElements
 */

/**
 * regular colors
 */

/* recolor the primary elements of an icon */
.jp-icon-hover :hover .jp-icon0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-hover :hover .jp-icon1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-hover :hover .jp-icon2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-hover :hover .jp-icon3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-hover :hover .jp-icon4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-hover :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-hover :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-hover :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-hover :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-hover :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-hover :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-hover :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-hover :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-hover :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-hover :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-hover :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-hover :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-hover :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-hover :hover .jp-icon-none-hover[fill] {
  fill: none;
}

.jp-icon-hover :hover .jp-icon-none-hover[stroke] {
  stroke: none;
}

/**
 * inverse colors
 */

/* inverse recolor the primary elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* inverse recolor the accent elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-IFrame {
  width: 100%;
  height: 100%;
}

.jp-IFrame > iframe {
  border: none;
}

/*
When drag events occur, `lm-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-IFrame {
  position: relative;
}

body.lm-mod-override-cursor .jp-IFrame::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-HoverBox {
  position: fixed;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FormGroup-content fieldset {
  border: none;
  padding: 0;
  min-width: 0;
  width: 100%;
}

/* stylelint-disable selector-max-type */

.jp-FormGroup-content fieldset .jp-inputFieldWrapper input,
.jp-FormGroup-content fieldset .jp-inputFieldWrapper select,
.jp-FormGroup-content fieldset .jp-inputFieldWrapper textarea {
  font-size: var(--jp-content-font-size2);
  border-color: var(--jp-input-border-color);
  border-style: solid;
  border-radius: var(--jp-border-radius);
  border-width: 1px;
  padding: 6px 8px;
  background: none;
  color: var(--jp-ui-font-color0);
  height: inherit;
}

.jp-FormGroup-content fieldset input[type='checkbox'] {
  position: relative;
  top: 2px;
  margin-left: 0;
}

.jp-FormGroup-content button.jp-mod-styled {
  cursor: pointer;
}

.jp-FormGroup-content .checkbox label {
  cursor: pointer;
  font-size: var(--jp-content-font-size1);
}

.jp-FormGroup-content .jp-root > fieldset > legend {
  display: none;
}

.jp-FormGroup-content .jp-root > fieldset > p {
  display: none;
}

/** copy of `input.jp-mod-styled:focus` style */
.jp-FormGroup-content fieldset input:focus,
.jp-FormGroup-content fieldset select:focus {
  -moz-outline-radius: unset;
  outline: var(--jp-border-width) solid var(--md-blue-500);
  outline-offset: -1px;
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-FormGroup-content fieldset input:hover:not(:focus),
.jp-FormGroup-content fieldset select:hover:not(:focus) {
  background-color: var(--jp-border-color2);
}

/* stylelint-enable selector-max-type */

.jp-FormGroup-content .checkbox .field-description {
  /* Disable default description field for checkbox:
   because other widgets do not have description fields,
   we add descriptions to each widget on the field level.
  */
  display: none;
}

.jp-FormGroup-content #root__description {
  display: none;
}

.jp-FormGroup-content .jp-modifiedIndicator {
  width: 5px;
  background-color: var(--jp-brand-color2);
  margin-top: 0;
  margin-left: calc(var(--jp-private-settingeditor-modifier-indent) * -1);
  flex-shrink: 0;
}

.jp-FormGroup-content .jp-modifiedIndicator.jp-errorIndicator {
  background-color: var(--jp-error-color0);
  margin-right: 0.5em;
}

/* RJSF ARRAY style */

.jp-arrayFieldWrapper legend {
  font-size: var(--jp-content-font-size2);
  color: var(--jp-ui-font-color0);
  flex-basis: 100%;
  padding: 4px 0;
  font-weight: var(--jp-content-heading-font-weight);
  border-bottom: 1px solid var(--jp-border-color2);
}

.jp-arrayFieldWrapper .field-description {
  padding: 4px 0;
  white-space: pre-wrap;
}

.jp-arrayFieldWrapper .array-item {
  width: 100%;
  border: 1px solid var(--jp-border-color2);
  border-radius: 4px;
  margin: 4px;
}

.jp-ArrayOperations {
  display: flex;
  margin-left: 8px;
}

.jp-ArrayOperationsButton {
  margin: 2px;
}

.jp-ArrayOperationsButton .jp-icon3[fill] {
  fill: var(--jp-ui-font-color0);
}

button.jp-ArrayOperationsButton.jp-mod-styled:disabled {
  cursor: not-allowed;
  opacity: 0.5;
}

/* RJSF form validation error */

.jp-FormGroup-content .validationErrors {
  color: var(--jp-error-color0);
}

/* Hide panel level error as duplicated the field level error */
.jp-FormGroup-content .panel.errors {
  display: none;
}

/* RJSF normal content (settings-editor) */

.jp-FormGroup-contentNormal {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.jp-FormGroup-contentNormal .jp-FormGroup-contentItem {
  margin-left: 7px;
  color: var(--jp-ui-font-color0);
}

.jp-FormGroup-contentNormal .jp-FormGroup-description {
  flex-basis: 100%;
  padding: 4px 7px;
}

.jp-FormGroup-contentNormal .jp-FormGroup-default {
  flex-basis: 100%;
  padding: 4px 7px;
}

.jp-FormGroup-contentNormal .jp-FormGroup-fieldLabel {
  font-size: var(--jp-content-font-size1);
  font-weight: normal;
  min-width: 120px;
}

.jp-FormGroup-contentNormal fieldset:not(:first-child) {
  margin-left: 7px;
}

.jp-FormGroup-contentNormal .field-array-of-string .array-item {
  /* Display `jp-ArrayOperations` buttons side-by-side with content except
    for small screens where flex-wrap will place them one below the other.
  */
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.jp-FormGroup-contentNormal .jp-objectFieldWrapper .form-group {
  padding: 2px 8px 2px var(--jp-private-settingeditor-modifier-indent);
  margin-top: 2px;
}

/* RJSF compact content (metadata-form) */

.jp-FormGroup-content.jp-FormGroup-contentCompact {
  width: 100%;
}

.jp-FormGroup-contentCompact .form-group {
  display: flex;
  padding: 0.5em 0.2em 0.5em 0;
}

.jp-FormGroup-contentCompact
  .jp-FormGroup-compactTitle
  .jp-FormGroup-description {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color2);
}

.jp-FormGroup-contentCompact .jp-FormGroup-fieldLabel {
  padding-bottom: 0.3em;
}

.jp-FormGroup-contentCompact .jp-inputFieldWrapper .form-control {
  width: 100%;
  box-sizing: border-box;
}

.jp-FormGroup-contentCompact .jp-arrayFieldWrapper .jp-FormGroup-compactTitle {
  padding-bottom: 7px;
}

.jp-FormGroup-contentCompact
  .jp-objectFieldWrapper
  .jp-objectFieldWrapper
  .form-group {
  padding: 2px 8px 2px var(--jp-private-settingeditor-modifier-indent);
  margin-top: 2px;
}

.jp-FormGroup-contentCompact ul.error-detail {
  margin-block-start: 0.5em;
  margin-block-end: 0.5em;
  padding-inline-start: 1em;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-SidePanel {
  display: flex;
  flex-direction: column;
  min-width: var(--jp-sidebar-min-width);
  overflow-y: auto;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  font-size: var(--jp-ui-font-size1);
}

.jp-SidePanel-header {
  flex: 0 0 auto;
  display: flex;
  border-bottom: var(--jp-border-width) solid var(--jp-border-color2);
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin: 0;
  padding: 2px;
  text-transform: uppercase;
}

.jp-SidePanel-toolbar {
  flex: 0 0 auto;
}

.jp-SidePanel-content {
  flex: 1 1 auto;
}

.jp-SidePanel-toolbar,
.jp-AccordionPanel-toolbar {
  height: var(--jp-private-toolbar-height);
}

.jp-SidePanel-toolbar.jp-Toolbar-micro {
  display: none;
}

.lm-AccordionPanel .jp-AccordionPanel-title {
  box-sizing: border-box;
  line-height: 25px;
  margin: 0;
  display: flex;
  align-items: center;
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  font-size: var(--jp-ui-font-size0);
}

.jp-AccordionPanel-title {
  cursor: pointer;
  user-select: none;
  -moz-user-select: none;
  -webkit-user-select: none;
  text-transform: uppercase;
}

.lm-AccordionPanel[data-orientation='horizontal'] > .jp-AccordionPanel-title {
  /* Title is rotated for horizontal accordion panel using CSS */
  display: block;
  transform-origin: top left;
  transform: rotate(-90deg) translate(-100%);
}

.jp-AccordionPanel-title .lm-AccordionPanel-titleLabel {
  user-select: none;
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
}

.jp-AccordionPanel-title .lm-AccordionPanel-titleCollapser {
  transform: rotate(-90deg);
  margin: auto 0;
  height: 16px;
}

.jp-AccordionPanel-title.lm-mod-expanded .lm-AccordionPanel-titleCollapser {
  transform: rotate(0deg);
}

.lm-AccordionPanel .jp-AccordionPanel-toolbar {
  background: none;
  box-shadow: none;
  border: none;
  margin-left: auto;
}

.lm-AccordionPanel .lm-SplitPanel-handle:hover {
  background: var(--jp-layout-color3);
}

.jp-text-truncated {
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Spinner {
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 10;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-layout-color0);
  outline: none;
}

.jp-SpinnerContent {
  font-size: 10px;
  margin: 50px auto;
  text-indent: -9999em;
  width: 3em;
  height: 3em;
  border-radius: 50%;
  background: var(--jp-brand-color3);
  background: linear-gradient(
    to right,
    #f37626 10%,
    rgba(255, 255, 255, 0) 42%
  );
  position: relative;
  animation: load3 1s infinite linear, fadeIn 1s;
}

.jp-SpinnerContent::before {
  width: 50%;
  height: 50%;
  background: #f37626;
  border-radius: 100% 0 0;
  position: absolute;
  top: 0;
  left: 0;
  content: '';
}

.jp-SpinnerContent::after {
  background: var(--jp-layout-color0);
  width: 75%;
  height: 75%;
  border-radius: 50%;
  content: '';
  margin: auto;
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }

  100% {
    opacity: 1;
  }
}

@keyframes load3 {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

button.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: none;
  box-sizing: border-box;
  text-align: center;
  line-height: 32px;
  height: 32px;
  padding: 0 12px;
  letter-spacing: 0.8px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input.jp-mod-styled {
  background: var(--jp-input-background);
  height: 28px;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color1);
  padding-left: 7px;
  padding-right: 7px;
  font-size: var(--jp-ui-font-size2);
  color: var(--jp-ui-font-color0);
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input[type='checkbox'].jp-mod-styled {
  appearance: checkbox;
  -webkit-appearance: checkbox;
  -moz-appearance: checkbox;
  height: auto;
}

input.jp-mod-styled:focus {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-select-wrapper {
  display: flex;
  position: relative;
  flex-direction: column;
  padding: 1px;
  background-color: var(--jp-layout-color1);
  box-sizing: border-box;
  margin-bottom: 12px;
}

.jp-select-wrapper:not(.multiple) {
  height: 28px;
}

.jp-select-wrapper.jp-mod-focused select.jp-mod-styled {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-input-active-background);
}

select.jp-mod-styled:hover {
  cursor: pointer;
  color: var(--jp-ui-font-color0);
  background-color: var(--jp-input-hover-background);
  box-shadow: inset 0 0 1px rgba(0, 0, 0, 0.5);
}

select.jp-mod-styled {
  flex: 1 1 auto;
  width: 100%;
  font-size: var(--jp-ui-font-size2);
  background: var(--jp-input-background);
  color: var(--jp-ui-font-color0);
  padding: 0 25px 0 8px;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

select.jp-mod-styled:not([multiple]) {
  height: 32px;
}

select.jp-mod-styled[multiple] {
  max-height: 200px;
  overflow-y: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-switch {
  display: flex;
  align-items: center;
  padding-left: 4px;
  padding-right: 4px;
  font-size: var(--jp-ui-font-size1);
  background-color: transparent;
  color: var(--jp-ui-font-color1);
  border: none;
  height: 20px;
}

.jp-switch:hover {
  background-color: var(--jp-layout-color2);
}

.jp-switch-label {
  margin-right: 5px;
  font-family: var(--jp-ui-font-family);
}

.jp-switch-track {
  cursor: pointer;
  background-color: var(--jp-switch-color, var(--jp-border-color1));
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 34px;
  height: 16px;
  width: 35px;
  position: relative;
}

.jp-switch-track::before {
  content: '';
  position: absolute;
  height: 10px;
  width: 10px;
  margin: 3px;
  left: 0;
  background-color: var(--jp-ui-inverse-font-color1);
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 50%;
}

.jp-switch[aria-checked='true'] .jp-switch-track {
  background-color: var(--jp-switch-true-position-color, var(--jp-warn-color0));
}

.jp-switch[aria-checked='true'] .jp-switch-track::before {
  /* track width (35) - margins (3 + 3) - thumb width (10) */
  left: 19px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toolbar-height: calc(
    28px + var(--jp-border-width)
  ); /* leave 28px for content */
}

.jp-Toolbar {
  color: var(--jp-ui-font-color1);
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: 2px;
  z-index: 8;
  overflow-x: hidden;
}

/* Toolbar items */

.jp-Toolbar > .jp-Toolbar-item.jp-Toolbar-spacer {
  flex-grow: 1;
  flex-shrink: 1;
}

.jp-Toolbar-item.jp-Toolbar-kernelStatus {
  display: inline-block;
  width: 32px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: 16px;
}

.jp-Toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  display: flex;
  padding-left: 1px;
  padding-right: 1px;
  font-size: var(--jp-ui-font-size1);
  line-height: var(--jp-private-toolbar-height);
  height: 100%;
}

/* Toolbar buttons */

/* This is the div we use to wrap the react component into a Widget */
div.jp-ToolbarButton {
  color: transparent;
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0;
  margin: 0;
}

button.jp-ToolbarButtonComponent {
  background: var(--jp-layout-color1);
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0 6px;
  margin: 0;
  height: 24px;
  border-radius: var(--jp-border-radius);
  display: flex;
  align-items: center;
  text-align: center;
  font-size: 14px;
  min-width: unset;
  min-height: unset;
}

button.jp-ToolbarButtonComponent:disabled {
  opacity: 0.4;
}

button.jp-ToolbarButtonComponent > span {
  padding: 0;
  flex: 0 0 auto;
}

button.jp-ToolbarButtonComponent .jp-ToolbarButtonComponent-label {
  font-size: var(--jp-ui-font-size1);
  line-height: 100%;
  padding-left: 2px;
  color: var(--jp-ui-font-color1);
  font-family: var(--jp-ui-font-family);
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar.jp-Toolbar-micro {
  padding: 0;
  min-height: 0;
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar {
  border: none;
  box-shadow: none;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-WindowedPanel-outer {
  position: relative;
  overflow-y: auto;
}

.jp-WindowedPanel-inner {
  position: relative;
}

.jp-WindowedPanel-window {
  position: absolute;
  left: 0;
  right: 0;
  overflow: visible;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* Sibling imports */

body {
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
}

/* Disable native link decoration styles everywhere outside of dialog boxes */
a {
  text-decoration: unset;
  color: unset;
}

a:hover {
  text-decoration: unset;
  color: unset;
}

/* Accessibility for links inside dialog box text */
.jp-Dialog-content a {
  text-decoration: revert;
  color: var(--jp-content-link-color);
}

.jp-Dialog-content a:hover {
  text-decoration: revert;
}

/* Styles for ui-components */
.jp-Button {
  color: var(--jp-ui-font-color2);
  border-radius: var(--jp-border-radius);
  padding: 0 12px;
  font-size: var(--jp-ui-font-size1);

  /* Copy from blueprint 3 */
  display: inline-flex;
  flex-direction: row;
  border: none;
  cursor: pointer;
  align-items: center;
  justify-content: center;
  text-align: left;
  vertical-align: middle;
  min-height: 30px;
  min-width: 30px;
}

.jp-Button:disabled {
  cursor: not-allowed;
}

.jp-Button:empty {
  padding: 0 !important;
}

.jp-Button.jp-mod-small {
  min-height: 24px;
  min-width: 24px;
  font-size: 12px;
  padding: 0 7px;
}

/* Use our own theme for hover styles */
.jp-Button.jp-mod-minimal:hover {
  background-color: var(--jp-layout-color2);
}

.jp-Button.jp-mod-minimal {
  background: none;
}

.jp-InputGroup {
  display: block;
  position: relative;
}

.jp-InputGroup input {
  box-sizing: border-box;
  border: none;
  border-radius: 0;
  background-color: transparent;
  color: var(--jp-ui-font-color0);
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
  padding-bottom: 0;
  padding-top: 0;
  padding-left: 10px;
  padding-right: 28px;
  position: relative;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  font-size: 14px;
  font-weight: 400;
  height: 30px;
  line-height: 30px;
  outline: none;
  vertical-align: middle;
}

.jp-InputGroup input:focus {
  box-shadow: inset 0 0 0 var(--jp-border-width)
      var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-InputGroup input:disabled {
  cursor: not-allowed;
  resize: block;
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color2);
}

.jp-InputGroup input:disabled ~ span {
  cursor: not-allowed;
  color: var(--jp-ui-font-color2);
}

.jp-InputGroup input::placeholder,
input::placeholder {
  color: var(--jp-ui-font-color2);
}

.jp-InputGroupAction {
  position: absolute;
  bottom: 1px;
  right: 0;
  padding: 6px;
}

.jp-HTMLSelect.jp-DefaultStyle select {
  background-color: initial;
  border: none;
  border-radius: 0;
  box-shadow: none;
  color: var(--jp-ui-font-color0);
  display: block;
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  height: 24px;
  line-height: 14px;
  padding: 0 25px 0 10px;
  text-align: left;
  -moz-appearance: none;
  -webkit-appearance: none;
}

.jp-HTMLSelect.jp-DefaultStyle select:disabled {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color2);
  cursor: not-allowed;
  resize: block;
}

.jp-HTMLSelect.jp-DefaultStyle select:disabled ~ span {
  cursor: not-allowed;
}

/* Use our own theme for hover and option styles */
/* stylelint-disable-next-line selector-max-type */
.jp-HTMLSelect.jp-DefaultStyle select:hover,
.jp-HTMLSelect.jp-DefaultStyle select > option {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color0);
}

select {
  box-sizing: border-box;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-StatusBar-Widget {
  display: flex;
  align-items: center;
  background: var(--jp-layout-color2);
  min-height: var(--jp-statusbar-height);
  justify-content: space-between;
  padding: 0 10px;
}

.jp-StatusBar-Left {
  display: flex;
  align-items: center;
  flex-direction: row;
}

.jp-StatusBar-Middle {
  display: flex;
  align-items: center;
}

.jp-StatusBar-Right {
  display: flex;
  align-items: center;
  flex-direction: row-reverse;
}

.jp-StatusBar-Item {
  max-height: var(--jp-statusbar-height);
  margin: 0 2px;
  height: var(--jp-statusbar-height);
  white-space: nowrap;
  text-overflow: ellipsis;
  color: var(--jp-ui-font-color1);
  padding: 0 6px;
}

.jp-mod-highlighted:hover {
  background-color: var(--jp-layout-color3);
}

.jp-mod-clicked {
  background-color: var(--jp-brand-color1);
}

.jp-mod-clicked:hover {
  background-color: var(--jp-brand-color0);
}

.jp-mod-clicked .jp-StatusBar-TextItem {
  color: var(--jp-ui-inverse-font-color1);
}

.jp-StatusBar-HoverItem {
  box-shadow: '0px 4px 4px rgba(0, 0, 0, 0.25)';
}

.jp-StatusBar-TextItem {
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  line-height: 24px;
  color: var(--jp-ui-font-color1);
}

.jp-StatusBar-GroupItem {
  display: flex;
  align-items: center;
  flex-direction: row;
}

.jp-Statusbar-ProgressCircle svg {
  display: block;
  margin: 0 auto;
  width: 16px;
  height: 24px;
  align-self: normal;
}

.jp-Statusbar-ProgressCircle path {
  fill: var(--jp-inverse-layout-color3);
}

.jp-Statusbar-ProgressBar-progress-bar {
  height: 10px;
  width: 100px;
  border: solid 0.25px var(--jp-brand-color2);
  border-radius: 3px;
  overflow: hidden;
  align-self: center;
}

.jp-Statusbar-ProgressBar-progress-bar > div {
  background-color: var(--jp-brand-color2);
  background-image: linear-gradient(
    -45deg,
    rgba(255, 255, 255, 0.2) 25%,
    transparent 25%,
    transparent 50%,
    rgba(255, 255, 255, 0.2) 50%,
    rgba(255, 255, 255, 0.2) 75%,
    transparent 75%,
    transparent
  );
  background-size: 40px 40px;
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 14px;
  color: #fff;
  text-align: center;
  animation: jp-Statusbar-ExecutionTime-progress-bar 2s linear infinite;
}

.jp-Statusbar-ProgressBar-progress-bar p {
  color: var(--jp-ui-font-color1);
  font-family: var(--jp-ui-font-family);
  font-size: var(--jp-ui-font-size1);
  line-height: 10px;
  width: 100px;
}

@keyframes jp-Statusbar-ExecutionTime-progress-bar {
  0% {
    background-position: 0 0;
  }

  100% {
    background-position: 40px 40px;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-commandpalette-search-height: 28px;
}

/*-----------------------------------------------------------------------------
| Overall styles
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  padding-bottom: 0;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);

  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Modal variant
|----------------------------------------------------------------------------*/

.jp-ModalCommandPalette {
  position: absolute;
  z-index: 10000;
  top: 38px;
  left: 30%;
  margin: 0;
  padding: 4px;
  width: 40%;
  box-shadow: var(--jp-elevation-z4);
  border-radius: 4px;
  background: var(--jp-layout-color0);
}

.jp-ModalCommandPalette .lm-CommandPalette {
  max-height: 40vh;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-close-icon::after {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-header {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-item {
  margin-left: 4px;
  margin-right: 4px;
}

.jp-ModalCommandPalette
  .lm-CommandPalette
  .lm-CommandPalette-item.lm-mod-disabled {
  display: none;
}

/*-----------------------------------------------------------------------------
| Search
|----------------------------------------------------------------------------*/

.lm-CommandPalette-search {
  padding: 4px;
  background-color: var(--jp-layout-color1);
  z-index: 2;
}

.lm-CommandPalette-wrapper {
  overflow: overlay;
  padding: 0 9px;
  background-color: var(--jp-input-active-background);
  height: 30px;
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.lm-CommandPalette.lm-mod-focused .lm-CommandPalette-wrapper {
  box-shadow: inset 0 0 0 1px var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-SearchIconGroup {
  color: white;
  background-color: var(--jp-brand-color1);
  position: absolute;
  top: 4px;
  right: 4px;
  padding: 5px 5px 1px;
}

.jp-SearchIconGroup svg {
  height: 20px;
  width: 20px;
}

.jp-SearchIconGroup .jp-icon3[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-input {
  background: transparent;
  width: calc(100% - 18px);
  float: left;
  border: none;
  outline: none;
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  line-height: var(--jp-private-commandpalette-search-height);
}

.lm-CommandPalette-input::-webkit-input-placeholder,
.lm-CommandPalette-input::-moz-placeholder,
.lm-CommandPalette-input:-ms-input-placeholder {
  color: var(--jp-ui-font-color2);
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Results
|----------------------------------------------------------------------------*/

.lm-CommandPalette-header:first-child {
  margin-top: 0;
}

.lm-CommandPalette-header {
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin-top: 8px;
  padding: 8px 0 8px 12px;
  text-transform: uppercase;
}

.lm-CommandPalette-header.lm-mod-active {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-header > mark {
  background-color: transparent;
  font-weight: bold;
  color: var(--jp-ui-font-color1);
}

.lm-CommandPalette-item {
  padding: 4px 12px 4px 4px;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  font-weight: 400;
  display: flex;
}

.lm-CommandPalette-item.lm-mod-disabled {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item.lm-mod-active {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item.lm-mod-active .lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-inverse-font-color0);
}

.lm-CommandPalette-item.lm-mod-active .jp-icon-selectable[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-item.lm-mod-active:hover:not(.lm-mod-disabled) {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item:hover:not(.lm-mod-active):not(.lm-mod-disabled) {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-itemContent {
  overflow: hidden;
}

.lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.lm-CommandPalette-item.lm-mod-disabled mark {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item .lm-CommandPalette-itemIcon {
  margin: 0 4px 0 0;
  position: relative;
  width: 16px;
  top: 2px;
  flex: 0 0 auto;
}

.lm-CommandPalette-item.lm-mod-disabled .lm-CommandPalette-itemIcon {
  opacity: 0.6;
}

.lm-CommandPalette-item .lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemCaption {
  display: none;
}

.lm-CommandPalette-content {
  background-color: var(--jp-layout-color1);
}

.lm-CommandPalette-content:empty::after {
  content: 'No results';
  margin: auto;
  margin-top: 20px;
  width: 100px;
  display: block;
  font-size: var(--jp-ui-font-size2);
  font-family: var(--jp-ui-font-family);
  font-weight: lighter;
}

.lm-CommandPalette-emptyMessage {
  text-align: center;
  margin-top: 24px;
  line-height: 1.32;
  padding: 0 8px;
  color: var(--jp-content-font-color3);
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Dialog {
  position: absolute;
  z-index: 10000;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  top: 0;
  left: 0;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-dialog-background);
}

.jp-Dialog-content {
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  background: var(--jp-layout-color1);
  padding: 24px 24px 12px;
  min-width: 300px;
  min-height: 150px;
  max-width: 1000px;
  max-height: 500px;
  box-sizing: border-box;
  box-shadow: var(--jp-elevation-z20);
  word-wrap: break-word;
  border-radius: var(--jp-border-radius);

  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color1);
  resize: both;
}

.jp-Dialog-content.jp-Dialog-content-small {
  max-width: 500px;
}

.jp-Dialog-button {
  overflow: visible;
}

button.jp-Dialog-button:focus {
  outline: 1px solid var(--jp-brand-color1);
  outline-offset: 4px;
  -moz-outline-radius: 0;
}

button.jp-Dialog-button:focus::-moz-focus-inner {
  border: 0;
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-accept:focus,
button.jp-Dialog-button.jp-mod-styled.jp-mod-warn:focus,
button.jp-Dialog-button.jp-mod-styled.jp-mod-reject:focus {
  outline-offset: 4px;
  -moz-outline-radius: 0;
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-accept:focus {
  outline: 1px solid var(--jp-accept-color-normal, var(--jp-brand-color1));
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-warn:focus {
  outline: 1px solid var(--jp-warn-color-normal, var(--jp-error-color1));
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-reject:focus {
  outline: 1px solid var(--jp-reject-color-normal, var(--md-grey-600));
}

button.jp-Dialog-close-button {
  padding: 0;
  height: 100%;
  min-width: unset;
  min-height: unset;
}

.jp-Dialog-header {
  display: flex;
  justify-content: space-between;
  flex: 0 0 auto;
  padding-bottom: 12px;
  font-size: var(--jp-ui-font-size3);
  font-weight: 400;
  color: var(--jp-ui-font-color1);
}

.jp-Dialog-body {
  display: flex;
  flex-direction: column;
  flex: 1 1 auto;
  font-size: var(--jp-ui-font-size1);
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

.jp-Dialog-footer {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  align-items: center;
  flex: 0 0 auto;
  margin-left: -12px;
  margin-right: -12px;
  padding: 12px;
}

.jp-Dialog-checkbox {
  padding-right: 5px;
}

.jp-Dialog-checkbox > input:focus-visible {
  outline: 1px solid var(--jp-input-active-border-color);
  outline-offset: 1px;
}

.jp-Dialog-spacer {
  flex: 1 1 auto;
}

.jp-Dialog-title {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.jp-Dialog-body > .jp-select-wrapper {
  width: 100%;
}

.jp-Dialog-body > button {
  padding: 0 16px;
}

.jp-Dialog-body > label {
  line-height: 1.4;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-button.jp-mod-styled:not(:last-child) {
  margin-right: 12px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-Input-Boolean-Dialog {
  flex-direction: row-reverse;
  align-items: end;
  width: 100%;
}

.jp-Input-Boolean-Dialog > label {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MainAreaWidget > :focus {
  outline: none;
}

.jp-MainAreaWidget .jp-MainAreaWidget-error {
  padding: 6px;
}

.jp-MainAreaWidget .jp-MainAreaWidget-error > pre {
  width: auto;
  padding: 10px;
  background: var(--jp-error-color3);
  border: var(--jp-border-width) solid var(--jp-error-color1);
  border-radius: var(--jp-border-radius);
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  white-space: pre-wrap;
  word-wrap: break-word;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/**
 * google-material-color v1.2.6
 * https://github.com/danlevan/google-material-color
 */
:root {
  --md-red-50: #ffebee;
  --md-red-100: #ffcdd2;
  --md-red-200: #ef9a9a;
  --md-red-300: #e57373;
  --md-red-400: #ef5350;
  --md-red-500: #f44336;
  --md-red-600: #e53935;
  --md-red-700: #d32f2f;
  --md-red-800: #c62828;
  --md-red-900: #b71c1c;
  --md-red-A100: #ff8a80;
  --md-red-A200: #ff5252;
  --md-red-A400: #ff1744;
  --md-red-A700: #d50000;
  --md-pink-50: #fce4ec;
  --md-pink-100: #f8bbd0;
  --md-pink-200: #f48fb1;
  --md-pink-300: #f06292;
  --md-pink-400: #ec407a;
  --md-pink-500: #e91e63;
  --md-pink-600: #d81b60;
  --md-pink-700: #c2185b;
  --md-pink-800: #ad1457;
  --md-pink-900: #880e4f;
  --md-pink-A100: #ff80ab;
  --md-pink-A200: #ff4081;
  --md-pink-A400: #f50057;
  --md-pink-A700: #c51162;
  --md-purple-50: #f3e5f5;
  --md-purple-100: #e1bee7;
  --md-purple-200: #ce93d8;
  --md-purple-300: #ba68c8;
  --md-purple-400: #ab47bc;
  --md-purple-500: #9c27b0;
  --md-purple-600: #8e24aa;
  --md-purple-700: #7b1fa2;
  --md-purple-800: #6a1b9a;
  --md-purple-900: #4a148c;
  --md-purple-A100: #ea80fc;
  --md-purple-A200: #e040fb;
  --md-purple-A400: #d500f9;
  --md-purple-A700: #a0f;
  --md-deep-purple-50: #ede7f6;
  --md-deep-purple-100: #d1c4e9;
  --md-deep-purple-200: #b39ddb;
  --md-deep-purple-300: #9575cd;
  --md-deep-purple-400: #7e57c2;
  --md-deep-purple-500: #673ab7;
  --md-deep-purple-600: #5e35b1;
  --md-deep-purple-700: #512da8;
  --md-deep-purple-800: #4527a0;
  --md-deep-purple-900: #311b92;
  --md-deep-purple-A100: #b388ff;
  --md-deep-purple-A200: #7c4dff;
  --md-deep-purple-A400: #651fff;
  --md-deep-purple-A700: #6200ea;
  --md-indigo-50: #e8eaf6;
  --md-indigo-100: #c5cae9;
  --md-indigo-200: #9fa8da;
  --md-indigo-300: #7986cb;
  --md-indigo-400: #5c6bc0;
  --md-indigo-500: #3f51b5;
  --md-indigo-600: #3949ab;
  --md-indigo-700: #303f9f;
  --md-indigo-800: #283593;
  --md-indigo-900: #1a237e;
  --md-indigo-A100: #8c9eff;
  --md-indigo-A200: #536dfe;
  --md-indigo-A400: #3d5afe;
  --md-indigo-A700: #304ffe;
  --md-blue-50: #e3f2fd;
  --md-blue-100: #bbdefb;
  --md-blue-200: #90caf9;
  --md-blue-300: #64b5f6;
  --md-blue-400: #42a5f5;
  --md-blue-500: #2196f3;
  --md-blue-600: #1e88e5;
  --md-blue-700: #1976d2;
  --md-blue-800: #1565c0;
  --md-blue-900: #0d47a1;
  --md-blue-A100: #82b1ff;
  --md-blue-A200: #448aff;
  --md-blue-A400: #2979ff;
  --md-blue-A700: #2962ff;
  --md-light-blue-50: #e1f5fe;
  --md-light-blue-100: #b3e5fc;
  --md-light-blue-200: #81d4fa;
  --md-light-blue-300: #4fc3f7;
  --md-light-blue-400: #29b6f6;
  --md-light-blue-500: #03a9f4;
  --md-light-blue-600: #039be5;
  --md-light-blue-700: #0288d1;
  --md-light-blue-800: #0277bd;
  --md-light-blue-900: #01579b;
  --md-light-blue-A100: #80d8ff;
  --md-light-blue-A200: #40c4ff;
  --md-light-blue-A400: #00b0ff;
  --md-light-blue-A700: #0091ea;
  --md-cyan-50: #e0f7fa;
  --md-cyan-100: #b2ebf2;
  --md-cyan-200: #80deea;
  --md-cyan-300: #4dd0e1;
  --md-cyan-400: #26c6da;
  --md-cyan-500: #00bcd4;
  --md-cyan-600: #00acc1;
  --md-cyan-700: #0097a7;
  --md-cyan-800: #00838f;
  --md-cyan-900: #006064;
  --md-cyan-A100: #84ffff;
  --md-cyan-A200: #18ffff;
  --md-cyan-A400: #00e5ff;
  --md-cyan-A700: #00b8d4;
  --md-teal-50: #e0f2f1;
  --md-teal-100: #b2dfdb;
  --md-teal-200: #80cbc4;
  --md-teal-300: #4db6ac;
  --md-teal-400: #26a69a;
  --md-teal-500: #009688;
  --md-teal-600: #00897b;
  --md-teal-700: #00796b;
  --md-teal-800: #00695c;
  --md-teal-900: #004d40;
  --md-teal-A100: #a7ffeb;
  --md-teal-A200: #64ffda;
  --md-teal-A400: #1de9b6;
  --md-teal-A700: #00bfa5;
  --md-green-50: #e8f5e9;
  --md-green-100: #c8e6c9;
  --md-green-200: #a5d6a7;
  --md-green-300: #81c784;
  --md-green-400: #66bb6a;
  --md-green-500: #4caf50;
  --md-green-600: #43a047;
  --md-green-700: #388e3c;
  --md-green-800: #2e7d32;
  --md-green-900: #1b5e20;
  --md-green-A100: #b9f6ca;
  --md-green-A200: #69f0ae;
  --md-green-A400: #00e676;
  --md-green-A700: #00c853;
  --md-light-green-50: #f1f8e9;
  --md-light-green-100: #dcedc8;
  --md-light-green-200: #c5e1a5;
  --md-light-green-300: #aed581;
  --md-light-green-400: #9ccc65;
  --md-light-green-500: #8bc34a;
  --md-light-green-600: #7cb342;
  --md-light-green-700: #689f38;
  --md-light-green-800: #558b2f;
  --md-light-green-900: #33691e;
  --md-light-green-A100: #ccff90;
  --md-light-green-A200: #b2ff59;
  --md-light-green-A400: #76ff03;
  --md-light-green-A700: #64dd17;
  --md-lime-50: #f9fbe7;
  --md-lime-100: #f0f4c3;
  --md-lime-200: #e6ee9c;
  --md-lime-300: #dce775;
  --md-lime-400: #d4e157;
  --md-lime-500: #cddc39;
  --md-lime-600: #c0ca33;
  --md-lime-700: #afb42b;
  --md-lime-800: #9e9d24;
  --md-lime-900: #827717;
  --md-lime-A100: #f4ff81;
  --md-lime-A200: #eeff41;
  --md-lime-A400: #c6ff00;
  --md-lime-A700: #aeea00;
  --md-yellow-50: #fffde7;
  --md-yellow-100: #fff9c4;
  --md-yellow-200: #fff59d;
  --md-yellow-300: #fff176;
  --md-yellow-400: #ffee58;
  --md-yellow-500: #ffeb3b;
  --md-yellow-600: #fdd835;
  --md-yellow-700: #fbc02d;
  --md-yellow-800: #f9a825;
  --md-yellow-900: #f57f17;
  --md-yellow-A100: #ffff8d;
  --md-yellow-A200: #ff0;
  --md-yellow-A400: #ffea00;
  --md-yellow-A700: #ffd600;
  --md-amber-50: #fff8e1;
  --md-amber-100: #ffecb3;
  --md-amber-200: #ffe082;
  --md-amber-300: #ffd54f;
  --md-amber-400: #ffca28;
  --md-amber-500: #ffc107;
  --md-amber-600: #ffb300;
  --md-amber-700: #ffa000;
  --md-amber-800: #ff8f00;
  --md-amber-900: #ff6f00;
  --md-amber-A100: #ffe57f;
  --md-amber-A200: #ffd740;
  --md-amber-A400: #ffc400;
  --md-amber-A700: #ffab00;
  --md-orange-50: #fff3e0;
  --md-orange-100: #ffe0b2;
  --md-orange-200: #ffcc80;
  --md-orange-300: #ffb74d;
  --md-orange-400: #ffa726;
  --md-orange-500: #ff9800;
  --md-orange-600: #fb8c00;
  --md-orange-700: #f57c00;
  --md-orange-800: #ef6c00;
  --md-orange-900: #e65100;
  --md-orange-A100: #ffd180;
  --md-orange-A200: #ffab40;
  --md-orange-A400: #ff9100;
  --md-orange-A700: #ff6d00;
  --md-deep-orange-50: #fbe9e7;
  --md-deep-orange-100: #ffccbc;
  --md-deep-orange-200: #ffab91;
  --md-deep-orange-300: #ff8a65;
  --md-deep-orange-400: #ff7043;
  --md-deep-orange-500: #ff5722;
  --md-deep-orange-600: #f4511e;
  --md-deep-orange-700: #e64a19;
  --md-deep-orange-800: #d84315;
  --md-deep-orange-900: #bf360c;
  --md-deep-orange-A100: #ff9e80;
  --md-deep-orange-A200: #ff6e40;
  --md-deep-orange-A400: #ff3d00;
  --md-deep-orange-A700: #dd2c00;
  --md-brown-50: #efebe9;
  --md-brown-100: #d7ccc8;
  --md-brown-200: #bcaaa4;
  --md-brown-300: #a1887f;
  --md-brown-400: #8d6e63;
  --md-brown-500: #795548;
  --md-brown-600: #6d4c41;
  --md-brown-700: #5d4037;
  --md-brown-800: #4e342e;
  --md-brown-900: #3e2723;
  --md-grey-50: #fafafa;
  --md-grey-100: #f5f5f5;
  --md-grey-200: #eee;
  --md-grey-300: #e0e0e0;
  --md-grey-400: #bdbdbd;
  --md-grey-500: #9e9e9e;
  --md-grey-600: #757575;
  --md-grey-700: #616161;
  --md-grey-800: #424242;
  --md-grey-900: #212121;
  --md-blue-grey-50: #eceff1;
  --md-blue-grey-100: #cfd8dc;
  --md-blue-grey-200: #b0bec5;
  --md-blue-grey-300: #90a4ae;
  --md-blue-grey-400: #78909c;
  --md-blue-grey-500: #607d8b;
  --md-blue-grey-600: #546e7a;
  --md-blue-grey-700: #455a64;
  --md-blue-grey-800: #37474f;
  --md-blue-grey-900: #263238;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| RenderedText
|----------------------------------------------------------------------------*/

:root {
  /* This is the padding value to fill the gaps between lines containing spans with background color. */
  --jp-private-code-span-padding: calc(
    (var(--jp-code-line-height) - 1) * var(--jp-code-font-size) / 2
  );
}

.jp-RenderedText {
  text-align: left;
  padding-left: var(--jp-code-padding);
  line-height: var(--jp-code-line-height);
  font-family: var(--jp-code-font-family);
}

.jp-RenderedText pre,
.jp-RenderedJavaScript pre,
.jp-RenderedHTMLCommon pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
  border: none;
  margin: 0;
  padding: 0;
}

.jp-RenderedText pre a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedText pre a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedText pre a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* console foregrounds and backgrounds */
.jp-RenderedText pre .ansi-black-fg {
  color: #3e424d;
}

.jp-RenderedText pre .ansi-red-fg {
  color: #e75c58;
}

.jp-RenderedText pre .ansi-green-fg {
  color: #00a250;
}

.jp-RenderedText pre .ansi-yellow-fg {
  color: #ddb62b;
}

.jp-RenderedText pre .ansi-blue-fg {
  color: #208ffb;
}

.jp-RenderedText pre .ansi-magenta-fg {
  color: #d160c4;
}

.jp-RenderedText pre .ansi-cyan-fg {
  color: #60c6c8;
}

.jp-RenderedText pre .ansi-white-fg {
  color: #c5c1b4;
}

.jp-RenderedText pre .ansi-black-bg {
  background-color: #3e424d;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-red-bg {
  background-color: #e75c58;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-green-bg {
  background-color: #00a250;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-yellow-bg {
  background-color: #ddb62b;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-blue-bg {
  background-color: #208ffb;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-magenta-bg {
  background-color: #d160c4;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-cyan-bg {
  background-color: #60c6c8;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-white-bg {
  background-color: #c5c1b4;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-black-intense-fg {
  color: #282c36;
}

.jp-RenderedText pre .ansi-red-intense-fg {
  color: #b22b31;
}

.jp-RenderedText pre .ansi-green-intense-fg {
  color: #007427;
}

.jp-RenderedText pre .ansi-yellow-intense-fg {
  color: #b27d12;
}

.jp-RenderedText pre .ansi-blue-intense-fg {
  color: #0065ca;
}

.jp-RenderedText pre .ansi-magenta-intense-fg {
  color: #a03196;
}

.jp-RenderedText pre .ansi-cyan-intense-fg {
  color: #258f8f;
}

.jp-RenderedText pre .ansi-white-intense-fg {
  color: #a1a6b2;
}

.jp-RenderedText pre .ansi-black-intense-bg {
  background-color: #282c36;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-red-intense-bg {
  background-color: #b22b31;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-green-intense-bg {
  background-color: #007427;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-yellow-intense-bg {
  background-color: #b27d12;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-blue-intense-bg {
  background-color: #0065ca;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-magenta-intense-bg {
  background-color: #a03196;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-cyan-intense-bg {
  background-color: #258f8f;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-white-intense-bg {
  background-color: #a1a6b2;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-default-inverse-fg {
  color: var(--jp-ui-inverse-font-color0);
}

.jp-RenderedText pre .ansi-default-inverse-bg {
  background-color: var(--jp-inverse-layout-color0);
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-bold {
  font-weight: bold;
}

.jp-RenderedText pre .ansi-underline {
  text-decoration: underline;
}

.jp-RenderedText[data-mime-type='application/vnd.jupyter.stderr'] {
  background: var(--jp-rendermime-error-background);
  padding-top: var(--jp-code-padding);
}

/*-----------------------------------------------------------------------------
| RenderedLatex
|----------------------------------------------------------------------------*/

.jp-RenderedLatex {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
}

/* Left-justify outputs.*/
.jp-OutputArea-output.jp-RenderedLatex {
  padding: var(--jp-code-padding);
  text-align: left;
}

/*-----------------------------------------------------------------------------
| RenderedHTML
|----------------------------------------------------------------------------*/

.jp-RenderedHTMLCommon {
  color: var(--jp-content-font-color1);
  font-family: var(--jp-content-font-family);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);

  /* Give a bit more R padding on Markdown text to keep line lengths reasonable */
  padding-right: 20px;
}

.jp-RenderedHTMLCommon em {
  font-style: italic;
}

.jp-RenderedHTMLCommon strong {
  font-weight: bold;
}

.jp-RenderedHTMLCommon u {
  text-decoration: underline;
}

.jp-RenderedHTMLCommon a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* Headings */

.jp-RenderedHTMLCommon h1,
.jp-RenderedHTMLCommon h2,
.jp-RenderedHTMLCommon h3,
.jp-RenderedHTMLCommon h4,
.jp-RenderedHTMLCommon h5,
.jp-RenderedHTMLCommon h6 {
  line-height: var(--jp-content-heading-line-height);
  font-weight: var(--jp-content-heading-font-weight);
  font-style: normal;
  margin: var(--jp-content-heading-margin-top) 0
    var(--jp-content-heading-margin-bottom) 0;
}

.jp-RenderedHTMLCommon h1:first-child,
.jp-RenderedHTMLCommon h2:first-child,
.jp-RenderedHTMLCommon h3:first-child,
.jp-RenderedHTMLCommon h4:first-child,
.jp-RenderedHTMLCommon h5:first-child,
.jp-RenderedHTMLCommon h6:first-child {
  margin-top: calc(0.5 * var(--jp-content-heading-margin-top));
}

.jp-RenderedHTMLCommon h1:last-child,
.jp-RenderedHTMLCommon h2:last-child,
.jp-RenderedHTMLCommon h3:last-child,
.jp-RenderedHTMLCommon h4:last-child,
.jp-RenderedHTMLCommon h5:last-child,
.jp-RenderedHTMLCommon h6:last-child {
  margin-bottom: calc(0.5 * var(--jp-content-heading-margin-bottom));
}

.jp-RenderedHTMLCommon h1 {
  font-size: var(--jp-content-font-size5);
}

.jp-RenderedHTMLCommon h2 {
  font-size: var(--jp-content-font-size4);
}

.jp-RenderedHTMLCommon h3 {
  font-size: var(--jp-content-font-size3);
}

.jp-RenderedHTMLCommon h4 {
  font-size: var(--jp-content-font-size2);
}

.jp-RenderedHTMLCommon h5 {
  font-size: var(--jp-content-font-size1);
}

.jp-RenderedHTMLCommon h6 {
  font-size: var(--jp-content-font-size0);
}

/* Lists */

/* stylelint-disable selector-max-type, selector-max-compound-selectors */

.jp-RenderedHTMLCommon ul:not(.list-inline),
.jp-RenderedHTMLCommon ol:not(.list-inline) {
  padding-left: 2em;
}

.jp-RenderedHTMLCommon ul {
  list-style: disc;
}

.jp-RenderedHTMLCommon ul ul {
  list-style: square;
}

.jp-RenderedHTMLCommon ul ul ul {
  list-style: circle;
}

.jp-RenderedHTMLCommon ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol ol {
  list-style: upper-alpha;
}

.jp-RenderedHTMLCommon ol ol ol {
  list-style: lower-alpha;
}

.jp-RenderedHTMLCommon ol ol ol ol {
  list-style: lower-roman;
}

.jp-RenderedHTMLCommon ol ol ol ol ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol,
.jp-RenderedHTMLCommon ul {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon ul ul,
.jp-RenderedHTMLCommon ul ol,
.jp-RenderedHTMLCommon ol ul,
.jp-RenderedHTMLCommon ol ol {
  margin-bottom: 0;
}

/* stylelint-enable selector-max-type, selector-max-compound-selectors */

.jp-RenderedHTMLCommon hr {
  color: var(--jp-border-color2);
  background-color: var(--jp-border-color1);
  margin-top: 1em;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon > pre {
  margin: 1.5em 2em;
}

.jp-RenderedHTMLCommon pre,
.jp-RenderedHTMLCommon code {
  border: 0;
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  line-height: var(--jp-code-line-height);
  padding: 0;
  white-space: pre-wrap;
}

.jp-RenderedHTMLCommon :not(pre) > code {
  background-color: var(--jp-layout-color2);
  padding: 1px 5px;
}

/* Tables */

.jp-RenderedHTMLCommon table {
  border-collapse: collapse;
  border-spacing: 0;
  border: none;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  table-layout: fixed;
  margin-left: auto;
  margin-bottom: 1em;
  margin-right: auto;
}

.jp-RenderedHTMLCommon thead {
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  vertical-align: bottom;
}

.jp-RenderedHTMLCommon td,
.jp-RenderedHTMLCommon th,
.jp-RenderedHTMLCommon tr {
  vertical-align: middle;
  padding: 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}

.jp-RenderedMarkdown.jp-RenderedHTMLCommon td,
.jp-RenderedMarkdown.jp-RenderedHTMLCommon th {
  max-width: none;
}

:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon td,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon th,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon tr {
  text-align: right;
}

.jp-RenderedHTMLCommon th {
  font-weight: bold;
}

.jp-RenderedHTMLCommon tbody tr:nth-child(odd) {
  background: var(--jp-layout-color0);
}

.jp-RenderedHTMLCommon tbody tr:nth-child(even) {
  background: var(--jp-rendermime-table-row-background);
}

.jp-RenderedHTMLCommon tbody tr:hover {
  background: var(--jp-rendermime-table-row-hover-background);
}

.jp-RenderedHTMLCommon p {
  text-align: left;
  margin: 0;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon img {
  -moz-force-broken-image-icon: 1;
}

/* Restrict to direct children as other images could be nested in other content. */
.jp-RenderedHTMLCommon > img {
  display: block;
  margin-left: 0;
  margin-right: 0;
  margin-bottom: 1em;
}

/* Change color behind transparent images if they need it... */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-light-background {
  background-color: var(--jp-inverse-layout-color1);
}

[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-dark-background {
  background-color: var(--jp-inverse-layout-color1);
}

.jp-RenderedHTMLCommon img,
.jp-RenderedImage img,
.jp-RenderedHTMLCommon svg,
.jp-RenderedSVG svg {
  max-width: 100%;
  height: auto;
}

.jp-RenderedHTMLCommon img.jp-mod-unconfined,
.jp-RenderedImage img.jp-mod-unconfined,
.jp-RenderedHTMLCommon svg.jp-mod-unconfined,
.jp-RenderedSVG svg.jp-mod-unconfined {
  max-width: none;
}

.jp-RenderedHTMLCommon .alert {
  padding: var(--jp-notebook-padding);
  border: var(--jp-border-width) solid transparent;
  border-radius: var(--jp-border-radius);
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon .alert-info {
  color: var(--jp-info-color0);
  background-color: var(--jp-info-color3);
  border-color: var(--jp-info-color2);
}

.jp-RenderedHTMLCommon .alert-info hr {
  border-color: var(--jp-info-color3);
}

.jp-RenderedHTMLCommon .alert-info > p:last-child,
.jp-RenderedHTMLCommon .alert-info > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-warning {
  color: var(--jp-warn-color0);
  background-color: var(--jp-warn-color3);
  border-color: var(--jp-warn-color2);
}

.jp-RenderedHTMLCommon .alert-warning hr {
  border-color: var(--jp-warn-color3);
}

.jp-RenderedHTMLCommon .alert-warning > p:last-child,
.jp-RenderedHTMLCommon .alert-warning > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-success {
  color: var(--jp-success-color0);
  background-color: var(--jp-success-color3);
  border-color: var(--jp-success-color2);
}

.jp-RenderedHTMLCommon .alert-success hr {
  border-color: var(--jp-success-color3);
}

.jp-RenderedHTMLCommon .alert-success > p:last-child,
.jp-RenderedHTMLCommon .alert-success > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-danger {
  color: var(--jp-error-color0);
  background-color: var(--jp-error-color3);
  border-color: var(--jp-error-color2);
}

.jp-RenderedHTMLCommon .alert-danger hr {
  border-color: var(--jp-error-color3);
}

.jp-RenderedHTMLCommon .alert-danger > p:last-child,
.jp-RenderedHTMLCommon .alert-danger > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon blockquote {
  margin: 1em 2em;
  padding: 0 1em;
  border-left: 5px solid var(--jp-border-color2);
}

a.jp-InternalAnchorLink {
  visibility: hidden;
  margin-left: 8px;
  color: var(--md-blue-800);
}

h1:hover .jp-InternalAnchorLink,
h2:hover .jp-InternalAnchorLink,
h3:hover .jp-InternalAnchorLink,
h4:hover .jp-InternalAnchorLink,
h5:hover .jp-InternalAnchorLink,
h6:hover .jp-InternalAnchorLink {
  visibility: visible;
}

.jp-RenderedHTMLCommon kbd {
  background-color: var(--jp-rendermime-table-row-background);
  border: 1px solid var(--jp-border-color0);
  border-bottom-color: var(--jp-border-color2);
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
  display: inline-block;
  font-size: var(--jp-ui-font-size0);
  line-height: 1em;
  padding: 0.2em 0.5em;
}

/* Most direct children of .jp-RenderedHTMLCommon have a margin-bottom of 1.0.
 * At the bottom of cells this is a bit too much as there is also spacing
 * between cells. Going all the way to 0 gets too tight between markdown and
 * code cells.
 */
.jp-RenderedHTMLCommon > *:last-child {
  margin-bottom: 0.5em;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-cursor-backdrop {
  position: fixed;
  width: 200px;
  height: 200px;
  margin-top: -100px;
  margin-left: -100px;
  will-change: transform;
  z-index: 100;
}

.lm-mod-drag-image {
  will-change: transform;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-lineFormSearch {
  padding: 4px 12px;
  background-color: var(--jp-layout-color2);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
  font-size: var(--jp-ui-font-size1);
}

.jp-lineFormCaption {
  font-size: var(--jp-ui-font-size0);
  line-height: var(--jp-ui-font-size1);
  margin-top: 4px;
  color: var(--jp-ui-font-color0);
}

.jp-baseLineForm {
  border: none;
  border-radius: 0;
  position: absolute;
  background-size: 16px;
  background-repeat: no-repeat;
  background-position: center;
  outline: none;
}

.jp-lineFormButtonContainer {
  top: 4px;
  right: 8px;
  height: 24px;
  padding: 0 12px;
  width: 12px;
}

.jp-lineFormButtonIcon {
  top: 0;
  right: 0;
  background-color: var(--jp-brand-color1);
  height: 100%;
  width: 100%;
  box-sizing: border-box;
  padding: 4px 6px;
}

.jp-lineFormButton {
  top: 0;
  right: 0;
  background-color: transparent;
  height: 100%;
  width: 100%;
  box-sizing: border-box;
}

.jp-lineFormWrapper {
  overflow: hidden;
  padding: 0 8px;
  border: 1px solid var(--jp-border-color0);
  background-color: var(--jp-input-active-background);
  height: 22px;
}

.jp-lineFormWrapperFocusWithin {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-lineFormInput {
  background: transparent;
  width: 200px;
  height: 100%;
  border: none;
  outline: none;
  color: var(--jp-ui-font-color0);
  line-height: 28px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-JSONEditor {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.jp-JSONEditor-host {
  flex: 1 1 auto;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0;
  background: var(--jp-layout-color0);
  min-height: 50px;
  padding: 1px;
}

.jp-JSONEditor.jp-mod-error .jp-JSONEditor-host {
  border-color: red;
  outline-color: red;
}

.jp-JSONEditor-header {
  display: flex;
  flex: 1 0 auto;
  padding: 0 0 0 12px;
}

.jp-JSONEditor-header label {
  flex: 0 0 auto;
}

.jp-JSONEditor-commitButton {
  height: 16px;
  width: 16px;
  background-size: 18px;
  background-repeat: no-repeat;
  background-position: center;
}

.jp-JSONEditor-host.jp-mod-focused {
  background-color: var(--jp-input-active-background);
  border: 1px solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

.jp-Editor.jp-mod-dropTarget {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/
.jp-DocumentSearch-input {
  border: none;
  outline: none;
  color: var(--jp-ui-font-color0);
  font-size: var(--jp-ui-font-size1);
  background-color: var(--jp-layout-color0);
  font-family: var(--jp-ui-font-family);
  padding: 2px 1px;
  resize: none;
}

.jp-DocumentSearch-overlay {
  position: absolute;
  background-color: var(--jp-toolbar-background);
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  border-left: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  top: 0;
  right: 0;
  z-index: 7;
  min-width: 405px;
  padding: 2px;
  font-size: var(--jp-ui-font-size1);

  --jp-private-document-search-button-height: 20px;
}

.jp-DocumentSearch-overlay button {
  background-color: var(--jp-toolbar-background);
  outline: 0;
}

.jp-DocumentSearch-overlay button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-overlay button:active {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-overlay-row {
  display: flex;
  align-items: center;
  margin-bottom: 2px;
}

.jp-DocumentSearch-button-content {
  display: inline-block;
  cursor: pointer;
  box-sizing: border-box;
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-button-content svg {
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-input-wrapper {
  border: var(--jp-border-width) solid var(--jp-border-color0);
  display: flex;
  background-color: var(--jp-layout-color0);
  margin: 2px;
}

.jp-DocumentSearch-input-wrapper:focus-within {
  border-color: var(--jp-cell-editor-active-border-color);
}

.jp-DocumentSearch-toggle-wrapper,
.jp-DocumentSearch-button-wrapper {
  all: initial;
  overflow: hidden;
  display: inline-block;
  border: none;
  box-sizing: border-box;
}

.jp-DocumentSearch-toggle-wrapper {
  width: 14px;
  height: 14px;
}

.jp-DocumentSearch-button-wrapper {
  width: var(--jp-private-document-search-button-height);
  height: var(--jp-private-document-search-button-height);
}

.jp-DocumentSearch-toggle-wrapper:focus,
.jp-DocumentSearch-button-wrapper:focus {
  outline: var(--jp-border-width) solid
    var(--jp-cell-editor-active-border-color);
  outline-offset: -1px;
}

.jp-DocumentSearch-toggle-wrapper,
.jp-DocumentSearch-button-wrapper,
.jp-DocumentSearch-button-content:focus {
  outline: none;
}

.jp-DocumentSearch-toggle-placeholder {
  width: 5px;
}

.jp-DocumentSearch-input-button::before {
  display: block;
  padding-top: 100%;
}

.jp-DocumentSearch-input-button-off {
  opacity: var(--jp-search-toggle-off-opacity);
}

.jp-DocumentSearch-input-button-off:hover {
  opacity: var(--jp-search-toggle-hover-opacity);
}

.jp-DocumentSearch-input-button-on {
  opacity: var(--jp-search-toggle-on-opacity);
}

.jp-DocumentSearch-index-counter {
  padding-left: 10px;
  padding-right: 10px;
  user-select: none;
  min-width: 35px;
  display: inline-block;
}

.jp-DocumentSearch-up-down-wrapper {
  display: inline-block;
  padding-right: 2px;
  margin-left: auto;
  white-space: nowrap;
}

.jp-DocumentSearch-spacer {
  margin-left: auto;
}

.jp-DocumentSearch-up-down-wrapper button {
  outline: 0;
  border: none;
  width: var(--jp-private-document-search-button-height);
  height: var(--jp-private-document-search-button-height);
  vertical-align: middle;
  margin: 1px 5px 2px;
}

.jp-DocumentSearch-up-down-button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-up-down-button:active {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-filter-button {
  border-radius: var(--jp-border-radius);
}

.jp-DocumentSearch-filter-button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-filter-button-enabled {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-filter-button-enabled:hover {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-search-options {
  padding: 0 8px;
  margin-left: 3px;
  width: 100%;
  display: grid;
  justify-content: start;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  justify-items: stretch;
}

.jp-DocumentSearch-search-filter-disabled {
  color: var(--jp-ui-font-color2);
}

.jp-DocumentSearch-search-filter {
  display: flex;
  align-items: center;
  user-select: none;
}

.jp-DocumentSearch-regex-error {
  color: var(--jp-error-color0);
}

.jp-DocumentSearch-replace-button-wrapper {
  overflow: hidden;
  display: inline-block;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color0);
  margin: auto 2px;
  padding: 1px 4px;
  height: calc(var(--jp-private-document-search-button-height) + 2px);
}

.jp-DocumentSearch-replace-button-wrapper:focus {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
}

.jp-DocumentSearch-replace-button {
  display: inline-block;
  text-align: center;
  cursor: pointer;
  box-sizing: border-box;
  color: var(--jp-ui-font-color1);

  /* height - 2 * (padding of wrapper) */
  line-height: calc(var(--jp-private-document-search-button-height) - 2px);
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-replace-button:focus {
  outline: none;
}

.jp-DocumentSearch-replace-wrapper-class {
  margin-left: 14px;
  display: flex;
}

.jp-DocumentSearch-replace-toggle {
  border: none;
  background-color: var(--jp-toolbar-background);
  border-radius: var(--jp-border-radius);
}

.jp-DocumentSearch-replace-toggle:hover {
  background-color: var(--jp-layout-color2);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.cm-editor {
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  border: 0;
  border-radius: 0;
  height: auto;

  /* Changed to auto to autogrow */
}

.cm-editor pre {
  padding: 0 var(--jp-code-padding);
}

.jp-CodeMirrorEditor[data-type='inline'] .cm-dialog {
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

.jp-CodeMirrorEditor {
  cursor: text;
}

/* When zoomed out 67% and 33% on a screen of 1440 width x 900 height */
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .jp-CodeMirrorEditor[data-type='inline'] .cm-cursor {
    border-left: var(--jp-code-cursor-width1) solid
      var(--jp-editor-cursor-color);
  }
}

/* When zoomed out less than 33% */
@media screen and (min-width: 4320px) {
  .jp-CodeMirrorEditor[data-type='inline'] .cm-cursor {
    border-left: var(--jp-code-cursor-width2) solid
      var(--jp-editor-cursor-color);
  }
}

.cm-editor.jp-mod-readOnly .cm-cursor {
  display: none;
}

.jp-CollaboratorCursor {
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-top: none;
  border-bottom: 3px solid;
  background-clip: content-box;
  margin-left: -5px;
  margin-right: -5px;
}

.cm-searching,
.cm-searching span {
  /* `.cm-searching span`: we need to override syntax highlighting */
  background-color: var(--jp-search-unselected-match-background-color);
  color: var(--jp-search-unselected-match-color);
}

.cm-searching::selection,
.cm-searching span::selection {
  background-color: var(--jp-search-unselected-match-background-color);
  color: var(--jp-search-unselected-match-color);
}

.jp-current-match > .cm-searching,
.jp-current-match > .cm-searching span,
.cm-searching > .jp-current-match,
.cm-searching > .jp-current-match span {
  background-color: var(--jp-search-selected-match-background-color);
  color: var(--jp-search-selected-match-color);
}

.jp-current-match > .cm-searching::selection,
.cm-searching > .jp-current-match::selection,
.jp-current-match > .cm-searching span::selection {
  background-color: var(--jp-search-selected-match-background-color);
  color: var(--jp-search-selected-match-color);
}

.cm-trailingspace {
  background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAgAAAAFCAYAAAB4ka1VAAAAsElEQVQIHQGlAFr/AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA7+r3zKmT0/+pk9P/7+r3zAAAAAAAAAAABAAAAAAAAAAA6OPzM+/q9wAAAAAA6OPzMwAAAAAAAAAAAgAAAAAAAAAAGR8NiRQaCgAZIA0AGR8NiQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQyoYJ/SY80UAAAAASUVORK5CYII=);
  background-position: center left;
  background-repeat: repeat-x;
}

.jp-CollaboratorCursor-hover {
  position: absolute;
  z-index: 1;
  transform: translateX(-50%);
  color: white;
  border-radius: 3px;
  padding-left: 4px;
  padding-right: 4px;
  padding-top: 1px;
  padding-bottom: 1px;
  text-align: center;
  font-size: var(--jp-ui-font-size1);
  white-space: nowrap;
}

.jp-CodeMirror-ruler {
  border-left: 1px dashed var(--jp-border-color2);
}

/* Styles for shared cursors (remote cursor locations and selected ranges) */
.jp-CodeMirrorEditor .cm-ySelectionCaret {
  position: relative;
  border-left: 1px solid black;
  margin-left: -1px;
  margin-right: -1px;
  box-sizing: border-box;
}

.jp-CodeMirrorEditor .cm-ySelectionCaret > .cm-ySelectionInfo {
  white-space: nowrap;
  position: absolute;
  top: -1.15em;
  padding-bottom: 0.05em;
  left: -1px;
  font-size: 0.95em;
  font-family: var(--jp-ui-font-family);
  font-weight: bold;
  line-height: normal;
  user-select: none;
  color: white;
  padding-left: 2px;
  padding-right: 2px;
  z-index: 101;
  transition: opacity 0.3s ease-in-out;
}

.jp-CodeMirrorEditor .cm-ySelectionInfo {
  transition-delay: 0.7s;
  opacity: 0;
}

.jp-CodeMirrorEditor .cm-ySelectionCaret:hover > .cm-ySelectionInfo {
  opacity: 1;
  transition-delay: 0s;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MimeDocument {
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-filebrowser-button-height: 28px;
  --jp-private-filebrowser-button-width: 48px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FileBrowser .jp-SidePanel-content {
  display: flex;
  flex-direction: column;
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  flex-wrap: wrap;
  row-gap: 12px;
  border-bottom: none;
  height: auto;
  margin: 8px 12px 0;
  box-shadow: none;
  padding: 0;
  justify-content: flex-start;
}

.jp-FileBrowser-Panel {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
}

.jp-BreadCrumbs {
  flex: 0 0 auto;
  margin: 8px 12px;
}

.jp-BreadCrumbs-item {
  margin: 0 2px;
  padding: 0 2px;
  border-radius: var(--jp-border-radius);
  cursor: pointer;
}

.jp-BreadCrumbs-item:hover {
  background-color: var(--jp-layout-color2);
}

.jp-BreadCrumbs-item:first-child {
  margin-left: 0;
}

.jp-BreadCrumbs-item.jp-mod-dropTarget {
  background-color: var(--jp-brand-color2);
  opacity: 0.7;
}

/*-----------------------------------------------------------------------------
| Buttons
|----------------------------------------------------------------------------*/

.jp-FileBrowser-toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  padding-left: 0;
  padding-right: 2px;
  align-items: center;
  height: unset;
}

.jp-FileBrowser-toolbar > .jp-Toolbar-item .jp-ToolbarButtonComponent {
  width: 40px;
}

/*-----------------------------------------------------------------------------
| Other styles
|----------------------------------------------------------------------------*/

.jp-FileDialog.jp-mod-conflict input {
  color: var(--jp-error-color1);
}

.jp-FileDialog .jp-new-name-title {
  margin-top: 12px;
}

.jp-LastModified-hidden {
  display: none;
}

.jp-FileSize-hidden {
  display: none;
}

.jp-FileBrowser .lm-AccordionPanel > h3:first-child {
  display: none;
}

/*-----------------------------------------------------------------------------
| DirListing
|----------------------------------------------------------------------------*/

.jp-DirListing {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
  outline: 0;
}

.jp-DirListing-header {
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  align-items: center;
  overflow: hidden;
  border-top: var(--jp-border-width) solid var(--jp-border-color2);
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
}

.jp-DirListing-headerItem {
  padding: 4px 12px 2px;
  font-weight: 500;
}

.jp-DirListing-headerItem:hover {
  background: var(--jp-layout-color2);
}

.jp-DirListing-headerItem.jp-id-name {
  flex: 1 0 84px;
}

.jp-DirListing-headerItem.jp-id-modified {
  flex: 0 0 112px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-DirListing-headerItem.jp-id-filesize {
  flex: 0 0 75px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-id-narrow {
  display: none;
  flex: 0 0 5px;
  padding: 4px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
  color: var(--jp-border-color2);
}

.jp-DirListing-narrow .jp-id-narrow {
  display: block;
}

.jp-DirListing-narrow .jp-id-modified,
.jp-DirListing-narrow .jp-DirListing-itemModified {
  display: none;
}

.jp-DirListing-headerItem.jp-mod-selected {
  font-weight: 600;
}

/* increase specificity to override bundled default */
.jp-DirListing-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-DirListing-content mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.jp-DirListing-content .jp-DirListing-item.jp-mod-selected mark {
  color: var(--jp-ui-inverse-font-color0);
}

/* Style the directory listing content when a user drops a file to upload */
.jp-DirListing.jp-mod-native-drop .jp-DirListing-content {
  outline: 5px dashed rgba(128, 128, 128, 0.5);
  outline-offset: -10px;
  cursor: copy;
}

.jp-DirListing-item {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 4px 12px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-DirListing-checkboxWrapper {
  /* Increases hit area of checkbox. */
  padding: 4px;
}

.jp-DirListing-header
  .jp-DirListing-checkboxWrapper
  + .jp-DirListing-headerItem {
  padding-left: 4px;
}

.jp-DirListing-content .jp-DirListing-checkboxWrapper {
  position: relative;
  left: -4px;
  margin: -4px 0 -4px -8px;
}

.jp-DirListing-checkboxWrapper.jp-mod-visible {
  visibility: visible;
}

/* For devices that support hovering, hide checkboxes until hovered, selected...
*/
@media (hover: hover) {
  .jp-DirListing-checkboxWrapper {
    visibility: hidden;
  }

  .jp-DirListing-item:hover .jp-DirListing-checkboxWrapper,
  .jp-DirListing-item.jp-mod-selected .jp-DirListing-checkboxWrapper {
    visibility: visible;
  }
}

.jp-DirListing-item[data-is-dot] {
  opacity: 75%;
}

.jp-DirListing-item.jp-mod-selected {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.jp-DirListing-item.jp-mod-dropTarget {
  background: var(--jp-brand-color3);
}

.jp-DirListing-item:hover:not(.jp-mod-selected) {
  background: var(--jp-layout-color2);
}

.jp-DirListing-itemIcon {
  flex: 0 0 20px;
  margin-right: 4px;
}

.jp-DirListing-itemText {
  flex: 1 0 64px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  user-select: none;
}

.jp-DirListing-itemText:focus {
  outline-width: 2px;
  outline-color: var(--jp-inverse-layout-color1);
  outline-style: solid;
  outline-offset: 1px;
}

.jp-DirListing-item.jp-mod-selected .jp-DirListing-itemText:focus {
  outline-color: var(--jp-layout-color1);
}

.jp-DirListing-itemModified {
  flex: 0 0 125px;
  text-align: right;
}

.jp-DirListing-itemFileSize {
  flex: 0 0 90px;
  text-align: right;
}

.jp-DirListing-editor {
  flex: 1 0 64px;
  outline: none;
  border: none;
  color: var(--jp-ui-font-color1);
  background-color: var(--jp-layout-color1);
}

.jp-DirListing-item.jp-mod-running .jp-DirListing-itemIcon::before {
  color: var(--jp-success-color1);
  content: '\25CF';
  font-size: 8px;
  position: absolute;
  left: -8px;
}

.jp-DirListing-item.jp-mod-running.jp-mod-selected
  .jp-DirListing-itemIcon::before {
  color: var(--jp-ui-inverse-font-color1);
}

.jp-DirListing-item.lm-mod-drag-image,
.jp-DirListing-item.jp-mod-selected.lm-mod-drag-image {
  font-size: var(--jp-ui-font-size1);
  padding-left: 4px;
  margin-left: 4px;
  width: 160px;
  background-color: var(--jp-ui-inverse-font-color2);
  box-shadow: var(--jp-elevation-z2);
  border-radius: 0;
  color: var(--jp-ui-font-color1);
  transform: translateX(-40%) translateY(-58%);
}

.jp-Document {
  min-width: 120px;
  min-height: 120px;
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Main OutputArea
| OutputArea has a list of Outputs
|----------------------------------------------------------------------------*/

.jp-OutputArea {
  overflow-y: auto;
}

.jp-OutputArea-child {
  display: table;
  table-layout: fixed;
  width: 100%;
  overflow: hidden;
}

.jp-OutputPrompt {
  width: var(--jp-cell-prompt-width);
  color: var(--jp-cell-outprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);

  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-OutputArea-prompt {
  display: table-cell;
  vertical-align: top;
}

.jp-OutputArea-output {
  display: table-cell;
  width: 100%;
  height: auto;
  overflow: auto;
  user-select: text;
  -moz-user-select: text;
  -webkit-user-select: text;
  -ms-user-select: text;
}

.jp-OutputArea .jp-RenderedText {
  padding-left: 1ch;
}

/**
 * Prompt overlay.
 */

.jp-OutputArea-promptOverlay {
  position: absolute;
  top: 0;
  width: var(--jp-cell-prompt-width);
  height: 100%;
  opacity: 0.5;
}

.jp-OutputArea-promptOverlay:hover {
  background: var(--jp-layout-color2);
  box-shadow: inset 0 0 1px var(--jp-inverse-layout-color0);
  cursor: zoom-out;
}

.jp-mod-outputsScrolled .jp-OutputArea-promptOverlay:hover {
  cursor: zoom-in;
}

/**
 * Isolated output.
 */
.jp-OutputArea-output.jp-mod-isolated {
  width: 100%;
  display: block;
}

/*
When drag events occur, `lm-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated {
  position: relative;
}

body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/* pre */

.jp-OutputArea-output pre {
  border: none;
  margin: 0;
  padding: 0;
  overflow-x: auto;
  overflow-y: auto;
  word-break: break-all;
  word-wrap: break-word;
  white-space: pre-wrap;
}

/* tables */

.jp-OutputArea-output.jp-RenderedHTMLCommon table {
  margin-left: 0;
  margin-right: 0;
}

/* description lists */

.jp-OutputArea-output dl,
.jp-OutputArea-output dt,
.jp-OutputArea-output dd {
  display: block;
}

.jp-OutputArea-output dl {
  width: 100%;
  overflow: hidden;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dt {
  font-weight: bold;
  float: left;
  width: 20%;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dd {
  float: left;
  width: 80%;
  padding: 0;
  margin: 0;
}

.jp-TrimmedOutputs pre {
  background: var(--jp-layout-color3);
  font-size: calc(var(--jp-code-font-size) * 1.4);
  text-align: center;
  text-transform: uppercase;
}

/* Hide the gutter in case of
 *  - nested output areas (e.g. in the case of output widgets)
 *  - mirrored output areas
 */
.jp-OutputArea .jp-OutputArea .jp-OutputArea-prompt {
  display: none;
}

/* Hide empty lines in the output area, for instance due to cleared widgets */
.jp-OutputArea-prompt:empty {
  padding: 0;
  border: 0;
}

/*-----------------------------------------------------------------------------
| executeResult is added to any Output-result for the display of the object
| returned by a cell
|----------------------------------------------------------------------------*/

.jp-OutputArea-output.jp-OutputArea-executeResult {
  margin-left: 0;
  width: 100%;
}

/* Text output with the Out[] prompt needs a top padding to match the
 * alignment of the Out[] prompt itself.
 */
.jp-OutputArea-executeResult .jp-RenderedText.jp-OutputArea-output {
  padding-top: var(--jp-code-padding);
  border-top: var(--jp-border-width) solid transparent;
}

/*-----------------------------------------------------------------------------
| The Stdin output
|----------------------------------------------------------------------------*/

.jp-Stdin-prompt {
  color: var(--jp-content-font-color0);
  padding-right: var(--jp-code-padding);
  vertical-align: baseline;
  flex: 0 0 auto;
}

.jp-Stdin-input {
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  color: inherit;
  background-color: inherit;
  width: 42%;
  min-width: 200px;

  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;

  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0 0.25em;
  margin: 0 0.25em;
  flex: 0 0 70%;
}

.jp-Stdin-input::placeholder {
  opacity: 0;
}

.jp-Stdin-input:focus {
  box-shadow: none;
}

.jp-Stdin-input:focus::placeholder {
  opacity: 1;
}

/*-----------------------------------------------------------------------------
| Output Area View
|----------------------------------------------------------------------------*/

.jp-LinkedOutputView .jp-OutputArea {
  height: 100%;
  display: block;
}

.jp-LinkedOutputView .jp-OutputArea-output:only-child {
  height: 100%;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

@media print {
  .jp-OutputArea-child {
    break-inside: avoid-page;
  }
}

/*-----------------------------------------------------------------------------
| Mobile
|----------------------------------------------------------------------------*/
@media only screen and (max-width: 760px) {
  .jp-OutputPrompt {
    display: table-row;
    text-align: left;
  }

  .jp-OutputArea-child .jp-OutputArea-output {
    display: table-row;
    margin-left: var(--jp-notebook-padding);
  }
}

/* Trimmed outputs warning */
.jp-TrimmedOutputs > a {
  margin: 10px;
  text-decoration: none;
  cursor: pointer;
}

.jp-TrimmedOutputs > a:hover {
  text-decoration: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Table of Contents
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toc-active-width: 4px;
}

.jp-TableOfContents {
  display: flex;
  flex-direction: column;
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  height: 100%;
}

.jp-TableOfContents-placeholder {
  text-align: center;
}

.jp-TableOfContents-placeholderContent {
  color: var(--jp-content-font-color2);
  padding: 8px;
}

.jp-TableOfContents-placeholderContent > h3 {
  margin-bottom: var(--jp-content-heading-margin-bottom);
}

.jp-TableOfContents .jp-SidePanel-content {
  overflow-y: auto;
}

.jp-TableOfContents-tree {
  margin: 4px;
}

.jp-TableOfContents ol {
  list-style-type: none;
}

/* stylelint-disable-next-line selector-max-type */
.jp-TableOfContents li > ol {
  /* Align left border with triangle icon center */
  padding-left: 11px;
}

.jp-TableOfContents-content {
  /* left margin for the active heading indicator */
  margin: 0 0 0 var(--jp-private-toc-active-width);
  padding: 0;
  background-color: var(--jp-layout-color1);
}

.jp-tocItem {
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-tocItem-heading {
  display: flex;
  cursor: pointer;
}

.jp-tocItem-heading:hover {
  background-color: var(--jp-layout-color2);
}

.jp-tocItem-content {
  display: block;
  padding: 4px 0;
  white-space: nowrap;
  text-overflow: ellipsis;
  overflow-x: hidden;
}

.jp-tocItem-collapser {
  height: 20px;
  margin: 2px 2px 0;
  padding: 0;
  background: none;
  border: none;
  cursor: pointer;
}

.jp-tocItem-collapser:hover {
  background-color: var(--jp-layout-color3);
}

/* Active heading indicator */

.jp-tocItem-heading::before {
  content: ' ';
  background: transparent;
  width: var(--jp-private-toc-active-width);
  height: 24px;
  position: absolute;
  left: 0;
  border-radius: var(--jp-border-radius);
}

.jp-tocItem-heading.jp-tocItem-active::before {
  background-color: var(--jp-brand-color1);
}

.jp-tocItem-heading:hover.jp-tocItem-active::before {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapser {
  flex: 0 0 var(--jp-cell-collapser-width);
  padding: 0;
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
  border-radius: var(--jp-border-radius);
  opacity: 1;
}

.jp-Collapser-child {
  display: block;
  width: 100%;
  box-sizing: border-box;

  /* height: 100% doesn't work because the height of its parent is computed from content */
  position: absolute;
  top: 0;
  bottom: 0;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

/*
Hiding collapsers in print mode.

Note: input and output wrappers have "display: block" propery in print mode.
*/

@media print {
  .jp-Collapser {
    display: none;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Header/Footer
|----------------------------------------------------------------------------*/

/* Hidden by zero height by default */
.jp-CellHeader,
.jp-CellFooter {
  height: 0;
  width: 100%;
  padding: 0;
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Input
|----------------------------------------------------------------------------*/

/* All input areas */
.jp-InputArea {
  display: table;
  table-layout: fixed;
  width: 100%;
  overflow: hidden;
}

.jp-InputArea-editor {
  display: table-cell;
  overflow: hidden;
  vertical-align: top;

  /* This is the non-active, default styling */
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0;
  background: var(--jp-cell-editor-background);
}

.jp-InputPrompt {
  display: table-cell;
  vertical-align: top;
  width: var(--jp-cell-prompt-width);
  color: var(--jp-cell-inprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  opacity: var(--jp-cell-prompt-opacity);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;

  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

/*-----------------------------------------------------------------------------
| Mobile
|----------------------------------------------------------------------------*/
@media only screen and (max-width: 760px) {
  .jp-InputArea-editor {
    display: table-row;
    margin-left: var(--jp-notebook-padding);
  }

  .jp-InputPrompt {
    display: table-row;
    text-align: left;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Placeholder {
  display: table;
  table-layout: fixed;
  width: 100%;
}

.jp-Placeholder-prompt {
  display: table-cell;
  box-sizing: border-box;
}

.jp-Placeholder-content {
  display: table-cell;
  padding: 4px 6px;
  border: 1px solid transparent;
  border-radius: 0;
  background: none;
  box-sizing: border-box;
  cursor: pointer;
}

.jp-Placeholder-contentContainer {
  display: flex;
}

.jp-Placeholder-content:hover,
.jp-InputPlaceholder > .jp-Placeholder-content:hover {
  border-color: var(--jp-layout-color3);
}

.jp-Placeholder-content .jp-MoreHorizIcon {
  width: 32px;
  height: 16px;
  border: 1px solid transparent;
  border-radius: var(--jp-border-radius);
}

.jp-Placeholder-content .jp-MoreHorizIcon:hover {
  border: 1px solid var(--jp-border-color1);
  box-shadow: 0 0 2px 0 rgba(0, 0, 0, 0.25);
  background-color: var(--jp-layout-color0);
}

.jp-PlaceholderText {
  white-space: nowrap;
  overflow-x: hidden;
  color: var(--jp-inverse-layout-color3);
  font-family: var(--jp-code-font-family);
}

.jp-InputPlaceholder > .jp-Placeholder-content {
  border-color: var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-cell-scrolling-output-offset: 5px;
}

/*-----------------------------------------------------------------------------
| Cell
|----------------------------------------------------------------------------*/

.jp-Cell {
  padding: var(--jp-cell-padding);
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Common input/output
|----------------------------------------------------------------------------*/

.jp-Cell-inputWrapper,
.jp-Cell-outputWrapper {
  display: flex;
  flex-direction: row;
  padding: 0;
  margin: 0;

  /* Added to reveal the box-shadow on the input and output collapsers. */
  overflow: visible;
}

/* Only input/output areas inside cells */
.jp-Cell-inputArea,
.jp-Cell-outputArea {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Collapser
|----------------------------------------------------------------------------*/

/* Make the output collapser disappear when there is not output, but do so
 * in a manner that leaves it in the layout and preserves its width.
 */
.jp-Cell.jp-mod-noOutputs .jp-Cell-outputCollapser {
  border: none !important;
  background: transparent !important;
}

.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputCollapser {
  min-height: var(--jp-cell-collapser-min-height);
}

/*-----------------------------------------------------------------------------
| Output
|----------------------------------------------------------------------------*/

/* Put a space between input and output when there IS output */
.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputWrapper {
  margin-top: 5px;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea {
  overflow-y: auto;
  max-height: 24em;
  margin-left: var(--jp-private-cell-scrolling-output-offset);
  resize: vertical;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea[style*='height'] {
  max-height: unset;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea::after {
  content: ' ';
  box-shadow: inset 0 0 6px 2px rgb(0 0 0 / 30%);
  width: 100%;
  height: 100%;
  position: sticky;
  bottom: 0;
  top: 0;
  margin-top: -50%;
  float: left;
  display: block;
  pointer-events: none;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-child {
  padding-top: 6px;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  width: calc(
    var(--jp-cell-prompt-width) - var(--jp-private-cell-scrolling-output-offset)
  );
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-promptOverlay {
  left: calc(-1 * var(--jp-private-cell-scrolling-output-offset));
}

/*-----------------------------------------------------------------------------
| CodeCell
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| MarkdownCell
|----------------------------------------------------------------------------*/

.jp-MarkdownOutput {
  display: table-cell;
  width: 100%;
  margin-top: 0;
  margin-bottom: 0;
  padding-left: var(--jp-code-padding);
}

.jp-MarkdownOutput.jp-RenderedHTMLCommon {
  overflow: auto;
}

/* collapseHeadingButton (show always if hiddenCellsButton is _not_ shown) */
.jp-collapseHeadingButton {
  display: flex;
  min-height: var(--jp-cell-collapser-min-height);
  font-size: var(--jp-code-font-size);
  position: absolute;
  background-color: transparent;
  background-size: 25px;
  background-repeat: no-repeat;
  background-position-x: center;
  background-position-y: top;
  background-image: var(--jp-icon-caret-down);
  right: 0;
  top: 0;
  bottom: 0;
}

.jp-collapseHeadingButton.jp-mod-collapsed {
  background-image: var(--jp-icon-caret-right);
}

/*
 set the container font size to match that of content
 so that the nested collapse buttons have the right size
*/
.jp-MarkdownCell .jp-InputPrompt {
  font-size: var(--jp-content-font-size1);
}

/*
  Align collapseHeadingButton with cell top header
  The font sizes are identical to the ones in packages/rendermime/style/base.css
*/
.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='1'] {
  font-size: var(--jp-content-font-size5);
  background-position-y: calc(0.3 * var(--jp-content-font-size5));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='2'] {
  font-size: var(--jp-content-font-size4);
  background-position-y: calc(0.3 * var(--jp-content-font-size4));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='3'] {
  font-size: var(--jp-content-font-size3);
  background-position-y: calc(0.3 * var(--jp-content-font-size3));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='4'] {
  font-size: var(--jp-content-font-size2);
  background-position-y: calc(0.3 * var(--jp-content-font-size2));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='5'] {
  font-size: var(--jp-content-font-size1);
  background-position-y: top;
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='6'] {
  font-size: var(--jp-content-font-size0);
  background-position-y: top;
}

/* collapseHeadingButton (show only on (hover,active) if hiddenCellsButton is shown) */
.jp-Notebook.jp-mod-showHiddenCellsButton .jp-collapseHeadingButton {
  display: none;
}

.jp-Notebook.jp-mod-showHiddenCellsButton
  :is(.jp-MarkdownCell:hover, .jp-mod-active)
  .jp-collapseHeadingButton {
  display: flex;
}

/* showHiddenCellsButton (only show if jp-mod-showHiddenCellsButton is set, which
is a consequence of the showHiddenCellsButton option in Notebook Settings)*/
.jp-Notebook.jp-mod-showHiddenCellsButton .jp-showHiddenCellsButton {
  margin-left: calc(var(--jp-cell-prompt-width) + 2 * var(--jp-code-padding));
  margin-top: var(--jp-code-padding);
  border: 1px solid var(--jp-border-color2);
  background-color: var(--jp-border-color3) !important;
  color: var(--jp-content-font-color0) !important;
  display: flex;
}

.jp-Notebook.jp-mod-showHiddenCellsButton .jp-showHiddenCellsButton:hover {
  background-color: var(--jp-border-color2) !important;
}

.jp-showHiddenCellsButton {
  display: none;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

/*
Using block instead of flex to allow the use of the break-inside CSS property for
cell outputs.
*/

@media print {
  .jp-Cell-inputWrapper,
  .jp-Cell-outputWrapper {
    display: block;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-notebook-toolbar-padding: 2px 5px 2px 2px;
}

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-NotebookPanel-toolbar {
  padding: var(--jp-notebook-toolbar-padding);

  /* disable paint containment from lumino 2.0 default strict CSS containment */
  contain: style size !important;
}

.jp-Toolbar-item.jp-Notebook-toolbarCellType .jp-select-wrapper.jp-mod-focused {
  border: none;
  box-shadow: none;
}

.jp-Notebook-toolbarCellTypeDropdown select {
  height: 24px;
  font-size: var(--jp-ui-font-size1);
  line-height: 14px;
  border-radius: 0;
  display: block;
}

.jp-Notebook-toolbarCellTypeDropdown span {
  top: 5px !important;
}

.jp-Toolbar-responsive-popup {
  position: absolute;
  height: fit-content;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: flex-end;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: var(--jp-notebook-toolbar-padding);
  z-index: 1;
  right: 0;
  top: 0;
}

.jp-Toolbar > .jp-Toolbar-responsive-opener {
  margin-left: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-Notebook-ExecutionIndicator {
  position: relative;
  display: inline-block;
  height: 100%;
  z-index: 9997;
}

.jp-Notebook-ExecutionIndicator-tooltip {
  visibility: hidden;
  height: auto;
  width: max-content;
  width: -moz-max-content;
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color1);
  text-align: justify;
  border-radius: 6px;
  padding: 0 5px;
  position: fixed;
  display: table;
}

.jp-Notebook-ExecutionIndicator-tooltip.up {
  transform: translateX(-50%) translateY(-100%) translateY(-32px);
}

.jp-Notebook-ExecutionIndicator-tooltip.down {
  transform: translateX(calc(-100% + 16px)) translateY(5px);
}

.jp-Notebook-ExecutionIndicator-tooltip.hidden {
  display: none;
}

.jp-Notebook-ExecutionIndicator:hover .jp-Notebook-ExecutionIndicator-tooltip {
  visibility: visible;
}

.jp-Notebook-ExecutionIndicator span {
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  color: var(--jp-ui-font-color1);
  line-height: 24px;
  display: block;
}

.jp-Notebook-ExecutionIndicator-progress-bar {
  display: flex;
  justify-content: center;
  height: 100%;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*
 * Execution indicator
 */
.jp-tocItem-content::after {
  content: '';

  /* Must be identical to form a circle */
  width: 12px;
  height: 12px;
  background: none;
  border: none;
  position: absolute;
  right: 0;
}

.jp-tocItem-content[data-running='0']::after {
  border-radius: 50%;
  border: var(--jp-border-width) solid var(--jp-inverse-layout-color3);
  background: none;
}

.jp-tocItem-content[data-running='1']::after {
  border-radius: 50%;
  border: var(--jp-border-width) solid var(--jp-inverse-layout-color3);
  background-color: var(--jp-inverse-layout-color3);
}

.jp-tocItem-content[data-running='0'],
.jp-tocItem-content[data-running='1'] {
  margin-right: 12px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-Notebook-footer {
  height: 27px;
  margin-left: calc(
    var(--jp-cell-prompt-width) + var(--jp-cell-collapser-width) +
      var(--jp-cell-padding)
  );
  width: calc(
    100% -
      (
        var(--jp-cell-prompt-width) + var(--jp-cell-collapser-width) +
          var(--jp-cell-padding) + var(--jp-cell-padding)
      )
  );
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  color: var(--jp-ui-font-color3);
  margin-top: 6px;
  background: none;
  cursor: pointer;
}

.jp-Notebook-footer:focus {
  border-color: var(--jp-cell-editor-active-border-color);
}

/* For devices that support hovering, hide footer until hover */
@media (hover: hover) {
  .jp-Notebook-footer {
    opacity: 0;
  }

  .jp-Notebook-footer:focus,
  .jp-Notebook-footer:hover {
    opacity: 1;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Imports
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-side-by-side-output-size: 1fr;
  --jp-side-by-side-resized-cell: var(--jp-side-by-side-output-size);
  --jp-private-notebook-dragImage-width: 304px;
  --jp-private-notebook-dragImage-height: 36px;
  --jp-private-notebook-selected-color: var(--md-blue-400);
  --jp-private-notebook-active-color: var(--md-green-400);
}

/*-----------------------------------------------------------------------------
| Notebook
|----------------------------------------------------------------------------*/

/* stylelint-disable selector-max-class */

.jp-NotebookPanel {
  display: block;
  height: 100%;
}

.jp-NotebookPanel.jp-Document {
  min-width: 240px;
  min-height: 120px;
}

.jp-Notebook {
  padding: var(--jp-notebook-padding);
  outline: none;
  overflow: auto;
  background: var(--jp-layout-color0);
}

.jp-Notebook.jp-mod-scrollPastEnd::after {
  display: block;
  content: '';
  min-height: var(--jp-notebook-scroll-padding);
}

.jp-MainAreaWidget-ContainStrict .jp-Notebook * {
  contain: strict;
}

.jp-Notebook .jp-Cell {
  overflow: visible;
}

.jp-Notebook .jp-Cell .jp-InputPrompt {
  cursor: move;
}

/*-----------------------------------------------------------------------------
| Notebook state related styling
|
| The notebook and cells each have states, here are the possibilities:
|
| - Notebook
|   - Command
|   - Edit
| - Cell
|   - None
|   - Active (only one can be active)
|   - Selected (the cells actions are applied to)
|   - Multiselected (when multiple selected, the cursor)
|   - No outputs
|----------------------------------------------------------------------------*/

/* Command or edit modes */

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-InputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-OutputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

/* cell is active */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser {
  background: var(--jp-brand-color1);
}

/* cell is dirty */
.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt {
  color: var(--jp-warn-color1);
}

.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt::before {
  color: var(--jp-warn-color1);
  content: '•';
}

.jp-Notebook .jp-Cell.jp-mod-active.jp-mod-dirty .jp-Collapser {
  background: var(--jp-warn-color1);
}

/* collapser is hovered */
.jp-Notebook .jp-Cell .jp-Collapser:hover {
  box-shadow: var(--jp-elevation-z2);
  background: var(--jp-brand-color1);
  opacity: var(--jp-cell-collapser-not-active-hover-opacity);
}

/* cell is active and collapser is hovered */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser:hover {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/* Command mode */

.jp-Notebook.jp-mod-commandMode .jp-Cell.jp-mod-selected {
  background: var(--jp-notebook-multiselected-color);
}

.jp-Notebook.jp-mod-commandMode
  .jp-Cell.jp-mod-active.jp-mod-selected:not(.jp-mod-multiSelected) {
  background: transparent;
}

/* Edit mode */

.jp-Notebook.jp-mod-editMode .jp-Cell.jp-mod-active .jp-InputArea-editor {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-cell-editor-active-background);
}

/*-----------------------------------------------------------------------------
| Notebook drag and drop
|----------------------------------------------------------------------------*/

.jp-Notebook-cell.jp-mod-dropSource {
  opacity: 0.5;
}

.jp-Notebook-cell.jp-mod-dropTarget,
.jp-Notebook.jp-mod-commandMode
  .jp-Notebook-cell.jp-mod-active.jp-mod-selected.jp-mod-dropTarget {
  border-top-color: var(--jp-private-notebook-selected-color);
  border-top-style: solid;
  border-top-width: 2px;
}

.jp-dragImage {
  display: block;
  flex-direction: row;
  width: var(--jp-private-notebook-dragImage-width);
  height: var(--jp-private-notebook-dragImage-height);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
  overflow: visible;
}

.jp-dragImage-singlePrompt {
  box-shadow: 2px 2px 4px 0 rgba(0, 0, 0, 0.12);
}

.jp-dragImage .jp-dragImage-content {
  flex: 1 1 auto;
  z-index: 2;
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  line-height: var(--jp-code-line-height);
  padding: var(--jp-code-padding);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background-color);
  color: var(--jp-content-font-color3);
  text-align: left;
  margin: 4px 4px 4px 0;
}

.jp-dragImage .jp-dragImage-prompt {
  flex: 0 0 auto;
  min-width: 36px;
  color: var(--jp-cell-inprompt-font-color);
  padding: var(--jp-code-padding);
  padding-left: 12px;
  font-family: var(--jp-cell-prompt-font-family);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: 1.9;
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
}

.jp-dragImage-multipleBack {
  z-index: -1;
  position: absolute;
  height: 32px;
  width: 300px;
  top: 8px;
  left: 8px;
  background: var(--jp-layout-color2);
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  box-shadow: 2px 2px 4px 0 rgba(0, 0, 0, 0.12);
}

/*-----------------------------------------------------------------------------
| Cell toolbar
|----------------------------------------------------------------------------*/

.jp-NotebookTools {
  display: block;
  min-width: var(--jp-sidebar-min-width);
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);

  /* This is needed so that all font sizing of children done in ems is
    * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  overflow: auto;
}

.jp-ActiveCellTool {
  padding: 12px 0;
  display: flex;
}

.jp-ActiveCellTool-Content {
  flex: 1 1 auto;
}

.jp-ActiveCellTool .jp-ActiveCellTool-CellContent {
  background: var(--jp-cell-editor-background);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0;
  min-height: 29px;
}

.jp-ActiveCellTool .jp-InputPrompt {
  min-width: calc(var(--jp-cell-prompt-width) * 0.75);
}

.jp-ActiveCellTool-CellContent > pre {
  padding: 5px 4px;
  margin: 0;
  white-space: normal;
}

.jp-MetadataEditorTool {
  flex-direction: column;
  padding: 12px 0;
}

.jp-RankedPanel > :not(:first-child) {
  margin-top: 12px;
}

.jp-KeySelector select.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: var(--jp-border-width) solid var(--jp-border-color1);
}

.jp-KeySelector label,
.jp-MetadataEditorTool label,
.jp-NumberSetter label {
  line-height: 1.4;
}

.jp-NotebookTools .jp-select-wrapper {
  margin-top: 4px;
  margin-bottom: 0;
}

.jp-NumberSetter input {
  width: 100%;
  margin-top: 4px;
}

.jp-NotebookTools .jp-Collapse {
  margin-top: 16px;
}

/*-----------------------------------------------------------------------------
| Presentation Mode (.jp-mod-presentationMode)
|----------------------------------------------------------------------------*/

.jp-mod-presentationMode .jp-Notebook {
  --jp-content-font-size1: var(--jp-content-presentation-font-size1);
  --jp-code-font-size: var(--jp-code-presentation-font-size);
}

.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-InputPrompt,
.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-OutputPrompt {
  flex: 0 0 110px;
}

/*-----------------------------------------------------------------------------
| Side-by-side Mode (.jp-mod-sideBySide)
|----------------------------------------------------------------------------*/
.jp-mod-sideBySide.jp-Notebook .jp-Notebook-cell {
  margin-top: 3em;
  margin-bottom: 3em;
  margin-left: 5%;
  margin-right: 5%;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell {
  display: grid;
  grid-template-columns: minmax(0, 1fr) min-content minmax(
      0,
      var(--jp-side-by-side-output-size)
    );
  grid-template-rows: auto minmax(0, 1fr) auto;
  grid-template-areas:
    'header header header'
    'input handle output'
    'footer footer footer';
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell.jp-mod-resizedCell {
  grid-template-columns: minmax(0, 1fr) min-content minmax(
      0,
      var(--jp-side-by-side-resized-cell)
    );
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellHeader {
  grid-area: header;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-Cell-inputWrapper {
  grid-area: input;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-Cell-outputWrapper {
  /* overwrite the default margin (no vertical separation needed in side by side move */
  margin-top: 0;
  grid-area: output;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellFooter {
  grid-area: footer;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellResizeHandle {
  grid-area: handle;
  user-select: none;
  display: block;
  height: 100%;
  cursor: ew-resize;
  padding: 0 var(--jp-cell-padding);
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellResizeHandle::after {
  content: '';
  display: block;
  background: var(--jp-border-color2);
  height: 100%;
  width: 5px;
}

.jp-mod-sideBySide.jp-Notebook
  .jp-CodeCell.jp-mod-resizedCell
  .jp-CellResizeHandle::after {
  background: var(--jp-border-color0);
}

.jp-CellResizeHandle {
  display: none;
}

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Cell-Placeholder {
  padding-left: 55px;
}

.jp-Cell-Placeholder-wrapper {
  background: #fff;
  border: 1px solid;
  border-color: #e5e6e9 #dfe0e4 #d0d1d5;
  border-radius: 4px;
  -webkit-border-radius: 4px;
  margin: 10px 15px;
}

.jp-Cell-Placeholder-wrapper-inner {
  padding: 15px;
  position: relative;
}

.jp-Cell-Placeholder-wrapper-body {
  background-repeat: repeat;
  background-size: 50% auto;
}

.jp-Cell-Placeholder-wrapper-body div {
  background: #f6f7f8;
  background-image: -webkit-linear-gradient(
    left,
    #f6f7f8 0%,
    #edeef1 20%,
    #f6f7f8 40%,
    #f6f7f8 100%
  );
  background-repeat: no-repeat;
  background-size: 800px 104px;
  height: 104px;
  position: absolute;
  right: 15px;
  left: 15px;
  top: 15px;
}

div.jp-Cell-Placeholder-h1 {
  top: 20px;
  height: 20px;
  left: 15px;
  width: 150px;
}

div.jp-Cell-Placeholder-h2 {
  left: 15px;
  top: 50px;
  height: 10px;
  width: 100px;
}

div.jp-Cell-Placeholder-content-1,
div.jp-Cell-Placeholder-content-2,
div.jp-Cell-Placeholder-content-3 {
  left: 15px;
  right: 15px;
  height: 10px;
}

div.jp-Cell-Placeholder-content-1 {
  top: 100px;
}

div.jp-Cell-Placeholder-content-2 {
  top: 120px;
}

div.jp-Cell-Placeholder-content-3 {
  top: 140px;
}

</style>
<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
The following CSS variables define the main, public API for styling JupyterLab.
These variables should be used by all plugins wherever possible. In other
words, plugins should not define custom colors, sizes, etc unless absolutely
necessary. This enables users to change the visual theme of JupyterLab
by changing these variables.

Many variables appear in an ordered sequence (0,1,2,3). These sequences
are designed to work well together, so for example, `--jp-border-color1` should
be used with `--jp-layout-color1`. The numbers have the following meanings:

* 0: super-primary, reserved for special emphasis
* 1: primary, most important under normal situations
* 2: secondary, next most important under normal situations
* 3: tertiary, next most important under normal situations

Throughout JupyterLab, we are mostly following principles from Google's
Material Design when selecting colors. We are not, however, following
all of MD as it is not optimized for dense, information rich UIs.
*/

:root {
  /* Elevation
   *
   * We style box-shadows using Material Design's idea of elevation. These particular numbers are taken from here:
   *
   * https://github.com/material-components/material-components-web
   * https://material-components-web.appspot.com/elevation.html
   */

  --jp-shadow-base-lightness: 0;
  --jp-shadow-umbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.2
  );
  --jp-shadow-penumbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.14
  );
  --jp-shadow-ambient-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.12
  );
  --jp-elevation-z0: none;
  --jp-elevation-z1: 0 2px 1px -1px var(--jp-shadow-umbra-color),
    0 1px 1px 0 var(--jp-shadow-penumbra-color),
    0 1px 3px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z2: 0 3px 1px -2px var(--jp-shadow-umbra-color),
    0 2px 2px 0 var(--jp-shadow-penumbra-color),
    0 1px 5px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z4: 0 2px 4px -1px var(--jp-shadow-umbra-color),
    0 4px 5px 0 var(--jp-shadow-penumbra-color),
    0 1px 10px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z6: 0 3px 5px -1px var(--jp-shadow-umbra-color),
    0 6px 10px 0 var(--jp-shadow-penumbra-color),
    0 1px 18px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z8: 0 5px 5px -3px var(--jp-shadow-umbra-color),
    0 8px 10px 1px var(--jp-shadow-penumbra-color),
    0 3px 14px 2px var(--jp-shadow-ambient-color);
  --jp-elevation-z12: 0 7px 8px -4px var(--jp-shadow-umbra-color),
    0 12px 17px 2px var(--jp-shadow-penumbra-color),
    0 5px 22px 4px var(--jp-shadow-ambient-color);
  --jp-elevation-z16: 0 8px 10px -5px var(--jp-shadow-umbra-color),
    0 16px 24px 2px var(--jp-shadow-penumbra-color),
    0 6px 30px 5px var(--jp-shadow-ambient-color);
  --jp-elevation-z20: 0 10px 13px -6px var(--jp-shadow-umbra-color),
    0 20px 31px 3px var(--jp-shadow-penumbra-color),
    0 8px 38px 7px var(--jp-shadow-ambient-color);
  --jp-elevation-z24: 0 11px 15px -7px var(--jp-shadow-umbra-color),
    0 24px 38px 3px var(--jp-shadow-penumbra-color),
    0 9px 46px 8px var(--jp-shadow-ambient-color);

  /* Borders
   *
   * The following variables, specify the visual styling of borders in JupyterLab.
   */

  --jp-border-width: 1px;
  --jp-border-color0: var(--md-grey-400);
  --jp-border-color1: var(--md-grey-400);
  --jp-border-color2: var(--md-grey-300);
  --jp-border-color3: var(--md-grey-200);
  --jp-inverse-border-color: var(--md-grey-600);
  --jp-border-radius: 2px;

  /* UI Fonts
   *
   * The UI font CSS variables are used for the typography all of the JupyterLab
   * user interface elements that are not directly user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-ui-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-ui-font-scale-factor: 1.2;
  --jp-ui-font-size0: 0.83333em;
  --jp-ui-font-size1: 13px; /* Base font size */
  --jp-ui-font-size2: 1.2em;
  --jp-ui-font-size3: 1.44em;
  --jp-ui-font-family: system-ui, -apple-system, blinkmacsystemfont, 'Segoe UI',
    helvetica, arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji',
    'Segoe UI Symbol';

  /*
   * Use these font colors against the corresponding main layout colors.
   * In a light theme, these go from dark to light.
   */

  /* Defaults use Material Design specification */
  --jp-ui-font-color0: rgba(0, 0, 0, 1);
  --jp-ui-font-color1: rgba(0, 0, 0, 0.87);
  --jp-ui-font-color2: rgba(0, 0, 0, 0.54);
  --jp-ui-font-color3: rgba(0, 0, 0, 0.38);

  /*
   * Use these against the brand/accent/warn/error colors.
   * These will typically go from light to darker, in both a dark and light theme.
   */

  --jp-ui-inverse-font-color0: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color1: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color2: rgba(255, 255, 255, 0.7);
  --jp-ui-inverse-font-color3: rgba(255, 255, 255, 0.5);

  /* Content Fonts
   *
   * Content font variables are used for typography of user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-content-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-content-line-height: 1.6;
  --jp-content-font-scale-factor: 1.2;
  --jp-content-font-size0: 0.83333em;
  --jp-content-font-size1: 14px; /* Base font size */
  --jp-content-font-size2: 1.2em;
  --jp-content-font-size3: 1.44em;
  --jp-content-font-size4: 1.728em;
  --jp-content-font-size5: 2.0736em;

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-content-presentation-font-size1: 17px;
  --jp-content-heading-line-height: 1;
  --jp-content-heading-margin-top: 1.2em;
  --jp-content-heading-margin-bottom: 0.8em;
  --jp-content-heading-font-weight: 500;

  /* Defaults use Material Design specification */
  --jp-content-font-color0: rgba(0, 0, 0, 1);
  --jp-content-font-color1: rgba(0, 0, 0, 0.87);
  --jp-content-font-color2: rgba(0, 0, 0, 0.54);
  --jp-content-font-color3: rgba(0, 0, 0, 0.38);
  --jp-content-link-color: var(--md-blue-900);
  --jp-content-font-family: system-ui, -apple-system, blinkmacsystemfont,
    'Segoe UI', helvetica, arial, sans-serif, 'Apple Color Emoji',
    'Segoe UI Emoji', 'Segoe UI Symbol';

  /*
   * Code Fonts
   *
   * Code font variables are used for typography of code and other monospaces content.
   */

  --jp-code-font-size: 13px;
  --jp-code-line-height: 1.3077; /* 17px for 13px base */
  --jp-code-padding: 5px; /* 5px for 13px base, codemirror highlighting needs integer px value */
  --jp-code-font-family-default: menlo, consolas, 'DejaVu Sans Mono', monospace;
  --jp-code-font-family: var(--jp-code-font-family-default);

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-code-presentation-font-size: 16px;

  /* may need to tweak cursor width if you change font size */
  --jp-code-cursor-width0: 1.4px;
  --jp-code-cursor-width1: 2px;
  --jp-code-cursor-width2: 4px;

  /* Layout
   *
   * The following are the main layout colors use in JupyterLab. In a light
   * theme these would go from light to dark.
   */

  --jp-layout-color0: white;
  --jp-layout-color1: white;
  --jp-layout-color2: var(--md-grey-200);
  --jp-layout-color3: var(--md-grey-400);
  --jp-layout-color4: var(--md-grey-600);

  /* Inverse Layout
   *
   * The following are the inverse layout colors use in JupyterLab. In a light
   * theme these would go from dark to light.
   */

  --jp-inverse-layout-color0: #111;
  --jp-inverse-layout-color1: var(--md-grey-900);
  --jp-inverse-layout-color2: var(--md-grey-800);
  --jp-inverse-layout-color3: var(--md-grey-700);
  --jp-inverse-layout-color4: var(--md-grey-600);

  /* Brand/accent */

  --jp-brand-color0: var(--md-blue-900);
  --jp-brand-color1: var(--md-blue-700);
  --jp-brand-color2: var(--md-blue-300);
  --jp-brand-color3: var(--md-blue-100);
  --jp-brand-color4: var(--md-blue-50);
  --jp-accent-color0: var(--md-green-900);
  --jp-accent-color1: var(--md-green-700);
  --jp-accent-color2: var(--md-green-300);
  --jp-accent-color3: var(--md-green-100);

  /* State colors (warn, error, success, info) */

  --jp-warn-color0: var(--md-orange-900);
  --jp-warn-color1: var(--md-orange-700);
  --jp-warn-color2: var(--md-orange-300);
  --jp-warn-color3: var(--md-orange-100);
  --jp-error-color0: var(--md-red-900);
  --jp-error-color1: var(--md-red-700);
  --jp-error-color2: var(--md-red-300);
  --jp-error-color3: var(--md-red-100);
  --jp-success-color0: var(--md-green-900);
  --jp-success-color1: var(--md-green-700);
  --jp-success-color2: var(--md-green-300);
  --jp-success-color3: var(--md-green-100);
  --jp-info-color0: var(--md-cyan-900);
  --jp-info-color1: var(--md-cyan-700);
  --jp-info-color2: var(--md-cyan-300);
  --jp-info-color3: var(--md-cyan-100);

  /* Cell specific styles */

  --jp-cell-padding: 5px;
  --jp-cell-collapser-width: 8px;
  --jp-cell-collapser-min-height: 20px;
  --jp-cell-collapser-not-active-hover-opacity: 0.6;
  --jp-cell-editor-background: var(--md-grey-100);
  --jp-cell-editor-border-color: var(--md-grey-300);
  --jp-cell-editor-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-cell-editor-active-background: var(--jp-layout-color0);
  --jp-cell-editor-active-border-color: var(--jp-brand-color1);
  --jp-cell-prompt-width: 64px;
  --jp-cell-prompt-font-family: var(--jp-code-font-family-default);
  --jp-cell-prompt-letter-spacing: 0;
  --jp-cell-prompt-opacity: 1;
  --jp-cell-prompt-not-active-opacity: 0.5;
  --jp-cell-prompt-not-active-font-color: var(--md-grey-700);

  /* A custom blend of MD grey and blue 600
   * See https://meyerweb.com/eric/tools/color-blend/#546E7A:1E88E5:5:hex */
  --jp-cell-inprompt-font-color: #307fc1;

  /* A custom blend of MD grey and orange 600
   * https://meyerweb.com/eric/tools/color-blend/#546E7A:F4511E:5:hex */
  --jp-cell-outprompt-font-color: #bf5b3d;

  /* Notebook specific styles */

  --jp-notebook-padding: 10px;
  --jp-notebook-select-background: var(--jp-layout-color1);
  --jp-notebook-multiselected-color: var(--md-blue-50);

  /* The scroll padding is calculated to fill enough space at the bottom of the
  notebook to show one single-line cell (with appropriate padding) at the top
  when the notebook is scrolled all the way to the bottom. We also subtract one
  pixel so that no scrollbar appears if we have just one single-line cell in the
  notebook. This padding is to enable a 'scroll past end' feature in a notebook.
  */
  --jp-notebook-scroll-padding: calc(
    100% - var(--jp-code-font-size) * var(--jp-code-line-height) -
      var(--jp-code-padding) - var(--jp-cell-padding) - 1px
  );

  /* Rendermime styles */

  --jp-rendermime-error-background: #fdd;
  --jp-rendermime-table-row-background: var(--md-grey-100);
  --jp-rendermime-table-row-hover-background: var(--md-light-blue-50);

  /* Dialog specific styles */

  --jp-dialog-background: rgba(0, 0, 0, 0.25);

  /* Console specific styles */

  --jp-console-padding: 10px;

  /* Toolbar specific styles */

  --jp-toolbar-border-color: var(--jp-border-color1);
  --jp-toolbar-micro-height: 8px;
  --jp-toolbar-background: var(--jp-layout-color1);
  --jp-toolbar-box-shadow: 0 0 2px 0 rgba(0, 0, 0, 0.24);
  --jp-toolbar-header-margin: 4px 4px 0 4px;
  --jp-toolbar-active-background: var(--md-grey-300);

  /* Statusbar specific styles */

  --jp-statusbar-height: 24px;

  /* Input field styles */

  --jp-input-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-input-active-background: var(--jp-layout-color1);
  --jp-input-hover-background: var(--jp-layout-color1);
  --jp-input-background: var(--md-grey-100);
  --jp-input-border-color: var(--jp-inverse-border-color);
  --jp-input-active-border-color: var(--jp-brand-color1);
  --jp-input-active-box-shadow-color: rgba(19, 124, 189, 0.3);

  /* General editor styles */

  --jp-editor-selected-background: #d9d9d9;
  --jp-editor-selected-focused-background: #d7d4f0;
  --jp-editor-cursor-color: var(--jp-ui-font-color0);

  /* Code mirror specific styles */

  --jp-mirror-editor-keyword-color: #008000;
  --jp-mirror-editor-atom-color: #88f;
  --jp-mirror-editor-number-color: #080;
  --jp-mirror-editor-def-color: #00f;
  --jp-mirror-editor-variable-color: var(--md-grey-900);
  --jp-mirror-editor-variable-2-color: rgb(0, 54, 109);
  --jp-mirror-editor-variable-3-color: #085;
  --jp-mirror-editor-punctuation-color: #05a;
  --jp-mirror-editor-property-color: #05a;
  --jp-mirror-editor-operator-color: #a2f;
  --jp-mirror-editor-comment-color: #408080;
  --jp-mirror-editor-string-color: #ba2121;
  --jp-mirror-editor-string-2-color: #708;
  --jp-mirror-editor-meta-color: #a2f;
  --jp-mirror-editor-qualifier-color: #555;
  --jp-mirror-editor-builtin-color: #008000;
  --jp-mirror-editor-bracket-color: #997;
  --jp-mirror-editor-tag-color: #170;
  --jp-mirror-editor-attribute-color: #00c;
  --jp-mirror-editor-header-color: blue;
  --jp-mirror-editor-quote-color: #090;
  --jp-mirror-editor-link-color: #00c;
  --jp-mirror-editor-error-color: #f00;
  --jp-mirror-editor-hr-color: #999;

  /*
    RTC user specific colors.
    These colors are used for the cursor, username in the editor,
    and the icon of the user.
  */

  --jp-collaborator-color1: #ffad8e;
  --jp-collaborator-color2: #dac83d;
  --jp-collaborator-color3: #72dd76;
  --jp-collaborator-color4: #00e4d0;
  --jp-collaborator-color5: #45d4ff;
  --jp-collaborator-color6: #e2b1ff;
  --jp-collaborator-color7: #ff9de6;

  /* Vega extension styles */

  --jp-vega-background: white;

  /* Sidebar-related styles */

  --jp-sidebar-min-width: 250px;

  /* Search-related styles */

  --jp-search-toggle-off-opacity: 0.5;
  --jp-search-toggle-hover-opacity: 0.8;
  --jp-search-toggle-on-opacity: 1;
  --jp-search-selected-match-background-color: rgb(245, 200, 0);
  --jp-search-selected-match-color: black;
  --jp-search-unselected-match-background-color: var(
    --jp-inverse-layout-color0
  );
  --jp-search-unselected-match-color: var(--jp-ui-inverse-font-color0);

  /* Icon colors that work well with light or dark backgrounds */
  --jp-icon-contrast-color0: var(--md-purple-600);
  --jp-icon-contrast-color1: var(--md-green-600);
  --jp-icon-contrast-color2: var(--md-pink-600);
  --jp-icon-contrast-color3: var(--md-blue-600);

  /* Button colors */
  --jp-accept-color-normal: var(--md-blue-700);
  --jp-accept-color-hover: var(--md-blue-800);
  --jp-accept-color-active: var(--md-blue-900);
  --jp-warn-color-normal: var(--md-red-700);
  --jp-warn-color-hover: var(--md-red-800);
  --jp-warn-color-active: var(--md-red-900);
  --jp-reject-color-normal: var(--md-grey-600);
  --jp-reject-color-hover: var(--md-grey-700);
  --jp-reject-color-active: var(--md-grey-800);

  /* File or activity icons and switch semantic variables */
  --jp-jupyter-icon-color: #f37626;
  --jp-notebook-icon-color: #f37626;
  --jp-json-icon-color: var(--md-orange-700);
  --jp-console-icon-background-color: var(--md-blue-700);
  --jp-console-icon-color: white;
  --jp-terminal-icon-background-color: var(--md-grey-800);
  --jp-terminal-icon-color: var(--md-grey-200);
  --jp-text-editor-icon-color: var(--md-grey-700);
  --jp-inspector-icon-color: var(--md-grey-700);
  --jp-switch-color: var(--md-grey-400);
  --jp-switch-true-position-color: var(--md-orange-900);
}
</style>
<style type="text/css">
/* Force rendering true colors when outputing to pdf */
* {
  -webkit-print-color-adjust: exact;
}

/* Misc */
a.anchor-link {
  display: none;
}

/* Input area styling */
.jp-InputArea {
  overflow: hidden;
}

.jp-InputArea-editor {
  overflow: hidden;
}

.cm-editor.cm-s-jupyter .highlight pre {
/* weird, but --jp-code-padding defined to be 5px but 4px horizontal padding is hardcoded for pre.cm-line */
  padding: var(--jp-code-padding) 4px;
  margin: 0;

  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
  color: inherit;

}

.jp-OutputArea-output pre {
  line-height: inherit;
  font-family: inherit;
}

.jp-RenderedText pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
}

/* Hiding the collapser by default */
.jp-Collapser {
  display: none;
}

@page {
    margin: 0.5in; /* Margin for each printed piece of paper */
}

@media print {
  .jp-Cell-inputWrapper,
  .jp-Cell-outputWrapper {
    display: block;
  }
}
</style>
<!-- Load mathjax -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/latest.js?config=TeX-AMS_CHTML-full,Safe"> </script>
<!-- MathJax configuration -->
<script type="text/x-mathjax-config">
    init_mathjax = function() {
        if (window.MathJax) {
        // MathJax loaded
            MathJax.Hub.Config({
                TeX: {
                    equationNumbers: {
                    autoNumber: "AMS",
                    useLabelIds: true
                    }
                },
                tex2jax: {
                    inlineMath: [ ['$','$'], ["\\(","\\)"] ],
                    displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
                    processEscapes: true,
                    processEnvironments: true
                },
                displayAlign: 'center',
                messageStyle: 'none',
                CommonHTML: {
                    linebreaks: {
                    automatic: true
                    }
                }
            });

            MathJax.Hub.Queue(["Typeset", MathJax.Hub]);
        }
    }
    init_mathjax();
    </script>
<!-- End of mathjax configuration --><script type="module">
  document.addEventListener("DOMContentLoaded", async () => {
    const diagrams = document.querySelectorAll(".jp-Mermaid > pre.mermaid");
    // do not load mermaidjs if not needed
    if (!diagrams.length) {
      return;
    }
    const mermaid = (await import("https://cdnjs.cloudflare.com/ajax/libs/mermaid/10.7.0/mermaid.esm.min.mjs")).default;
    const parser = new DOMParser();

    mermaid.initialize({
      maxTextSize: 100000,
      maxEdges: 100000,
      startOnLoad: false,
      fontFamily: window
        .getComputedStyle(document.body)
        .getPropertyValue("--jp-ui-font-family"),
      theme: document.querySelector("body[data-jp-theme-light='true']")
        ? "default"
        : "dark",
    });

    let _nextMermaidId = 0;

    function makeMermaidImage(svg) {
      const img = document.createElement("img");
      const doc = parser.parseFromString(svg, "image/svg+xml");
      const svgEl = doc.querySelector("svg");
      const { maxWidth } = svgEl?.style || {};
      const firstTitle = doc.querySelector("title");
      const firstDesc = doc.querySelector("desc");

      img.setAttribute("src", `data:image/svg+xml,${encodeURIComponent(svg)}`);
      if (maxWidth) {
        img.width = parseInt(maxWidth);
      }
      if (firstTitle) {
        img.setAttribute("alt", firstTitle.textContent);
      }
      if (firstDesc) {
        const caption = document.createElement("figcaption");
        caption.className = "sr-only";
        caption.textContent = firstDesc.textContent;
        return [img, caption];
      }
      return [img];
    }

    async function makeMermaidError(text) {
      let errorMessage = "";
      try {
        await mermaid.parse(text);
      } catch (err) {
        errorMessage = `${err}`;
      }

      const result = document.createElement("details");
      result.className = 'jp-RenderedMermaid-Details';
      const summary = document.createElement("summary");
      summary.className = 'jp-RenderedMermaid-Summary';
      const pre = document.createElement("pre");
      const code = document.createElement("code");
      code.innerText = text;
      pre.appendChild(code);
      summary.appendChild(pre);
      result.appendChild(summary);

      const warning = document.createElement("pre");
      warning.innerText = errorMessage;
      result.appendChild(warning);
      return [result];
    }

    async function renderOneMarmaid(src) {
      const id = `jp-mermaid-${_nextMermaidId++}`;
      const parent = src.parentNode;
      let raw = src.textContent.trim();
      const el = document.createElement("div");
      el.style.visibility = "hidden";
      document.body.appendChild(el);
      let results = null;
      let output = null;
      try {
        let { svg } = await mermaid.render(id, raw, el);
        svg = cleanMermaidSvg(svg);
        results = makeMermaidImage(svg);
        output = document.createElement("figure");
        results.map(output.appendChild, output);
      } catch (err) {
        parent.classList.add("jp-mod-warning");
        results = await makeMermaidError(raw);
        output = results[0];
      } finally {
        el.remove();
      }
      parent.classList.add("jp-RenderedMermaid");
      parent.appendChild(output);
    }


    /**
     * Post-process to ensure mermaid diagrams contain only valid SVG and XHTML.
     */
    function cleanMermaidSvg(svg) {
      return svg.replace(RE_VOID_ELEMENT, replaceVoidElement);
    }


    /**
     * A regular expression for all void elements, which may include attributes and
     * a slash.
     *
     * @see https://developer.mozilla.org/en-US/docs/Glossary/Void_element
     *
     * Of these, only `<br>` is generated by Mermaid in place of `\n`,
     * but _any_ "malformed" tag will break the SVG rendering entirely.
     */
    const RE_VOID_ELEMENT =
      /<\s*(area|base|br|col|embed|hr|img|input|link|meta|param|source|track|wbr)\s*([^>]*?)\s*>/gi;

    /**
     * Ensure a void element is closed with a slash, preserving any attributes.
     */
    function replaceVoidElement(match, tag, rest) {
      rest = rest.trim();
      if (!rest.endsWith('/')) {
        rest = `${rest} /`;
      }
      return `<${tag} ${rest}>`;
    }

    void Promise.all([...diagrams].map(renderOneMarmaid));
  });
</script>
<style>
  .jp-Mermaid:not(.jp-RenderedMermaid) {
    display: none;
  }

  .jp-RenderedMermaid {
    overflow: auto;
    display: flex;
  }

  .jp-RenderedMermaid.jp-mod-warning {
    width: auto;
    padding: 0.5em;
    margin-top: 0.5em;
    border: var(--jp-border-width) solid var(--jp-warn-color2);
    border-radius: var(--jp-border-radius);
    color: var(--jp-ui-font-color1);
    font-size: var(--jp-ui-font-size1);
    white-space: pre-wrap;
    word-wrap: break-word;
  }

  .jp-RenderedMermaid figure {
    margin: 0;
    overflow: auto;
    max-width: 100%;
  }

  .jp-RenderedMermaid img {
    max-width: 100%;
  }

  .jp-RenderedMermaid-Details > pre {
    margin-top: 1em;
  }

  .jp-RenderedMermaid-Summary {
    color: var(--jp-warn-color2);
  }

  .jp-RenderedMermaid:not(.jp-mod-warning) pre {
    display: none;
  }

  .jp-RenderedMermaid-Summary > pre {
    display: inline-block;
    white-space: normal;
  }
</style>
<!-- End of mermaid configuration --></head>
<body class="jp-Notebook" data-jp-theme-light="true" data-jp-theme-name="JupyterLab Light">
<main>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p><a href="https://colab.research.google.com/github/DrWalleTeaching/Modelling-and-Simulation/blob/main/modelling_and_simulation.ipynb" target="_parent"><img alt="Open In Colab" src="https://colab.research.google.com/assets/colab-badge.svg"/></a></p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h1 id="Modelling-&amp;-Simulation---Stress-Shielding">Modelling &amp; Simulation - Stress Shielding<a class="anchor-link" href="#Modelling-&amp;-Simulation---Stress-Shielding">¶</a></h1><hr/>
<h2 id="Definition-&amp;-Etiology"><em>Definition &amp; Etiology</em><a class="anchor-link" href="#Definition-&amp;-Etiology">¶</a></h2><p>Stress shielding is a common phenomenon in patients after total hip replacement surgery, where bone mass is lost due to changes in the local loading environment. The stiff implant bears the load that the bone used to bear, "shielding" the bone from its usual stress (Figure 1). According to Wolff's law, the unloaded bone gets resorbed, leading to changes in the radiolucency of the cortical bone of the femur, which can be seen along the diaphysis and at the base of the neck (Figure 2).</p>
<table>
<thead>
<tr>
<th style="text-align:center"><img alt="stress_shielding.jpg" src="data:image/jpeg;base64,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GRw9Yt0SZLUwxdXJjkjSO+StwxduEc61lf8AJ9KIsbj/AGPOI6LVwost7vNlYaxLhLe8CvDzD7jikzJrDLSHGUlA7xtPIokkpPQdOtEWqYh2Pu0kZGJIzV/h9Gh4bwpvPDeEm2TpTrry3oqWY8p1bjKRyrPUoSPmwknayvSSLrDs9YDeOFfAvAeG2QmEbpjOPQbXNVCWVsKfZZShakKKUkgqBOykE7oikKiJREoiURKIlESiJREoiURKIlESiJREoiURKIlEXJ+UcI+0ziXarzbjpwfsOA3i35hjlusjYv8AepMRcNyOOrqm2o6+8TzfkhQJHqDRFbcNOx3m/DDPOCeRNZTbb+nDpGXXTMLg/wA8d2XcL02glcVlKVJ5A4nl0VJ8I35nVEWCsHY64t2rgfwE4duXTHxduGfE1GX3laJjvdLgibLeKWVd3tbnJIQOUhI3zDfvIrDJOxBmx4lZ8I+LYnl+HcRsnOSyH7vmF8tyrep1aFOtOW6IoMTORTYW2pSkHZAJASNEUhReyhk17xrtKYdk91tkCLxmvUibaJ8NS3Xo7LkVttHfoKU/RcRvkCiCCrqN0RRvYOxpxUkYFl1gyDCMJtuQvcOblhVpvjebXy7uynpDKWwQ3M21CjkoKlIQlZBUkJ0EnZFneLfYlzbi5PhW+df7TbbWjgt+IDspt1xbrd3RLjSG3A3yALj80fSjzBRBI0N7oiq8Suz72meNmCYic9tnD+2ZBw2vUC42e3Wi/wByZj3htuO4zKD0tltp2EVhaFNFpKigoUFbChoixl57I2eyeGS4EDgpw3Tf7nkT19lNHPL8qZBkiMhqPPj3dxK3/aUqSsqT3aUFJbHUpPMRdV8HsYzHC+FuL4pxCy1eUZJarazGul4WVEzJCU+JzavEr3cyvEdbPUmiLcaIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlEXw4620krdcShI8yo6FEXyzKiyBtiS04B+YsH+yiKrREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREo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oykWa9c71BWDsAwHRA8zDrDhZvuXS6EBtCW0+SQAN/CpLAyiwW/AWFl9V9X1KIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJRFSVKjpkohqeQH3G1Opb34ihJAUQPcCpP3iiKrREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURKIlESiJREoiURcN9mftC8ceJHF6/uZ7mU5rD7LlGSW1Wo1ij21EaEXO6QtRcE8qSkcylhHL4ASSnmIIpb7XnFziFjPA6w5b2c8js719yvI7HarJOcDMmFLROeCG9LVzIKF8yfGPQ7B9aIoKxftycXneIGe5NntqZxDDmcGgX3F7DeLatUpuS7ckW7mfSwkyFKdlJfShsdCktHw7KqIsrkn4RfLcG4WxeJeUcKrStEXK73hd1t6L0mPM9uitByM+0yvm0yTsPhSipkaUOcURdMROKrs/hjd5L+Q4oM7tOKm+XC3WW5onNQVOR1uMLBOlLaVy+FakhKwCR0oi494XdsHtS4/w5RxWzCwy8zxe5WXG/ZZuSWhnGEG+3GYyw4xFebSoSISWnS4JBb69OoHSiKRL/2puLeE8Qs3x97E7fPyiLcsCx9NllZFqzw5t6S+lRjuIiB7lC0tlalhRUNkJRy8pIq1g7anEzKG7LhcTEsAs2bSbxlNsuM275A81YWxY1toeLDob71xTheQQnQ5UIcWdgaoioRu1dxFs95m4pZYtjuF1vXEHJbIzNye/clrtrVvtDE/TbrMdKvZzzqQgKBV1Cis70CLHzfwilyMXh/frNg0GVEyGDj0rIrVt/2qzi6yVMNL9pIDJSdBTaQFLWN8wQCFURb/AMOOOGa2Xsz8YuK2R3NzJrngt/zUQS8lCe8Yt8l8RmiGwByhLaR79etEUb8du0NxO4D9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"/></th>
</tr>
</thead>
<tbody>
</tbody>
</table>
<p>|Figure 1 - Maximum absolute principal strains at the mid‐coronal cross section of the proximal part of the femur for intact and implanted models (implant size 2) and local difference of strains between the implanted and the intact femur models.
| --- |
| source:<a href="https://doi.org/10.1002/jor.23540">https://doi.org/10.1002/jor.23540</a> |</p>
<table>
<thead>
<tr>
<th style="text-align:center"><img alt="resorption.jpeg" src="data:image/jpeg;base64,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"/></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Figure 2 - Radiographs demonstrating pronounced bone-remodeling in a sixty-six-year-old woman. The immediate postoperative radiograph (on the left) shows an anatomic medullary locking stem that fills the intramedullary canal at the isthmus.<br/>The two-year follow-up radiograph is on the right. Note the marked thinning and decreased density of the cortices along the middle of the implant stem and increased density at the distal end of the implant.</td>
</tr>
<tr>
<td style="text-align:center">---</td>
</tr>
<tr>
<td style="text-align:center">source: <a href="https://journals.lww.com/jbjsjournal/toc/1997/07000">Journal of Bone and Joint Surgery - American Volume</a></td>
</tr>
</tbody>
</table>
<h3 id="Does-it-occur-with-all-implants?">Does it occur with all implants?<a class="anchor-link" href="#Does-it-occur-with-all-implants?">¶</a></h3><p>Stress shielding occurs when the implant bears more load than the bone, which is common with stiff metal implants (e.g., steel, titanium, cobalt chrome) in load-bearing bones like the femur. It may not occur with less stiff materials like PMMA, ceramics, or bioglass.</p>
<h3 id="Long-term-Consequences">Long-term Consequences<a class="anchor-link" href="#Long-term-Consequences">¶</a></h3><p>While less load on weak bones may seem beneficial, changes to the physiological loading of the femur can cause problems over time. Significant bone resorption due to stress shielding can lead to aseptic loosening (failure of the implant-bone bond), increased micromotion, pain, and joint degradation. Revision surgery, which is more complicated and less successful than primary implantation, is the only solution.</p>
<h1 id="Activity">Activity<a class="anchor-link" href="#Activity">¶</a></h1><hr/>
<p>In this activity, you will run a 2D finite element simulation to investigate how different implant materials affect the stress distribution within the implanted femur.</p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="c1"># @title Setting up the research environment</span>

<span class="c1">#import standard scientific python libraries</span>
<span class="kn">import</span><span class="w"> </span><span class="nn">numpy</span><span class="w"> </span><span class="k">as</span><span class="w"> </span><span class="nn">np</span>
<span class="kn">import</span><span class="w"> </span><span class="nn">matplotlib.pyplot</span><span class="w"> </span><span class="k">as</span><span class="w"> </span><span class="nn">plt</span>
<span class="kn">import</span><span class="w"> </span><span class="nn">pandas</span><span class="w"> </span><span class="k">as</span><span class="w"> </span><span class="nn">pd</span>
<span class="kn">from</span><span class="w"> </span><span class="nn">scipy</span><span class="w"> </span><span class="kn">import</span> <span class="n">ndimage</span>
<span class="kn">import</span><span class="w"> </span><span class="nn">sys</span>
<span class="kn">import</span><span class="w"> </span><span class="nn">os</span>
<span class="o">%</span><span class="n">matplotlib</span> <span class="n">inline</span>

<span class="c1"># Some path definitions for this notebook</span>
<span class="n">pat</span> <span class="o">=</span> <span class="s2">"github token"</span>
<span class="n">repo_url</span> <span class="o">=</span> <span class="s1">'https://github.com/DrWalleTeaching/Modelling-and-Simulation'</span>  <span class="c1"># Replace with your repository URL</span>

<span class="n">target_directory</span> <span class="o">=</span> <span class="s1">'/content/Modelling-and-Simulation'</span>

<span class="n">sys</span><span class="o">.</span><span class="n">path</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">os</span><span class="o">.</span><span class="n">path</span><span class="o">.</span><span class="n">join</span><span class="p">(</span><span class="n">target_directory</span><span class="p">,</span><span class="s1">'Helpers'</span><span class="p">))</span>
<span class="n">datapath</span> <span class="o">=</span> <span class="n">os</span><span class="o">.</span><span class="n">path</span><span class="o">.</span><span class="n">join</span><span class="p">(</span><span class="n">target_directory</span><span class="p">,</span><span class="s1">'Helpers/data'</span><span class="p">)</span>

<span class="c1"># Modify the repo URL to include the PAT for authentication</span>
<span class="n">modified_url</span> <span class="o">=</span> <span class="n">repo_url</span><span class="o">.</span><span class="n">replace</span><span class="p">(</span><span class="s1">'https://'</span><span class="p">,</span> <span class="sa">f</span><span class="s1">'https://</span><span class="si">{</span><span class="n">pat</span><span class="si">}</span><span class="s1">@'</span><span class="p">)</span>

<span class="c1"># Clone the repo</span>

<span class="c1"># Remove the directory if it exists</span>
<span class="k">if</span> <span class="n">os</span><span class="o">.</span><span class="n">path</span><span class="o">.</span><span class="n">exists</span><span class="p">(</span><span class="n">target_directory</span><span class="p">):</span>
    <span class="err">!</span><span class="n">rm</span> <span class="o">-</span><span class="n">rf</span> <span class="p">{</span><span class="n">target_directory</span><span class="p">}</span>

<span class="err">!</span><span class="n">git</span> <span class="n">clone</span> <span class="p">{</span><span class="n">modified_url</span><span class="p">}</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="c1"># @title Loading the data for our Femur/Implant models</span>

<span class="c1">#load datasets, this includes the pelvis image (density: 0-255) and masks (bool) arrays we generated in the SegmentFemur notebook</span>
<span class="n">data</span> <span class="o">=</span> <span class="p">[</span><span class="s1">'pelvis'</span><span class="p">,</span><span class="s1">'implant'</span><span class="p">,</span><span class="s1">'fem_implant'</span><span class="p">,</span><span class="s1">'femur'</span><span class="p">]</span>
<span class="n">dict_data</span> <span class="o">=</span> <span class="p">{}</span>
<span class="c1">#plot and read datasets into a dictionary (makes for a neater code later on)</span>
<span class="k">for</span> <span class="n">i</span><span class="p">,</span> <span class="n">file</span> <span class="ow">in</span> <span class="nb">enumerate</span><span class="p">(</span><span class="n">data</span><span class="p">):</span>
    <span class="n">image</span> <span class="o">=</span> <span class="p">[</span><span class="n">np</span><span class="o">.</span><span class="n">load</span><span class="p">(</span><span class="sa">f</span><span class="s1">'</span><span class="si">{</span><span class="n">datapath</span><span class="si">}</span><span class="s1">/</span><span class="si">{</span><span class="n">file</span><span class="si">}</span><span class="s1">.npz'</span><span class="p">)[</span><span class="n">arr</span><span class="p">]</span> <span class="k">for</span> <span class="n">arr</span> <span class="ow">in</span> <span class="n">np</span><span class="o">.</span><span class="n">load</span><span class="p">(</span><span class="sa">f</span><span class="s1">'</span><span class="si">{</span><span class="n">datapath</span><span class="si">}</span><span class="s1">/</span><span class="si">{</span><span class="n">file</span><span class="si">}</span><span class="s1">.npz'</span><span class="p">)][</span><span class="mi">0</span><span class="p">]</span>
    <span class="n">dict_data</span><span class="p">[</span><span class="n">file</span><span class="p">]</span> <span class="o">=</span> <span class="n">image</span>

<span class="n">_</span><span class="p">,</span> <span class="n">axes</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">1</span><span class="p">,</span> <span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">5</span><span class="p">,</span><span class="mi">5</span><span class="p">))</span>

<span class="n">axes</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">dict_data</span><span class="p">[</span><span class="s1">'pelvis'</span><span class="p">],</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">gray</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>
<span class="n">axes</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s1">'CT of pelvis'</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="c1"># @title Extract implant, femur and contralateral side</span>

<span class="c1">#Crop the image and masks to a smaller size</span>
<span class="n">segmented_contra</span> <span class="o">=</span> <span class="n">dict_data</span><span class="p">[</span><span class="s1">'pelvis'</span><span class="p">][</span><span class="mi">550</span><span class="p">:</span><span class="o">-</span><span class="mi">150</span><span class="p">,:</span><span class="mi">900</span><span class="p">]</span>
<span class="n">segmented_fem</span> <span class="o">=</span> <span class="p">(</span><span class="n">dict_data</span><span class="p">[</span><span class="s1">'fem_implant'</span><span class="p">]</span><span class="o">*</span><span class="n">dict_data</span><span class="p">[</span><span class="s1">'pelvis'</span><span class="p">])[</span><span class="mi">700</span><span class="p">:,</span><span class="mi">1700</span><span class="p">:]</span>
<span class="n">segmented_stem</span> <span class="o">=</span> <span class="p">(</span><span class="n">dict_data</span><span class="p">[</span><span class="s1">'implant'</span><span class="p">]</span><span class="o">*</span><span class="n">dict_data</span><span class="p">[</span><span class="s1">'pelvis'</span><span class="p">]</span><span class="o">*</span><span class="n">dict_data</span><span class="p">[</span><span class="s1">'fem_implant'</span><span class="p">])[</span><span class="mi">700</span><span class="p">:,</span><span class="mi">1700</span><span class="p">:]</span><span class="o">.</span><span class="n">astype</span><span class="p">(</span><span class="nb">bool</span><span class="p">)</span><span class="o">.</span><span class="n">astype</span><span class="p">(</span><span class="nb">int</span><span class="p">)</span>
<span class="n">segmented_femur</span> <span class="o">=</span> <span class="p">(</span><span class="n">dict_data</span><span class="p">[</span><span class="s1">'femur'</span><span class="p">]</span><span class="o">*</span><span class="n">dict_data</span><span class="p">[</span><span class="s1">'pelvis'</span><span class="p">])[</span><span class="mi">700</span><span class="p">:,</span><span class="mi">1700</span><span class="p">:]</span>

<span class="c1">#Plot the images and masks</span>
<span class="n">_</span><span class="p">,</span> <span class="n">axes</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">4</span><span class="p">,</span> <span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">15</span><span class="p">,</span><span class="mi">20</span><span class="p">))</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">segmented_contra</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">gray</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">1</span><span class="p">]</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">segmented_fem</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">gray</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">2</span><span class="p">]</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">segmented_stem</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">gray</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">3</span><span class="p">]</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">segmented_femur</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">gray</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="sa">f</span><span class="s1">'Contralateral side (control)'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">1</span><span class="p">]</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="sa">f</span><span class="s1">'Segmented implant site'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">2</span><span class="p">]</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="sa">f</span><span class="s1">'Segmented implant'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">3</span><span class="p">]</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="sa">f</span><span class="s1">'Segmented femur'</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="c1"># @title Material Properties</span>
<span class="kn">from</span><span class="w"> </span><span class="nn">IPython.display</span><span class="w"> </span><span class="kn">import</span> <span class="n">display</span><span class="p">,</span> <span class="n">clear_output</span>

<span class="c1"># Create a function to check the selected option</span>
<span class="k">def</span><span class="w"> </span><span class="nf">check_option</span><span class="p">(</span><span class="n">option</span><span class="p">):</span>
    <span class="n">correct_answer</span> <span class="o">=</span> <span class="s1">'linear-elastic'</span>  <span class="c1"># Set the correct answer</span>

    <span class="c1"># Display feedback based on the selected option</span>
    <span class="k">with</span> <span class="n">output</span><span class="p">:</span>
        <span class="n">clear_output</span><span class="p">()</span>  <span class="c1"># Clear previous output</span>
        <span class="k">if</span> <span class="n">option</span> <span class="o">==</span> <span class="n">correct_answer</span><span class="p">:</span>
            <span class="nb">print</span><span class="p">(</span><span class="s2">"Correct! A linear-elastic material is suitable for day-to-day loading."</span><span class="p">)</span>
        <span class="k">else</span><span class="p">:</span>
            <span class="nb">print</span><span class="p">(</span><span class="s2">"Incorrect. A linear-elastic material is the recommended choice for day-to-day loading."</span><span class="p">)</span>

<span class="c1"># Create radio buttons widget for the multiple-choice question</span>
<span class="n">choices</span> <span class="o">=</span> <span class="p">[</span><span class="s1">'non-linear'</span><span class="p">,</span> <span class="s1">'linear-elastic'</span><span class="p">,</span> <span class="s1">'elastic-plastic'</span><span class="p">,</span> <span class="s1">'viscoelastic'</span><span class="p">]</span>
<span class="n">radio_buttons</span> <span class="o">=</span> <span class="n">widgets</span><span class="o">.</span><span class="n">RadioButtons</span><span class="p">(</span><span class="n">options</span><span class="o">=</span><span class="n">choices</span><span class="p">,</span> <span class="n">description</span><span class="o">=</span><span class="s1">'Select an option:'</span><span class="p">)</span>

<span class="c1"># Create an output widget for displaying feedback</span>
<span class="n">output</span> <span class="o">=</span> <span class="n">widgets</span><span class="o">.</span><span class="n">Output</span><span class="p">()</span>

<span class="c1"># Display the question, radio buttons, and feedback output</span>
<span class="n">question</span> <span class="o">=</span> <span class="n">widgets</span><span class="o">.</span><span class="n">HTML</span><span class="p">(</span><span class="s1">'&lt;h3&gt;For day-to-day loading, what material would you choose?&lt;/h3&gt;'</span><span class="p">)</span>
<span class="n">display</span><span class="p">(</span><span class="n">question</span><span class="p">,</span> <span class="n">radio_buttons</span><span class="p">,</span> <span class="n">output</span><span class="p">)</span>

<span class="c1"># Call the check_option function when the radio button value changes</span>
<span class="n">radio_buttons</span><span class="o">.</span><span class="n">observe</span><span class="p">(</span><span class="k">lambda</span> <span class="n">change</span><span class="p">:</span> <span class="n">check_option</span><span class="p">(</span><span class="n">change</span><span class="o">.</span><span class="n">new</span><span class="p">),</span> <span class="n">names</span><span class="o">=</span><span class="s1">'value'</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="c1"># @title Choose Material Stiffness [GPa]</span>

<span class="kn">import</span><span class="w"> </span><span class="nn">ipywidgets</span><span class="w"> </span><span class="k">as</span><span class="w"> </span><span class="nn">widgets</span>

<span class="c1"># Define default values</span>
<span class="n">default_values</span> <span class="o">=</span> <span class="p">{</span>
    <span class="s2">"titanium_grade5"</span><span class="p">:</span> <span class="mi">110</span><span class="p">,</span>
    <span class="s2">"steel_440"</span><span class="p">:</span> <span class="mi">210</span><span class="p">,</span>
    <span class="s2">"graphite"</span><span class="p">:</span> <span class="mi">20</span><span class="p">,</span>
    <span class="s2">"unobtanium"</span><span class="p">:</span> <span class="mi">20000</span><span class="p">,</span>
    <span class="s2">"jelly"</span><span class="p">:</span> <span class="mi">1</span>
<span class="p">}</span>

<span class="c1"># Create sliders for each material</span>
<span class="n">titanium_slider</span> <span class="o">=</span> <span class="n">widgets</span><span class="o">.</span><span class="n">FloatSlider</span><span class="p">(</span><span class="n">value</span><span class="o">=</span><span class="n">default_values</span><span class="p">[</span><span class="s2">"titanium_grade5"</span><span class="p">],</span> <span class="nb">min</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="nb">max</span><span class="o">=</span><span class="mi">500</span><span class="p">,</span> <span class="n">description</span><span class="o">=</span><span class="s2">"Titanium Grade 5 (GPa)"</span><span class="p">)</span>
<span class="n">steel_slider</span> <span class="o">=</span> <span class="n">widgets</span><span class="o">.</span><span class="n">FloatSlider</span><span class="p">(</span><span class="n">value</span><span class="o">=</span><span class="n">default_values</span><span class="p">[</span><span class="s2">"steel_440"</span><span class="p">],</span> <span class="nb">min</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="nb">max</span><span class="o">=</span><span class="mi">500</span><span class="p">,</span> <span class="n">description</span><span class="o">=</span><span class="s2">"Steel 440 (GPa)"</span><span class="p">)</span>
<span class="n">graphite_slider</span> <span class="o">=</span> <span class="n">widgets</span><span class="o">.</span><span class="n">FloatSlider</span><span class="p">(</span><span class="n">value</span><span class="o">=</span><span class="n">default_values</span><span class="p">[</span><span class="s2">"graphite"</span><span class="p">],</span> <span class="nb">min</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="nb">max</span><span class="o">=</span><span class="mi">500</span><span class="p">,</span> <span class="n">description</span><span class="o">=</span><span class="s2">"Graphite (GPa)"</span><span class="p">)</span>
<span class="n">unobtanium_slider</span> <span class="o">=</span> <span class="n">widgets</span><span class="o">.</span><span class="n">FloatSlider</span><span class="p">(</span><span class="n">value</span><span class="o">=</span><span class="n">default_values</span><span class="p">[</span><span class="s2">"unobtanium"</span><span class="p">],</span> <span class="nb">min</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="nb">max</span><span class="o">=</span><span class="mi">50000</span><span class="p">,</span> <span class="n">description</span><span class="o">=</span><span class="s2">"Unobtanium (GPa)"</span><span class="p">)</span>
<span class="n">jelly_slider</span> <span class="o">=</span> <span class="n">widgets</span><span class="o">.</span><span class="n">FloatSlider</span><span class="p">(</span><span class="n">value</span><span class="o">=</span><span class="n">default_values</span><span class="p">[</span><span class="s2">"jelly"</span><span class="p">],</span> <span class="nb">min</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="nb">max</span><span class="o">=</span><span class="mi">10</span><span class="p">,</span> <span class="n">description</span><span class="o">=</span><span class="s2">"Jelly (GPa)"</span><span class="p">)</span>

<span class="c1"># Define dictionary to store material properties</span>
<span class="n">fem_dict</span> <span class="o">=</span> <span class="p">{</span>
    <span class="s1">'titanium'</span><span class="p">:</span> <span class="n">titanium_slider</span><span class="o">.</span><span class="n">value</span><span class="p">,</span>
    <span class="s1">'steel'</span><span class="p">:</span> <span class="n">steel_slider</span><span class="o">.</span><span class="n">value</span><span class="p">,</span>
    <span class="s1">'graphite'</span><span class="p">:</span> <span class="n">graphite_slider</span><span class="o">.</span><span class="n">value</span><span class="p">,</span>
    <span class="s1">'unobtanium'</span><span class="p">:</span> <span class="n">unobtanium_slider</span><span class="o">.</span><span class="n">value</span><span class="p">,</span>
    <span class="s1">'jelly'</span><span class="p">:</span> <span class="n">jelly_slider</span><span class="o">.</span><span class="n">value</span>
<span class="p">}</span>

<span class="c1"># Function to update dictionary with slider values</span>
<span class="k">def</span><span class="w"> </span><span class="nf">update_fem_dict</span><span class="p">():</span>
    <span class="n">fem_dict</span><span class="p">[</span><span class="s1">'titanium'</span><span class="p">]</span> <span class="o">=</span> <span class="n">titanium_slider</span><span class="o">.</span><span class="n">value</span>
    <span class="n">fem_dict</span><span class="p">[</span><span class="s1">'steel'</span><span class="p">]</span> <span class="o">=</span> <span class="n">steel_slider</span><span class="o">.</span><span class="n">value</span>
    <span class="n">fem_dict</span><span class="p">[</span><span class="s1">'graphite'</span><span class="p">]</span> <span class="o">=</span> <span class="n">graphite_slider</span><span class="o">.</span><span class="n">value</span>
    <span class="n">fem_dict</span><span class="p">[</span><span class="s1">'unobtanium'</span><span class="p">]</span> <span class="o">=</span> <span class="n">unobtanium_slider</span><span class="o">.</span><span class="n">value</span>
    <span class="n">fem_dict</span><span class="p">[</span><span class="s1">'jelly'</span><span class="p">]</span> <span class="o">=</span> <span class="n">jelly_slider</span><span class="o">.</span><span class="n">value</span>

<span class="c1"># Display sliders</span>
<span class="n">display</span><span class="p">(</span><span class="n">titanium_slider</span><span class="p">,</span> <span class="n">steel_slider</span><span class="p">,</span> <span class="n">graphite_slider</span><span class="p">,</span> <span class="n">unobtanium_slider</span><span class="p">,</span> <span class="n">jelly_slider</span><span class="p">)</span>

<span class="c1"># Call the function to update the dictionary initially</span>
<span class="n">update_fem_dict</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="c1"># @title Convert Density to Young's Modulus</span>

<span class="c1"># This is to segment the contralateral femur from the background and to assign material properties</span>
<span class="c1"># Note that here we are not elminating the pelvis to speed up the segmentation process</span>

<span class="c1">#binary threshold the bone from the surrounding tissue (&gt;140) and dilate the mask (the dilation is required for the next step)</span>
<span class="n">healthy</span> <span class="o">=</span> <span class="n">ndimage</span><span class="o">.</span><span class="n">binary_dilation</span><span class="p">((</span><span class="n">segmented_contra</span><span class="o">&gt;</span><span class="mi">140</span><span class="p">),</span><span class="n">iterations</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>

<span class="c1">#fill the false negative holes in the mask to get a uniform mask</span>
<span class="n">healthy_mask</span> <span class="o">=</span> <span class="n">ndimage</span><span class="o">.</span><span class="n">binary_fill_holes</span><span class="p">(</span><span class="n">healthy</span><span class="p">)</span>

<span class="c1">#erode the mask back down to the original size</span>
<span class="n">healthy_mask</span> <span class="o">=</span> <span class="n">ndimage</span><span class="o">.</span><span class="n">binary_erosion</span><span class="p">(</span><span class="n">healthy_mask</span><span class="p">,</span> <span class="n">iterations</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>

<span class="c1">#perform binary opening (erosion then dilation) to remove the false positives</span>
<span class="n">healthy_mask</span> <span class="o">=</span> <span class="n">ndimage</span><span class="o">.</span><span class="n">binary_opening</span><span class="p">(</span><span class="n">healthy_mask</span><span class="p">,</span> <span class="n">iterations</span><span class="o">=</span><span class="mi">10</span><span class="p">)</span>

<span class="c1">#use the mask to segment the bone from the image and convert the bone density to Young's modulus in MPa by setting the max image values (255.0) to</span>
<span class="c1">#17.0 GPa (representative of cortical bone) = 17.0*1000 MPa</span>
<span class="n">healthy</span> <span class="o">=</span> <span class="p">(</span><span class="n">healthy_mask</span><span class="o">*</span><span class="mf">17.0</span><span class="o">*</span><span class="mf">1000.0</span><span class="o">*</span><span class="n">segmented_contra</span><span class="o">/</span><span class="mf">255.0</span><span class="p">)[</span><span class="mi">10</span><span class="p">:</span><span class="o">-</span><span class="mi">10</span><span class="p">,</span><span class="mi">10</span><span class="p">:</span><span class="o">-</span><span class="mi">10</span><span class="p">]</span>


<span class="c1"># High density in yellow and low density in blue</span>
<span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">6</span><span class="p">,</span><span class="mi">6</span><span class="p">))</span>
<span class="n">plt</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">flip</span><span class="p">(</span><span class="n">healthy_low</span><span class="p">,</span><span class="mi">1</span><span class="p">),</span> <span class="n">cmap</span><span class="o">=</span><span class="s1">'plasma'</span><span class="p">)</span>  <span class="c1"># Change cmap to plasma for better visibility</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s1">'Material properties of the bone tissue [GPa]'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">axis</span><span class="p">(</span><span class="s1">'off'</span><span class="p">)</span>  <span class="c1"># Remove axes</span>
<span class="n">plt</span><span class="o">.</span><span class="n">colorbar</span><span class="p">(</span><span class="n">label</span><span class="o">=</span><span class="s1">'GPa'</span><span class="p">)</span>  <span class="c1"># Add colorbar with label</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="c1"># @title Decide Model Complexity (Size)</span>
<span class="c1"># Create a slider for the zoom factor</span>
<span class="n">zoom_factor_slider</span> <span class="o">=</span> <span class="n">widgets</span><span class="o">.</span><span class="n">FloatSlider</span><span class="p">(</span><span class="n">value</span><span class="o">=</span><span class="mf">0.1</span><span class="p">,</span> <span class="nb">min</span><span class="o">=</span><span class="mf">0.1</span><span class="p">,</span> <span class="nb">max</span><span class="o">=</span><span class="mf">1.0</span><span class="p">,</span> <span class="n">description</span><span class="o">=</span><span class="s1">'Model Complexity'</span><span class="p">)</span>

<span class="c1"># Display the slider</span>
<span class="n">zoom_factor_slider</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="c1"># @title Run the Finite Element Analysis</span>

<span class="c1">#Downsample ('zoom out' x10) in order to reduce the image size and reduce processing time for the simulation</span>
<span class="c1"># !important (will overload server if not downsampled)</span>

<span class="n">zoom_factor</span> <span class="o">=</span> <span class="n">zoom_factor_slider</span><span class="o">.</span><span class="n">value</span>

<span class="n">healthy_low</span> <span class="o">=</span> <span class="n">ndimage</span><span class="o">.</span><span class="n">zoom</span><span class="p">(</span><span class="n">healthy</span><span class="p">,</span> <span class="n">zoom_factor</span><span class="p">,</span> <span class="n">order</span><span class="o">=</span><span class="mi">4</span><span class="p">)</span>

<span class="c1">#set all background values to 300.0 MPa (need to have a minimum stiffness value for all voxels or FE will not converge on solution)</span>
<span class="n">healthy_low</span><span class="p">[</span><span class="n">healthy_low</span> <span class="o">&lt;</span> <span class="mi">500</span><span class="p">]</span> <span class="o">=</span> <span class="mf">300.0</span>

<span class="c1">#image processing of the stem and femur image, downsample ('zoom out' x10) in order to reduce simulation time</span>
<span class="n">stem_low</span> <span class="o">=</span> <span class="n">ndimage</span><span class="o">.</span><span class="n">binary_dilation</span><span class="p">(</span><span class="n">ndimage</span><span class="o">.</span><span class="n">zoom</span><span class="p">(</span><span class="n">segmented_stem</span><span class="p">,</span> <span class="n">zoom_factor</span><span class="p">,</span> <span class="n">order</span><span class="o">=</span><span class="mi">0</span><span class="p">),</span> <span class="n">iterations</span><span class="o">=</span><span class="mi">1</span><span class="p">)</span>
<span class="n">femur_low</span> <span class="o">=</span> <span class="n">ndimage</span><span class="o">.</span><span class="n">zoom</span><span class="p">(</span><span class="n">segmented_femur</span><span class="p">,</span> <span class="n">zoom_factor</span><span class="p">,</span> <span class="n">order</span><span class="o">=</span><span class="mi">4</span><span class="p">)</span>

<span class="c1">#generate masks to crop the outputs</span>
<span class="n">bool_model</span> <span class="o">=</span> <span class="p">((</span><span class="mi">10</span><span class="o">*</span><span class="n">stem_low</span> <span class="o">+</span> <span class="n">femur_low</span><span class="p">)</span> <span class="o">&gt;</span> <span class="mi">5</span> <span class="p">)</span><span class="o">.</span><span class="n">astype</span><span class="p">(</span><span class="nb">int</span><span class="p">)</span>
<span class="n">bool_control</span> <span class="o">=</span> <span class="p">(</span><span class="n">healthy_low</span> <span class="o">&gt;</span> <span class="mi">500</span><span class="p">)</span><span class="o">.</span><span class="n">astype</span><span class="p">(</span><span class="nb">int</span><span class="p">)</span>

<span class="c1">#generate the FE models using the specified young's moduli above</span>
<span class="c1">#the BMD is scaled to the max E value of cortical bone of ca. 17.0 GPa</span>
<span class="c1">#all background stiffness values are set to 3.0 MPa</span>
<span class="n">fem_dict_modulus</span> <span class="o">=</span> <span class="p">{}</span>
<span class="k">for</span> <span class="n">model</span><span class="p">,</span> <span class="n">young_E</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">fem_dict</span><span class="o">.</span><span class="n">keys</span><span class="p">(),</span> <span class="n">fem_dict</span><span class="o">.</span><span class="n">values</span><span class="p">()):</span>
    <span class="n">fem</span> <span class="o">=</span> <span class="p">(</span><span class="n">stem_low</span><span class="o">*</span><span class="n">young_E</span> <span class="o">+</span> <span class="mf">17.0</span><span class="o">*</span><span class="n">femur_low</span><span class="o">/</span><span class="mf">255.0</span><span class="p">)</span><span class="o">*</span><span class="mf">1000.0</span>
    <span class="n">fem</span><span class="p">[</span><span class="n">fem</span><span class="o">&lt;</span><span class="mi">500</span><span class="p">]</span> <span class="o">=</span> <span class="mf">300.0</span>
    <span class="n">fem_dict_modulus</span><span class="p">[</span><span class="n">model</span><span class="p">]</span> <span class="o">=</span> <span class="n">fem</span>

<span class="c1">#add the control from above to the same fem dict</span>
<span class="n">fem_dict_modulus</span><span class="p">[</span><span class="s1">'control'</span><span class="p">]</span> <span class="o">=</span> <span class="n">healthy_low</span>

<span class="c1">#import the image FE solver (open source! feel free to investigate and play around)</span>
<span class="kn">from</span><span class="w"> </span><span class="nn">pixFE.basic</span><span class="w"> </span><span class="kn">import</span> <span class="n">compress</span>
<span class="kn">import</span><span class="w"> </span><span class="nn">time</span>

<span class="n">results</span> <span class="o">=</span> <span class="p">{}</span>
<span class="c1">#run the fem dict and simulate each value, the compress function returns strains and stresses</span>
<span class="c1">#we will be looking at the von_mises stress so we need to process the output a bit further (2D Mohr's circle)</span>
<span class="k">for</span> <span class="n">test</span><span class="p">,</span> <span class="n">fem</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">fem_dict_modulus</span><span class="o">.</span><span class="n">keys</span><span class="p">(),</span> <span class="n">fem_dict_modulus</span><span class="o">.</span><span class="n">values</span><span class="p">()):</span>
    <span class="nb">print</span><span class="p">(</span><span class="sa">f</span><span class="s1">'simulation of </span><span class="si">{</span><span class="n">test</span><span class="si">}</span><span class="s1">'</span><span class="p">)</span>
    <span class="n">SED</span><span class="p">,</span> <span class="n">strain</span><span class="p">,</span> <span class="n">stress</span> <span class="o">=</span> <span class="n">compress</span><span class="p">(</span><span class="n">fem</span><span class="p">,</span><span class="mf">0.05</span><span class="p">)</span>
    <span class="n">max_principal_stress</span> <span class="o">=</span> <span class="p">(</span><span class="n">stress</span><span class="p">[</span><span class="s1">'xx'</span><span class="p">]</span><span class="o">+</span><span class="n">stress</span><span class="p">[</span><span class="s1">'yy'</span><span class="p">])</span><span class="o">/</span><span class="mi">2</span> <span class="o">+</span> <span class="p">((</span><span class="n">stress</span><span class="p">[</span><span class="s1">'xx'</span><span class="p">]</span><span class="o">+</span><span class="n">stress</span><span class="p">[</span><span class="s1">'yy'</span><span class="p">])</span><span class="o">**</span><span class="mi">2</span><span class="o">/</span><span class="mi">4</span> <span class="o">+</span> <span class="n">stress</span><span class="p">[</span><span class="s1">'xy'</span><span class="p">]</span><span class="o">**</span><span class="mi">2</span><span class="p">)</span><span class="o">**</span><span class="mf">0.5</span>
    <span class="n">min_principal_stress</span> <span class="o">=</span> <span class="p">(</span><span class="n">stress</span><span class="p">[</span><span class="s1">'xx'</span><span class="p">]</span><span class="o">+</span><span class="n">stress</span><span class="p">[</span><span class="s1">'yy'</span><span class="p">])</span><span class="o">/</span><span class="mi">2</span> <span class="o">-</span> <span class="p">((</span><span class="n">stress</span><span class="p">[</span><span class="s1">'xx'</span><span class="p">]</span><span class="o">+</span><span class="n">stress</span><span class="p">[</span><span class="s1">'yy'</span><span class="p">])</span><span class="o">**</span><span class="mi">2</span><span class="o">/</span><span class="mi">4</span> <span class="o">+</span> <span class="n">stress</span><span class="p">[</span><span class="s1">'xy'</span><span class="p">]</span><span class="o">**</span><span class="mi">2</span><span class="p">)</span><span class="o">**</span><span class="mf">0.5</span>
    <span class="n">von_mises</span> <span class="o">=</span> <span class="n">max_principal_stress</span> <span class="o">-</span> <span class="n">min_principal_stress</span>
    <span class="n">results</span><span class="p">[</span><span class="n">test</span><span class="p">]</span> <span class="o">=</span> <span class="p">{}</span>
    <span class="n">results</span><span class="p">[</span><span class="n">test</span><span class="p">][</span><span class="s1">'von_mises'</span><span class="p">]</span> <span class="o">=</span> <span class="n">von_mises</span>
    <span class="n">results</span><span class="p">[</span><span class="n">test</span><span class="p">][</span><span class="s1">'strain'</span><span class="p">]</span> <span class="o">=</span> <span class="n">strain</span>
    <span class="n">results</span><span class="p">[</span><span class="n">test</span><span class="p">][</span><span class="s1">'SED'</span><span class="p">]</span> <span class="o">=</span> <span class="n">SED</span>
    <span class="nb">print</span><span class="p">(</span><span class="s1">''</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="c1"># @title Simulation Results (Von Mises Stress)</span>
<span class="c1">#Plot von mises stresses for entire model</span>

<span class="n">fig</span><span class="p">,</span> <span class="n">axes</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">8</span><span class="p">,</span><span class="mi">6</span><span class="p">))</span>
<span class="n">scale</span> <span class="o">=</span> <span class="mi">2200</span> <span class="c1">#Proper scaling of von_mises stress due to (unphysiological) 5% compression</span>

<span class="c1">#'mirrored' the contralateral side to match those of the fe models using np.flip(array,axis=1)</span>
<span class="n">im</span> <span class="o">=</span> <span class="n">axes</span><span class="p">[</span><span class="mi">0</span><span class="p">,</span><span class="mi">0</span><span class="p">]</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">flip</span><span class="p">(</span><span class="n">results</span><span class="p">[</span><span class="s1">'control'</span><span class="p">][</span><span class="s1">'von_mises'</span><span class="p">]</span><span class="o">*</span><span class="n">bool_control</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span><span class="o">*</span><span class="n">scale</span><span class="p">,</span> <span class="n">vmin</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="n">vmax</span><span class="o">=</span><span class="mi">50</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">plasma</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">0</span><span class="p">,</span><span class="mi">1</span><span class="p">]</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">results</span><span class="p">[</span><span class="s1">'titanium'</span><span class="p">][</span><span class="s1">'von_mises'</span><span class="p">]</span><span class="o">*</span><span class="n">bool_model</span><span class="o">*</span><span class="n">scale</span><span class="p">,</span> <span class="n">vmin</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="n">vmax</span><span class="o">=</span><span class="mi">50</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">plasma</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">0</span><span class="p">,</span><span class="mi">2</span><span class="p">]</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">results</span><span class="p">[</span><span class="s1">'steel'</span><span class="p">][</span><span class="s1">'von_mises'</span><span class="p">]</span><span class="o">*</span><span class="n">bool_model</span><span class="o">*</span><span class="n">scale</span><span class="p">,</span> <span class="n">vmin</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="n">vmax</span><span class="o">=</span><span class="mi">50</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">plasma</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">1</span><span class="p">,</span><span class="mi">0</span><span class="p">]</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">results</span><span class="p">[</span><span class="s1">'graphite'</span><span class="p">][</span><span class="s1">'von_mises'</span><span class="p">]</span><span class="o">*</span><span class="n">bool_model</span><span class="o">*</span><span class="n">scale</span><span class="p">,</span> <span class="n">vmin</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="n">vmax</span><span class="o">=</span><span class="mi">50</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">plasma</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">]</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">results</span><span class="p">[</span><span class="s1">'jelly'</span><span class="p">][</span><span class="s1">'von_mises'</span><span class="p">]</span><span class="o">*</span><span class="n">bool_model</span><span class="o">*</span><span class="n">scale</span><span class="p">,</span> <span class="n">vmin</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="n">vmax</span><span class="o">=</span><span class="mi">50</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">plasma</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">]</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">results</span><span class="p">[</span><span class="s1">'unobtanium'</span><span class="p">][</span><span class="s1">'von_mises'</span><span class="p">]</span><span class="o">*</span><span class="n">bool_model</span><span class="o">*</span><span class="n">scale</span><span class="o">/</span><span class="mi">4</span><span class="p">,</span> <span class="n">vmin</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="n">vmax</span><span class="o">=</span><span class="mi">50</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">plasma</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>

<span class="n">axes</span><span class="p">[</span><span class="mi">0</span><span class="p">,</span><span class="mi">0</span><span class="p">]</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="sa">f</span><span class="s1">'Control'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">0</span><span class="p">,</span><span class="mi">1</span><span class="p">]</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="sa">f</span><span class="s1">'Titanium '</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">0</span><span class="p">,</span><span class="mi">2</span><span class="p">]</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="sa">f</span><span class="s1">'Steel '</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">1</span><span class="p">,</span><span class="mi">0</span><span class="p">]</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="sa">f</span><span class="s1">'Graphite'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">]</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="sa">f</span><span class="s1">'Jelly'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">]</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="sa">f</span><span class="s1">'Unobtanium'</span><span class="p">)</span>

<span class="k">for</span> <span class="n">ax</span> <span class="ow">in</span> <span class="n">axes</span><span class="o">.</span><span class="n">flatten</span><span class="p">():</span>
  <span class="n">ax</span><span class="o">.</span><span class="n">axis</span><span class="p">(</span><span class="s1">'off'</span><span class="p">)</span>

<span class="n">fig</span><span class="o">.</span><span class="n">subplots_adjust</span><span class="p">(</span><span class="n">right</span><span class="o">=</span><span class="mf">0.8</span><span class="p">)</span>
<span class="c1"># put colorbar at desired position</span>
<span class="n">cbar_ax</span> <span class="o">=</span> <span class="n">fig</span><span class="o">.</span><span class="n">add_axes</span><span class="p">([</span><span class="mf">0.85</span><span class="p">,</span> <span class="mf">0.15</span><span class="p">,</span> <span class="mf">0.05</span><span class="p">,</span> <span class="mf">0.7</span><span class="p">])</span>
<span class="n">colorbar</span> <span class="o">=</span> <span class="n">fig</span><span class="o">.</span><span class="n">colorbar</span><span class="p">(</span><span class="n">im</span><span class="p">,</span> <span class="n">cax</span><span class="o">=</span><span class="n">cbar_ax</span><span class="p">)</span>
<span class="n">colorbar</span><span class="o">.</span><span class="n">set_label</span><span class="p">(</span><span class="s1">'Von Mises Stress (GPa)'</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>How does the implant material property affect the stress distribution within the implant?</p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="c1"># @title Simulation Results in Bone tissue</span>
<span class="c1">#Plot von Mises without stem</span>
<span class="n">_femur</span> <span class="o">=</span> <span class="p">(</span><span class="n">femur_low</span> <span class="o">&gt;</span> <span class="mi">5</span><span class="p">)</span><span class="o">.</span><span class="n">astype</span><span class="p">(</span><span class="nb">int</span><span class="p">)</span>
<span class="n">fig</span><span class="p">,</span> <span class="n">axes</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">4</span><span class="p">,</span> <span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">14</span><span class="p">,</span><span class="mi">6</span><span class="p">))</span>
<span class="c1">#'mirrored' the contralateral side to match those of the fe models using np.flip(array,axis=1)</span>
<span class="n">scale</span> <span class="o">=</span> <span class="mi">2200</span>
<span class="n">bool2</span><span class="o">=</span><span class="n">ndimage</span><span class="o">.</span><span class="n">binary_erosion</span><span class="p">(</span><span class="n">bool_control</span><span class="p">)</span>

<span class="n">im</span> <span class="o">=</span> <span class="n">axes</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">flip</span><span class="p">(</span><span class="n">results</span><span class="p">[</span><span class="s1">'control'</span><span class="p">][</span><span class="s1">'von_mises'</span><span class="p">]</span><span class="o">*</span><span class="n">bool_control</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span><span class="o">*</span><span class="n">scale</span><span class="p">,</span> <span class="n">vmin</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="n">vmax</span><span class="o">=</span><span class="mi">50</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">plasma</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">2</span><span class="p">]</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">results</span><span class="p">[</span><span class="s1">'titanium'</span><span class="p">][</span><span class="s1">'von_mises'</span><span class="p">]</span><span class="o">*</span><span class="n">_femur</span><span class="o">*</span><span class="n">scale</span><span class="p">,</span> <span class="n">vmin</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="n">vmax</span><span class="o">=</span><span class="mi">50</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">plasma</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">3</span><span class="p">]</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">results</span><span class="p">[</span><span class="s1">'steel'</span><span class="p">][</span><span class="s1">'von_mises'</span><span class="p">]</span><span class="o">*</span><span class="n">_femur</span><span class="o">*</span><span class="n">scale</span><span class="p">,</span> <span class="n">vmin</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="n">vmax</span><span class="o">=</span><span class="mi">50</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">plasma</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">1</span><span class="p">]</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">results</span><span class="p">[</span><span class="s1">'graphite'</span><span class="p">][</span><span class="s1">'von_mises'</span><span class="p">]</span><span class="o">*</span><span class="n">_femur</span><span class="o">*</span><span class="n">scale</span><span class="p">,</span> <span class="n">vmin</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="n">vmax</span><span class="o">=</span><span class="mi">50</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="n">plt</span><span class="o">.</span><span class="n">cm</span><span class="o">.</span><span class="n">plasma</span><span class="p">,</span> <span class="n">interpolation</span><span class="o">=</span><span class="s1">'nearest'</span><span class="p">)</span>
<span class="c1"># axes[1,1].imshow(results['jelly']['von_mises']*_femur*scale, vmin=0, vmax=50, cmap=plt.cm.plasma, interpolation='nearest')</span>
<span class="c1"># axes[1,2].imshow(results['unobtanium']['von_mises']*_femur*scale/4, vmin=0, vmax=50, cmap=plt.cm.plasma, interpolation='nearest')</span>

<span class="n">axes</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="sa">f</span><span class="s1">'control'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">2</span><span class="p">]</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="sa">f</span><span class="s1">'titanium model'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">3</span><span class="p">]</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="sa">f</span><span class="s1">'steel model'</span><span class="p">)</span>
<span class="n">axes</span><span class="p">[</span><span class="mi">1</span><span class="p">]</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="sa">f</span><span class="s1">'graphite model'</span><span class="p">)</span>
<span class="c1"># axes[1,1].set_title(f'jelly model')</span>
<span class="c1"># axes[1,2].set_title(f'unobtanium model')</span>

<span class="k">for</span> <span class="n">ax</span> <span class="ow">in</span> <span class="n">axes</span><span class="o">.</span><span class="n">flatten</span><span class="p">():</span>
  <span class="n">ax</span><span class="o">.</span><span class="n">axis</span><span class="p">(</span><span class="s1">'off'</span><span class="p">)</span>

<span class="n">fig</span><span class="o">.</span><span class="n">subplots_adjust</span><span class="p">(</span><span class="n">right</span><span class="o">=</span><span class="mf">0.8</span><span class="p">)</span>
<span class="c1"># put colorbar at desired position</span>
<span class="n">cbar_ax</span> <span class="o">=</span> <span class="n">fig</span><span class="o">.</span><span class="n">add_axes</span><span class="p">([</span><span class="mf">0.85</span><span class="p">,</span> <span class="mf">0.15</span><span class="p">,</span> <span class="mf">0.05</span><span class="p">,</span> <span class="mf">0.7</span><span class="p">])</span>
<span class="n">colorbar</span> <span class="o">=</span> <span class="n">fig</span><span class="o">.</span><span class="n">colorbar</span><span class="p">(</span><span class="n">im</span><span class="p">,</span> <span class="n">cax</span><span class="o">=</span><span class="n">cbar_ax</span><span class="p">)</span>
<span class="n">colorbar</span><span class="o">.</span><span class="n">set_label</span><span class="p">(</span><span class="s1">'Von Mises Stress (GPa)'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>How does the implant material property affect the stress distribution within the bone?</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Implant-Selection">Implant Selection<a class="anchor-link" href="#Implant-Selection">¶</a></h3><p>The Mechanostat is a term describing the way in which mechanical loading influences bone structure by changing the mass (amount of bone) and architecture (its arrangement) to provide a structure that resists habitual loads with an economical amount of material. As changes in the skeleton are accomplished by the processes of formation (bone growth) and resorption (bone loss), the mechanostat models the effect of influences on the skeleton by those processes, through their effector cells, osteocytes, osteoblasts, and osteoclasts.</p>
<p>The long-time clinical performance of an implant is therefore dependant on the optimum strain level within the surrounding bone. A sufficiently low strain would lead to bone loss, whereas large strain can cause damage to overstrained bone areas. Here we want to select an implant, that leads to physiological strain, or an acceptable amount of overuse around the implant. Further, it is improtant that the implant does not get overly strained to assure a long implant durability. Here we will assume that our implant strain should not exceed 500 microstrain.</p>
<p><img alt="images.png" src="data:image/png;base64,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"/></p>
<p>After running the code in the cell below, you see the strain histograms for each model.</p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="c1"># @title Mechanostat Results</span>

<span class="kn">import</span><span class="w"> </span><span class="nn">numpy</span><span class="w"> </span><span class="k">as</span><span class="w"> </span><span class="nn">np</span>
<span class="kn">import</span><span class="w"> </span><span class="nn">matplotlib.pyplot</span><span class="w"> </span><span class="k">as</span><span class="w"> </span><span class="nn">plt</span>

<span class="n">fig</span><span class="p">,</span> <span class="n">axs</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="mi">2</span><span class="p">,</span> <span class="mi">2</span><span class="p">,</span> <span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">12</span><span class="p">,</span> <span class="mi">8</span><span class="p">))</span>
<span class="n">fig</span><span class="o">.</span><span class="n">suptitle</span><span class="p">(</span><span class="s1">'Effective Strain Analysis'</span><span class="p">)</span>

<span class="n">keys</span> <span class="o">=</span> <span class="p">[</span><span class="s1">'control'</span><span class="p">,</span> <span class="s1">'graphite'</span><span class="p">,</span> <span class="s1">'titanium'</span><span class="p">,</span> <span class="s1">'steel'</span><span class="p">]</span>
<span class="n">masks_bone</span> <span class="o">=</span> <span class="p">[</span><span class="n">bool_control</span><span class="p">,</span> <span class="n">_femur</span><span class="p">,</span> <span class="n">_femur</span><span class="p">,</span> <span class="n">_femur</span><span class="p">]</span>
<span class="n">masks_stem</span> <span class="o">=</span> <span class="p">[</span><span class="n">np</span><span class="o">.</span><span class="n">zeros_like</span><span class="p">(</span><span class="n">bool_control</span><span class="p">),</span> <span class="n">stem_low</span><span class="p">,</span> <span class="n">stem_low</span><span class="p">,</span> <span class="n">stem_low</span><span class="p">]</span>

<span class="n">scale</span> <span class="o">=</span> <span class="mi">22</span> <span class="o">*</span> <span class="mi">10</span> <span class="o">**</span> <span class="mi">6</span>

<span class="k">for</span> <span class="n">key</span><span class="p">,</span> <span class="n">ax</span><span class="p">,</span> <span class="n">mask_bone</span><span class="p">,</span> <span class="n">mask_stem</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">keys</span><span class="p">,</span> <span class="n">axs</span><span class="o">.</span><span class="n">flatten</span><span class="p">(),</span> <span class="n">masks_bone</span><span class="p">,</span> <span class="n">masks_stem</span><span class="p">):</span>
    <span class="n">ym</span> <span class="o">=</span> <span class="n">fem_dict_modulus</span><span class="p">[</span><span class="n">key</span><span class="p">]</span>
    <span class="n">sed</span> <span class="o">=</span> <span class="n">results</span><span class="p">[</span><span class="n">key</span><span class="p">][</span><span class="s1">'SED'</span><span class="p">]</span>

    <span class="n">eff</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">sqrt</span><span class="p">(</span><span class="mi">2</span> <span class="o">*</span> <span class="n">sed</span> <span class="o">/</span> <span class="n">ym</span><span class="p">)</span>

    <span class="n">data_bone</span> <span class="o">=</span> <span class="n">eff</span><span class="o">.</span><span class="n">flatten</span><span class="p">()</span> <span class="o">*</span> <span class="n">scale</span> <span class="o">*</span> <span class="n">mask_bone</span><span class="o">.</span><span class="n">flatten</span><span class="p">()</span>
    <span class="n">data_stem</span> <span class="o">=</span> <span class="n">eff</span><span class="o">.</span><span class="n">flatten</span><span class="p">()</span> <span class="o">*</span> <span class="n">scale</span> <span class="o">*</span> <span class="n">mask_stem</span><span class="o">.</span><span class="n">flatten</span><span class="p">()</span>

    <span class="n">bone_hist</span><span class="p">,</span> <span class="n">bone_bins</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">histogram</span><span class="p">(</span><span class="n">data_bone</span><span class="p">,</span> <span class="n">bins</span><span class="o">=</span><span class="mi">100</span><span class="p">,</span> <span class="nb">range</span><span class="o">=</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="n">np</span><span class="o">.</span><span class="n">percentile</span><span class="p">(</span><span class="n">data_bone</span><span class="p">,</span> <span class="mi">99</span><span class="p">)),</span> <span class="n">density</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
    <span class="n">stem_hist</span><span class="p">,</span> <span class="n">stem_bins</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">histogram</span><span class="p">(</span><span class="n">data_stem</span><span class="p">,</span> <span class="n">bins</span><span class="o">=</span><span class="mi">100</span><span class="p">,</span> <span class="nb">range</span><span class="o">=</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="n">np</span><span class="o">.</span><span class="n">percentile</span><span class="p">(</span><span class="n">data_stem</span><span class="p">,</span> <span class="mi">99</span><span class="p">)),</span> <span class="n">density</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>

    <span class="n">ax</span><span class="o">.</span><span class="n">hist</span><span class="p">(</span><span class="n">bone_bins</span><span class="p">[:</span><span class="o">-</span><span class="mi">1</span><span class="p">],</span> <span class="n">bins</span><span class="o">=</span><span class="n">bone_bins</span><span class="p">,</span> <span class="n">weights</span><span class="o">=</span><span class="n">bone_hist</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'blue'</span><span class="p">,</span> <span class="n">label</span><span class="o">=</span><span class="s1">'bone'</span><span class="p">,</span> <span class="n">density</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">hist</span><span class="p">(</span><span class="n">stem_bins</span><span class="p">[:</span><span class="o">-</span><span class="mi">1</span><span class="p">],</span> <span class="n">bins</span><span class="o">=</span><span class="n">stem_bins</span><span class="p">,</span> <span class="n">weights</span><span class="o">=</span><span class="n">stem_hist</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'red'</span><span class="p">,</span> <span class="n">label</span><span class="o">=</span><span class="s1">'implant'</span><span class="p">,</span> <span class="n">density</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>

    <span class="n">max_density</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">max</span><span class="p">(</span><span class="n">bone_hist</span><span class="p">)</span>

    <span class="n">ax</span><span class="o">.</span><span class="n">axvline</span><span class="p">(</span><span class="mi">200</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">1</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'cyan'</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">axvline</span><span class="p">(</span><span class="mi">500</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">1</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'orange'</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">axvline</span><span class="p">(</span><span class="mi">2500</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">1</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'cyan'</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">axvline</span><span class="p">(</span><span class="mi">4000</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">1</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'cyan'</span><span class="p">)</span>

    <span class="n">ax</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">loc</span><span class="o">=</span><span class="s1">'lower right'</span><span class="p">)</span>

    <span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="n">key</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">set_xlabel</span><span class="p">(</span><span class="s1">'microstrain'</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">set_xlim</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span> <span class="mi">5000</span><span class="p">])</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">set_ylim</span><span class="p">([</span><span class="mf">0.0</span><span class="p">,</span> <span class="n">max_density</span> <span class="o">*</span> <span class="mf">1.1</span><span class="p">])</span>  <span class="c1"># Set y-limit based on max density</span>

    <span class="c1"># Setting text</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="mi">900</span><span class="p">,</span> <span class="n">max_density</span><span class="p">,</span> <span class="sa">r</span><span class="s1">'Physiological'</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="mi">11</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="mi">2900</span><span class="p">,</span> <span class="n">max_density</span><span class="p">,</span> <span class="sa">r</span><span class="s1">'Overuse'</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="mi">11</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="mi">4050</span><span class="p">,</span> <span class="n">max_density</span><span class="p">,</span> <span class="sa">r</span><span class="s1">'Pathological'</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="mi">11</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">annotate</span><span class="p">(</span><span class="sa">r</span><span class="s1">'Implant Overuse'</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="mi">8</span><span class="p">,</span> <span class="n">xy</span><span class="o">=</span><span class="p">(</span><span class="mi">500</span><span class="p">,</span> <span class="n">max_density</span><span class="o">*</span> <span class="mf">0.9</span><span class="p">),</span> <span class="n">xytext</span><span class="o">=</span><span class="p">(</span><span class="mi">1000</span><span class="p">,</span> <span class="n">max_density</span><span class="o">*</span> <span class="mf">0.9</span><span class="p">),</span>
                <span class="n">arrowprops</span><span class="o">=</span><span class="nb">dict</span><span class="p">(</span><span class="n">arrowstyle</span><span class="o">=</span><span class="s1">'-&gt;, head_width=0.2'</span><span class="p">,</span> <span class="n">facecolor</span><span class="o">=</span><span class="s1">'orange'</span><span class="p">,</span> <span class="n">edgecolor</span><span class="o">=</span><span class="s1">'orange'</span><span class="p">))</span>

<span class="n">plt</span><span class="o">.</span><span class="n">tight_layout</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>Why would you choose one material over another when designing an implant?</p>
</div>
</div>
</div>
</div>
</main>
</body>
</html>

@charset "utf-8";

/**
 * ----------------------------------------------------------------------------------------------
 * This is a variation of Normalize.css (http://necolas.github.io/normalize.css/)
 * ----------------------------------------------------------------------------------------------
 */
/**
 * Base
 */
*,
*:before,
*:after {
  box-sizing: border-box !important;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

html {
  font-family: sans-serif;
  -webkit-text-size-adjust: 100%;
     -moz-text-size-adjust: 100%;
      -ms-text-size-adjust: 100%;
          text-size-adjust: 100%;
  -ms-overflow-style: -ms-autohiding-scrollbar;
  overflow-x: hidden!important;
} 
body {
  margin: 0;
}

@media (max-width: 640px) {
  body {
    overflow-x: hidden!important;
  }
}

[hidden] {
  display: none !important;
}

/**
 * HTML5 display definitions
 */
article,
aside,
details,
figcaption,
figure,
footer,
header,
main,
nav,
section,
summary {
  display: block;
}


audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}

audio:not([controls]) {
  display: none;
  height: 0;
}

.color-line {
    background: linear-gradient(to right, #ffff4a 0, #fcd000 4%, #ffc112 5%, #a3d3fd 50%, #dbeeff 84%, #00d62e 119%);
    background-image: linear-gradient(to right, #ffff4a 0, #fcd000 7%, #ffc112 11%, #ff8a00 17%, #ff5f5f 23%, #ff5156 29%, #ff7ae7 35%, #ff5193 41%, #c739ff 46%, #a400e1 63%, #2eceff 76%, #0086ff 87%, #72f772 97%, #00d604);
    height: 5px;
    width: 100%;
}

/**
 * Text-level semantic
 */
:active {
  outline: none;
}

a {
  color: inherit;
  background-color: transparent;
  text-decoration: none;
}
a:active, a:hover {
  outline: 0;
}

b,
strong {
  font-weight: bold;
}

small {
  font-size: 80%;
}

p,
h1,
h2,
h3,
h4,
h5,
h6 {
  margin-top: 0;
  font-size: inherit;
  font-weight: inherit;
}

p:last-child,
h1:last-child,
h2:last-child,
h3:last-child,
h4:last-child,
h5:last-child,
h6:last-child {
  margin-bottom: 0;
}

/**
 * Embedded content
 */
img {
  max-width: 100%;
  height: auto;
  border-style: none;
  vertical-align: top;
}

/**
 * Grouping content
 */
ul,
ol {
  margin: 0;
  padding: 0;
  list-style-position: inside;
}

pre {
  overflow: auto;
}

code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 16px;
}

/**
 * Forms
 */
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}

button,
input[type=submit] {
  padding: 0;
  overflow: visible;
  background: none;
  border: none;
  border-radius: 0;
  -webkit-appearance: none;
}

.shipping-preview {
    margin: 30px 0 40px 0;
    color: #1f1f1f;
}

.shipping-preview i {
    float: left;
    margin-right: 15px;
    top: 0px;
    position: relative;
    width: 40px;
}

.shipping-preview p {
    font-size: 14px;
    line-height: 21px;
}

.shipping-preview h4 {
    font-size: 18px;
    margin-bottom: 5px;
    line-height: 1;
}

.shipping-preview h4 b {
    color: var(--accent-color);
}

.verification__stamp {
    font-size: 18px;
    position: relative;
    display: inline-block;
    top: -2px;
}

.verification__stamp:after {
    font-family: "Font Awesome 5 Free";
    font-weight: 900;
    content: "\f058";
    color: #0086FF;
}

.barradefundo {
    margin-top: 10px;
    background: var(--product-on-sale-accent);
    padding: 3px 10px 4px 10px;
    border-radius: 30px;
    color: var(--product-on-sale-color);
    font-weight: bold;
    font-size: 12px;
}

.fretefundo {
    margin: 18px 1px 54px 1px;
    background: none;
    border-radius: 50px;
    border: 2px solid #00bd58;
    padding: 10px 21px 11px 18px;
}

.product-block-list__item--description img {
    margin: 0 auto!important;
}

.security__payment p {
    color: var(--primary-button-background);
    text-align: center;
    margin: 0 auto;
    font-size: 14px;
    font-weight: 100;
    margin-top: 30px;
}

button,
select {
  text-transform: none;
}

button,
html input[type=button],
input[type=reset],
input[type=submit] {
  -webkit-appearance: button;
  cursor: pointer;
}

button[disabled],
html input[disabled] {
  cursor: default;
}

button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}

input {
  line-height: normal;
  -moz-appearance: none;
  border-radius: 0;
}

input[type=checkbox],
input[type=radio] {
  box-sizing: border-box;
  padding: 0;
}

input[type=number]::-webkit-inner-spin-button,
input[type=number]::-webkit-outer-spin-button {
  height: auto;
}

input[type=search] {
  -webkit-appearance: none;
  box-sizing: content-box;
}

input[type=search]::-webkit-search-cancel-button,
input[type=search]::-webkit-search-decoration {
  -webkit-appearance: none;
}

input::-webkit-input-placeholder, textarea::-webkit-input-placeholder {
  color: inherit;
}

input::-moz-placeholder, textarea::-moz-placeholder {
  color: inherit;
}

input:-ms-input-placeholder, textarea:-ms-input-placeholder {
  color: inherit;
}

input::-ms-input-placeholder, textarea::-ms-input-placeholder {
  color: inherit;
}

input::placeholder,
textarea::placeholder {
  color: inherit;
}

.is-tabbing input[type=radio]:focus + label {
  /* Helps improving accessibility */
  outline: 1px dotted #212121;
  outline: 5px auto -webkit-focus-ring-color;
}

fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 6px 10px 12px;
}

legend {
  border: 0;
  padding: 0;
}

textarea {
  overflow: auto;
}

optgroup {
  font-weight: bold;
}

/**
 * Tables
 */
table {
  border-collapse: collapse;
  border-spacing: 0;
}

td,
th {
  padding: 0;
}
.flickity-enabled {
  position: relative;
  overflow: visible !important;
}

.flickity-enabled:focus {
  outline: none;
}

.flickity-viewport {
  overflow: hidden;
  position: relative;
  height: 100%;
  width: 100%;
}

.flickity-slider {
  position: absolute;
  width: 100%;
  height: 100%;
}

/* draggable */
.flickity-enabled.is-draggable {
  -webkit-tap-highlight-color: transparent;
  -webkit-user-select: none;
     -moz-user-select: none;
      -ms-user-select: none;
          user-select: none;
}

.flickity-enabled.is-draggable .flickity-viewport {
  cursor: -webkit-grab;
  cursor: grab;
}

.flickity-enabled.is-draggable .flickity-viewport.is-pointer-down {
  cursor: -webkit-grabbing;
  cursor: grabbing;
}

/* page dots */
.flickity-page-dots {
  position: absolute;
  width: 100%;
  padding: 0;
  bottom: 0;
  list-style: none;
  text-align: center;
  line-height: 0;
  padding-right: 40px;
}

.flickity-rtl .flickity-page-dots {
  direction: rtl;
}

.flickity-page-dots .dot {
  position: relative;
  display: inline-block;
  width: 6px;
  height: 6px;
  margin: 0 5px;
  background: rgba(var(--text-color-rgb), 0.8);
  border-radius: 100%;
  cursor: pointer;
  transform: scale(1);
  will-change: transform;
  transition: background 0.2s ease-in-out, transform 0.2s ease-in-out;
}
.flickity-page-dots .dot::before {
  position: absolute;
  content: "";
  top: -4px;
  right: -4px;
  left: -4px;
  bottom: -4px;
}

.flickity-page-dots .dot.is-selected {
  transform: scale(1.35);
  background: var(--heading-color);
}

/* prev/next buttons */
.flickity-prev-next-button {
  position: absolute;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 50px;
  height: 50px;
  top: calc(50% - 25px);
  border-radius: 100%;
  visibility: visible;
  background: var(--flickity-arrow-color);
  opacity: 0;
  transition: all 0.2s ease-in-out;
  transform: scale(0.7);
  z-index: 1;
}
.flickity-prev-next-button:hover {
  background: var(--accent-color);
}
.flickity-prev-next-button svg {
  position: relative;
  width: 15px;
  height: 15px;
  fill: var(--secondary-background);
  vertical-align: middle;
}
.flickity-prev-next-button[disabled] {
  opacity: 0;
  visibility: hidden;
}

.flickity-prev-next-button.previous {
  left: -25px;
}
.flickity-prev-next-button.previous svg {
  left: 1px;
}

.flickity-prev-next-button.next {
  right: -25px;
}
.flickity-prev-next-button.next svg {
  left: -1px;
}

.flickity-enabled:hover .flickity-prev-next-button:not([disabled]) {
  transform: scale(1);
  opacity: 1;
}

/*
   flickity-fade

   NOTE: there is currently a bug in Flickity-fade when there are only 2 slides (https://github.com/metafizzy/flickity-fade/issues/1),
         which requires currently those ugly !important rules to fix the issue
 */
.flickity-enabled.is-fade .flickity-slider > * {
  pointer-events: none;
  z-index: 0;
  visibility: hidden;
  transition: opacity 0.3s linear, visibility 0.3s linear !important;
  opacity: 0 !important;
}

.flickity-enabled.is-fade .flickity-slider > .is-selected {
  pointer-events: auto;
  z-index: 1;
  visibility: visible;
  opacity: 1 !important;
}

/* Make sure that if Flickity is embedded within a modal, the slideshow are not with auto pointer events */
.modal[aria-hidden=true] .flickity-slider > * {
  pointer-events: none !important;
}

/* Temporary fix for slideshow, should be fixed once Flickity is fixed */
.product-gallery__carousel.is-fade .flickity-slider > * {
  transition: opacity 0.3s linear !important;
}
@-webkit-keyframes drift-fadeZoomIn {
  0% {
    transform: scale(1.2);
    opacity: 0;
  }
  100% {
    transform: scale(1);
    opacity: 1;
  }
}
@keyframes drift-fadeZoomIn {
  0% {
    transform: scale(1.2);
    opacity: 0;
  }
  100% {
    transform: scale(1);
    opacity: 1;
  }
}

@-webkit-keyframes drift-fadeZoomOut {
  0% {
    transform: scale(1);
    opacity: 1;
  }
  100% {
    transform: scale(0.5);
    opacity: 0;
  }
}

@keyframes drift-fadeZoomOut {
  0% {
    transform: scale(1);
    opacity: 1;
  }
  100% {
    transform: scale(0.5);
    opacity: 0;
  }
}

@-webkit-keyframes drift-loader-rotate {
  0% {
    transform: translate(-50%, -50%) rotate(0);
  }
  50% {
    transform: translate(-50%, -50%) rotate(-180deg);
  }
  100% {
    transform: translate(-50%, -50%) rotate(-360deg);
  }
}

@keyframes drift-loader-rotate {
  0% {
    transform: translate(-50%, -50%) rotate(0);
  }
  50% {
    transform: translate(-50%, -50%) rotate(-180deg);
  }
  100% {
    transform: translate(-50%, -50%) rotate(-360deg);
  }
}

@-webkit-keyframes drift-loader-before {
  0% {
    transform: scale(1);
  }
  10% {
    transform: scale(1.2) translateX(6px);
  }
  25% {
    transform: scale(1.3) translateX(8px);
  }
  40% {
    transform: scale(1.2) translateX(6px);
  }
  50% {
    transform: scale(1);
  }
  60% {
    transform: scale(0.8) translateX(6px);
  }
  75% {
    transform: scale(0.7) translateX(8px);
  }
  90% {
    transform: scale(0.8) translateX(6px);
  }
  100% {
    transform: scale(1);
  }
}

@keyframes drift-loader-before {
  0% {
    transform: scale(1);
  }
  10% {
    transform: scale(1.2) translateX(6px);
  }
  25% {
    transform: scale(1.3) translateX(8px);
  }
  40% {
    transform: scale(1.2) translateX(6px);
  }
  50% {
    transform: scale(1);
  }
  60% {
    transform: scale(0.8) translateX(6px);
  }
  75% {
    transform: scale(0.7) translateX(8px);
  }
  90% {
    transform: scale(0.8) translateX(6px);
  }
  100% {
    transform: scale(1);
  }
}

@-webkit-keyframes drift-loader-after {
  0% {
    transform: scale(1);
  }
  10% {
    transform: scale(1.2) translateX(-6px);
  }
  25% {
    transform: scale(1.3) translateX(-8px);
  }
  40% {
    transform: scale(1.2) translateX(-6px);
  }
  50% {
    transform: scale(1);
  }
  60% {
    transform: scale(0.8) translateX(-6px);
  }
  75% {
    transform: scale(0.7) translateX(-8px);
  }
  90% {
    transform: scale(0.8) translateX(-6px);
  }
  100% {
    transform: scale(1);
  }
}

@keyframes drift-loader-after {
  0% {
    transform: scale(1);
  }
  10% {
    transform: scale(1.2) translateX(-6px);
  }
  25% {
    transform: scale(1.3) translateX(-8px);
  }
  40% {
    transform: scale(1.2) translateX(-6px);
  }
  50% {
    transform: scale(1);
  }
  60% {
    transform: scale(0.8) translateX(-6px);
  }
  75% {
    transform: scale(0.7) translateX(-8px);
  }
  90% {
    transform: scale(0.8) translateX(-6px);
  }
  100% {
    transform: scale(1);
  }
}

.drift-zoom-pane {
  position: absolute;
  background: var(--secondary-background);
  top: 0;
  left: 0;
  height: 520px;
  width: 100%;
  max-width: 520px;
  z-index: 2;
  border: 1px solid var(--accent-color);
  border-radius: 3px;
  box-shadow: 0 1px 2px rgba(#000000, 0.2);
  /* This is required because of a bug that causes border-radius to not work with child elements in certain cases. */
  transform: translate3d(0, 0, 0);
}

.drift-zoom-pane.drift-opening {
  -webkit-animation: drift-fadeZoomIn 180ms ease-out;
          animation: drift-fadeZoomIn 180ms ease-out;
}

.drift-zoom-pane.drift-closing {
  -webkit-animation: drift-fadeZoomOut 210ms ease-in;
          animation: drift-fadeZoomOut 210ms ease-in;
}

.drift-zoom-pane.drift-inline {
  position: absolute;
  width: 150px;
  height: 150px;
  border-radius: 50%;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.3);
}

.drift-loading .drift-zoom-pane-loader {
  display: block;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 66px;
  height: 20px;
  -webkit-animation: drift-loader-rotate 1800ms infinite linear;
          animation: drift-loader-rotate 1800ms infinite linear;
}

.drift-zoom-pane-loader:before,
.drift-zoom-pane-loader:after {
  content: "";
  display: block;
  width: 20px;
  height: 20px;
  position: absolute;
  top: 50%;
  margin-top: -10px;
  border-radius: 20px;
  background: rgba(var(--text-color-rgb), 0.4);
}

.drift-zoom-pane-loader:before {
  left: 0;
  -webkit-animation: drift-loader-before 1800ms infinite linear;
          animation: drift-loader-before 1800ms infinite linear;
}

.drift-zoom-pane-loader:after {
  right: 0;
  -webkit-animation: drift-loader-after 1800ms infinite linear;
          animation: drift-loader-after 1800ms infinite linear;
  -webkit-animation-delay: -900ms;
          animation-delay: -900ms;
}

.drift-bounding-box {
  background-color: rgba(var(--accent-color-rgb), 0.05);
  border: 1px solid var(--accent-color);
  border-radius: 3px;
}

@media screen and (min-width: 641px) {
  .drift-zoom-pane.drift-inline {
    width: 240px;
    height: 240px;
  }
}

/**
 * ----------------------------------------------------------------------------
 * GENERAL
 * ----------------------------------------------------------------------------
 */

html {
  font-family: var(--text-font-family);
  font-weight: var(--text-font-weight);
  font-style: var(--text-font-style);
  font-size: calc(var(--base-text-font-size) - 1px);
  line-height: 1.87;
  color: var(--text-color);
  background: var(--background);
}

@media screen and (min-width: 641px) {
  html {
    font-size: var(--base-text-font-size);
  }
}

/**
 * ----------------------------------------------------------------------------
 * MP INFOS
 * ----------------------------------------------------------------------------
 */

#badges-product {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    flex-direction: column;
    width: 100%;
}
#badges-product .badge {
    display: flex;
    align-items: flex-start;
    justify-content: start;
    width: 100%;
}
#badges-product .badge .badge-icon {
    margin-right: 10px;
    margin-top: 5px;
    fill: rgba(0, 0, 0, 0.55);
    color: rgba(0, 0, 0, 0.55);
}
#badges-product .badge .badge-text {
    flex: 1;
    color: rgba(0, 0, 0, 0.55);
    font-size: 13px;
    margin-bottom: 5px;
}
#badges-product p {
    margin: 0;
    padding: 0;
}
#badges-product .badge .badge-text .highlight-text {
    color: #0086ff;
}

/**
 * ----------------------------------------------------------------------------
 * HEADINGS
 * ----------------------------------------------------------------------------
 */

.heading {
  font-family: var(--heading-font-family);
  font-weight: var(--heading-font-weight);
  font-style: var(--heading-font-style);
  color: var(--heading-color);
}

.h1, .rte h1 {
  margin-bottom: 20px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 24px));
  line-height: 1.45;
}

.h2, .rte h2 {
  margin-bottom: 20px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 22px));
  line-height: 1.55;
}

.h3, .rte h3 {
  margin-bottom: 14px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 20px));
  line-height: 1.6;
}

.h4, .rte h4 {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
  line-height: 1.75;
}

.h5, .rte h4 {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  line-height: 1.85;
  text-transform: uppercase;
}

.h6, .rte h5 {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
  line-height: 1.85;
  text-transform: uppercase;
}

@media screen and (min-width: 641px) {
  .h1, .rte h1 {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 26px));
    line-height: 1.43;
  }

  .h2, .rte h2 {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 25px));
    line-height: 1.5;
  }

  .h3, .rte h3 {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 21px));
    line-height: 1.5;
  }

  .h4, .rte h4 {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 18px));
    line-height: 1.7;
  }

  .h5, .rte h5 {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
    line-height: 1.75;
  }

  .h6, .rte h6 {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
    line-height: 1.7;
  }
}

/**
 * --------------------------------------------------------------------
 * TEXT HEADING
 * --------------------------------------------------------------------
 */

.text--strong, .highlight {
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
    font-weight: normal;
}}

.text--pull {
  margin-top: -0.435em;
  /* This can be applied to pull up the text and remove the effect of line-height to preserve better spacing */
}

/**
 * --------------------------------------------------------------------
 * LINKS
 * --------------------------------------------------------------------
 */

.link {
  transition: color 0.2s ease-in-out;
  
}

.link:hover,
.link:focus {
  color: var(--link-color);
}

.link--secondary:hover,
.link--secondary:focus {
  color: var(--heading-color);
}

.link--strong {
  font-weight: var(--heading-font-weight);
}

.link--accented {
  color: var(--accent-color);
}

.link--accented:hover {
  text-decoration: underline;
}

.link--underline {
  text-decoration: underline;
}

.link1 {
  transition: color 0.2s ease-in-out;
  color: var(--secondary-button-background);
  margin-botton: 2px;
  
}

.link1:hover,
.link1:focus {
  color: var(--primary-button-background);
}

.link1--secondary:hover,
.link1--secondary:focus {
  color: var(--heading-color);
}

.link1--strong {
  font-weight: var(--heading-font-weight);
}

.link1--accented {
  color: var(--accent-color);
}

.link1--accented:hover {
  text-decoration: underline;
}

.link1--underline {
  text-decoration: underline;
}


/**
 * --------------------------------------------------------------------
 * ICON
 * --------------------------------------------------------------------
 */

@-webkit-keyframes spinnerRotation {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

@keyframes spinnerRotation {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

.icon {
  display: inline-block;
  height: 1em;
  width: 1em;
  fill: currentColor;
  vertical-align: middle;
  background: none;
  pointer-events: none;
  overflow: visible;
}

.icon--search-loader {
  -webkit-animation: spinnerRotation 0.7s infinite linear;
          animation: spinnerRotation 0.7s infinite linear;
}

@media (-moz-touch-enabled: 1), (hover: none) {
  .touch-area {
    position: relative;
    background: transparent;
    /* This is used to increase the clickable area */
  }

  .touch-area::before {
    position: absolute;
    content: "";
    top: -8px;
    right: -8px;
    left: -8px;
    bottom: -8px;
    transform: translateZ(0);
    /* Needed to avoid a glitch on iOS */
  }
}

/**
 * --------------------------------------------------------------------
 * TABLE
 * --------------------------------------------------------------------
 */

.table-wrapper {
  overflow: auto;
  white-space: nowrap;
  -webkit-overflow-scrolling: touch;
}

.overflow-none {
  overflow: hidden;
}

.table,
.rte table {
  width: 100%;
  text-align: left;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.table th {
  font-weight: normal;
}

.table th,
.table td {
  padding: 16px 20px;
}

.table th:first-child,
.table td:first-child {
  padding-left: 20px;
}

.table th:last-child,
.table td:last-child {
  padding-right: 20px;
}

.table tbody tr {
  border-top: 1px solid var(--border-color);
}

.table .table__cell--right {
  text-align: right;
}

.table .table__cell--center {
  text-align: center;
}

.table--loose tbody td {
  padding-top: 26px;
  padding-bottom: 26px;
}

@media screen and (max-width: 640px) {
  /* When a table is within a card, on mobile, we need to change the margin and padding to respect the funny iOS-style border */
  .card .table {
    margin-left: 20px;
  }

  .card .table th:first-child,
  .card .table td:first-child {
    padding-left: 0;
  }
}

@media screen and (min-width: 641px) {
  .table th, .table td {
    padding: 15px 30px;
  }

  .table th:first-child,
  .table td:first-child {
    padding-left: 30px;
  }

  .table th:last-child,
  .table td:last-child {
    padding-right: 30px;
  }
}

@media screen and (min-width: 1000px) {
  .table-wrapper {
    white-space: normal;
    overflow: visible;
  }
}
html {
  overflow-x: hidden;
}

body:not(.is-tabbing) [tabindex]:focus,
body:not(.is-tabbing) label:focus,
body:not(.is-tabbing) button:focus,
body:not(.is-tabbing) input:focus,
body:not(.is-tabbing) select:focus,
body:not(.is-tabbing) textarea:focus {
  outline: none;
}

.is-locked {
  overflow-y: hidden;
}

.visually-hidden {
  position: absolute !important;
  overflow: hidden;
  clip: rect(0 0 0 0);
  height: 1px;
  width: 1px;
  margin: -1px;
  padding: 0;
  border: 0;
}

.container {
  max-width: 1480px;
  margin-left: auto;
  margin-right: auto;
  padding: 0 var(--mobile-container-gutter);
}

.container--medium {
  max-width: 1150px;
}

.container--narrow {
  max-width: 800px;
}

.container--extra-narrow {
  max-width: 630px;
}

.container--giga-narrow {
  max-width: 520px;
}

.anchor {
  display: block;
  position: relative;
  top: -75px;
  visibility: hidden;
}

@supports (--css: variables) {
  .anchor {
    top: calc(-1 * var(--header-height));
  }
}

.js .no-js {
  display: none !important;
}

@media screen and (max-width: 640px) {
  .container--flush {
    padding: 0;
  }

  .container--unflush {
    padding: 0 var(--mobile-container-gutter);
  }
}

@media screen and (min-width: 641px) {
  .container {
    padding: 0 var(--desktop-container-gutter);
  }
}
/**
 * --------------------------------------------------------------------
 * ASPECT RATIO
 * --------------------------------------------------------------------
 */

.aspect-ratio {
  position: relative;
  margin-left: auto;
  margin-right: auto;
}

.image-border-radius > img {
  overflow: auto;
  border-radius: 50px;
}

.image-principal-border-radius {
  overflow: auto;
  border-radius: 8px;
}

/* The aspect-ratio can also contain a native HTML5 video element */
.aspect-ratio img,
.aspect-ratio video,
.aspect-ratio svg {
  position: absolute;
  height: 100%;
  width: 100%;
  max-width: 100%;
  max-height: 100%;
  top: 0;
  left: 0;
}

.aspect-ratio--square {
  padding-bottom: 100% !important;
}

.aspect-ratio--short {
  padding-bottom: 75% !important;
}

.aspect-ratio--tall {
  padding-bottom: 150% !important;
}

.aspect-ratio--square img,
.aspect-ratio--short img,
.aspect-ratio--tall img {
  position: absolute;
  width: auto;
  height: auto;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
@supports ((-o-object-fit: contain) or (object-fit: contain)) {
  .aspect-ratio--square img,
  .aspect-ratio--short img,
  .aspect-ratio--tall img {
    width: 100%;
    height: 100%;
    -o-object-fit: contain;
       object-fit: contain;
  }
}

/**
 * --------------------------------------------------------------------
 * LAZY LOADING
 * --------------------------------------------------------------------
 */

@-webkit-keyframes lazyLoader {
  0%, 100% {
    transform: translateX(-50%);
  }
  50% {
    transform: translateX(100%);
  }
}

@keyframes lazyLoader {
  0%, 100% {
    transform: translateX(-50%);
  }
  50% {
    transform: translateX(100%);
  }
}
img.lazyload[data-sizes=auto] {
  width: 100%;
  /* this is needed to help LazySizes calculate the correct size */
}

.image--fade-in {
  opacity: 0;
  transition: opacity 0.3s ease-in-out;
}

.lazyloaded.image--fade-in,
.no-js [data-bgset],
.no-js [data-bg] {
  opacity: 1;
}

.lazyload__loader {
  position: absolute;
  display: block;
  height: 2px;
  width: 40px;
  left: 0;
  bottom: 0;
  right: 0;
  top: 0;
  opacity: 0;
  visibility: hidden;
  margin: auto;
  pointer-events: none;
  background-color: var(--border-color);
  z-index: -1;
  transition: all 0.2s ease-in-out;
  overflow: hidden;
}

.lazyload__loader::after {
  position: absolute;
  content: "";
  bottom: 0;
  right: 0;
  top: 0;
  height: 100%;
  width: 200%;
  background-color: var(--text-color);
}

.lazyloading ~ .lazyload__loader {
  opacity: 1;
  visibility: visible;
  z-index: 1;
}
.lazyloading ~ .lazyload__loader::after {
  -webkit-animation: lazyLoader 3s infinite;
          animation: lazyLoader 3s infinite;
  -webkit-animation-timing-function: cubic-bezier(0.43, 0.43, 0.25, 0.99);
          animation-timing-function: cubic-bezier(0.43, 0.43, 0.25, 0.99);
}

/**
 * --------------------------------------------------------------------
 * PLACEHOLDER SVG
 * --------------------------------------------------------------------
 */

.placeholder-background {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.placeholder-svg {
  display: block;
  fill: var(--text-color);
  background-color: rgba(var(--text-color-rgb), 0.1);
  width: 100%;
  height: 100%;
  max-width: 100%;
  max-height: 100%;
}

.placeholder-svg--inverted {
  fill: var(--background);
  background-color: var(--text-color);
  fill-opacity: 0.5;
}
/* This is just a foundation for an ultra simplistic grid */

.grid {
  display: flex;
  flex-wrap: wrap;
  list-style: none;
  padding: 0;
  margin: 0 0 -18px -18px;
  font-size: 0;
}

.grid__cell {
  box-sizing: border-box;
  display: inline-block;
  width: 100%;
  padding: 0 0 18px 18px;
  margin: 0;
  vertical-align: top;
  font-size: 1rem;
}

.grid__cell--top {
  align-self: flex-start;
}

.grid__cell--middle {
  align-self: center;
}

.grid__cell--bottom {
  align-self: flex-end;
}

@media screen and (min-width: 641px) {
  .grid {
    margin: 0 0 -30px -30px;
  }

  .grid__cell {
    padding: 0 0 30px 30px;
  }
}

.\31\/1 {
  width: 100%;
}

.\31\/2 {
  width: 50%;
}

.\31\/3 {
  width: 33.333333%;
}

.\31\/4 {
  width: 25%;
}

.\31\/5 {
  width: 20%;
}

.\31\/6 {
  width: 16.666667%;
}

@media screen and (max-width: 640px) {
  .hidden-phone {
    display: none !important;
  }

  .\31\/1--phone {
    width: 100%;
  }

  .\31\/2--phone {
    width: 50%;
  }

  .\31\/3--phone {
    width: 33.333333%;
  }

  .\31\/4--phone {
    width: 25%;
  }

  .\31\/5--phone {
    width: 20%;
  }

  .\31\/6--phone {
    width: 16.666667%;
  }
}

@media screen and (min-width: 641px) and (max-width: 999px) {
  .hidden-tablet {
    display: none !important;
  }

  .\31\/1--tablet {
    width: 100%;
  }

  .\31\/2--tablet {
    width: 50%;
  }

  .\31\/3--tablet {
    width: 33.333333%;
  }

  .\31\/4--tablet {
    width: 25%;
  }

  .\31\/5--tablet {
    width: 20%;
  }

  .\31\/6--tablet {
    width: 16.666667%;
  }
}

@media screen and (min-width: 641px) {
  .hidden-tablet-and-up {
    display: none !important;
  }

  .\31\/1--tablet-and-up {
    width: 100%;
  }

  .\31\/2--tablet-and-up {
    width: 50%;
  }

  .\31\/3--tablet-and-up {
    width: 33.333333%;
  }

  .\31\/4--tablet-and-up {
    width: 25%;
  }

  .\31\/5--tablet-and-up {
    width: 20%;
  }

  .\31\/6--tablet-and-up {
    width: 16.666667%;
  }
}

@media screen and (max-width: 999px) {
  .hidden-pocket {
    display: none !important;
  }

  .\31\/1--pocket {
    width: 100%;
  }

  .\31\/2--pocket {
    width: 50%;
  }

  .\31\/3--pocket {
    width: 33.333333%;
  }

  .\31\/4--pocket {
    width: 25%;
  }

  .\31\/5--pocket {
    width: 20%;
  }

  .\31\/6--pocket {
    width: 16.666667%;
  }
}

@media screen and (min-width: 1000px) and (max-width: 1279px) {
  .hidden-lap {
    display: none !important;
  }

  .\31\/1--lap {
    width: 100%;
  }

  .\39\/12--lap {
    width: 75%;
  }

  .\32\/3--lap {
    width: 66.666666%;
  }

  .\31\/2--lap {
    width: 50%;
  }

  .\31\/3--lap {
    width: 33.333333%;
  }

  .\31\/4--lap {
    width: 25%;
  }

  .\31\/5--lap {
    width: 20%;
  }

  .\31\/6--lap {
    width: 16.666667%;
  }
}

@media screen and (min-width: 1000px) {
  .hidden-lap-and-up {
    display: none !important;
  }

  .\31\/1--lap-and-up {
    width: 100%;
  }

  .\39\/12--lap-and-up {
    width: 75%;
  }

  .\32\/3--lap-and-up {
    width: 66.666666%;
  }

  .\31\/2--lap-and-up {
    width: 50%;
  }

  .\31\/3--lap-and-up {
    width: 33.333333%;
  }

  .\31\/4--lap-and-up {
    width: 25%;
  }

  .\31\/5--lap-and-up {
    width: 20%;
  }

  .\31\/6--lap-and-up {
    width: 16.666667%;
  }
}

@media screen and (min-width: 1280px) {
  .hidden-desk {
    display: none !important;
  }

  .\31\/1--desk {
    width: 100%;
  }

  .\39\/12--desk {
    width: 75%;
  }

  .\32\/3--desk {
    width: 66.666666%;
  }

  .\31\/2--desk {
    width: 50%;
  }

  .\31\/3--desk {
    width: 33.333333%;
  }

  .\31\/4--desk {
    width: 25%;
  }

  .\31\/5--desk {
    width: 20%;
  }

  .\31\/6--desk {
    width: 16.666667%;
  }
}

@media screen and (min-width: 1440px) {
  .hidden-wide {
    display: none !important;
  }

  .\31\/1--wide {
    width: 100%;
  }

  .\39\/12--wide {
    width: 75%;
  }

  .\32\/3--wide {
    width: 66.666666%;
  }

  .\31\/2--wide {
    width: 50%;
  }

  .\31\/3--wide {
    width: 33.333333%;
  }

  .\31\/4--wide {
    width: 25%;
  }

  .\31\/5--wide {
    width: 20%;
  }

  .\31\/6--wide {
    width: 20%;
  }
}

/**
 * --------------------------------------------------------------------
 * BLOCK LIST
 *
 * This component is used by various elements on mobile to allow items
 * to becomes scrollable on mobile and small tablets
 * --------------------------------------------------------------------
 */

.block-list {
  display: flex;
  flex-flow: column nowrap;
  margin: 0 -7px -20px -7px;
}

.block-list--no-flush.block-list--no-flush {
  margin-bottom: 0; /* The double class is to increase specifity and avoid to set it at each breakpoint */
}

.block-list__item {
  display: flex; /* Allow to stretch the content if different block items have different height */
}

/* Unfortunately IE11 does not like nested flex items, so for IE11, we revert to display: block */
@media screen and (-ms-high-contrast: active), (-ms-high-contrast: none) {
  .block-list__item {
    display: block;
  }
}

.block-list__item > :first-child {
  margin: 0 7px 20px 7px;
  flex: 1 0 0%;
  border-radius: 10px
}

@media only screen and (max-width: 999px){
  .mobhide {
      display: none !important;
  }
  
  .flex{
  	flex-direction: column;
  }
  
  .metade{
  	width: 100%!important;
  }
  
  .frete{
    margin-left: 0;
  }
  
  .product-form__info-content .price-list, .product-form__info-content .product-meta__label-list{
  	margin-left: 0;
  }
}

.metade{
 	width: 48%; 
}

.metade span {
	width: 100%;
    background: none;
    border: 2px solid var(--product-on-sale-accent);
    color: var(--product-on-sale-accent);
}

.metade span:hover {
    background: var(--product-on-sale-accent);
    border: 2px solid var(--product-on-sale-accent);
    color: white;
	width: 100%;
}

.flex{
	display: flex;
      width: 100%;
    justify-content: space-between;
}


@media screen and (max-width: 999px) {
  .scroller .block-list {
    white-space: nowrap;
    flex-flow: row nowrap;
  }

  .scroller .block-list::before {
    content: "";
    flex: 0 0 var(--mobile-container-gutter);
  }

  .scroller .block-list::after {
    content: "";
    flex: 0 0 calc(var(--mobile-container-gutter) - 7px);
  }

  .scroller .block-list__item {
    flex: 0 0 auto;
    white-space: normal;
    scroll-snap-align: center;
  }
}

@media screen and (max-width: 640px) {
  .scroller .block-list__item {
    width: 81%;
  }
}

@media screen and (min-width: 641px) and (max-width: 999px) {
  .scroller .block-list__item {
    width: 56%;
  }

  .scroller .block-list::before {
    flex: 0 0 var(--desktop-container-gutter);
  }

  .scroller .block-list::after {
    flex: 0 0 calc(var(--desktop-container-gutter) - 15px);
  }
}

@media screen and (min-width: 641px) {
  .block-list {
    flex-direction: row;
    flex-wrap: wrap;
    margin: 0 -15px -30px -15px;
  }

  .block-list__item > :first-child {
    margin: 0 15px 30px 15px;
  }
}

@media screen and (min-width: 1000px) {
  .block-list {
    white-space: normal;
  }

  .block-list::before,
  .block-list::after {
    display: none;
  }

  .block-list__item--grow {
    flex-grow: 1;
  }
}

/**
 * VARIATIONS
 */

.block-list--loose {
  margin-bottom: -45px;
}
.block-list--loose .block-list__item > :first-child {
  margin-bottom: 45px;
}

@media screen and (min-width: 641px) {
  .block-list--loose {
    margin-bottom: -60px;
  }

  .block-list--loose .block-list__item > :first-child {
    margin-bottom: 60px;
  }
}
/**
 * --------------------------------------------------------------------
 * ARTICLE ITEM
 * --------------------------------------------------------------------
 */

.article-item__image-container {
  display: block;
  margin-bottom: 15px;
  border-radius: 3px;
  overflow: hidden;
}

.article-item__image-container--placeholder {
  height: 200px;
}

.article-item__image {
  -o-object-fit: cover;
     object-fit: cover;
  -o-object-position: center;
     object-position: center;
  font-family: "object-fit: cover; object-position: center";
  /* IE11 polyfill */
  transform: scale(1.01);
  /* The 1.01 is necessary to avoid some rounding issues on Chrome */
  transition: opacity 0.2s ease-in-out, transform 0.95s cubic-bezier(0.25, 0.46, 0.45, 0.94);
}

@media (-moz-touch-enabled: 0),(hover: hover) {
  .features--animate-zoom .article-item:hover .article-item__image {
    transform: scale(1.07);
  }

  .article-item:hover .article-item__title {
    color: var(--accent-color);
  }
}

.article-item__meta {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
}

.article-item__meta-item:not(:last-child)::after {
  display: inline-block;
  content: "";
  width: 5px;
  height: 5px;
  margin: -1px 10px 0 10px;
  border-radius: 100%;
  background: rgba(var(--text-color-rgb), 0.4);
  vertical-align: middle;
}

.article-item__title {
  margin-bottom: 4px;
}

.article-item__excerpt {
  margin-top: 12px;
}

@media screen and (max-width: 999px) {
  .article-item:not(:last-child) {
    padding-bottom: 20px;
  }

  .scroller .article-item:not(:last-child) {
    padding-bottom: 0;
  }
}

@media screen and (min-width: 641px) {
  .article-item__meta {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
  }
}

@media screen and (min-width: 1000px) {
  .blog-container--without-sidebar .article-item--featured .aspect-ratio {
    padding-bottom: 40% !important;
    /* We have a small exception to make image smaller in case there is no sidebar on the featured item */
  }
}

@media screen and (min-width: 1280px) {
  .article-item__meta-item + .article-item__meta-item::before {
    margin: 0 14px;
  }
}

/**
 * --------------------------------------------------------------------
 * ARTICLE DETAILS
 * --------------------------------------------------------------------
 */

.article__image-wrapper {
  position: relative;
  width: calc(100% + (var(--mobile-container-gutter) * 2));
  left: calc(-1 * var(--mobile-container-gutter));
  margin-top: 4px;
  z-index: 1;
}

.article__toolbar,
.article__toolbar-item {
  display: flex;
  align-items: center;
}

.article__toolbar {
  justify-content: space-between;
}

.article__toolbar-item .icon--bi-comment {
  width: 24px;
  height: 23px;
  margin-right: 15px;
}

.article__share-label {
  margin-right: 20px;
}

.article__comments-count {
  color: var(--heading-color);
}

.article__inner {
  max-width: 680px;
  margin: 40px auto 100px auto;
}

.article__content {
  margin-bottom: 2.8em;
}

.article__aside {
  margin-bottom: 50px;
}

.article__aside-item {
  display: flex;
  align-items: center;
}

.article__aside-item + .article__aside-item {
  margin-top: 20px;
}

.article__navigation {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 41px 0;
  border-top: 1px solid var(--border-color);
  border-bottom: 1px solid var(--border-color);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.article__navigation svg {
  width: 8px;
  height: 12px;
  vertical-align: -1px;
}

.article__navigation--align-right {
  justify-content: flex-end;
}

.article__navigation-item--prev svg {
  margin-right: 12px;
}

.article__navigation-item--next svg {
  margin-left: 12px;
}

.article__comment-list {
  margin-top: 50px;
}

.article__comment-list-heading {
  margin-bottom: 30px;
}

.article-comment {
  display: flex;
  align-items: flex-start;
  margin-bottom: 32px;
}

.article-comment:first-child {
  margin-top: 30px;
}

.article-comment:last-child {
  margin-bottom: 0;
}

.article-comment__gravatar {
  border-radius: 100%;
  max-width: 50px;
  margin: 5px 22px 0 0;
}

.article-comment__author {
  margin-bottom: 0;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.article-comment__date {
  display: block;
  margin-bottom: 12px;
  font-style: italic;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.article__comment-form {
  margin-top: 50px;
}

.article__comment-list + .article__comment-form {
  margin-top: 70px;
}

.article__comment-form-title {
  margin-bottom: 12px;
}

.article__moderated-note {
  font-style: italic;
}

.article__comment-form-wrapper {
  margin-top: 32px;
}

@media screen and (min-width: 641px) {
  .article__image-wrapper {
    position: relative;
    width: 100%;
    left: 0;
    border-radius: 3px 3px 0 0;
    margin: 0 0 -1px 0;
    /* This -1 allows to cover the border of the card */
    overflow: hidden;
  }

  .article__image-wrapper + .card {
    border-top-left-radius: 0;
    border-top-right-radius: 0;
  }

  .article__inner {
    margin-top: 60px;
  }

  .article__content {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
  }

  .article-comment {
    margin-bottom: 42px;
  }

  .article-comment__author {
    margin-bottom: 2px;
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
  }

  .article-comment__date {
    margin-bottom: 12px;
  }
}

/**
 * --------------------------------------------------------------------
 * BLOG
 * --------------------------------------------------------------------
 */

.shopify-section__article {
  max-width: 980px;
}

.blog-sidebar__item {
  margin-bottom: 45px;
}

.blog-sidebar__item--products,
.blog-sidebar__item--newsletter {
  margin-bottom: 50px;
  /* we add a bit of additional spacing to those two are the content is not made of text that brings its own spacing due to line-height */
}

.blog-sidebar__item:first-child:not(.blog-sidebar__item--newsletter) {
  margin-top: -0.435em;
}

.blog-sidebar__block-title {
  margin-bottom: 20px;
}

@media screen and (min-width: 1000px) {
  /* From tablet and up the sidebar is on the right */
  .blog-container {
    display: flex;
    align-items: flex-start;
    justify-content: center;
  }

  .shopify-section__blog-posts,
  .shopify-section__article {
    /* IE11 has issue with the shorthand form */
    flex-grow: 1;
    flex-shrink: 0;
    flex-basis: 0;
  }

  .blog-sidebar {
    width: 300px;
    margin-left: 60px;
  }
}

@media screen and (min-width: 641px) and (max-width: 999px) {
  .blog-sidebar {
    width: 350px;
    margin-left: auto;
    margin-right: auto;
  }
}

@media screen and (min-width: 1280px) {
  .blog-sidebar {
    width: 350px;
    margin-left: 70px;
  }
}

/* Newsletter */
.blog-sidebar__item--newsletter {
  padding: 30px 20px 30px 20px;
  border-radius: 3px;
  text-align: center;
}

.blog-sidebar__item--newsletter .heading {
  color: inherit;
}

@media screen and (max-width: 640px) {
  /* On mobile it goes to the edge */
  .blog-sidebar__item--newsletter {
    border-radius: 0;
    margin-left: calc(-1 * var(--mobile-container-gutter));
    margin-right: calc(-1 * var(--mobile-container-gutter));
  }
}

/* Featured blog posts */
.blog-sidebar__post-list {
  list-style: none;
}

.blog-sidebar__post-item {
  display: flex;
  align-items: flex-start;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.features--animate-zoom .blog-sidebar__post-item:hover .blog-sidebar__post-image {
  transform: scale(1.1);
}

.blog-sidebar__post-item:hover .blog-sidebar__post-title {
  color: var(--accent-color);
}

.blog-sidebar__post-item + .blog-sidebar__post-item {
  margin-top: 30px;
}

.blog-sidebar__post-image-wrapper {
  position: relative;
  display: block;
  flex-shrink: 0;
  width: 100px;
  margin-right: 20px;
}

.blog-sidebar__post-image,
.blog-sidebar__post-placeholder {
  min-height: 80px;
  transition: transform 0.65s cubic-bezier(0.25, 0.46, 0.45, 0.94);
}

.blog-sidebar__post-image-overflow {
  overflow: hidden;
  border-radius: 3px;
}

.blog-sidebar__post-title {
  position: relative;
  display: block;
  display: -webkit-box;
  margin-top: 2px;
  line-height: 1.55;
  overflow: hidden;
  text-overflow: ellipsis;
  -webkit-line-clamp: 2;
  /* autoprefixer: ignore next */
  -webkit-box-orient: vertical;
}

.blog-sidebar__post-meta {
  margin-top: 4px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
}

.blog-sidebar__post-meta-item:not(:last-child)::after {
  display: inline-block;
  content: "";
  width: 5px;
  height: 5px;
  margin: 0 10px;
  border-radius: 100%;
  background: rgba(var(--text-color-rgb), 0.4);
  vertical-align: middle;
}

.blog-sidebar__post-list--ranked {
  counter-reset: post-ranking 0;
}

.blog-sidebar__post-list--ranked .blog-sidebar__post-image-wrapper::before {
  position: absolute;
  content: counter(post-ranking);
  top: calc(50% - 16px);
  left: -16px;
  border: 2px solid var(--background);
  height: 32px;
  width: 32px;
  line-height: 28px;
  /* 32px minus 4px of border */
  text-align: center;
  border-radius: 100%;
  background: var(--accent-color);
  color: var(--secondary-background);
  font-weight: var(--text-font-bolder-weight);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  counter-increment: post-ranking;
  z-index: 1;
}

/* Products */
.blog-sidebar__item--products .product-item {
  width: 100%;
}

.blog-sidebar__item--products .product-item__image-wrapper {
  width: 75px !important;
}

.blog-sidebar__item--products .product-item__price-list > .price {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
}

@media screen and (max-width: 640px) {
  /* For the sidebar the products display slightly differently as they do not goes edge to edge */
  .blog-sidebar__item--products .product-list--horizontal {
    border: 1px solid var(--border-color);
    border-radius: 3px;
  }
}

/* Linklists */
.blog-sidebar__linklist {
  list-style: none;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.blog-sidebar__link-item {
  padding: 14px 0;
  border-bottom: 1px solid var(--form-border-color);
  line-height: 1.5;
}

.blog-sidebar__link-item:first-child {
  padding-top: 5px;
}

.blog-sidebar__link-item:last-child {
  border-bottom: none;
  padding-bottom: 0;
}

.blog-sidebar__link-item > a {
  display: block;
}
.button {
  position: relative;
  display: inline-block;
  padding: 0px 30px;
  padding-bottom: 3px;
  line-height: 45px;
  border-radius: 40px;
  text-align: center;
  font-weight: var(--text-font-bolder-weight);
  font-size: var(--base-text-font-size);
  cursor: pointer;
  transition: background 0.25s ease-in-out, color 0.25s ease-in-out, box-shadow 0.25s ease-in-out;
}

.button2 {
  position: relative;
  display: inline-block;
  padding: 0 30px;
  line-height: 48px;
  border-radius: 2px;
  width: 75% !important;
  text-align: center;
  font-weight: var(--text-font-bolder-weight);
  font-size: var(--base-text-font-size);
  cursor: pointer;
  transition: background 0.25s ease-in-out, color 0.25s ease-in-out, box-shadow 0.25s ease-in-out;
}

.button[disabled] {
  cursor: not-allowed;
}

.button--extra-small {
  padding: 0 15px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  line-height: 34px;
}

.button--small {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  line-height: 42px;
}

.button--large {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
  line-height: 55px;
}

.button--extra-large {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 18px));
  line-height: 60px;
}

.button--primary-add {
  outline: 2px solid var(--secondary-button-background);
  outline-offset: -2px;
  color: var(--secondary-button-background);
  margin-top: 0px!important;
}

.button--primary-add:hover {
  background: var(--secondary-button-background);
  color: var(--secondary-button-text-color);
}

.button--primary {
  background: var(--primary-button-background);
  color: var(--primary-button-text-color);
}

.button--primary:hover {
  background: rgba(var(--primary-button-background-rgb), 0.8);
  animation: shake 0.82s cubic-bezier(.36,.07,.19,.97) both;
  transform: translate3d(0, 0, 0);
  perspective: 1000px;
}

.button2--primary {
  background: var(--primary-button-background);
  color: var(--primary-button-text-color);
}

.button2--primary:hover {
  background: rgba(var(--primary-button-background-rgb), 0.8);
}

.button2--primary::after {
    content: "";
    height: 0px;
  width: 75% !important;
    display: block;
    background: var(--primary-button-background);
    filter: brightness(0.8);
    margin: -4px -30px;
    top: 0px;
    position: relative;
    border-bottom-left-radius: 8px;
    border-bottom-right-radius: 8px;
}

.button2--primary {
  background: var(--primary-button-background);
  color: var(--primary-button-text-color);
  height: 0px;
}

.button2--primary:hover {
  background: rgba(var(--primary-button-background-rgb), 0.8);
}

.button2--primary::after {
    content: "";
    height: 0px;
    display: block;
    background: var(--primary-button-background);
    filter: brightness(0.8);
    margin: -4px -30px;
    top: 0px;
    position: relative;
    border-bottom-left-radius: 8px;
    border-bottom-right-radius: 8px;
}

.button--secondary {
  background: var(--secondary-button-background);
  color: var(--secondary-button-text-color);
}

.button--secondary:hover {
  background: rgba(var(--secondary-button-background-rgb), 0.8);
}

.button--ternary {
  color: var(--accent-color);
  box-shadow: 0 0 0 1px var(--border-color) inset;
  /* use box-shadow instead of border to not create additional space */
}

.button--ternary:hover {
  background: rgba(var(--border-color-rgb), 0.5);
  color: var(--text-color);
}

.button--transparent {
  color: var(--text-color);
  box-shadow: 0 0 0 1px var(--border-color) inset;
  /* use box-shadow instead of border to not create additional space */
}

.button--transparent:hover {
  background: var(--primary-button-background);
  color: var(--primary-button-text-color);
  box-shadow: 0 0 0 1px var(--primary-button-background) inset;
}

/* The color scheme is a bit hacky here, but basically this button is only used for the sold out button, so we re-use the
   sold out label to create some consistence */
.button--disabled {
  background: var(--product-sold-out-color);
  box-shadow: 0 0 0 1px var(--product-sold-out-color) inset; /* use box-shadow instead of border to not create additional space */
  color: var(--secondary-background);
}

.button--full {
  width: 100%;
}

.button--min-width {
  min-width: 200px;
}

.button--floating {
  transition: box-shadow 0.2s ease-in-out;
}

.button--floating:hover {
  box-shadow: 0 2px 2px 2px rgba(0, 0, 0, 0.06);
}

/**
 * --------------------------------------------------------------------
 * BUTTON WRAPPER
 * --------------------------------------------------------------------
 */

.button-wrapper {
  text-align: center;
}

/**
 * --------------------------------------------------------------------
 * DROPMETA CSS
 * --------------------------------------------------------------------
 */

.tempofrete {
    border-radius: 16px;
    padding: 14px 15px 14px 18px;
    background: #f2f2f5;
}

/**
 * --------------------------------------------------------------------
 * BUTTON STACK
 * --------------------------------------------------------------------
 */

.button-stack {
  display: flex;
  flex-direction: column;
}

.button-stack > .button + .button {
  margin-top: 10px;
}

/**
 * --------------------------------------------------------------------
 * BUTTON GROUP
 * --------------------------------------------------------------------
 */

.button-group {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  margin: -5px;
}

.button-group > * {
  margin: 5px;
}

.button-group--fit > * {
  flex: 1 0 0;
  padding-left: 15px;
  padding-right: 15px;
}

.button-group--loose {
  margin: -10px;
}

.button-group--loose > * {
  margin: 10px;
}
/**
 * --------------------------------------------------------------------
 * Standard card
 * --------------------------------------------------------------------
 */

.card {
  position: relative;
  margin-bottom: 18px;
  background: var(--secondary-background);
}

.card__header {
  position: relative;
  padding: 20px 20px 0 20px;
}

.card__header--flex {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.card__title {
  margin-bottom: 0;
  text-align: center;
}

.card__subtitle {
  margin-bottom: 14px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
}

.card__subtitle:first-child {
  margin-top: -0.435em;
}

.card__title--small {
  text-align: center;
  margin-bottom: 10px;
  margin-top: -2px;
  /* Those kind of micro-adjustments rules are not really beautiful, but it's here to satisfy need of pixel perfect... */
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 20px));
}

.card__section,
.card__collapsible-button {
  position: relative;
  padding: 24px;
}

.card__collapsible-button {
  display: flex;
  align-items: center;
  justify-content: space-between;
  text-align: left;
  width: 100%;
  cursor: pointer;
}
.card__collapsible-button .plus-button {
  margin-left: 10px;
  color: var(--heading-color);
}

.card__section + .card__section::before {
  position: absolute;
  display: block;
  content: "";
  width: calc(100% - var(--mobile-container-gutter));
  top: 0;
  right: 0;
  height: 1px;
  background: var(--border-color);
}

.card__section--no-padding {
  padding: 0 !important;
}

.card__collapsible {
  height: 0;
  overflow: hidden;
  transition: 0.3s ease-in-out;
}

.card__collapsible-content {
  padding: 0 20px 20px 20px;
}

.card__separator {
  width: calc(100% + var(--mobile-container-gutter));
  margin: 20px 0;
  border: none;
  border-top: 1px solid var(--border-color);
}

.card__navigation {
  display: flex;
  justify-content: space-between;
  margin-bottom: 12px;
  margin-top: -3px; /* Yeah, designers like making things simple complicated :D */
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.card__navigation-breadcrumb svg {
  margin-right: 12px;
  width: 8px;
  height: 12px;
  vertical-align: -1px;
}

.card__linklist {
  list-style: none;
}

.card__linklist-item {
  display: block;
  padding: 2px 0;
  text-align: left;
}

@media screen and (max-width: 640px) {
  .card {
    border-radius: 0; /* cards expand full-width on mobile */
  }

  .card__section--flex .button {
    margin-top: 20px;
    width: 100%;
  }
}

@media screen and (max-width: 999px) {
  .card--collapsed {
    margin-top: -18px !important;
    border-top: none !important;
    box-shadow: 0 -1px var(--secondary-background); /* allows to hide the border of the previous card */
  }

  .card--collapsed .card__header,
  .card--collapsed .card__section {
    padding-top: 0;
  }
}

@media screen and (min-width: 641px) and (max-width: 999px) {
  .card--collapsed {
    margin-top: -30px !important;
    border-radius: 0 0 3px 3px;
  }
}

@media screen and (min-width: 641px) {
  .card {
    margin-bottom: 30px;
    border-radius: 25px;
    box-shadow: 0px 5px 10px 0px #00000008;
  }

  .card__header {
    padding: 30px 30px 0 30px;
  }

  .card__section,
  .card__collapsible-button {
    padding: 35px;
  }

  .card__section + .card__section::before {
    width: 100%;
  }

  .card__section--flex {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .card__subtitle {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
  }

  .card__collapsible-content {
    padding: 0 30px 30px 30px;
  }

  .card__separator {
    width: 100%;
    margin: 24px 0;
  }

  .card__header--tight {
    padding-top: 20px;
  }

  .card__section--tight {
    padding: 20px 25px;
  }

  .card__section--tight .card__separator {
    margin: 20px 0;
  }

  .card__navigation {
    margin-bottom: 15px;
  }
}

@media screen and (min-width: 1000px) {
  .card--sticky {
    position: -webkit-sticky;
    position: sticky;
    top: 0;
    margin-bottom: 0;
  }

  @supports (--css: variables) {
    .card--sticky {
      top: calc((var(--header-height) + 30px) * 0);
      top: calc((var(--header-height) + 30px) * var(--header-is-sticky, 0));
    }
  }
}

.card__section .rte .button:last-child {
  margin-bottom: 15px;
}
/**
 * --------------------------------------------------------------------
 * Mini-cart
 * --------------------------------------------------------------------
 */

.mini-cart {
  position: absolute;
  width: 100vw;
  height: 100vh;
  left: 0;
  top: 100%;
  max-height: 0;
  /* This is needed to fix a bug on iOS, DO NOT REMOVE */
  background: var(--secondary-background);
  color: var(--text-color);
  z-index: 1;
  visibility: hidden;
  opacity: 0;
  transform: scale(0.9);
  transition: opacity 0.25s ease-in-out, transform 0.25s ease-in-out, visibility 0.25s ease-in-out, max-height 0s linear 0.25s;
  will-change: transform;
}

.mini-cart[aria-hidden=false] {
  visibility: visible;
  opacity: 1;
  transform: scale(1);
  transition: opacity 0.4s cubic-bezier(0, 1, 0.4, 1), transform 0.4s cubic-bezier(0.18, 1.25, 0.4, 1), visibility 0.4s linear;
}

.mini-cart .icon--nav-triangle-borderless {
  position: absolute;
  width: 38px;
  height: 8px;
  right: 6px;
  bottom: 100%;
  z-index: 2;
  -webkit-filter: drop-shadow(0 -2px 2px rgba(0, 0, 0, 0.12));
          filter: drop-shadow(0 -2px 2px rgba(0, 0, 0, 0.12));
}

.mini-cart__alert-wrapper {
  padding-top: 20px;
}

.mini-cart .alert {
  margin-bottom: 0;
  flex-shrink: 0;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.mini-cart__content:not(.mini-cart__content--empty) > * {
  padding-left: 20px;
  padding-right: 20px;
}

.mini-cart__content--empty {
  padding: 20px 25px 25px 25px;
}

.mini-cart__empty-state {
  padding: 70px 0 60px 0;
  text-align: center;
}
.mini-cart__empty-state svg {
  margin-bottom: 10px;
}

.mini-cart__line-item-list {
  overflow: auto;
  -webkit-overflow-scrolling: touch;
  -ms-scroll-chaining: none;
      overscroll-behavior: none;
}

.mini-cart__line-item {
  display: flex;
  align-items: flex-start;
  padding: 20px 0;
}

.mini-cart__line-item + .mini-cart__line-item {
  border-top: 1px solid var(--border-color);
}

.mini-cart__image-wrapper {
  min-width: 80px;
  width: 80px;
  margin-right: 20px;
}

.mini-cart__product-info {
  margin-bottom: 12px;
}

.mini-cart__product-vendor {
  display: block;
  margin-bottom: 7px;
  line-height: 1.55;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
  text-transform: uppercase;
}

.mini-cart__product-title {
  display: block;
  margin-bottom: 4px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  line-height: 1.5;
}

.mini-cart__property-list {
  line-height: 1.5;
  margin: 6px 0;
}

.mini-cart__price-list > .price {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
  font-weight: var(--text-font-bolder-weight);
}

.mini-cart__price-info {
  margin-top: -2px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
}

.mini-cart__discount-list {
  list-style: none;
  margin-top: 2px;
}

.mini-cart__discount {
  display: inline-block;
  font-weight: var(--text-font-bolder-weight);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
  background: rgba(var(--product-on-sale-accent-rgb), 0.08);
  color: var(--product-on-sale-accent);
  border-radius: 2px;
  padding: 0 11px;
}

.mini-cart__discount svg {
  margin-right: 6px;
  vertical-align: text-bottom;
}

.mini-cart__discount + .mini-cart__discount {
  margin-top: 5px;
}

.mini-cart__quantity-remove {
  display: inline-block;
  margin-left: 10px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
  line-height: 1;
}

.mini-cart__recap {
  padding: 15px 20px 20px 20px;
  border-top: 1px solid var(--border-color);
}

.mini-cart__recap-price-line {
  display: flex;
  align-items: center;
  justify-content: space-between;
  color: var(--heading-color);
  font-weight: var(--text-font-bolder-weight);
}

.mini-cart__recap-price-line--highlight {
  color: var(--product-on-sale-accent);
}

.mini-cart__recap-price-line + .mini-cart__recap-price-line {
  margin-top: 4px;
}

.mini-cart__amount-saved {
  color: var(--product-on-sale-accent);
  font-weight: var(--text-font-bolder-weight);
}

.mini-cart__button-container {
  margin-top: 16px;
}

@media screen and (max-width: 640px) {
  .mini-cart .icon--nav-triangle-borderless {
    right: 24px;
  }

  .mini-cart__content {
    display: flex;
    flex-direction: column;
  }

  .mini-cart__inner,
  .mini-cart__content--empty {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
}

@media screen and (min-width: 641px) {
  .mini-cart {
    left: auto;
    right: 0;
    top: calc(100% + 14px);
    max-height: none;
    width: 470px;
    height: auto;
    border-radius: 10px;
    box-shadow: 0 1px 5px 2px rgb(0 0 0 / 5%);
    border: 3px solid var(--primary-button-background);
  }

  .mini-cart__content > * {
    padding-left: 25px;
    padding-right: 25px;
  }

  .mini-cart__content--empty {
    padding-bottom: 25px;
  }

  .mini-cart__line-item-list {
    max-height: 300px;
  }

  .mini-cart__item-wrapper {
    display: flex;
    flex-grow: 1;
    align-items: flex-start;
    justify-content: space-between;
  }

  .mini-cart__quantity-remove {
    display: block;
    width: -webkit-max-content;
    width: -moz-max-content;
    width: max-content;
    margin: 10px auto 0 auto;
  }

  .mini-cart__product-info {
    margin: 0 20px 0 0;
  }

  .mini-cart__recap {
    padding: 15px 25px 25px 25px;
  }
}

@media screen and (min-height: 700px) and (min-width: 641px) {
  .mini-cart__line-item-list {
    max-height: 330px;
  }
}

@media screen and (min-width: 1280px) {
  .mini-cart .icon--nav-triangle-borderless {
    right: 58px;
  }
}

/**
 * --------------------------------------------------------------------
 * Main cart general layout
 *
 * On desktop, the recap is moved to the right, while the main content
 * has a restricted width
 * --------------------------------------------------------------------
 */

.cart-recap__secure-payment-list {
  max-width: 300px;
  margin: -4px auto !important;
}

@media screen and (max-width: 999px) {
  .cart-wrapper {
    min-height: 0 !important;
  }
}

@media screen and (min-width: 1000px) {
  .cart-wrapper {
    max-width: 1480px;
    margin-left: auto;
    margin-right: auto;
  }

  .cart-wrapper__inner {
    position: relative;
  }

  .cart-wrapper__inner-inner {
    width: calc(100% - 380px);
  }

  .cart-recap {
    position: absolute;
    right: var(--desktop-container-gutter);
    top: 0;
    width: 350px;
    height: 100%;
  }

  .cart-recap__scroller {
    position: -webkit-sticky;
    position: sticky;
    top: 0;
  }

  @supports (--css: variables) {
    .cart-recap__scroller {
      top: calc(var(--header-height) + 30px);
    }
  }
}

@media screen and (min-width: 1280px) {
  .cart-wrapper__inner-inner {
    width: calc(100% - 430px);
  }

  .cart-recap {
    width: 400px;
  }
}

/**
 * --------------------------------------------------------------------
 * Gift wrap
 * --------------------------------------------------------------------
 */

.gift-wrap {
  padding: 20px 10px 20px 20px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.gift-wrap__left {
  display: flex;
  align-items: center;
  margin-bottom: 18px;
}

.gift-wrap__icon svg {
  display: block;
  margin-top: -4px;
  margin-right: 25px;
  width: 24px;
  height: 24px;
}

.gift-wrap__text > span:first-child {
  margin-right: 10px;
}

@media screen and (min-width: 641px) {
  .gift-wrap {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 10px 10px 30px;
  }

  .gift-wrap__left {
    margin-bottom: 0;
  }
}

/**
 * --------------------------------------------------------------------
 * Estimate shipping (this is quite similar to the gift wrap code, and
 * may be good to find a good block abstraction to make the code re-usable
 * --------------------------------------------------------------------
 */

.estimate-shipping {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.estimate-shipping__toggle {
  display: flex;
  align-items: center;
  padding: 20px;
  width: 100%;
  color: var(--heading-color);
  font-weight: var(--text-font-bolder-weight);
}

.estimate-shipping__icon svg {
  display: block;
  margin-right: 25px;
  width: 24px;
  height: 24px;
}

.estimate-shipping__arrow {
  margin-left: auto;
}
.estimate-shipping__arrow svg {
  width: 12px;
  height: 8px;
  transition: transform 0.2s ease-in-out;
}

.estimate-shipping__toggle[aria-expanded=true] .estimate-shipping__arrow svg {
  transform: rotateZ(180deg);
}

.estimate-shipping__collapsible .shipping-estimator {
  padding: 0 20px 20px 20px;
}

@media screen and (min-width: 641px) {
  .estimate-shipping__toggle {
    padding: 20px 30px;
  }

  .estimate-shipping__collapsible .shipping-estimator {
    padding-right: 30px;
    padding-left: 30px;
  }
}

/**
 * --------------------------------------------------------------------
 * Cart recap
 * --------------------------------------------------------------------
 */

.cart-recap__price-line {
  display: flex;
  justify-content: space-between;
  margin-bottom: 4px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 15px));
  font-weight: var(--text-font-bolder-weight);
  color: var(--heading-color);
}

.cart-recap__price-line + .cart-recap__price-line {
  margin-top: 4px;
}

.cart-recap__price-line--highlight {
  color: var(--product-on-sale-accent);
}

.cart-recap__amount-saved {
  color: var(--product-on-sale-accent);
  font-weight: var(--text-font-bolder-weight);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 15px));
}

.cart-recap__note {
  margin-top: 14px;
  border-top: 1px solid var(--border-color);
  border-bottom: 1px solid var(--border-color);
}

.cart-recap__note-inner {
  padding-bottom: 20px;
}

.cart-recap__note-button {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 0;
  width: 100%;
}
.cart-recap__note-button svg {
  width: 12px;
  height: 8px;
  transition: transform 0.2s ease-in-out;
}
.cart-recap__note-button[aria-expanded=true] svg {
  transform: rotateZ(180deg);
}

.cart-recap__note-edit {
  margin-right: 14px;
  color: var(--accent-color);
  opacity: 0;
  transition: opacity 0.2s ease-in-out;
}

.cart-recap__note-edit.is-visible {
  opacity: 1;
}

.cart-recap__notices {
  margin: 24px 0;
}

.cart-recap__secure-payment-title {
  margin-bottom: 10px;
  text-align: center;
  font-weight: var(--text-font-bolder-weight);
}

.cart-recap__secure-payment-title svg {
  margin-right: 8px;
  vertical-align: text-top;
}

@media screen and (min-width: 641px) {
  .cart-recap__price-line {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 18px));
  }

  .cart-recap__amount-saved {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
  }

  .cart-recap__note {
    margin-top: 20px;
  }
}
/**
 * --------------------------------------------------------------------
 * MAIN COLLECTION
 * --------------------------------------------------------------------
 */

.collection__image-wrapper {
  position: relative;
  height: 180px;
  margin-bottom: -1px;
  z-index: 1;
  overflow: hidden;
}

.collection__image-wrapper--small {
  height: 140px;
}

.collection__image-wrapper--large {
  height: 230px;
}

.collection__image-wrapper--preserve-ratio {
  height: auto !important;
  /* Height depends on the ratio of the original image */
}

.collection__image-wrapper + .card {
  border-top-left-radius: 0;
  border-top-right-radius: 0;
}

.collection__image {
  height: 100%;
  background-size: cover;
  background-position: center;
}

.collection__title {
  margin-bottom: 5px;
}

.collection__meta {
  margin-bottom: 12px;
}

.collection__description {
  margin-top: 20px;
}

.collection__brand-logo-wrapper {
  margin-right: 20px;
  padding: 10px;
  width: 70px;
  height: 70px;
  border: 1px solid var(--border-color);
  border-radius: 3px;
}

.collection__brand-logo-image {
  height: 100%;
  width: 100%;
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center;
}

.collection__products-count {
  margin-bottom: 18px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
}

.collection__toolbar {
  position: relative;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 22px;
  padding: 0 var(--mobile-container-gutter);
  box-shadow: 0 1px var(--border-color), 0 -1px var(--border-color);
  background: var(--secondary-background);
  z-index: 3;
}

.collection__toolbar-item {
  display: flex;
  align-items: center;
  height: 48px;
}

.collection__toolbar-item--filter svg {
  margin-right: 12px;
  width: 19px;
  height: 20px;
}

.collection__layout-label {
  margin-right: 20px;
}

.collection__layout-button {
  opacity: 0.7;
  transition: all 0.2s ease-in-out;
}

.collection__layout-button:last-child {
  margin-left: 15px;
}

.collection__layout-button:hover {
  opacity: 1;
}

.collection__layout-button.is-selected {
  opacity: 1;
  color: var(--heading-color);
}

.collection__layout-button svg {
  display: block;
  width: 18px;
  height: 18px;
}

/* Adjustment when the expanded description is enabled */
.collection__header .expandable-content--expandable {
  margin-bottom: -22px;
}

/* Brand variant */
.collection__header--brand .collection__meta {
  display: flex;
  align-items: center;
}

.collection__header--brand .collection__description {
  margin-top: 0;
}

@media screen and (max-width: 999px) {
  .collection__toolbar {
    position: -webkit-sticky;
    position: sticky;
    top: calc(var(--header-height) * 0);
    top: calc(var(--header-height) * var(--header-is-sticky, 0));
  }
}

@media screen and (min-width: 641px) {
  .collection__image-wrapper {
    height: 230px;
    border-radius: 3px 3px 0 0;
  }

  .collection__image-wrapper--small {
    height: 200px;
  }

  .collection__image-wrapper--large {
    height: 310px;
  }

  .collection__brand-logo-wrapper {
    width: 90px;
    height: 90px;
    margin-right: 30px;
  }

  .collection__products-count {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  }

  .collection__toolbar {
    padding: 0 30px;
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  }

  .collection__toolbar--bordered {
    margin-top: 30px;
    box-shadow: 0 1px var(--border-color), 0 -1px var(--border-color);
  }

  .card__header--tight + .collection__toolbar--bordered {
    margin-top: 25px;
  }

  .collection__toolbar-item {
    height: 58px;
  }

  .collection__toolbar-item .value-picker-button {
    margin-left: 4px;
  }
}

@media screen and (max-width: 640px) {
  .collection__toolbar-item--count + .collection__toolbar-item--layout {
    margin-left: auto;
  }
}

@media screen and (min-width: 1000px) {
  .collection__toolbar:not(.collection__toolbar--bordered) {
    margin-top: -12px;
    box-shadow: 0 1px var(--border-color);
  }

  .collection__brand-logo-wrapper {
    width: 110px;
    height: 110px;
    flex: none;
  }

  /* Brand variation */
  .collection__header--brand {
    display: flex;
    align-items: flex-start;
  }
  .collection__header--brand .collection__meta {
    display: block;
  }
}

@media screen and (min-width: 1280px) {
  .collection__title {
    margin-bottom: 12px;
  }

  .collection__description {
    margin-top: 10px;
  }

  .collection__showing-count,
  .collection__toolbar-item--sort {
    margin-right: 45px;
  }

  .collection__toolbar-item--sort {
    margin-left: auto;
  }

  /* Brand variation */
  .collection__header--brand .collection__meta {
    margin-bottom: 0;
  }
}

@media screen and (min-width: 1440px) {
  .collection__showing-count,
  .collection__toolbar-item--sort {
    margin-right: 80px;
  }
}

/**
 * --------------------------------------------------------------------
 * MAIN COLLECTION (FILTER BAR)
 * --------------------------------------------------------------------
 */

.collection__filter-group-list--ordered {
  display: flex;
  flex-direction: column;
}

.collection__filter-group {
  padding: 13px 20px 14px 20px;
  border-bottom: 1px solid var(--border-color);
}

.collection__filter-group-name {
  display: flex;
  width: 100%;
  justify-content: space-between;
  align-items: center;
  text-align: left;
}
.collection__filter-group-name svg {
  width: 12px;
  height: 8px;
  margin-left: 10px;
  transition: transform 0.25s ease-in-out;
}

.collection__filter-group-name[aria-expanded=true] svg {
  transform: rotateZ(180deg);
}

.collection__filter-collapsible {
  height: 0;
  overflow: hidden;
  visibility: hidden;
  transition: 0.2s ease-in-out;
}

.collection__filter-collapsible[aria-hidden=false] {
  visibility: visible;
}

.collection__filter-item-active {
  display: block;
  margin-top: -5px;
  color: var(--accent-color);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
}

/* Linklist */
.collection__filter-linklist {
  list-style: none;
  padding: 4px 0 8px 0;
}

.collection__filter-link {
  display: block;
  width: 100%;
  padding: 3px 0 4px 0;
  text-align: left;
}
.collection__filter-link svg {
  width: 12px;
  height: 8px;
  margin-left: 8px;
  transition: transform 0.25s ease-in-out;
}

.collection__filter-link[aria-expanded=true] svg {
  transform: rotateZ(180deg);
}

.collection__filter-link.is-active {
  font-weight: var(--text-font-bolder-weight);
  color: var(--accent-color);
}

.collection__filter-linklist .collection__filter-linklist {
  padding: 0 0 0 10px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

/* Colors */
.collection__filter-color-list {
  padding: 7px 0 5px 6px;
}

/* Checkbox */
.collection__filter-checkbox-list {
  list-style: none;
}

.collection__filter-collapsible .collection__filter-checkbox-list {
  padding: 8px 0 7px 10px;
  /* When embedded into a collapsible it get more padding */
}

.collection__filter-checkbox {
  display: flex;
  align-items: center;
  padding: 2px 0 3px 0;
}

.collection__filter-checkbox label {
  margin-left: 4px; /* This is micro-alignment to respect the design due to the usage of flexbox here */
  line-height: 1.5;
}

/* Active filters */

.collection__filter-icon--active {
  position: relative;
}

.collection__filter-icon--active::after {
  content: "";
  position: absolute;
  top: 3px;
  left: 13px;
  width: 8px;
  height: 8px;
  border-radius: 100%;
  background: var(--accent-color);
}

.collection__active-filters {
  margin: -5px 0 16px 0;
}

.collection__active-filters:empty {
  display: none;
}

.collection__active-filter-item {
  display: flex;
  width: 100%;
  padding: 4px 0;
  align-items: center;
  line-height: 1.5;
  font-weight: var(--text-font-bolder-weight);
  color: var(--accent-color);
}

.collection__active-filter-cross {
  position: relative;
  display: inline-block;
  margin-right: 12px;
  background: var(--accent-color);
  color: var(--secondary-background);
  height: 20px;
  width: 20px;
  border-radius: 3px;
  box-shadow: 0 1px rgba(var(--border-color-rgb), 0.4);
}

.collection__active-filter-cross svg {
  position: absolute;
  top: 6px;
  left: 6px;
  width: 8px;
  height: 8px;
  stroke-width: 2px;
  stroke: white;
}

.collection__clear-filter {
  margin: 13px 0 9px 0;
}

@media screen and (min-width: 1000px) {
  .collection__filter-group {
    padding: 6px 0;
    border-bottom: 0;
  }

  .collection__filter-group-name {
    justify-content: flex-start;
  }

  /* Linklist */
  .collection__filter-linklist {
    padding: 0 0 9px 0;
  }

  .collection__filter-linklist .collection__filter-linklist {
    padding-left: 15px;
  }

  .collection__filter-link {
    padding: 2px 0;
  }

  /* Color */
  .collection__filter-color-list {
    padding: 12px 0 10px 0;
  }

  /* Checkbox */
  .collection__filter-collapsible .collection__filter-checkbox-list {
    padding-bottom: 12px;
  }

  .collection__filter-group:last-child .collection__filter-checkbox-list {
    padding-bottom: 0;
    /* Last one must have its padding removed */
  }

  .collection__filter-checkbox {
    padding: 0;
  }
  .collection__filter-checkbox .checkbox-wrapper {
    margin: 8px 0;
  }
}

@media screen and (min-width: 1280px) {
  .collection__sidebar {
    flex-basis: 290px;
  }
}

/**
 * --------------------------------------------------------------------
 * MAIN COLLECTION (FILTER BAR MOBILE)
 * --------------------------------------------------------------------
 */

.collection__mobile-filters-recap {
  background: var(--background);
  border-bottom: 1px solid var(--border-color);
}

.collection__mobile-active-filters {
  margin: -5px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
}

.collection__mobile-active-filter-item {
  padding: 4px 12px;
  background: var(--accent-color);
  border-radius: 3px;
  box-shadow: 0 1px rgba(var(--accent-color-rgb), 0.15);
  color: var(--secondary-background);
  font-weight: var(--text-font-bolder-weight);
}

.collection__mobile-active-filter-item,
.collection__mobile-active-clear {
  margin: 5px;
}

.collection__mobile-active-filter-cross {
  margin-right: 7px;
}

.collection__mobile-active-filter-cross svg {
  width: 7px;
  height: 7px;
  stroke: currentColor;
  stroke-width: 3px;
}

.collection__mobile-active-clear {
  position: relative;
  margin-left: 15px;
}

.collection__mobile-active-clear::after {
  content: "";
  position: absolute;
  left: 0;
  bottom: 3px;
  width: 100%;
  height: 1px;
  background: currentColor;
}

.collection__mobile-active-filters-results {
  display: block;
  margin-top: 25px;
  margin-bottom: -5px;
}

/**
 * --------------------------------------------------------------------
 * COLLECTION FILTER DRAWER (MOBILE)
 * --------------------------------------------------------------------
 */

.collection-drawer {
  display: flex;
  flex-direction: column;
  height: 100%;
}

.collection-drawer__header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex: 1 0 auto;
  max-height: 64px;
  padding: 15px 15px 15px 25px;
  border-bottom: 1px solid var(--border-color);
  z-index: 1;
}

.collection-drawer__header > div {
  display: flex;
  align-items: center;
}

.collection-drawer__close {
  margin-right: 16px;
  color: var(--heading-color);
}

.collection-drawer__close svg {
  display: block;
  width: 19px;
  height: 19px;
  margin-top: -1px;
}

.collection-drawer__title {
  margin-bottom: 0;
}

.collection-drawer__inner {
  flex: 1 1 auto;
  overflow: auto;
  -webkit-overflow-scrolling: touch;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 15px));
}

.collection-drawer__section-title {
  margin: 0;
  padding: 4px 15px;
  text-transform: uppercase;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
  font-weight: var(--text-font-bolder-weight);
  background: var(--background);
  border-bottom: 1px solid var(--border-color);
}

.collection-drawer__footer {
  padding: 15px;
  box-shadow: 0 -2px 2px rgba(var(--border-color-rgb), 0.65);
}

.collection-drawer__footer .button {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

/**
 * --------------------------------------------------------------------
 * PRODUCT LIST
 * --------------------------------------------------------------------
 */

.product-list {
  position: relative;
  display: flex;
  flex-wrap: wrap;
  overflow: hidden;
  width: 100%;
  border-top: 1px solid var(--border-color);
  border-bottom: 1px solid var(--border-color);
  z-index: 1; /* This is needed to create a new stacking context to improve performance on iOS */
}

.product-list .flickity-viewport {
  border-radius: 3px;
}

.product-list--scrollable {
  flex-wrap: nowrap;
}

.product-list--collection::before {
  display: none;
}

/* This allows to push the content in case when the product item has a quick form button (like on cart page) */
.product-item--vertical,
.product-item--vertical .product-item__info {
  display: flex;
  flex-direction: column;
}

.product-item--vertical .product-item__info {
  justify-content: space-between;
  flex: 1 0 auto;
}

.product-list__column {
  width: 100%;
}

@media screen and (max-width: 640px) {
  .product-list--scrollable::before,
  .product-list--scrollable::after {
    content: "";
    flex: 0 0 var(--mobile-container-gutter);
  }

  .product-list--scrollable .product-item {
    width: 62%;
  }

  .product-list--collage {
    border-width: 1px 0;
  }

  .product-list--collection .product-item--vertical {
    width: 50%;
  }
}

@media screen and (min-width: 641px) and (max-width: 999px) {
  .product-list--scrollable::before,
  .product-list--scrollable::after {
    content: "";
    flex: 0 0 var(--desktop-container-gutter);
  }

  .product-list--scrollable .product-item {
    width: 36%;
  }
}

@media screen and (min-width: 641px) {
  .product-list {
    background: none;
    border-radius: 3px;
    border: none;
  }

  /* This needs to be done instead of applying a border to the product-list to fix a z-index issue with the product labels */
  .product-list--collage::before {
    position: absolute;
    content: "";
    width: 100%;
    height: calc(100% + 0px); /* This solves an issue on Safari, where 100% does not always work - likely a pixel rounding issue - */
    border: 1px solid var(--border-color);
    z-index: 1;
    pointer-events: none;
    border-radius: 3px;
  }

  .product-list__column {
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    flex: 0 0 33.333333%;
  }

  .product-list__column > .product-item {
    flex: 1 0 auto;
  }

  .product-list__column--highlight .product-item__title {
    font-size: 1rem;
  }

  @supports (display: grid) {
    .product-list--collage {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(295px, 1fr));
    }

    .product-list__column {
      display: grid;
      grid-auto-rows: 1fr;
    }

    .product-list__column--shrink {
      grid-template-rows: minmax(50%, -webkit-min-content);
      grid-template-rows: minmax(50%, min-content);
    }
  }
}

@media screen and (max-width: 999px) {
  .product-list--scrollable {
    overflow: visible;
    border: none;
    background: transparent;
  }

  .product-list--scrollable .product-item {
    border: none;
  }

  .product-list--scrollable .product-item + .product-item {
    border-left: none;
  }

  .product-list--scrollable .product-item:first-child {
    border-radius: 3px 0 0 3px;
  }

  .product-list--scrollable .product-item:last-child {
    border-radius: 0 3px 3px 0;
  }

  .product-list--collection {
    border: none;
  }
}

@media screen and (min-width: 1000px) {
  /* This needs to be done instead of applying a border to the product-list to fix a z-index issue with the product labels */
  .product-list::before {
    position: absolute;
    content: "";
    width: 100%;
    height: calc(100% + 0px); /* This solves an issue on Safari, where 100% does not always work - likely a pixel rounding issue - */
    border: 1px solid var(--border-color);
    z-index: 1;
    pointer-events: none;
    border: none;
  }

  .product-list--scrollable::after {
    content: "flickity";
    display: none;
  }

  .product-list--scrollable .product-item {
    min-height: 100%;
  }

  .product-list--stackable {
    flex-wrap: wrap;
  }

  .product-list__column {
    flex-basis: 25%;
  }
}

@media screen and (min-width: 1440px) {
  @supports (display: grid) {
    .product-list--collage {
      grid-template-columns: repeat(2, 1fr 1.05fr);
    }
  }
}

/**
 * --------------------------------------------------------------------
 * FEATURED COLLECTION (HOME PAGE)
 * --------------------------------------------------------------------
 */

.featured-collection {
  padding-top: 25px;
  background-size: 100%;
}

.featured-collection__header {
  padding: 0 var(--mobile-container-gutter) 40px var(--mobile-container-gutter);
}

.featured-collection__title {
  margin-bottom: 8px;
  color: inherit;
}

.featured-collection__cta {
  margin-top: 8px;
}

.featured-collection__image-wrapper {
  margin-top: 25px;
}

.featured-collection .product-list {
  margin-bottom: 20px;
  border-radius: 2px;
}

.featured-collection .product-item {
  border: none;
  border-right: none;
}

.featured-collection .product-item::after {
  display: none;
}

.featured-collection .product-item:last-child {
  border-right: 0;
}

@media screen and (max-width: 640px) {
  .featured-collection,
  .featured-collection__header {
    background-image: none;
  }
}

@media screen and (min-width: 641px) and (max-width: 999px) {
  .featured-collection {
    margin: 0 calc(-1 * var(--desktop-container-gutter));
    background-image: none !important;
  }

  .featured-collection__header {
    padding-left: var(--desktop-container-gutter);
    padding-right: var(--desktop-container-gutter);
    background-repeat: no-repeat;
    background-position: bottom 0 right -15px;
    background-size: 430px auto;
  }

  .featured-collection__image-wrapper {
    max-width: 400px;
    margin-left: auto;
    margin-right: auto;
  }

  .featured-collection .product-list {
    margin-bottom: var(--desktop-container-gutter);
  }
}

@media screen and (min-width: 1000px) {
  .featured-collection {
    display: table; /* using Flexbox here didn't work well, so let's use old school and reliable stuff */
    table-layout: fixed;
    width: 100%;
    padding: 6px 6px 6px 0;
    border-radius: 16px;
  }

  .featured-collection__header,
  .featured-collection__content {
    display: table-cell;
    vertical-align: top;
  }

  .featured-collection__header {
    width: 333px;
    padding: 20px 30px;
    background-image: none !important;
  }

  .featured-collection .product-list {
    margin-bottom: 0;
  }
  .featured-collection .product-list::before {
    display: none;
  }

  /* This code is absolutely ugly and hacky, but due to rounding errors on Chrome, sometimes everything is shifted by 1px,
     and designer couldn't tolerate it. I've found this hack which basically adds a box-shadow to "cover" artificially
     the border of last element in the list. No better fix were found so far */
  .featured-collection .flickity-viewport::after {
    content: "";
    position: absolute;
    height: 100%;
    width: 1px;
    background: none;
    right: 0;
  }
}
/**
 * --------------------------------------------------------------------
 * COLLECTION ITEM (round style)
 * --------------------------------------------------------------------
 */

.collection-item {
  display: inline-block;
  width: 36vw;
  margin: 0 14px;
  vertical-align: top;
  white-space: normal;
}

.collection-item:first-child {
  margin-left: var(--mobile-container-gutter);
}

.collection-item:last-child {
  margin-right: var(--mobile-container-gutter);
}

.collection-item__image-wrapper {
  margin-bottom: 15px;
  overflow: hidden;
}

.collection-item__image-wrapper--rounded {
  /* adding a stacking context (position: relative; z-index: 0;) is necessary due to a bug in Safari. More info here: https://bugs.webkit.org/show_bug.cgi?id=98538 */
  position: relative;
  z-index: 0;
  overflow: hidden;
  border-radius: 100%;
}

.collection-item__image-wrapper img {
  -o-object-fit: cover;
     object-fit: cover;
  -o-object-position: center;
     object-position: center;
  transform: scale(1.01);
  /* The 1.01 is necessary to avoid some rounding issues on Chrome */
  font-family: "object-fit: cover; object-position: center;";
  /* IE11 polyfill */
  transition: opacity 0.2s ease-in-out, transform 0.95s cubic-bezier(0.25, 0.46, 0.45, 0.94);
}

.collection-item__title {
  display: block;
  line-height: 1.4;
  text-align: center;
  transition: color 0.2s ease-in-out;
}

.collection-item__title svg {
  display: none;
}

@media screen and (min-width: 641px) and (max-width: 999px) {
  .collection-item {
    width: 190px;
  }

  .collection-item:first-child {
    margin-left: var(--desktop-container-gutter);
  }

  .collection-item:last-child {
    margin-right: var(--desktop-container-gutter);
  }
}

@media screen and (min-width: 641px) {
  .collection-item__title {
    transform: translateX(14px);
    transition: transform 0.35s cubic-bezier(0.645, 0.045, 0.355, 1);
  }

  .collection-item__title svg {
    /*
    Note: for some strange reasons, on Safari (even last version), if we use a transform it cause a delay of up to 1 second on heavy home page before the
    animation starts. I couldn't find any explanation, but maybe the nested transforms (on both the link and SVG) does not work correctly on Safari. As a
    consequence, I've used a animation on right property (which is much slower but should be ok on this small piece of content)
    */
    position: relative;
    display: inline-block;
    height: 14px;
    width: 14px;
    vertical-align: -2px;
    margin-left: 8px;
    right: -5px;
    opacity: 0;
    transition: all 0.35s cubic-bezier(0.645, 0.045, 0.355, 1);
  }
}

@media screen and (min-width: 1000px) {
  .collection-list {
    margin: 30px -14px 0 -14px;
    white-space: nowrap;
    overflow: hidden;
  }

  .collection-list::after {
    display: none;
    content: "flickity"; /* enable Flickity slideshow */
  }

  .collection-item {
    width: 20%;
    margin: 0 !important;
    padding: 0 14px;
  }

  .collection-list .flickity-prev-next-button {
    top: calc(50% - 25px - 12px - 0.5em); /* 12px is the margin bottom below the image and 0.5em is half a line of text */
  }

  .collection-list .flickity-prev-next-button.previous {
    left: -10px;
  }

  .collection-list .flickity-prev-next-button.next {
    right: -10px;
  }
}

@media screen and (min-width: 1280px) {
  .collection-item {
    width: 12.5%;
  }
}

@media (-moz-touch-enabled: 0),(hover: hover) {
  .collection-item:hover .collection-item__title {
    color: var(--accent-color);
  }

  .features--animate-zoom .collection-item:hover img {
    transform: scale(1.07);
  }

  .collection-item:hover .collection-item__title {
    transform: translateX(0);
  }

  .collection-item:hover .collection-item__title svg {
    opacity: 1;
    right: 0;
  }
}

/**
 * --------------------------------------------------------------------
 * COLLECTION ITEM (block style)
 * --------------------------------------------------------------------
 */

/* General */
.collection-list__section {
  margin-bottom: 40px;
}

@media screen and (min-width: 641px) {
  .collection-list__section {
    margin-bottom: 60px;
  }
}

.collection-block-item {
  display: block;
  position: relative;
  border-radius: 3px;
  overflow: hidden;
}

.collection-block-item--overlay::before {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.2);
  z-index: 1;
}

.collection-block-item__image {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-size: cover;
  background-position: center;
  transition: transform 8s linear, opacity 0.3s ease-in-out !important;
}

.collection-block-item__title {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 100%;
  padding: 0 20px;
  transform: translate(-50%, -50%);
  text-align: center;
  color: #ffffff;
  z-index: 1;
  text-shadow: 1px 2px 4px rgba(0, 0, 0, 0.2);
}

@media (-moz-touch-enabled: 0),(hover: hover) {
  .features--animate-zoom .collection-block-item:hover .collection-block-item__image {
    transform: scale(1.4);
  }
}
/**
 * --------------------------------------------------------------------
 * Custom content section (this one is a bit a "fit-all" section, so it
 * was hard to make it very generic)
 * --------------------------------------------------------------------
 */

.custom-content--centered {
  text-align: center;
}

.custom-content--right {
  text-align: right;
}

/* Small exception for the standalone product, that is not within a grid, so it must have borders on all edges */
.custom-content--product .product-item::after {
  box-shadow: none;
}
/**
 * --------------------------------------------------------------------
 * FIELD
 * --------------------------------------------------------------------
 */

.form__field {
display: block;
    padding: 12px 12px;
    border-radius: 40px;
    background: #ededed;
    border: none;
    width: 100%;
    line-height: normal;
    height: 48px;
    color: var(--heading-color);
    -webkit-appearance: none;
    resize: none;
    font-size: 1rem;
    transition: border-color 0.2s ease-in-out, box-shadow 0.2s ease-in-out, color 0.2s ease-in-out;
}

.form__field::-webkit-input-placeholder {
  color: var(--text-color);
}

.form__field::-moz-placeholder {
  color: var(--text-color);
}

.form__field:-ms-input-placeholder {
  color: var(--text-color);
}

.form__field::-ms-input-placeholder {
  color: var(--text-color);
}

.form__field::placeholder {
  color: var(--text-color);
}

.form__field:focus {
  border-color: var(--accent-color);
  box-shadow: 0 0 0 1px var(--accent-color);
  color: var(--heading-color);
  outline: none;
}

.form__field--small {
  height: 44px;
}

.form__field--large {
  height: 60px;
  padding: 20px 18px;
}

.form__field--textarea {
  height: auto;
  line-height: inherit;
  min-height: 48px;
  padding-top: 6px;
  padding-bottom: 6px;
}

.form__field--borderless {
  border: none;
}

.form__field--borderless:focus {
  box-shadow: none;
}

.form__label {
  display: block;
  margin-bottom: 6px;
  color: var(--heading-color);
  font-weight: var(--text-font-bolder-weight);
}

.form__label--light {
  color: var(--text-color);
}

.form__submit {
  display: block;
}

.form__submit--tight {
  margin-top: 12px;
  width: 100%;
  background: none;
  border: 2px solid var(--footer-text-color);
  color: var(--footer-text-color);
}

.form__submit--tight:hover {
  background: var(--footer-text-color);
  color: var(--footer-background);
  border: 2px solid var(--footer-text-color);
}

@media screen and (min-width: 641px) {
  .form__submit--centered {
    margin-left: auto;
    margin-right: auto;
  }
}

/**
 * --------------------------------------------------------------------
 * INPUT WRAPPER
 * This is used to create list of fields, optionally with a label
 * --------------------------------------------------------------------
 */

.form__input-wrapper {
  position: relative;
  width: 100%;
  margin-bottom: 12px;
}

.form__floating-label {
  position: absolute;
  left: 18px;
  top: 0;
  line-height: 48px; /* allows to center the field */
  font-size: 1rem;
  color: var(--text-color);
  transform: scale(1);
  transform-origin: left top;
  transition: transform 0.2s ease-in-out;
  pointer-events: none;
}

.form__field:focus + .form__floating-label,
.form__field.is-filled + .form__floating-label,
.select-wrapper.is-filled + .form__floating-label {
  transform: translateY(-6px) scale(0.8);
}

.form__input-wrapper--labelled .form__field {
  padding-top: 20px;
  padding-bottom: 3px;
}

.form__field--large + .form__floating-label {
  left: 18px;
  line-height: 60px;
}

.form__input-wrapper--labelled .form__field--large {
  padding-top: 20px;
  padding-bottom: 3px;
}

/**
 * --------------------------------------------------------------------
 * INPUT ROW
 * --------------------------------------------------------------------
 */

.form__input-row {
  display: flex;
  flex-direction: column;
}

.form__input-row .form__submit {
  margin-top: 0;
}

@media screen and (min-width: 641px) {
  .form__input-row {
    flex-direction: row;
    align-items: flex-end;
    margin: 0 -6px;
  }
  .form__input-row:not(:last-child) {
    margin-bottom: 12px;
  }

  .form__input-row > .form__input-wrapper {
    margin-bottom: 0;
  }

  .form__input-row > * {
    margin-left: 6px;
    margin-right: 6px;
  }

  .form__input-row > .form__submit {
    margin-top: 0;
  }

  .form__input-row > .form__submit {
    flex: 1 0 auto; /* we let the submit button grow freely */
  }
}

/**
 * --------------------------------------------------------------------
 * CONNECTED INPUT
 * --------------------------------------------------------------------
 */

.form__connected-item {
  display: flex;
  align-items: center;
  margin-bottom: 12px;
}

.form__connected-item .form__input-wrapper {
  margin-bottom: 0;
}

.form__connected-item .form__field {
  border-top-right-radius: 0;
  border-bottom-right-radius: 0;
  border-right: none; /* When connected with the icon, the box-shadow must be set inside */
}

.form__connected-item .form__field:focus {
  box-shadow: 0 0 0 1px var(--accent-color) inset;
}

.form__connected-item .form__connection {
  padding-left: 14px;
  padding-right: 14px;
  border-top-left-radius: 0;
  border-bottom-left-radius: 0;
}

.form__connected-item .form__connection svg {
  width: 23px;
  height: 23px;
}

/**
 * --------------------------------------------------------------------
 * FORM MAIN VARIATION (used when the form is the main element)
 * --------------------------------------------------------------------
 */

.form--main {
  max-width: 350px;
  margin: 60px auto;
  text-align: center;
}

.form__header,
.form__legend {
  margin-bottom: 30px;
}

.form__title {
  margin-bottom: 15px;
}

.form__secondary-action {
  margin-top: 32px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
}

.form__secondary-action > * {
  margin-bottom: 0;
}

@media screen and (min-width: 641px) {
  .form--main {
    margin-top: 110px;
    margin-bottom: 150px;
  }
}

/**
 * --------------------------------------------------------------------
 * SELECT
 * --------------------------------------------------------------------
 */

select::-ms-expand {
  display: none;
}

.select-wrapper {
  position: relative;
  color: currentColor;
  line-height: inherit;
  vertical-align: middle;
}

.select-wrapper svg {
  position: absolute;
  pointer-events: none;
  vertical-align: baseline;
  fill: currentColor;
}

.select-wrapper select {
  /* Disable built-in styles */
  -webkit-appearance: none;
  -moz-appearance: none;
  display: inline-block;
  color: inherit;
  cursor: pointer;
  border-radius: 0; /* Remove the ugly blue background on IE when a value is selected */
}

.select-wrapper select:focus::-ms-value {
  background: transparent;
  color: var(--text-color);
}

/* Make sure to have something easy to read... */
.select-wrapper option {
  background: white;
  color: black;
}

.select-wrapper--transparent select {
  padding-right: 22px;
  background: transparent;
  border: none;
  font-size: inherit;
}

.select-wrapper--transparent svg {
  top: calc(50% - 4px);
  right: 4px;
  width: 12px;
  height: 8px;
}

.select-wrapper--primary {
  position: relative;
  background: var(--secondary-background);
}

.select-wrapper--primary select {
  width: 100%;
  padding: 0 36px 0 12px;
  height: 48px;
  border: 1px solid var(--form-border-color);
  border-radius: 2px;
  background: transparent;
  box-shadow: 0 -1px 1px rgba(var(--border-color-rgb), 0.3) inset;
  font-size: 1rem;
  transition: border-color 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
}

.select-wrapper--primary select:focus {
  border-color: var(--accent-color);
  box-shadow: 0 0 0 1px var(--accent-color);
  outline: none;
}

.select-wrapper--primary select:valid {
  color: var(--heading-color);
        border-radius: 30px;

}

.select-wrapper--primary svg {
  width: 12px;
  height: 14px;
  top: calc(50% - 7px);
  right: 16px;
  opacity: 0.7;
}

.select-wrapper--primary.select-wrapper--small select {
  height: 44px;
  padding-left: 12px;
  padding-bottom: 1px;
  /* just for some pixel perfect alignment... but not sure if it's really good idea for cross-browser! */
}

.form__input-wrapper--labelled .select-wrapper--primary.is-filled select {
  padding-top: 16px;
}

/* Abstraction to just have a select button (without the actual select) */
.select-button {
  position: relative;
  background: var(--secondary-background);
  color: currentColor;
  line-height: inherit;
  vertical-align: middle;
  width: 100%;
  padding: 0 36px 0 12px;
  height: 48px;
  border: 1px solid var(--form-border-color);
  border-radius: 2px;
  box-shadow: 0 -1px 1px rgba(var(--border-color-rgb), 0.3) inset;
  font-size: 1rem;
  text-align: left;
  transition: border-color 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
}

.select-button:focus {
  border-color: var(--accent-color);
  box-shadow: 0 0 0 1px var(--accent-color);
  outline: none;
}

.select-button svg {
  position: absolute;
  pointer-events: none;
  width: 12px;
  height: 14px;
  top: calc(50% - 7px);
  right: 16px;
  opacity: 0.7;
  vertical-align: baseline;
  fill: currentColor;
}

.select-button--mini {
  height: 32px;
  padding: 0 44px 0 10px;
  font-size: 0.85rem;
}

.select-button--mini svg {
  right: 11px;
}

/**
 * --------------------------------------------------------------------
 * CUSTOM CHECKBOX
 * --------------------------------------------------------------------
 */

.checkbox-wrapper {
  position: relative;
  display: inline-block;
  vertical-align: middle;
  margin: 8px 0;
}

.checkbox-wrapper svg {
  position: absolute;
  width: 12px;
  height: 12px;
  left: 2px;
  top: calc(50% - 6px);
  transform: scale(0);
  transition: transform 0.2s ease-in-out;
  color: var(--secondary-background);
}

.checkbox-wrapper ~ label {
  vertical-align: middle;
  cursor: pointer;
}

.checkbox {
  display: block;
  margin-right: 10px;
  width: 16px;
  height: 16px;
  border: 1px solid var(--form-border-color);
  background: var(--secondary-background);
  box-shadow: 0 1px rgba(var(--border-color-rgb), 0.4);
  border-radius: 2px;
  -webkit-appearance: none;
  transition: border-color 0.2s ease-in-out, box-shadow 0.2s ease-in-out, background 0.2s ease-in-out;
}

.checkbox:focus {
  border-color: var(--accent-color);
  box-shadow: 0 0 0 1px var(--accent-color);
  outline: none;
}

.checkbox:checked {
  background: var(--accent-color);
  border-color: var(--accent-color);
  box-shadow: none;
}

.checkbox:checked + svg {
  transform: scale(1);
}

.checkbox.is-selected ~ label {
  color: var(--accent-color);
  font-weight: var(--text-font-bolder-weight);
}

.checkbox,
.checkbox ~ label {
  vertical-align: middle;
  cursor: pointer;
}

@media screen and (min-width: 1000px) {
  .checkbox-wrapper {
    margin: 12px 0;
  }
}
.gift-card__inner {
  padding: 30px 0;
}

.gift-card__main {
  position: relative;
  padding-top: 85px;
  text-align: center;
}

.gift-card__image {
  position: relative;
  width: 170px;
  height: 170px;
  top: -105px;
  border-radius: 100%;
  overflow: hidden;
  margin: 0 auto -75px auto;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
}

.gift-card__title {
  margin-bottom: 0;
}

.gift-card__amount {
  margin-bottom: 18px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 22px));
}

.gift-card__alert {
  margin-top: 20px;
}

.gift-card__code-container {
  max-width: 255px;
  margin: 0 auto 28px auto;
}

.gift-card__code {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 6px 15px;
  width: 100%;
  border: 1px solid var(--border-color);
  text-transform: uppercase;
  margin-bottom: 15px;
  border-radius: 3px;
  text-align: center;
}

.gift-card__expires-on {
  display: block;
  color: var(--product-in-stock-color);
  font-weight: var(--text-font-bolder-weight);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 15px));
}

.gift-card__expires-on::before {
  display: inline-block;
  content: "";
  width: 8px;
  height: 8px;
  margin-right: 0.7em;
  border-radius: 100%;
  background: currentColor;
  vertical-align: baseline;
}

.gift-card__share {
  padding-top: 15px;
  padding-bottom: 20px;
}

.gift-card__wallet {
  display: block;
  margin-bottom: 30px;
  text-align: center;
}

.gift-card__qr img {
  margin: 0 auto;
}

.gift-card__shop {
  margin-top: 15px;
  min-width: 300px;
}

@media screen and (max-width: 640px) {
  .gift-card__print {
    width: 100%;
  }

  .gift-card__qr img {
    max-width: 120px;
  }
}

@media screen and (min-width: 641px) {
  /* On gift card there is no search bar so we increase the header */
  .template-gift-card .header {
    padding-top: 30px;
    padding-bottom: 30px;
  }

  .gift-card__inner {
    display: flex;
    max-width: 920px;
    margin: 0 auto;
    padding: 70px 0 90px 0;
  }

  .gift-card__main {
    flex: 1 0 auto;
  }

  .gift-card__aside {
    flex: 0 0 255px;
    margin-top: 85px;
    margin-left: 30px;
  }

  .gift-card__image {
    width: 210px;
    height: 210px;
    top: -135px;
    margin-bottom: -80px;
  }

  .gift-card__amount {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 24px));
  }

  .gift-card__code-container {
    display: flex;
    justify-content: center;
    max-width: none;
  }

  .gift-card__code {
    margin-bottom: 0;
    margin-right: 15px;
    max-width: 250px;
  }

  .gift-card__print {
    flex-basis: 150px;
  }
}

@media print {
  .gift-card__aside {
    display: none;
  }
}
.footer {
  padding: 10px 0 30px 0;
  background: var(--footer-background);
  color: var(--footer-text-color);
}

.footer__block-list {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
}

.footer__title {
  position: relative;
  display: block;
  font-weight: bold;
  width: 100%;
  margin-bottom: 0.85em;
  text-align: left;
  color: var(--footer-text-color);
}

.footer__title[disabled] {
  cursor: text;
  -webkit-user-select: text;
     -moz-user-select: text;
      -ms-user-select: text;
          user-select: text;
}

.footer__linklist {
  margin-top: -8px;
  margin-bottom: -5px;
  line-height: 1.4;
}

.footer__link-item {
  display: block;
  padding: 5px 0;
  color: var(--footer-text-color);
}

.footer__newsletter-form {
  margin-top: 20px;
}

.footer__aside {
  display: flex;
  flex-direction: column;
  margin-top: 10px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
  color: var(--footer-text-color);
}

.footer__aside-item {
  margin-top: 34px;
}

.footer__aside-item--localization,
.footer__aside-item--copyright {
  margin-top: 45px;
  text-align: center;
}

.footer__aside-title {
  margin-bottom: 0.8em;
}

.footer__localization-form {
  display: flex;
}

.footer__localization-form .select-button {
  width: auto;
}

.footer__localization-form-item:not(:last-child) {
  margin-right: 10px;
}

@media screen and (max-width: 640px) {
  .footer__block-item {
    margin-right: calc(-1 * var(--mobile-container-gutter));
    padding-right: var(--mobile-container-gutter);
    border-bottom: 1px solid var(--footer-background);
  }

  .footer__block-item--newsletter {
    border-bottom: none;
    order: 1;
  }

  .footer__title {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 0;
    padding: 19px 0;
    color: var(--footer-text-color);
  }

  .footer__collapsible {
    height: 0;
    overflow: hidden;
    transition: 0.3s ease-in-out;
  }

  .footer__collapsible-content {
    padding: 0 20px 25px 0;
  }

  .footer__block-item .rte {
    margin-top: -0.425em;
  }
}

@media screen and (min-width: 641px) {
  .footer {
    padding: 0;
    border-top: none;
  }

  .footer__wrapper {
    padding: 50px 0;
    border-top: 0px solid var(--footer-background);
  }

  .footer__block-list {
    flex-direction: row;
    margin: -20px -35px;
  }

  .footer__block-item {
    flex: 0 0 50%;
    padding: 20px 35px;
  }

  .footer__block-item--newsletter {
    max-width: 350px;
  }

  .footer__block-item .plus-button {
    display: none;
  }

  .footer__localization-form {
    margin-bottom: 20px;
  }

  .footer__linklist {
    margin-top: -2px;
    margin-bottom: 0;
  }

  .footer__aside {
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
    margin-top: 30px;
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
  }

  .footer__aside-item {
    margin-top: 0;
  }

  .footer__aside-item--localization,
  .footer__aside-item--copyright {
    width: 100%;
  }

  .footer__aside-item--copyright:not(:only-child) {
    margin-top: 34px;
  }
}

@media screen and (min-width: 1000px) {
  .footer__block-item {
    flex: 1 0 auto;
  }

  .footer__block-item--text {
    flex-basis: 300px;
    flex: 0 0 35%;
  }

  .footer__block-item--newsletter {
    flex-basis: 350px;
  }

  .footer__block-item--links {
    max-width: 300px;
  }

  .footer__aside {
    align-items: center;
    gap: 16px;
  }

  .footer__aside-item--copyright {
    align-self: flex-end;
    margin-top: 0 !important;
    margin-bottom: -8px;
    text-align: left;
  }

  .footer__aside-item--localization,
  .footer__aside-item--copyright {
    width: auto;
  }
}
/* This is a bit hacky, but it allows to have a clearfix when the search bar on mobile is expanded */
#shopify-section-header::after {
  content: "";
  display: table;
  clear: both;
}

/**
 * --------------------------------------------------------------------
 * HEADER
 * --------------------------------------------------------------------
 */

.header {
  position: relative;
  padding: 13px 0;
  background: var(--header-background);
  color: var(--header-text-color);
  transition: margin-bottom 0.25s ease-in-out;
}

.header__inner {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
}

.header__inner--centered {
  justify-content: center;
}

.header__logo-link {
  display: block;
}

.header__logo {
  display: inline-block;
  vertical-align: middle;
  margin-bottom: 0;
}

@media screen and (max-width: 640px) {
 .logodorodape {
   display: flex;
   justify-content: center;
   margin: 12px 0 12px 0;
 }
}

.header__logo-image {
  display: block;
  vertical-align: middle;
  max-height: 130px;
}

.header__mobile-nav {
  display: inline-block;
  margin-right: 20px;
}

.header__desktop-nav {
  position: relative;
  margin-right: 22px;
}

.header__mobile-nav-toggle {
  top: -1px; /* Slight alignment for pixel perfect :D */
}

.header__desktop-nav-toggle {
  height: 44px;
  padding: 0 15px;
  border: 1px solid var(--header-border-color);
  border-radius: 3px;
  font-weight: var(--text-font-bolder-weight); /* Safari 10 does not allow using flexbox on button... so we have to use an additional wrapper */
}
.header__desktop-nav-toggle > span {
  display: flex;
  align-items: center;
}

.header__desktop-nav-text {
  position: relative;
  top: 1px; /* Slight alignment for the pixel perfect */
}

.header__search-bar-wrapper {
  flex: 1 0 auto;
  margin-right: 12px;
}


.header .icon--account,
.header .icon--hamburger,
.header .icon--hamburger-mobile,
.header .icon--search,
.header .icon--cart,
.header .icon--close {
  display: block;
}

.header .icon--account {
  width: 20px;
  height: 22px;
}

.header .icon--hamburger {
  width: 20px;
  height: 14px;
}

.header .icon--hamburger-mobile {
  width: 20px;
  height: 16px;
}

.header .icon--cart {
  width: 27px;
  height: 24px;
}

.header .icon--search {
  width: 22px;
  height: 22px;
  margin: 0 auto;
}

.header .icon--close {
  width: 19px;
  height: 19px;
}

@media screen and (max-width: 640px) {
  /* This trick allows to enforce a minimum height for header on mobile */
  .header {
    display: flex;
    align-items: center;
    min-height: 64px;
  }

  .header > .container {
    width: 100%;
  }

  /* On mobile, if the search is expanded by default, we must add extra margin to the header element to prevent the search to
     overlap the rest of the content */
  .header--search-expanded {
    margin-bottom: 59px;
  }
}

@media screen and (min-width: 641px) {
  .header {
    padding: 20px 0;
    padding-bottom: 5px;
  }

  .header__inner {
    flex-wrap: nowrap;
  }

  .header__logo {
    margin-right: 35px;
  }
}

@media screen and (min-width: 1000px) {
  .icon--hamburger {
    margin-right: 15px;
  }
}

@media screen and (min-width: 1280px) {
  .header__logo {
    margin-right: 40px;
  }

  .header__desktop-nav {
    margin-right: 30px;
  }

  .header__desktop-nav-toggle {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
  }
}

/**
 * --------------------------------------------------------------------
 * HEADER ACTION LIST
 * --------------------------------------------------------------------
 */

.header__action-list {
  display: flex;
  align-items: center;
  margin-left: auto;
}

.header__action-item {
  padding: 0 6px;
}
.header__action-item:last-child {
  padding-right: 4px; /* Last item is the cart, and we use a small padding to accommodate the presence of the cart item count */
}

.header__action-item-link {
  display: block;
  font-weight: var(--text-font-bolder-weight);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
}

.header__action-item-link--small {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
  font-weight: normal;
}

.header__action-item-title {
  display: block;
  margin-bottom: -6px;
  color: var(--header-light-text-color);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  font-weight: normal;
}

.header__action-item--currency,
.header__action-item--locale {
  margin-right: 25px;
  padding: 0 24px;
}

.header__currency-selector {
  font-weight: var(--text-font-bolder-weight);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
}

.header__action-item .icon--arrow-bottom {
  width: 12px;
  height: 8px;
  margin-left: 4px;
}

.header__action-item .icon--lock-2 {
  width: 12px;
  height: 15px;
}

.header__action-item .icon--lock-2 + span {
  margin-left: 14px;
}

.header__cart-icon {
  margin-left: -2px;
  margin-top: 0px;
}

.header__cart-count {
  display: inline-flex;
  position: absolute;
  right: -1px;
  top: 3px;
  align-items: center;
  justify-content: center;
  height: 20px;
  min-width: 20px;
  padding: 4px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
  font-weight: var(--text-font-bolder-weight);
  text-align: center;
  background: var(--header-accent-color);
  color: var(--secondary-background);
  border-radius: 1.75em;
  transition: transform 0.35s ease-in-out;
  will-change: transform;
  transform: scale(1.01);
  z-index: 1;
}

.header__cart-toggle[aria-expanded=true] .header__cart-count,
.header__cart-toggle:hover .header__cart-count {
  transform: scale(1.2);
}

@media screen and (max-width: 640px) {
  /* This code is not optimal but the cart icon has a specific positioning so we override it this way */
  .header__cart-icon .icon-state__secondary.icon-state__secondary {
    left: 8px;
  }

  .header__action-item .icon--lock-2 {
    display: block;
  }

  /*
    IMPLEMENTATION NOTE:
    I am using a transition on margin-bottom instead of doing a simpler and more efficient transform. However the issue is that we are doing
    another transition on margin-bottom for the header. If I would apply a transform here, due to the fact the transform is hardware accelerated,
    they will move at a slightly different speed, which is not desirable. It's therefore either all HW-accelerated or not.
   */
  .header__search-bar-wrapper {
    visibility: hidden;
    position: absolute; /* We move it outside of the document for easier positioning for other elements */
    padding: 0 20px 0 20px;
    width: 100%;
    bottom: 0;
    left: 0;
    background: var(--header-background);
    z-index: -1; /* because the position is absolutely positioned it get a higher z-index, but we need to revert it to avoid any trouble */
    transition: visibility 0.25s ease-in-out, margin-bottom 0.25s ease-in-out;
  }

  .header__search-bar-wrapper.is-visible {
    visibility: visible;
    margin-bottom: -59px;
  }

  /* When the user focus it, it becomes a fixed element */
  .header__search-bar-wrapper.is-fixed {
    position: fixed;
    top: 0;
    left: 0;
    height: 100vh;
    z-index: 10;
  }
}

@media screen and (min-width: 641px) {
  .header__action-list {
    padding-left: 28px;
  }

  .header__action-item,
  .header__action-item-content {
    position: relative;
  }

  .header__action-item-content {
    max-width: -webkit-max-content;
    max-width: -moz-max-content;
    max-width: max-content;
  }

  .header__action-item .icon--lock-2 {
    vertical-align: text-top;
  }
}

@media screen and (min-width: 1000px) {
  .header__action-list {
    padding-left: 5px;
  }

  .header__action-item:not(:last-child)::after {
    position: absolute;
    content: "";
    right: 0;
    top: calc(50% - 17px);
    background: var(--header-border-color);
    height: 34px;
    width: 1px;
  }

  .header__action-item--currency {
    margin-right: 20px;
  }
}

@media screen and (min-width: 1000px) and (max-width: 1279px) {
  .header__action-item:not(.header__action-item--currency):not(.header__action-item--locale)::after {
    display: none;
  }

  .header__action-item--currency + .header__action-item--locale {
    padding-left: 9px;
  }

  /* Not really beautiful but coulnd't find a better way */
  .header__action-item.hidden-tablet-and-up:first-child + .header__action-item {
    padding-left: 35px;
  }
}

@media screen and (min-width: 1280px) {
  .header__action-item {
    padding: 0 20px;
  }

  .header__action-item:last-child {
    padding-right: 0;
  }

  .header__action-item--currency,
  .header__action-item--locale {
    margin-right: 0;
  }

  .header__cart-icon {
    display: inline-block;
    margin-right: 22px;
    top: 4px; /* Slight adjustment for the pixel perfect muahah */
    margin-top: 0px!important;
  }
}

/**
 * --------------------------------------------------------------------
 * SEARCH
 * --------------------------------------------------------------------
 */

.search-bar {
  position: relative;
  min-width: 100%;
  padding-bottom: 15px;
  z-index: 1;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 15px));
}

/* Top part */
.search-bar__top {
  position: relative;
  display: flex;
  height: 45px;
  align-items: center;
  justify-content: space-between;
  border-radius: 40px;
  background: #fff;
  color: var(--text-color);
  z-index: 1;
}

.search-bar__input-wrapper {
  position: relative;
  height: 100%;
}

.search-bar__input {
  height: 100%;
  width: 100%;
  padding: 0 15px 1px 25px;
  border: none;
  background: transparent;
  line-height: normal;
  color: var(--heading-color);
  -webkit-appearance: none;
}

.search-bar__input::-webkit-input-placeholder {
  color: var(--text-color);
  opacity: 1;
}

.search-bar__input::-moz-placeholder {
  color: var(--text-color);
  opacity: 1;
}

.search-bar__input:-ms-input-placeholder {
  color: var(--text-color);
  opacity: 1;
}

.search-bar__input::-ms-input-placeholder {
  color: var(--text-color);
  opacity: 1;
}

.search-bar__input::placeholder {
  color: var(--text-color);
  opacity: 1;
}

.search-bar__input::-ms-clear {
  display: none;
}

.search-bar__input:focus {
  outline: none;
}

.search-bar__input-clear {
  position: absolute;
  right: 15px;
  top: calc(50% - 9px);
  display: none;
  opacity: 0.5;
}

.search-bar__input-clear svg {
  display: block;
  width: 17px;
  height: 17px;
}

.search-bar__input.is-filled + .search-bar__input-clear {
  display: block;
}

.search-bar__filter {
  display: none;
  border-left: 1px solid var(--header-border-color);
}

.search-bar__filter-label {
  display: block;
  height: 44px;
  padding: 0 30px 0 25px;
  line-height: 43px; /* The -1px allows to account for rounding errors */
}

.search-bar__filter-label svg {
  margin-left: 11px;
  width: 12px;
  height: 8px;
}

.search-bar__submit {
    flex: none;
    width: 60px;
    background: var(--header-accent-color);
    height: 37px;
    border-radius: 100px;
    color: white;
    margin-right: 4px;
}

.search-bar__submit svg {
  position: relative;
}

.search-bar__submit .icon--search {
  width: 18px;
  height: 19px;
}

.search-bar__submit .icon--search-loader {
  display: none;
  width: 24px;
  height: 24px;
  margin: 0 auto;
}

/* Inner */
.search-bar__inner {
  position: absolute;
  visibility: hidden;
  left: -20px;
  top: calc(100% + 8px);
  width: 100vw;
  height: 100vh;
  overflow: hidden;
  color: var(--text-color);
  background: var(--secondary-background);
}

@supports (--css: variables) {
  .search-bar__inner {
    height: calc(100vh - var(--header-height) - 25px);
  }
}

.search-bar__inner-animation {
  height: 100%;
}

.search-bar__results,
.search-bar__menu-wrapper {
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  background: var(--secondary-background);
  box-shadow: 0 1px 5px 2px rgba(0, 0, 0, 0.1);
  visibility: hidden;
  transition: visibility 0.1s ease-in-out;
}

.search-bar__results[aria-hidden=false],
.search-bar__menu-wrapper[aria-hidden=false] {
  visibility: visible;
}

.search-bar.is-expanded .search-bar__inner-animation {
  visibility: visible;
}

.search-bar__empty-state {
  text-align: center;
  padding: 50px 0;
}

/* To reduce the complexity of JavaScript and use Liquid as much as possible, the live search will output both
   the result for products and/or pages and blogs. We therefore then hide possible duplicate status in CSS */
.search-bar__result-products ~ .search-bar__empty-state {
  display: none;
}

/* Quick links */
.search-bar__menu-title {
  margin-bottom: 4px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
}

.search-bar__menu-wrapper {
  padding: 18px 0 12px 0;
  height: 100%;
  overflow: auto;
  -ms-scroll-chaining: none;
      overscroll-behavior: none;
}

.search-bar__menu-title,
.search-bar__menu-link {
  padding-left: 20px;
  padding-right: 20px;
}

.search-bar__menu-link {
  display: block;
  padding-top: 6px;
  padding-bottom: 6px;
  transition: color 0.15s ease-in-out, background 0.15s ease-in-out;
}

.search-bar__menu-link:hover, .search-bar__menu-link:focus {
  background: var(--accent-background);
  color: var(--accent-color);
  outline: none;
}

/* Results */
.search-bar__results .skeleton-container {
  display: none;
}

.search-bar__results {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  height: 100%;
  overflow: auto;
  -ms-scroll-chaining: none;
      overscroll-behavior: none;
}

.search-bar__result-category {
  margin: 0;
  padding: 4px 20px;
  text-transform: uppercase;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
  font-weight: var(--text-font-bolder-weight);
  background: var(--background);
  box-shadow: 0 1px var(--border-color), 0 -1px var(--border-color);
}

.search-bar__result-item {
  display: flex;
  align-items: center;
  padding: 15px 20px;
  transition: background 0.2s ease-in-out;
}

.search-bar__result-item:not(.search-bar__result-item--skeleton):hover,
.search-bar__result-item:not(.search-bar__result-item--skeleton):focus {
  background: var(--accent-background);
  outline: none;
}

.search-bar__result-item--skeleton {
  max-width: 300px;
}

.search-bar__image-container {
  flex: none;
  width: 60px;
  margin-right: 20px;
}

.search-bar__image-container img {
  color: transparent; /* allows to remove the alt on Firefox during image loading */
}

.search-bar__item-info {
  flex: 1 0 0;
}

.search-bar__item-title {
  margin-bottom: 0;
  line-height: 1.4;
}

.search-bar__item-price {
  color: var(--accent-color);
}

.search-bar__result-link {
  display: block;
  padding: 5px 20px;
  transition: color 0.2s ease-in-out, background 0.2s ease-in-out;
}

.search-bar__result-link:hover, .search-bar__result-link:focus {
  color: var(--accent-color);
  background: var(--accent-background);
  outline: none;
}

.search-bar__view-all {
  display: block;
  padding: 10px;
  width: 100%;
  text-align: center;
  font-weight: var(--text-font-bolder-weight);
  color: var(--accent-color);
  transition: background 0.2s ease-in-out;
}

.search-bar__view-all:hover,
.search-bar__view-all:focus {
  background: var(--accent-background);
  outline: none;
}

.search-bar__view-all svg {
  width: 6px;
  height: 10px;
  margin-left: 12px;
}

.search-bar__view-all path {
  stroke-width: 2.5px;
}

/* Loading state */
.search-bar.is-loading .search-bar__results-inner,
.search-bar.is-loading .search-bar__submit .icon--search {
  display: none;
}

.search-bar.is-loading .skeleton-container {
  display: block;
}

.search-bar.is-loading .search-bar__submit .icon--search-loader {
  display: block;
}

/* This is not really mobile-first for this specific part, but the mobile styles are way too specific so I prefer to have them here rather than having complex overwritings */
@media screen and (max-width: 640px) {
  .search-bar {
    opacity: 0;
    transition: opacity 0.2s ease-in-out;
  }

  .search-bar__inner {
    max-height: 0; /* This is needed to fix a bug on iOS, DO NOT REMOVE */
    height: calc(100vh - calc(44px - 18px)); /* 18px is padding around input element */
    top: 100%;
  }

  .search-bar__top-wrapper {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .search-bar__top {
    flex-grow: 1;
  }

  .search-bar__close-button {
    width: 0;
    height: 0;
    overflow: hidden;
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
    opacity: 0;
    transition: width 0.25s ease-in-out, opacity 0.25s ease-in-out;
  }

  .search-bar__close-text {
    padding-left: 22px;
  }

  .header__search-bar-wrapper.is-visible .search-bar {
    opacity: 1;
    transition-delay: 0.15s;
  }

  .header__search-bar-wrapper.is-fixed .search-bar {
    padding: 9px 0;
  }

  .header__search-bar-wrapper.is-fixed .search-bar__inner {
    max-height: none;
    visibility: visible;
  }

  .header__search-bar-wrapper.is-fixed .search-bar__inner-animation {
    transition: none;
  }

  .header__search-bar-wrapper.is-fixed .search-bar__close-button {
    height: auto;
    opacity: 1;
    white-space: nowrap;
  }
}

@media screen and (min-width: 641px) {
  .search-bar {
    margin-top: 0;
    padding-bottom: 0;
    min-width: 0;
  }

  .search-bar__inner {
    width: calc(100% - 40px); /* we do a little trick here to being able to use overflow hidden while still displaying box-shadow */
    top: 100%;
    left: -5px;
  }
  @supports (--css: variables) {
    .search-bar__inner {
      height: calc(100vh - var(--header-height) - 40px);
    }
  }

  .search-bar__submit .icon--search {
    top: 0px;
  }

  .search-bar__result-category {
    padding-left: 15px;
  }

  .search-bar__results {
    max-height: 310px;
    height: auto;
  }

  @supports (--css: variables) {
    .search-bar__results {
      max-height: calc(100vh - var(--header-height) - 40px);
    }
  }

  .search-bar__menu-wrapper {
    max-height: 310px;
    height: auto;
  }

  .search-bar__results,
  .search-bar__menu-wrapper {
    left: 5px;
    width: calc(100% - 10px);
    border-radius: 0 0 3px 3px;
  }

  .search-bar__menu-title,
  .search-bar__menu-link {
    padding-left: 25px;
    padding-right: 25px;
  }

  /* Expanded state */
  .search-bar.is-expanded .search-bar__top {
    border-bottom-left-radius: 0;
  }
}

@media screen and (min-width: 1280px) {
  .search-bar__filter {
    position: relative;
    display: block;
    height: 100%;
  }

  .search-bar__filter select {
    position: absolute;
    opacity: 0;
    width: 100%;
    height: 100%;
    left: 0;
    top: 0;
    -webkit-appearance: none;
  }
}
.map {
  padding: 0 20px;
  background: var(--secondary-background);
  border-radius: 3px;
  border: 1px solid var(--border-color);
}

.map__store-item:not(:last-child) {
  border-bottom: 1px solid var(--border-color);
}

.map__store-name {
  display: flex;
  width: 100%;
  align-items: center;
  justify-content: space-between;
  padding: 15px 0;
}

.map__store-name svg {
  width: 12px;
  height: 8px;
}

.map__icon-container {
  transform: rotateZ(0deg);
  transition: transform 0.2s ease-in-out;
}

.map__store-name[aria-expanded=true] .map__icon-container {
  transform: rotateZ(180deg);
}

.map__store-collapsible {
  display: block;
  height: 0;
  overflow: hidden;
  transition: height 0.25s ease-in-out;
}

.map__store-inner {
  margin-top: -0.425em;
}

.map__store-address {
  margin-bottom: 15px;
}
.map__store-address > p {
  margin-bottom: 0 !important;
}

.map__store-hours {
  margin-bottom: 22px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
}

.map__direction-link,
.map__map-container {
  margin-bottom: 30px;
}

.map__map-container {
  position: relative;
  height: 160px;
  background-size: cover;
  background-position: center;
  overflow: hidden;
}

.map__gmap {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
}

@media screen and (min-width: 641px) {
  .map__map-container {
    height: 300px;
  }
}

@media screen and (min-width: 1000px) {
  .map {
    display: flex;
    height: 405px;
    padding: 0;
  }

  .map__store-list {
    width: 50%;
    max-width: 580px;
    border-right: 1px solid var(--border-color);
  }

  .map__map-container {
    height: 100%;
    flex: 1 0 auto;
    margin: 0;
  }

  .map__store-list {
    padding: 0 40px 0 30px;
    overflow: auto;
  }

  .map__store-name {
    padding: 20px 0;
  }

  .map__store-address {
    margin-bottom: 22px;
  }
}
/**
 * --------------------------------------------------------------------
 * MEDIA API
 *
 * All those colors have been defined by Shopify and standardized by them
 * --------------------------------------------------------------------
 */
.plyr.plyr--full-ui.plyr--video {
  color: var(--text-color);
  background-color: transparent;
  /* stylelint-disable-next-line */
  /* stylelint-disable-next-line */
  /* stylelint-disable-next-line */
}
.plyr.plyr--full-ui.plyr--video .plyr__video-wrapper {
  background-color: transparent;
}
.plyr.plyr--full-ui.plyr--video:-webkit-full-screen .plyr__video-wrapper .plyr.plyr--full-ui.plyr--video:-webkit-full-screen .plyr__poster {
  background-color: #000;
}
.plyr.plyr--full-ui.plyr--video:-ms-fullscreen .plyr__video-wrapper .plyr.plyr--full-ui.plyr--video:-ms-fullscreen .plyr__poster {
  background-color: #000;
}
.plyr.plyr--full-ui.plyr--video:fullscreen .plyr__video-wrapper .plyr.plyr--full-ui.plyr--video:fullscreen .plyr__poster {
  background-color: #000;
}
.plyr.plyr--full-ui.plyr--video:-webkit-full-screen .plyr__video-wrapper, .plyr.plyr--full-ui.plyr--video:-webkit-full-screen .plyr__poster {
  background-color: #000;
}
.plyr.plyr--full-ui.plyr--video:-moz-full-screen .plyr__video-wrapper, .plyr.plyr--full-ui.plyr--video:-moz-full-screen .plyr__poster {
  background-color: #000;
}
.plyr.plyr--full-ui.plyr--video:-ms-fullscreen .plyr__video-wrapper, .plyr.plyr--full-ui.plyr--video:-ms-fullscreen .plyr__poster {
  background-color: #000;
}
.plyr.plyr--full-ui.plyr--video .plyr--fullscreen-fallback .plyr__video-wrapper,
.plyr.plyr--full-ui.plyr--video .plyr--fullscreen-fallback .plyr__poster {
  background-color: #000;
}
.plyr.plyr--full-ui.plyr--video .plyr__controls {
  background-color: var(--secondary-background);
  border-color: rgba(var(--text-color-rgb), 0.05);
}
.plyr.plyr--full-ui.plyr--video .plyr__control.plyr__control--overlaid {
  background-color: var(--secondary-background);
  border-color: rgba(var(--text-color-rgb), 0.05);
}
.plyr.plyr--full-ui.plyr--video .plyr__control.plyr__control--overlaid.plyr__tab-focus, .plyr.plyr--full-ui.plyr--video .plyr__control.plyr__control--overlaid:hover {
  color: rgba(var(--text-color-rgb) 0.55);
}
.plyr.plyr--full-ui.plyr--video .plyr__progress input[type=range]::-moz-range-thumb {
  box-shadow: 2px 0 0 0 var(--secondary-background);
}
.plyr.plyr--full-ui.plyr--video .plyr__progress input[type=range]::-ms-thumb {
  box-shadow: 2px 0 0 0 var(--secondary-background);
}
.plyr.plyr--full-ui.plyr--video .plyr__progress input[type=range]::-webkit-slider-thumb {
  box-shadow: 2px 0 0 0 var(--secondary-background);
}
.plyr.plyr--full-ui.plyr--video .plyr__progress input[type=range]::-webkit-slider-runnable-track {
  background-image: linear-gradient(to right, currentColor 0, rgba(var(--text-color-rgb) 0.6)) 0);
  background-image: linear-gradient(to right, currentColor var(--value, 0), rgba(var(--text-color-rgb) 0.6)) var(--value, 0));
}
.plyr.plyr--full-ui.plyr--video .plyr__progress input[type=range]::-moz-range-track {
  background-color: rgba(var(--text-color-rgb) 0.6);
}
.plyr.plyr--full-ui.plyr--video .plyr__progress input[type=range]::-ms-fill-upper {
  background-color: rgba(var(--text-color-rgb) 0.6);
}
.plyr.plyr--full-ui.plyr--video .plyr__progress input[type=range].plyr__tab-focus::-webkit-slider-runnable-track {
  box-shadow: 0 0 0 4px rgba(var(--text-color-rgb) 0.25);
}
.plyr.plyr--full-ui.plyr--video .plyr__progress input[type=range].plyr__tab-focus::-moz-range-track {
  box-shadow: 0 0 0 4px rgba(var(--text-color-rgb) 0.25);
}
.plyr.plyr--full-ui.plyr--video .plyr__progress input[type=range].plyr__tab-focus::-ms-track {
  box-shadow: 0 0 0 4px rgba(var(--text-color-rgb) 0.25);
}
.plyr.plyr--full-ui.plyr--video .plyr__progress input[type=range]:active::-moz-range-thumb {
  box-shadow: 0 0 0 3px rgba(var(--text-color-rgb) 0.25);
}
.plyr.plyr--full-ui.plyr--video .plyr__progress input[type=range]:active::-ms-thumb {
  box-shadow: 0 0 0 3px rgba(var(--text-color-rgb) 0.25);
}
.plyr.plyr--full-ui.plyr--video .plyr__progress input[type=range]:active::-webkit-slider-thumb {
  box-shadow: 0 0 0 3px rgba(var(--text-color-rgb) 0.25);
}
.plyr.plyr--full-ui.plyr--video .plyr__progress .plyr__tooltip {
  background-color: var(--text-color);
  color: var(--secondary-background);
}
.plyr.plyr--full-ui.plyr--video .plyr__progress .plyr__tooltip::before {
  border-top-color: var(--text-color);
}
.plyr.plyr--full-ui.plyr--video.plyr--loading .plyr__progress__buffer {
  background-image: linear-gradient(-45deg, rgba(var(--text-color-rgb) 0.6) 25%, transparent 25%, transparent 50%, rgba(var(--text-color-rgb) 0.6) 50%, rgba(var(--text-color-rgb) 0.6) 75%, transparent 75%, transparent);
}
.plyr.plyr--full-ui.plyr--video .plyr__volume input[type=range] {
  color: var(--secondary-background);
}
.plyr.plyr--full-ui.plyr--video .plyr__volume input[type=range]::-moz-range-thumb {
  box-shadow: 2px 0 0 0 var(--text-color);
}
.plyr.plyr--full-ui.plyr--video .plyr__volume input[type=range]::-ms-thumb {
  box-shadow: 2px 0 0 0 var(--text-color);
}
.plyr.plyr--full-ui.plyr--video .plyr__volume input[type=range]::-webkit-slider-thumb {
  box-shadow: 2px 0 0 0 var(--text-color);
}
.plyr.plyr--full-ui.plyr--video .plyr__volume input[type=range]::-webkit-slider-runnable-track {
  background-image: linear-gradient(to right, currentColor 0, rgba(var(--secondary-background-rgb), 0.6) 0);
  background-image: linear-gradient(to right, currentColor var(--value, 0), rgba(var(--secondary-background-rgb), 0.6) var(--value, 0));
}
.plyr.plyr--full-ui.plyr--video .plyr__volume input[type=range]::-moz-range-track, .plyr.plyr--full-ui.plyr--video .plyr__volume input[type=range]::-ms-fill-upper {
  background-color: rgba(var(--secondary-background-rgb), 0.6);
}
.plyr.plyr--full-ui.plyr--video .plyr__volume input[type=range].plyr__tab-focus::-webkit-slider-runnable-track {
  box-shadow: 0 0 0 4px rgba(var(--secondary-background-rgb), 0.25);
}
.plyr.plyr--full-ui.plyr--video .plyr__volume input[type=range].plyr__tab-focus::-moz-range-track {
  box-shadow: 0 0 0 4px rgba(var(--secondary-background-rgb), 0.25);
}
.plyr.plyr--full-ui.plyr--video .plyr__volume input[type=range].plyr__tab-focus::-ms-track {
  box-shadow: 0 0 0 4px rgba(var(--secondary-background-rgb), 0.25);
}
.plyr.plyr--full-ui.plyr--video .plyr__volume input[type=range]:active::-moz-range-thumb {
  box-shadow: 0 0 0 3px rgba(var(--secondary-background-rgb), 0.25);
}
.plyr.plyr--full-ui.plyr--video .plyr__volume input[type=range]:active::-ms-thumb {
  box-shadow: 0 0 0 3px rgba(var(--secondary-background-rgb), 0.25);
}
.plyr.plyr--full-ui.plyr--video .plyr__volume input[type=range]:active::-webkit-slider-thumb {
  box-shadow: 0 0 0 3px rgba(var(--secondary-background-rgb), 0.25);
}

.shopify-model-viewer-ui.shopify-model-viewer-ui .shopify-model-viewer-ui__controls-area {
  background: var(--secondary-background);
  border-color: rgba(var(--text-color-rgb) 0.05);
}
.shopify-model-viewer-ui.shopify-model-viewer-ui .shopify-model-viewer-ui__button {
  color: var(--text-color);
}
.shopify-model-viewer-ui.shopify-model-viewer-ui .shopify-model-viewer-ui__button--control:hover {
  color: rgba(var(--text-color-rgb) 0.55);
}
.shopify-model-viewer-ui.shopify-model-viewer-ui .shopify-model-viewer-ui__button--control:active, .shopify-model-viewer-ui.shopify-model-viewer-ui .shopify-model-viewer-ui__button--control.focus-visible:focus {
  color: rgba(var(--text-color-rgb) 0.55);
  background: rgba(var(--text-color-rgb) 0.05);
}
.shopify-model-viewer-ui.shopify-model-viewer-ui .shopify-model-viewer-ui__button--control:not(:last-child):after {
  border-color: rgba(var(--text-color-rgb) 0.05);
}
.shopify-model-viewer-ui.shopify-model-viewer-ui .shopify-model-viewer-ui__button--poster {
  background: var(--secondary-background);
  border-color: rgba(var(--text-color-rgb) 0.05);
}
.shopify-model-viewer-ui.shopify-model-viewer-ui .shopify-model-viewer-ui__button--poster:hover, .shopify-model-viewer-ui.shopify-model-viewer-ui .shopify-model-viewer-ui__button--poster:focus {
  color: rgba(var(--text-color-rgb) 0.55);
}

/**
 * --------------------------------------------------------------------
 * VIDEO WRAPPER
 * --------------------------------------------------------------------
 */

.video-wrapper {
  position: relative;
  cursor: pointer;
}
.video-wrapper::after {
  content: "";
  display: block;
  padding-bottom: 56.25%;
  /* 16:9 */
}

.video-wrapper iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.video-wrapper iframe:not([src]) {
  pointer-events: none;
}

/* For native one we use a different thing */
.video-wrapper--native::after {
  display: none;
}
.video-wrapper--native .plyr,
.video-wrapper--native video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
.video-wrapper--native .plyr__video-wrapper,
.video-wrapper--native video {
  height: 100%;
}

.video-wrapper__image-wrapper {
  opacity: 1;
  visibility: visible;
  transition: opacity 0.2s ease-in-out, visibility 0.2s ease-in-out;
}

.video-wrapper__image-wrapper,
.video-wrapper__image {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.video-wrapper__image {
  -o-object-fit: cover;
     object-fit: cover;
  -o-object-position: center;
     object-position: center;
  font-family: "object-fit: cover; object-position: center";
  /* IE 11 polyfill */
}

.icon--play {
  -webkit-filter: drop-shadow(0px 2px 2px rgba(0, 0, 0, 0.4));
          filter: drop-shadow(0px 2px 2px rgba(0, 0, 0, 0.4));
}

.video-wrapper .icon--play {
  position: absolute;
  left: calc(50% - 40px);
  top: calc(50% - 40px);
  height: 80px;
  width: 80px;
  opacity: 1;
  transition: transform 0.2s ease-in-out, opacity 0.2s ease-in-out;
}

@media (-moz-touch-enabled: 0),(hover: hover) {
  .video-wrapper:hover .icon--play {
    transform: scale(1.15);
  }
}

/**
 * --------------------------------------------------------------------
 * VIDEO ITEM (used for standalone section)
 * --------------------------------------------------------------------
 */

.video-item {
  max-width: 855px;
  margin: 20px auto;
}

.video-item--stretch {
  max-width: none;
}

.video-item[aria-hidden=true] {
  display: none;
}

.video-item .video-wrapper iframe {
  visibility: hidden;
  height: 0;
  width: 0; /* setting dimensions to zero allows to fix a bug in Safari iOS on which the iframe will capture all the clicks */
}

.video-item.is-playing .video-wrapper__image-wrapper {
  visibility: hidden;
  opacity: 0;
}

.video-item.is-playing iframe {
  visibility: visible;
  height: 100%;
  width: 100%;
}

/**
 * --------------------------------------------------------------------
 * 3D MODEL WRAPPER
 * --------------------------------------------------------------------
 */
.model-wrapper {
  position: relative;
  padding-bottom: 100%;
}

.model-wrapper .shopify-model-viewer-ui,
.model-wrapper model-viewer {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
.mosaic {
  margin: 0 -10px -20px -10px;
}

.mosaic__item {
  padding: 0 10px 20px 10px;
}

.mosaic__item > :first-child {
  min-height: 240px;
}

.mosaic--large .mosaic__item > :first-child {
  min-height: 280px;
}

@media screen and (max-width: 999px) {
  /* On mobile we increase the height of some elements (so that elements that appear bigger on desktop also appear bigger on mobile */
  .mosaic--two-columns .mosaic__column:first-child .mosaic__item > :first-child,
  .mosaic--three-columns .mosaic__column:nth-child(2) .mosaic__item > :first-child {
    min-height: 340px;
  }
}

@media screen and (min-width: 641px) {
  .mosaic {
    margin: 0 -15px -30px -15px;
  }

  .mosaic__item {
    padding: 0 15px 30px 15px;
  }
}

@media screen and (min-width: 1000px) {
  .mosaic {
    display: flex;
  }

  .mosaic__column {
    display: flex;
    flex-direction: column;
    flex: 1 0 0%;
  }

  .mosaic__item {
    display: flex;
    flex-direction: column;
    flex: 1 0 auto;
  }

  .mosaic__item > :first-child {
    flex: 1 0 auto;
    height: 100%;
    min-height: 260px;
  }

  .mosaic--small .mosaic__item > :first-child {
    min-height: 225px;
  }

  .mosaic--large .mosaic__item > :first-child {
    min-height: 300px;
  }

  /* In this configuration the first column is larger */
  .mosaic--two-columns .mosaic__column:first-child {
    flex-grow: 1.38;
  }

  /* In this configuration the second column is twice as large as others */
  .mosaic--three-columns .mosaic__column:nth-child(2) {
    flex-grow: 1.38;
  }
}
/**
 * --------------------------------------------------------------------
 * DROPDOWN MENU
 * --------------------------------------------------------------------
 */

.nav-dropdown {
  position: absolute;
  top: 100%;
  padding: 16px 0;
  list-style: none;
  background: var(--secondary-background);
  color: var(--text-color);
  border-radius: 0 0 3px 3px;
  white-space: nowrap;
  visibility: hidden;
  opacity: 0;
  z-index: 1;
  transition: opacity 0.2s ease-in-out, visibility 0.2s ease-in-out;
  box-shadow: 0 1px 5px 2px rgb(0 0 0 / 5%);
}

.nav-dropdown:not(.nav-dropdown--floating) {
  left: -15px;
}

.nav-dropdown--floating {
  margin-top: 7px;
  border: none;
  border-radius: 3px;
}

.nav-dropdown--floating::before {
  position: absolute;
  content: "";
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  box-shadow: 0 5px 5px -2px rgba(0, 0, 0, 0.1), 5px 0 5px -2px rgba(0, 0, 0, 0.1), 0 -5px 5px -2px rgba(0, 0, 0, 0.1);
  z-index: -1;
}

.nav-dropdown--glued:not(.nav-dropdown--inverse) {
  border-top-right-radius: 0 !important;
  border-bottom-right-radius: 0 !important;
}

.nav-dropdown--glued.nav-dropdown--inverse {
  border-top-left-radius: 0 !important;
  border-bottom-left-radius: 0 !important;
}

.nav-dropdown--fixed {
  min-height: 420px;
}

.nav-dropdown--restrict {
  max-height: calc(100vh - 0px - 0px - 40px);
  max-height: calc(100vh - var(--header-height, 0px) - var(--announcement-bar-height, 0px) - 40px);
  overflow: auto;
  -ms-scroll-chaining: none;
      overscroll-behavior: contain;
}

/* We have a way to set a max height for browsers supporting CSS variables */
@supports (--css: variables) {
  .nav-bar .nav-dropdown .nav-dropdown {
    max-height: calc(100vh - 0px - 40px);
    max-height: calc(100vh - var(--distance-to-top, 0px) - 40px);
    overflow: auto;
    -ms-scroll-chaining: none;
        overscroll-behavior: contain;
  }
}

.nav-dropdown[aria-hidden=false] {
  visibility: visible;
  opacity: 1;
}

.nav-dropdown .icon--nav-triangle-borderless {
  position: absolute;
  bottom: 100%;
  left: 16px;
  width: 20px;
  height: 9px;
  z-index: 1;
}

.nav-dropdown .icon--nav-triangle-left {
  position: absolute;
  top: 23px;
  right: 100%;
  height: 20px;
  width: 9px;
  z-index: 1;
}

.nav-dropdown__item:not(.has-mega-menu) {
  position: relative;
}

.nav-dropdown__link {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 2px 60px 2px 20px;
  cursor: pointer;
}

.nav-dropdown__link svg {
  position: relative;
  width: 8px;
  height: 12px;
  top: 1px;
  margin: 0 -40px 0 65px;
}

.nav-dropdown__link[aria-expanded=true] {
  color: var(--accent-color);
}

/* Handle sub-levels */
.nav-dropdown .nav-dropdown {
  left: 100%;
  top: -17px; /* 16px + 1px of border */
  margin-top: 0;
  min-width: 0;
  border-radius: 0 3px 3px 0;
}

.nav-dropdown--inverse .nav-dropdown {
  right: 100%;
  left: auto;
  border-radius: 3px 0 0 3px;
}

.nav-dropdown--inverse .nav-dropdown .icon--nav-triangle-left {
  right: auto;
  left: 100%;
  transform: rotateZ(180deg);
}

.nav-dropdown .nav-dropdown--floating {
  top: -16px; /* floating dropdown do not have border so there is one less pixel */
  border-left: 1px solid var(--border-color);
}

/**
 * --------------------------------------------------------------------
 * MEGA MENU
 * --------------------------------------------------------------------
 */

.mega-menu {
  position: absolute;
  width: 100vw;
  left: 0;
  top: 100%;
  background: var(--secondary-background);
  border-radius: 0 0 3px 3px;
  border-top: 1px solid var(--border-color);
  border-bottom: 1px solid var(--border-color);
  visibility: hidden;
  opacity: 0;
  transition: opacity 0.2s ease-in-out, visibility 0.2s ease-in-out;
}

.mega-menu--floating {
  max-width: 0;
}

.mega-menu[aria-hidden=false] {
  visibility: visible;
  opacity: 1;
}

.mega-menu__inner {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  padding: 25px 0 0 0;
  max-height: 100%;
  min-height: 100%;
  overflow: auto;
  -ms-scroll-chaining: none;
      overscroll-behavior: none;
}

.mega-menu__inner--center {
  justify-content: center;
}

.mega-menu__promo {
  display: block;
  flex: 0 1 230px;
  width: 230px;
  min-width: 200px;
  margin: 0 0 30px 50px;
  white-space: normal;
  text-align: center;
}

.mega-menu__promo + .mega-menu__promo {
  margin-left: 20px;
}

.mega-menu__column-list {
  display: flex;
  flex: 1 1 auto;
  flex-wrap: wrap;
  margin: 0 -40px;
  min-width: 0;
}

@supports (display: grid) {
  .mega-menu__column-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  }
}

.mega-menu__column {
  display: block;
  flex: 0 1 auto;
  margin: 0 30px 30px 30px;
}

.mega-menu:not(.mega-menu--floating) .mega-menu__column:first-child {
  margin-left: 0 !important;
}
.mega-menu:not(.mega-menu--floating) .mega-menu__column:last-child {
  margin-right: 0 !important;
}

.mega-menu__title {
  display: block;
  margin-bottom: 10px;
}

.mega-menu__linklist {
  list-style: none;
}

.mega-menu__link {
  display: block;
  padding: 5px 0 6px 0;
  line-height: 1.4;
}

.mega-menu__image-wrapper {
  margin: 5px 0 22px 0;
  border-radius: 3px;
  overflow: hidden;
}

.mega-menu__promo .aspect-ratio {
  transform: scale(1.01); /* This is necessary to fix an issue with rounding pixels on Chrome */
  transition: transform 0.6s ease-in-out;
}

.features--animate-zoom .mega-menu__promo:hover .aspect-ratio {
  transform: scale(1.06);
}

.mega-menu__promo:hover .mega-menu__image-heading {
  color: var(--accent-color);
}

.mega-menu__image-heading {
  display: block;
  margin-bottom: 7px;
  transition: color 0.2s ease-in-out;
}

.mega-menu__image-text {
  line-height: 1.5;
}

/* When inside a nav-bar (inline navigation) we have to restrict the height, so that in case it contains way too many links
   it can become scrollable. The 40px is just a way to give a bit more space below */
.nav-bar .mega-menu {
  max-height: calc(100vh - 0px - 0px - 40px);
  max-height: calc(100vh - var(--header-height, 0px) - var(--announcement-bar-height, 0px) - 40px);
  overflow: auto;
  -ms-scroll-chaining: none;
      overscroll-behavior: contain;
}

@media screen and (min-width: 1280px) {
  .mega-menu__column {
    margin-left: 40px;
    margin-right: 40px;
  }

  .mega-menu__inner--large .mega-menu__column {
    margin-left: 50px;
    margin-right: 50px;
  }

  .mega-menu__promo {
    flex-basis: 290px;
    width: 290px;
  }
}

@media screen and (min-width: 1440px) {
  .mega-menu__inner--center .mega-menu__column {
    margin-left: 45px;
    margin-right: 45px;
  }

  .mega-menu__inner--large .mega-menu__column {
    margin-left: 60px;
    margin-right: 60px;
  }

  .mega-menu__promo {
    min-width: 240px;
  }
}

/* Floating mega-menu variation */
.mega-menu--floating {
  width: 100vw;
  height: 100%;
  left: 100%;
  top: 0;
  border: none;
  border-radius: 0 3px 3px 0;
  border-left: 1px solid var(--border-color);
}

.mega-menu--floating::before {
  position: absolute;
  content: "";
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  box-shadow: 0 5px 5px -2px rgba(0, 0, 0, 0.1), 5px 0 5px -2px rgba(0, 0, 0, 0.1), 0 -5px 5px -2px rgba(0, 0, 0, 0.1);
  z-index: -1;
}

.mega-menu--floating .mega-menu__inner {
  margin: 0;
  padding-right: 30px;
  padding-left: 25px;
  /*max-width: 0;*/
  /* We do that to prevent overflow as the real size is dynamically calculated based on available space */
}
.mega-menu--floating .mega-menu__title {
  margin-bottom: 5px;
}

.mega-menu--floating .mega-menu__column {
  display: block;
  flex: 0 0 170px;
  margin-right: 30px;
  margin-left: 30px;
  white-space: normal;
}

.mega-menu--floating .mega-menu__column-list {
  margin: 0 -30px;
}

/**
 * --------------------------------------------------------------------
 * NAV BAR (this one is the inline navigation used on desktop)
 * --------------------------------------------------------------------
 */

.nav-bar {
  display: none;
}

@media screen and (min-width: 1000px) {
  .nav-bar {
    display: block;
    position: relative;
    left: 0;
    width: 100%;
    background: var(--header-background);
    text-align: center;
  }

  .nav-bar::after {
    content: "";
    position: absolute;
    height: 100%;
    width: 40px;
    right: 0;
    top: 0;
    background: var(--header-background);
  }

  .nav-bar__item {
    color: var(--header-cordotexto);
    position: relative;
    display: inline-block;
    margin-right: 35px;
    padding: 12px 0px 16px 0;
    text-align: center;
    font-size: 14px;
  }

  .nav-bar__item--static {
    position: static;
  }

  .nav-bar__item > .nav-dropdown {
    min-width: calc(100% + 20px);
    border-radius: 10px;
  }

  .nav-bar__link {
    display: block;
    cursor: pointer;
  }

  .nav-bar__link .icon--arrow-bottom {
    width: 12px;
    height: 8px;
    margin-left: 10px;
  }

  .nav-bar__link .icon--nav-triangle {
    opacity: 0;
    position: absolute;
    bottom: -1px;
    width: 20px;
    height: 9px;
    margin-left: -16px;
    z-index: 2;
    transition: 0.2s ease-in-out;
  }

  .nav-bar__link[aria-expanded=true] {
    color: var(--accent-color);
  }

  .nav-bar__link[aria-expanded=true] .icon--nav-triangle {
    opacity: 1;
  }
}

/**
 * --------------------------------------------------------------------
 * MOBILE MENU
 * --------------------------------------------------------------------
 */

.mobile-menu {
  position: absolute;
  width: 100vw;
  height: 100vh;
  left: 0;
  top: 100%;
  visibility: hidden;
  max-height: 0; /* This is needed to fix a bug on iOS, DO NOT REMOVE */
  z-index: 1;
  opacity: 0;
  color: var(--text-color);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
  transform: scale(0.9);
  transition: opacity 0.25s ease-in-out, transform 0.25s ease-in-out, visibility 0.25s ease-in-out, max-height 0s linear 0.25s;
  will-change: transform;
}

.mobile-menu .icon--arrow-right,
.mobile-menu .icon--arrow-left {
  width: 8px;
  height: 12px;
}

.mobile-menu[aria-hidden=false] {
  opacity: 1;
  visibility: visible;
  transform: scale(1);
  transition: opacity 0.4s cubic-bezier(0, 1, 0.4, 1), transform 0.4s cubic-bezier(0.18, 1.25, 0.4, 1), visibility 0.4s linear;
}

.mobile-menu__inner {
  position: relative;
  max-width: 100vw;
  height: 100%;
  overflow: hidden;
}

.mobile-menu .icon--nav-triangle-borderless {
  position: absolute;
  bottom: 100%;
  left: 20px;
  width: 18px;
  height: 8px;
  z-index: 1;
}

.mobile-menu__panel {
  position: relative;
  height: 100%;
  background: var(--secondary-background);
  overflow-y: auto;
  overflow-x: hidden;
  -ms-scroll-chaining: none;
      overscroll-behavior: none;
  -webkit-overflow-scrolling: touch;
  transition: transform 500ms cubic-bezier(0.23, 1, 0.32, 1), visibility 500ms cubic-bezier(0.23, 1, 0.32, 1);
}

.mobile-menu__panel.is-nested {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  visibility: hidden;
  z-index: 1;
  transform: translateX(100%);
}

.mobile-menu__section {
  padding: 16px 20px;
}

.mobile-menu__section--loose {
  padding-top: 18px;
  padding-bottom: 18px;
}

.mobile-menu__section:not(:last-child) {
  border-bottom: 1px solid var(--border-color);
}

.mobile-menu__section.is-sticky {
  position: -webkit-sticky;
  position: sticky;
  top: 0;
  background: var(--secondary-background);
  z-index: 1;
}

.mobile-menu__nav {
  list-style: none;
}

.mobile-menu__nav-link {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  padding: 8px 0 7px 0;
}

.mobile-menu__back-button {
  display: block;
  width: 100%;
  text-align: left;
}

.mobile-menu__back-button svg {
  margin-right: 8px;
  vertical-align: -1px;
}

.mobile-menu__nav-list {
  margin-top: 2px;
}

.mobile-menu__nav-list-toggle {
  width: 100%;
  text-align: left;
  padding: 4px 0; /* allows to increase touch area a bit */
}

.mobile-menu__nav-list-toggle svg {
  width: 12px;
  height: 8px;
  margin-left: 12px;
  transition: transform 0.3s ease-in-out;
}

.mobile-menu__nav-list-toggle[aria-expanded=true] svg {
  transform: rotateZ(180deg);
}

.mobile-menu__nav-list-item {
  margin-bottom: 22px;
}

.mobile-menu__nav-collapsible {
  height: 0;
  overflow: hidden;
  transition: 0.3s ease-in-out;
}

.mobile-menu__nav-collapsible-content {
  margin-top: 4px;
}

.mobile-menu__promo {
  display: block;
  padding: 20px 0 25px 0;
  text-align: center;
}

.mobile-menu__image-wrapper {
  margin-bottom: 22px;
  border-radius: 3px;
  overflow: hidden;
}

.mobile-menu__image-heading {
  display: block;
  margin-bottom: 0;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 18px));
}

.mobile-menu__image-text {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 15px));
}

.mobile-menu__promo-list {
  display: flex;
  flex-flow: row nowrap;
  margin-left: -10px;
  margin-right: -10px;
}

.mobile-menu__promo-list .mobile-menu__promo-item {
  flex: 0 0 auto;
  width: 81%;
  white-space: normal;
  scroll-snap-align: center;
}

.mobile-menu__promo-list .mobile-menu__promo {
  margin-left: 10px;
  margin-right: 10px;
}

.scroller .mobile-menu__promo-list::before {
  content: "";
  flex: 0 0 20px;
}

.scroller .mobile-menu__promo-list::after {
  content: "";
  flex: 0 0 13px;
}

@media screen and (min-width: 641px) {
  .mobile-menu .icon--nav-triangle-borderless {
    left: 40px;
  }
}

/* States */
.mobile-menu[aria-hidden=false] .mobile-menu__panel.is-open {
  transform: translateX(0);
  visibility: visible;
}

/* Help icons */
.mobile-menu__help-wrapper {
  display: flex;
  align-items: center;
}

.mobile-menu__help-wrapper .icon--bi-phone {
  margin-right: 16px;
  width: 24px;
  height: 24px;
}

.mobile-menu__help-wrapper .icon--bi-email {
  margin-right: 18px;
  width: 22px;
  height: 22px;
}

.mobile-menu__help-wrapper + .mobile-menu__help-wrapper {
  margin-top: 18px;
}
/**
 * --------------------------------------------------------------------
 * LINE ITEM
 * --------------------------------------------------------------------
 */

.line-item__product-info-wrapper {
  display: flex;
  align-items: flex-start;
}

.line-item__image-wrapper {
  width: 60px;
  min-width: 60px;
  margin-right: 20px;
}

.line-item__meta {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.line-item__vendor {
  display: block;
  margin-bottom: 7px;
  line-height: 1.55;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
  text-transform: uppercase;
}

.line-item__title {
  display: block;
  margin-bottom: 4px;
  line-height: 1.5;
}

.line-item__property-list {
  line-height: 1.5;
  margin: 6px 0;
}

.line-item__price {
  display: inline-block;
  font-weight: var(--text-font-bolder-weight);
  color: var(--accent-color);
}

.line-item__price--compare {
  color: var(--text-color);
}

.line-item__price--highlight {
  color: var(--product-on-sale-accent);
}

.line-item__price--compare {
  position: relative;
  margin-left: 20px;
}

.line-item__price--compare::before {
  position: absolute;
  content: "";
  top: 50%;
  left: -5px;
  width: calc(100% + 10px);
  height: 1px;
  background: rgba(var(--text-color-rgb), 0.7);
}

.line-item__price-info {
  margin-top: -2px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
}

.line-item__discount-list {
  list-style: none;
  margin-top: 2px;
}

.line-item__discount {
  display: inline-block;
  font-weight: var(--text-font-bolder-weight);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
  background: rgba(var(--product-on-sale-accent-rgb), 0.08);
  color: var(--product-on-sale-accent);
  border-radius: 2px;
  padding: 0 11px;
}

.line-item__discount svg {
  margin-right: 6px;
  vertical-align: text-bottom;
}

.line-item__quantity-remove {
  display: inline-block;
  margin-left: 10px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
  line-height: 1;
}

@media screen and (max-width: 640px) {
  /* On mobile the line items are displayed differently on cart page */
  .line-item-table,
  .line-item-table tbody {
    display: block;
    width: 95%;
  }

  .line-item--stack {
    display: block;
    white-space: normal;
  }

  .line-item--stack:first-child {
    border-top: none !important;
  }

  .line-item--stack .line-item__image-wrapper {
    width: 80px;
    min-width: 80px;
  }

  .line-item--stack .line-item__product-info {
    display: block; /* Allows to disable the table layout */
    padding-top: 20px;
    padding-bottom: 20px;
  }

  .line-item--stack .line-item__title {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  }

  .line-item--stack .line-item__price {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
  }

  .line-item--stack .line-item__quantity {
    margin-top: 12px;
  }
}

@media screen and (min-width: 641px) {
  .line-item__product-info-wrapper {
    align-items: center;
  }

  .line-item__title {
    white-space: normal;
  }

  .line-item__image-wrapper {
    width: 90px;
    min-width: 90px;
  }

  .line-item__quantity-remove {
    display: block;
    width: -webkit-max-content;
    width: -moz-max-content;
    width: max-content;
    margin: 10px auto 0 auto;
  }
}

/**
 * --------------------------------------------------------------------
 * FULFILLMENT ITEM (included in order details only)
 * --------------------------------------------------------------------
 */

/* Bit hacky and ugly, sorry! */
.fulfillment-item {
  border-top: none !important;
}

.fulfillment-item td {
  padding-top: 0 !important;
}

/**
 * --------------------------------------------------------------------
 * ORDER FOOT (used in order details in customer account)
 * --------------------------------------------------------------------
 */

.order-foot {
  border-top: 1px solid var(--border-color);
}

.order-foot__item {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 16px 20px 16px 0;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.order-foot__item + .order-foot__item {
  border-top: 1px solid var(--border-color);
}

.order-foot__item--highlight,
.order-foot__item--strong {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 15px));
  font-weight: var(--text-font-bolder-weight);
}

.order-foot__item--highlight {
  color: var(--product-on-sale-accent);
}

.order-foot__item--strong {
  color: var(--heading-color);
}

@media screen and (max-width: 640px) {
  .card .order-foot {
    margin-left: 20px;
  }
}

@media screen and (min-width: 641px) {
  .order-foot__inner {
    max-width: 470px;
    margin-left: auto;
  }

  .order-foot__item {
    padding-right: 30px;
    padding-left: 20px;
  }
}

/**
 * --------------------------------------------------------------------
 * ORDER SUMMARY (used on account pages)
 * --------------------------------------------------------------------
 */

.order-summary__alert {
  margin: 21px 0 5px 0;
}

@media screen and (min-width: 641px) {
  .order-summary__alert {
    margin: 24px 0 12px 0;
  }
}

/**
 * --------------------------------------------------------------------
 * ADDRESS LIST (used on account pages)
 * --------------------------------------------------------------------
 */

.address-list,
.address-list__item + .address-list__item {
  border-top: 1px solid var(--border-color);
}

.address-list__item {
  padding: 24px 20px;
}

.address-list__action-list {
  margin-top: 14px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
}

.address-list__action-list > :last-child {
  margin-left: 18px;
}

@media screen and (max-width: 640px) {
  .address-list,
  .address-list__item + .address-list__item {
    display: block;
    position: relative;
    border-top: none;
  }

  .address-list::before,
  .address-list__item + .address-list__item::before {
    position: absolute;
    content: "";
    height: 1px;
    width: calc(100% - 20px);
    top: 0;
    left: 20px;
    background: var(--border-color);
  }
}

@media screen and (min-width: 641px) {
  /* There is a slightly different adjustment on the design files just for this element, for no real reason, but well... let's respect the design with an ugly exception */
  .template-addresses .card__section--tight {
    padding-right: 20px;
  }

  .address-list {
    display: flex;
    flex-wrap: wrap;
  }

  .address-list__item {
    display: flex;
    justify-content: space-between;
    flex-direction: column;
    flex: 0 0 50%;
    padding-left: 30px;
    padding-right: 30px;
    box-shadow: 0 1px var(--border-color), 1px 0 var(--border-color);
    border-top: none !important;
  }
}

@media screen and (min-width: 1280px) {
  .address-list__item {
    flex-basis: 33.333333%;
  }
}
.page__header {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  margin: 28px 0;
}

.page__header--stack {
  flex-direction: column;
  align-items: flex-start;
}

.page__header--centered {
  justify-content: center;
  text-align: center;
}

.page__header--stack.page__header--centered {
  align-items: center;
}

.page__header--image {
  position: relative;
  justify-content: center;
  background-size: cover;
  background-position: center;
  min-height: 250px;
  padding: 25px;
  border-radius: 3px;
  text-shadow: 1px 2px 4px rgba(0, 0, 0, 0.2);
  overflow: hidden;
}

.page__header--image.page__header--overlay::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.3));
}

.page__header--image.page__header--overlay > * {
  z-index: 1;
}

.page__header--edge2edge {
  border-radius: 0;
  margin-top: 0 !important;
}

.page__image-placeholder {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: auto;
  fill: dimgrey;
  background: darkgrey;
}

.page__title {
  margin-bottom: 0;
}

/* Page sub-header is a small text container that is typically used to hold breadcrumbs and other secondary info (only on tablet and up) */
.page__sub-header {
  display: none;
  margin: 23px 0;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
}

/* Page description must be contained within a page__header, and has less spacing than page__content */
.page__description {
  margin: 10px 0 0 0;
}

.page__button-action {
  margin-top: 20px;
}

.page__tag-list {
  margin: 12px -20px -10px -20px;
  list-style: none;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.page__tag-item {
  position: relative;
  display: inline-block;
  margin: 0 20px 10px 20px;
}

.page__tag-item.is-selected {
  color: var(--accent-color);
}

.page__tag-item.is-selected::after {
  position: absolute;
  content: "";
  left: 0;
  bottom: 0;
  width: 100%;
  height: 1px;
  background: currentColor;
}

.page__meta {
  margin-top: 8px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
}

.page__meta-item:not(:last-child)::after {
  display: inline-block;
  content: "";
  width: 5px;
  height: 5px;
  margin: 0 10px;
  border-radius: 100%;
  background: rgba(var(--text-color-rgb), 0.4);
  vertical-align: middle;
}

.page__navigation-item svg {
  width: 6px;
  height: 9px;
}

.page__navigation-item svg path {
  stroke-width: 1.5px;
}

.page__navigation-item--prev svg {
  margin-right: 9px;
}

.page__navigation-item--next svg {
  margin-left: 9px;
}

.page__navigation-item--prev + .page__navigation-item--next::before {
  display: inline-block;
  content: "";
  width: 1px;
  height: 12px;
  margin: 0 15px;
  background: var(--text-color);
  vertical-align: -2px;
}

.page__content {
  margin-bottom: 40px;
}

@media screen and (min-width: 641px) {
  .page__header {
    margin: 35px 0;
  }

  .page__header--image {
    min-height: 430px;
  }

  .page__sub-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .page__sub-header + .page__header {
    margin-top: 20px;
  }

  .page__meta {
    margin-top: 10px;
    font-size: 1rem;
  }

  .page__meta-item:not(:last-child)::after {
    margin: 0 16px;
  }

  .page__content {
    margin-bottom: 90px;
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
  }
}

@media screen and (min-width: 1000px) {
  .page__header {
    flex-direction: column;
    align-items: flex-start;
  }

  .page__header--centered {
    align-items: center;
  }
}
.popover {
  position: absolute;
  width: 100vw;
  left: 0;
  top: 100%;
  background: var(--secondary-background);
  color: var(--text-color);
  z-index: 1;
  visibility: hidden;
  opacity: 0;
  transform: scale(0.9);
  transition: opacity 0.25s ease-in-out, transform 0.25s ease-in-out, visibility 0.25s ease-in-out;
  will-change: transform;
}

.popover .icon--nav-triangle-borderless {
  right: 67px;
}

.popover--large {
  text-align: center;
}

.popover[aria-hidden=false] {
  visibility: visible;
  opacity: 1;
  transform: scale(1.001); /* Using 1.001 force browsers like Chrome to not perform some optimizations that may result in small visual glitch */
  transition: opacity 0.4s cubic-bezier(0, 1, 0.4, 1), transform 0.4s cubic-bezier(0.18, 1.25, 0.4, 1), visibility 0.4s linear;
}

.popover__inner {
  padding: 15px 20px 20px 20px;
}

.popover__inner--no-padding {
  padding-left: 0 !important;
  padding-right: 0 !important;
}

.popover .icon--nav-triangle-borderless {
  position: absolute;
  bottom: 100%;
  width: 18px;
  height: 8px;
  z-index: 2;
  -webkit-filter: drop-shadow(0 -2px 2px rgba(0, 0, 0, 0.12));
          filter: drop-shadow(0 -2px 2px rgba(0, 0, 0, 0.12));
}

.popover__header {
  padding: 12px 0 30px 0;
}

.popover__title {
  margin-bottom: 4px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 20px));
}

.popover__legend {
  margin-bottom: 16px;
}

.popover__secondary-action {
  margin-top: 16px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
}

.popover__secondary-action > p {
  margin-bottom: 0;
}

@media screen and (max-width: 640px) {
  .popover__panel-list,
  .popover__panel {
    height: 100% !important;
  }

  .popover__inner {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100%;
    overflow: auto;
    -webkit-overflow-scrolling: touch;
  }
}

@media screen and (min-width: 641px) {
  .popover {
    width: auto;
    min-width: 160px;
    right: -2px;
    top: calc(100% + 15px);
    left: auto;
    border-radius: 3px;
    box-shadow: 0 1px 5px 2px rgb(0 0 0 / 5%);
  }

  .popover .icon--nav-triangle-borderless {
    right: 27px;
  }

  .popover--large {
    min-width: 320px;
  }

  .popover__inner {
    padding: 15px 25px 15px 25px;
  }

  .popover__header {
    padding-bottom: 15px;
  }

  .popover__title {
    margin-bottom: 8px;
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 18px));
  }
}

@media screen and (min-width: 1280px) {
  .popover {
    top: calc(100% + 4px);
  }
}

/* Linklist */
.popover__linklist {
  white-space: nowrap;
  list-style: none;
}

.popover__link-item {
  display: block;
  padding: 2px 25px;
  cursor: pointer;
  width: 100%;
  transition: color 0.15s ease-in-out, background 0.15s ease-in-out;
}

.popover__link-item:hover {
  background: var(--accent-background);
  color: var(--accent-color);
}

/* Panel */
.popover__panel-list {
  position: relative;
  overflow: hidden;
  transition: height 0.2s ease-in-out;
}

.popover__panel {
  width: 100%;
  visibility: hidden;
  transition: transform 500ms cubic-bezier(0.23, 1, 0.32, 1), visibility 500ms cubic-bezier(0.23, 1, 0.32, 1);
}

.popover__panel--default {
  transform: translateX(-100%);
}

.popover__panel--sliding {
  position: absolute;
  top: 0;
  left: 0;
  transform: translateX(100%);
}

.popover[aria-hidden=false] .popover__panel.is-selected {
  visibility: visible;
}

.popover__panel.is-selected {
  transform: translateX(0);
}

/**
 * We have some specific positioning (like arrows...) for each popover, so we summarize specific code here
 */

.popover--password .icon--nav-triangle-borderless {
  right: 21px;
}

.popover--currency,
.popover--locale {
  min-width: 0;
}

@media screen and (min-width: 641px) {
  .popover--password .popover__inner {
    padding-bottom: 25px;
  }

  .popover--password .icon--nav-triangle-borderless {
    right: calc(50% - 13px);
  }

  .popover--currency {
    top: calc(100% + 3px);
    right: auto;
    left: -2px;
  }

  .popover--currency .icon--nav-triangle-borderless {
    right: 23px;
  }

  .popover--locale {
    top: calc(100% + 3px);
    right: -26px;
  }
  .popover--locale .icon--nav-triangle-borderless {
    right: 23px;
  }

  .popover--logged {
    right: -47px;
  }

  .popover--logged .icon--nav-triangle-borderless {
    right: 50px;
  }

  .popover--unlogged {
    right: -5px;
    border-radius: 10px;
  }
  .popover--unlogged .icon--nav-triangle-borderless {
    right: 6px;
  }
}

@media screen and (min-width: 1280px) {
  .popover--password {
    top: calc(100% + 15px);
    right: -2px;
  }

  .popover--logged {
    right: -32px;
  }

  .popover--logged .icon--nav-triangle-borderless {
    right: 29px;
  }

  .popover--unlogged {
    right: 0;
    transform: scale(0.9) translateX(calc(50% - 7px));
  }

  .popover--unlogged .icon--nav-triangle-borderless {
    left: calc(50% - 8px);
  }

  .popover--unlogged[aria-hidden=false] {
    transform: scale(1) translateX(calc(50% - 7px));
  }
}
/**
 * --------------------------------------------------------------------
 * PRODUCT GALLERY
 * --------------------------------------------------------------------
 */
.product-gallery {
  position: relative;
  margin-bottom: 12px;
}

.product-gallery__carousel-wrapper {
  position: relative;
  margin-bottom: 25px;
}

.product-gallery__carousel .flickity-viewport {
  transition: height 0.2s ease-in-out;
}

.product-gallery__carousel:not(.flickity-enabled) .product-gallery__carousel-item:not(.is-selected) {
  display: none;
}

.product-gallery__carousel-item {
  width: 100%;
  padding: 0 20px;
}

.product-gallery__carousel-item--hidden {
  visibility: hidden;
}

.product-gallery__carousel-item[aria-hidden=true] .plyr__control {
  /* This is a quick fix to prevent the controls to gain focus until if the slide is not visible */
  visibility: hidden;
}

.product-gallery__carousel-item.is-filtered {
  display: none;
}

.product-gallery__size-limiter {
  margin: 0 auto;
}

.product-gallery__view-in-space {
  background: rgba(var(--text-color-rgb), 0.08); /* This color is defined by Shopify spec */
  border-top-left-radius: 0;
  border-top-right-radius: 0;
}

.product-gallery__view-in-space[data-shopify-xr-hidden] {
  visibility: hidden;
}

@media screen and (min-width: 1000px) {
  .product-gallery__view-in-space[data-shopify-xr-hidden] {
    display: none;
  }
}

.product-gallery__view-in-space svg {
  margin: -1px 8px 0 0;
  width: 16px;
  height: 16px;
  vertical-align: middle;
}

.product-gallery__zoom-notice {
  display: none;
}

@media screen and (max-width: 640px) {
  .product-gallery__carousel {
    margin-left: calc(-1 * var(--mobile-container-gutter));
    margin-right: calc(-1 * var(--mobile-container-gutter));
  }
}

@media screen and (min-width: 1000px) {
  .product-gallery__carousel {
    margin: -4px;
  }

  .product-gallery__carousel-item {
    padding: 4px;
  }

  .product-gallery--with-thumbnails {
    display: flex;
    flex-direction: row-reverse;
    align-items: flex-start;
    width: 100%;
  }

  .product-gallery--with-thumbnails .product-gallery__carousel-wrapper {
    flex: 1 0 auto;
    margin: 10px 5px 0 42px;
  }
}

@media screen and (min-width: 1000px) and (-moz-touch-enabled: 0),screen and (min-width: 1000px) and (hover: hover) {
  /* Implementation note: starting from version 1.8, the theme now supports media type in Shopify (including 3D models
     and video. As a consequence, the "zoom" now only makes sense for "images", for which the slideshow becomes draggable.
     We therefore scope this so that the notice is only shown for images */
  .product-gallery__carousel--zoomable ~ .product-gallery__zoom-notice {
    display: block;
    margin: 26px 0 6px 0;
    width: 100%;
    text-align: center;
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  }

  .product-gallery__carousel--zoomable ~ .product-gallery__zoom-notice svg {
    width: 10px;
    height: 10px;
    margin-right: 14px;
    vertical-align: baseline;
  }
}

@media screen and (min-width: 1000px) {
  .product-gallery {
    margin-bottom: 0;
  }
}

/**
 * --------------------------------------------------------------------
 * PRODUCT THUMBNAILS
 * --------------------------------------------------------------------
 */

.product-gallery__thumbnail {
  position: relative;
  display: block;
  width: 60px;
  margin: 0 4px;
  border: 2px solid transparent;
  border-radius: 12px;
  transition: border 0.2s ease-in-out;
  cursor: pointer;
}

.product-gallery__thumbnail.is-nav-selected {
  border-radius: 12px;
  filter: brightness(0.9);
  transition: all 0.6s;
}

.product-gallery__thumbnail.is-filtered {
  display: none;
}

.product-gallery__thumbnail-badge {
  position: absolute;
  top: 3px;
  right: 3px;
  width: 20px;
  height: 20px;
  z-index: 1;
}

@media screen and (max-width: 999px) {
  .product-gallery__thumbnail-list::after, .product-gallery__thumbnail-list::before {
    content: "";
    display: inline-block;
    vertical-align: middle;
    width: calc(var(--mobile-container-gutter) - 4px);
  }

  .product-gallery__thumbnail {
    display: inline-block;
    vertical-align: top;
    /* This is done to comply with the media API that requires thumbnails to be aligned to the top */
    overflow: auto;
    border-radius: 12px;
  }
}

@media screen and (min-width: 641px) and (max-width: 999px) {
  .product-gallery .scroller {
    margin: 0 -15px;
  }
}

@media screen and (min-width: 641px) {
  .product-gallery__thumbnail {
    width: 72px;
  }
}

@media screen and (min-width: 1000px) {
  .product-gallery__thumbnail-list {
    position: relative;
    z-index: 1;
    margin: -2px 0 -2px -3px; /* negative to align the top edge to the featured image */
    max-height: 450px;
    width: 96px; /* Width + margin */
    overflow: auto;
    -ms-overflow-style: none; /* IE 11 */
    scrollbar-width: none; /* Firefox 64 */
    -ms-scroll-chaining: none;
        overscroll-behavior: contain;
  }

  .product-gallery__thumbnail-list::-webkit-scrollbar {
    -webkit-appearance: none;
  }

  .product-gallery__thumbnail {
    margin: 8px 4px;
    overflow: auto;
    border-radius: 12px;
  }
}

/**
 * --------------------------------------------------------------------
 * PRODUCT META
 * --------------------------------------------------------------------
 */

.product-meta {
  position: relative;
  margin: -11px 0 5px 0; /* Negative margin is to take into account for the padding */
}

.product-meta__title {
  margin-bottom: -5px;
}

/* When within a modal, we have to add an extra margin to prevent the title to overlap the close button */
.modal .product-meta__title {
  margin-right: 45px;
}

.product-meta__label-list {
  margin-bottom: 8px;
  font-size: 0;
}

.discount__percentage {
    font-size: 12px;
    padding: 4px 8px;
    color: #fff;
    font-weight: 600;
    background: var(--product-on-sale-accent);
    border-radius: 30px;
    display: inline-block;
    position: relative;
    top: -2px;
}

.discount__money {
    font-size: 14px;
    border: 1px solid var(--product-on-sale-accent);
    padding: 0px 10px;
    color: #fff;
    font-weight: 600;
    background: var(--product-on-sale-accent);
    border-radius: 5px;
    display: inline-block;
  	top: -5px;
}

.discount__money b {
    font-weight: 900;
    color: #fff;
}

.product-meta__label-list .product-label + .product-label {
  margin-left: 5px;
}

.product-meta__reference {
  margin-bottom: 3px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
}

.product-meta__reviews-badge {
  display: block;
}

.product-meta__reviews-badge .spr-badge {
  line-height: inherit;
}

.product-meta__reviews-badge .spr-badge .spr-badge-caption {
  margin-left: 12px;
}

.product-meta__vendor {
  text-transform: uppercase;
}

.product-meta__vendor + .product-meta__sku::before {
  display: inline-block;
  position: relative;
  content: "";
  margin: 0 14px;
  height: 13px;
  width: 1px;
  top: -1px;
  background: var(--border-color);
  vertical-align: middle;
}

.product-meta__share-buttons {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 40px;
}

.product-meta__share-buttons .social-media__item svg {
  opacity: 0.35;
}

.card__separator + .product-meta__share-buttons {
  margin-top: 0;
}

.product-meta__description {
  margin-bottom: 25px;
}

/* On featured product section it can be configured to be shown after the form */
.product-form + .product-meta__description {
  margin-top: 25px;
  margin-bottom: 0;
}

@media screen and (min-width: 641px) {
  /*
  IMPLEMENTATION NOTE: there are a lot of manual adjustments here with negative margins, depending on which elements are here or not. This is not
                       really something I'm really happy with as it makes editing more complex. However designer absolutely wanted a pixel-perfect
                       adjustment for all conditions... which result in more complex code :)
  */
  .product-meta__share-buttons {
    margin-top: 0;
  }

  .product-meta__label-list + .product-meta__share-buttons {
    margin-top: 22px;
  }

  .product-meta__reference,
  .product-meta__reviews-badge {
    margin-bottom: -2px;
    margin-top: 5px;
  }

  .product-meta__reviews-badge {
    margin-top: -4px;
    width: -webkit-fit-content;
    width: -moz-fit-content;
    width: fit-content;
  }

  .product-meta__reference ~ .product-meta__share-buttons,
  .product-meta__reviews-badge ~ .product-meta__share-buttons {
    position: absolute;
    right: 0;
    bottom: 0;
  }

  .product-meta__reference + .product-meta__reviews-badge {
    margin-top: -8px;
  }

  .product-meta__reviews-badge .spr-badge .spr-badge-caption {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  }
}

/**
 * --------------------------------------------------------------------
 * PRODUCT FORM
 * --------------------------------------------------------------------
 */

.product-form__variants {
  margin-bottom: 24px;
}

.product-form__option {
  margin-bottom: 23px;
}

.product-form__option-name {
  display: block;
  margin-bottom: 2px;
}

.product-form__selected-value {
  padding-left: 2px;
  color: var(--text-color);
}

.product-form__info-list {
  display: table;
  width: 100%;
  margin: -22px 0 6px 0;
  border-spacing: 0 22px;
}

.product-form__info-item {
  display: block;
  align-items: center;
}

.product-form__info-title {
  display: table-cell;
  padding-right: 40px;
  vertical-align: middle;
  white-space: nowrap;
}

.product-form__info-item--quantity > * {
  vertical-align: middle;
}

.product-form__info-content {
  display: table-cell;
  width: 100%;
}

.product-form__price-info {
  margin-top: 5px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.product-form__price-info + .product-form__price-info {
  margin-top: 0;
}

.product-form .select-wrapper {
  display: inline-block;
  vertical-align: middle;
}

.product-form__quantity {
  display: inline-block;
  width: 65px;
  vertical-align: middle;
}

.product-form__inventory.inventory::before {
  margin-right: 14px;
}

.product-form__payment-container {
  display: flex;
  flex-direction: column;
  margin-top: -30px;
  transition: all 0.5s;
}

.product-form__error {
  margin-top: 18px;
  height: 0;
  overflow: hidden;
  transition: height 0.25s ease-in-out;
}

.align-price-discount {
  display: flex;
  flex-direction: row;
  align-items: center;
}

.product-form .price--compare {
  top: -5px;
  font-size: 14px;
}

@media screen and (max-width: 640px) {
  .product-form__payment-container .shopify-payment-button {
    margin-top: 16px;
  }
}

@media screen and (min-width: 641px) {
  .product-form {
    margin-top: -8px; /* for pixel perfect alignment... */
  }

  .product-form__option-name {
    margin-bottom: 7px;
  }

  .product-form__variants {
    margin-bottom: 26px;
  }

  .product-form__payment-container {
    flex-direction: column;
    align-items: flex-start;
        margin: -16px -9px;

  }

  .product-form__payment-container > * {
    flex: none;
    line-height: 55px !important;
    width: calc(96%);
    border-radius: 40px;
    margin: -10px 0 11px 9px;
  }

}


/**
 * --------------------------------------------------------------------
 * SHOPIFY QUICK PAYMENT
 * --------------------------------------------------------------------
 */

.shopify-payment-button__button--unbranded {
  position: relative;
  display: inline-block;
  padding: 0 30px !important;
  line-height: 58px !important;
  border-radius: 5px !important;
  text-align: center;
  background: var(--secondary-button-background) !important;
  color: var(--secondary-button-text-color) !important;
  font-weight: var(--text-font-bolder-weight) !important;
  font-size: var(--base-text-font-size) !important;
  cursor: pointer;
  transition: background 0.25s ease-in-out, color 0.25s ease-in-out, box-shadow 0.25s ease-in-out;
}

.shopify-payment-button__button--unbranded:hover {
  background: rgba(var(--secondary-button-background-rgb), 0.8) !important;
}

.shopify-payment-button__button--branded {
  border-radius: 3px;
  overflow: hidden;
  min-height: 48px;
}

.shopify-payment-button__more-options {
  margin-top: 8px;
  color: var(--link-color);
  transition: color 0.2s ease-in-out;
}

.shopify-payment-button__more-options:not([disabled]):hover {
  text-decoration: none;
  color: var(--link-color-hover);
}

.shopify-payment-button__more-options[aria-hidden=true] {
  display: none;
}

/**
 * --------------------------------------------------------------------
 * BLOCK LIST
 * --------------------------------------------------------------------
 */

.product-block-list__item--trust .icon--lock {
  width: 18px;
  height: 24px;
  color: var(--heading-color);
}

/* This code is not super clean, but it's due to the wish of the designer to have some pixel perfect alignment that
   are specific JUST for this element and break the generic abstractions... thanks dude :D */
.product-block-list__item--shipping .shipping-estimator {
  margin-bottom: 10px;
  margin-top: -0.435em;
}

.product-block-list__item--shipping .shipping-estimator__results {
  margin-top: 26px;
  margin-bottom: -10px;
}

.product__refund-policy-link {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
}

.product__refund-policy-link svg {
  width: 8px;
  height: 12px;
}

@media screen and (max-width: 640px) {
  .product-block-list__item:first-child .card {
    border-top: none;
  }
}

@media screen and (max-width: 999px) {
  /* we have a logic on desktop with overflow scroller and we must force it to disabled on mobile */
  .product-block-list__wrapper {
    min-height: 0 !important;
  }

  .product-block-list__item--info > .card {
    top: 0 !important;
  }
}

@media screen and (min-width: 1000px) {
  .product-block-list {
    position: relative;
  }

  .product-block-list__wrapper {
    width: calc(50% - 15px);
    margin-left: 0;
  }

  .product-block-list__item--info {
    position: absolute;
    top: 0;
    right: 0;
    width: calc(50% - 15px);
    height: 100%;
  }
}

@media screen and (min-width: 1280px) {
  .product-block-list--medium .product-block-list__wrapper {
    width: calc(55% - 15px);
  }
  .product-block-list--medium .product-block-list__item--info {
    width: calc(45% - 15px);
  }

  .product-block-list--large .product-block-list__wrapper {
    width: calc(60% - 15px);
  }
  .product-block-list--large .product-block-list__item--info {
    width: calc(40% - 15px);
  }
}

/**
 * --------------------------------------------------------------------
 * FEATURED PRODUCT (HOMEPAGE)
 * --------------------------------------------------------------------
 */

/* When within the modal we need to remove the border */
.modal .featured-product .card {
  border: none;
}

.modal .featured-product .card:first-child {
  border-right: 1px solid var(--border-color);
}

@media screen and (min-width: 1000px) {
  .featured-product {
    display: table;
    width: 100%;
    table-layout: fixed;
  }

  .featured-product > * {
    display: table-cell;
    vertical-align: top;
    width: 50%;
  }

  .featured-product > :first-child {
    border-radius: 3px 0 0 3px;
  }

  .featured-product > :last-child {
    border-radius: 0 3px 3px 0;
    border-left: none;
  }
}
/**
 * --------------------------------------------------------------------
 * PRODUCT LABEL
 * --------------------------------------------------------------------
 */

.product-label {
  display: inline-block;
  padding: 5px 12px;
  color: #ffffff;
  border-radius: 21px;
  font-weight: var(--text-font-bolder-weight);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
  line-height: 1;
  vertical-align: top;
  width: -webkit-max-content;
  width: -moz-max-content;
  width: max-content;
}

.product-label--on-sale {
  background: var(--product-on-sale-accent);
  color: var(--product-on-sale-color);
}

.product-label--custom1 {
  background: var(--product-custom-label-1-background);
  color: var(--product-custom-label-1-color);
}

.product-label--custom2 {
  background: var(--product-custom-label-2-background);
  color: var(--product-custom-label-2-color);
}

/**
 * --------------------------------------------------------------------
 * PRODUCT PRICE
 * ---------
 -----------------------------------------------------------
 */
.label-price {
    color: #fff;
}

.price-list {
  line-height: 1;
}

.price-list2 {
  align-items: baseline;
  line-height:1;
}

.price {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 24px));
  color: var(--product-cor-do-preco);
}

.price--highlight {
  margin-right: 0.3em;
  color: var(--product-cor-do-preco);
  font-weight: 600;
  font-size: 28px;
}

.price--compare {
  position: relative;
  color: var(--product-cor-do-preco-riscado);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
}

.price--compare::before {
    position: absolute;
    content: "";
    top: 47%;
    left: -1px;
    width: calc(95% + 6px);
    height: 1px;
    background: var(--product-cor-do-preco-riscado);
    font-size: 10px;
}

/**
 * --------------------------------------------------------------------
 * INVENTORY AND BAR
 * --------------------------------------------------------------------
 */

.inventory {
  position: relative;
  display: block;
  padding-left: 1.4em;
  font-weight: var(--text-font-bolder-weight);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  line-height: 1.2;
}

.inventory::before {
  position: absolute;
  display: inline-block;
  content: "";
  width: 8px;
  height: 8px;
  left: 0;
  top: 0.45em;
  border-radius: 100%;
  background: currentColor;
}

.inventory--high {
  color: var(--product-in-stock-color);
}

.inventory--low {
  color: var(--product-low-stock-color);
}

.inventory-bar {
  position: relative;
  display: block;
  margin: 16px 0 10px 0;
  width: 100%;
  height: 4px;
  border-radius: 3px;
  background: var(--border-color);
  overflow: hidden;
}

.inventory-bar--hidden {
  display: none;
}

.inventory-bar__progress {
  position: absolute;
  left: 0;
  top: 0;
  height: 100%;
  width: 0;
  display: block;
  transition: width 1.15s ease-in-out;
}

.inventory--high + .inventory-bar > .inventory-bar__progress {
  background: var(--product-in-stock-color);
}

.inventory--low + .inventory-bar > .inventory-bar__progress {
  background: var(--product-low-stock-color);
}

@media screen and (min-width: 641px) {
  .inventory {
    font-size: 1rem;
  }

  .inventory-bar {
    margin-top: 23px;
  }
}

/**
 * --------------------------------------------------------------------
 * COLOR SWATCH
 * --------------------------------------------------------------------
 */

.color-swatch-list {
  margin: -2px -6px 0 -6px; /* We have to take into account the box-shadow and inner spacing added when an element is active */
  padding-left: 4px;
}

.color-swatch {
  position: relative;
  display: inline-block;
  margin: 6px;
  vertical-align: middle;
}

.color-swatch__radio {
  position: absolute;
  height: 0;
  width: 0;
  opacity: 0;
}

.color-swatch__item {
  position: relative;
  display: block;
  width: 18px;
  height: 18px;
  cursor: pointer;
  background-size: cover;
}

.color-swatch__item svg {
  display: none;
}

.color-swatch__item-link {
  display: none;
  position: relative;
  padding-left: 8px;
  padding-right: 8px;
  height: 18px;
  background-color: var(--secondary-background);
  box-shadow: 0 0 0 1px var(--form-border-color) inset;
  border-radius: 10px;
  width: auto;
  line-height: 18px;
  font-size: 12px;
}

.color-swatch__button {
  vertical-align: middle;
}

.color-swatch__button--labelled {
  display: flex;
  align-items: center;
  justify-content: flex-start;
}

.color-swatch__label {
  display: inline-block;
  vertical-align: middle;
  margin-left: 14px;
}

.color-swatch__radio:checked + .color-swatch__item::after,
.color-swatch__button.is-selected .color-swatch__item::after {
  position: absolute;
  content: "";
  width: calc(100% + 8px);
  height: calc(100% + 8px);
  top: -4px;
  left: -4px;
  border-radius: 8px;
  border: 2px solid var(--accent-color);
}

.color-swatch__button.is-selected .color-swatch__label {
  font-weight: var(--text-font-bolder-weight);
  color: var(--accent-color);
}

.color-swatch--white .color-swatch__item {
  box-shadow: 0 0 0 1px var(--form-border-color) inset;
}

/* The view more is used on listing, to restrict the number of displayed swatches */
.color-swatch--view-more ~ .color-swatch {
  display: none;
}

.color-swatch--view-more .color-swatch__item {
  display: none;
}

.color-swatch--view-more .color-swatch__item-link {
  display: block;
}

/** Large list variation **/
.color-swatch-list--large {
  margin: -4px -8px 0 -8px; /* We have to take into account the box-shadow and inner spacing added when an element is active */
}

.color-swatch-list--large .color-swatch {
  margin: 8px;
}

.color-swatch-list--large .color-swatch__item {
  width: 36px;
  height: 36px;
}

/** Stack list variation **/
.color-swatch-list--stack {
  margin: -3px -7px 0 -7px; /* We have to take into account the box-shadow and inner spacing added when an element is active */
}

.color-swatch-list--stack .color-swatch__item {
  width: 16px;
  height: 16px;
}

.color-swatch-list--stack .color-swatch {
  display: block;
  margin: 7px;
}

/* Disabled variation */
.color-swatch--disabled .color-swatch__item::before {
  position: absolute;
  content: "";
  left: 0;
  top: 0;
  height: 100%;
  width: 100%;
  background: rgba(var(--secondary-background-rgb), 0.5);
}

.color-swatch--disabled svg {
  display: block;
  position: absolute;
  z-index: 1;
  width: 14px;
  height: 14px;
  top: calc(50% - 7px);
  left: calc(50% - 7px);
  color: #4a4a4a;
}

/**
 * --------------------------------------------------------------------
 * BLOCK SWATCH
 * --------------------------------------------------------------------
 */

.block-swatch-list {
  margin: -3px -4px 0 -4px; /* We need to take into account the box-shadow height when element is active */
  padding-left: 2px;
}

.block-swatch {
  display: inline-block;
  margin: 4px;
}

.block-swatch__radio {
  position: absolute;
  height: 0;
  width: 0;
  opacity: 0;
}

.block-swatch__item {
  display: block;
  padding: 6px 16px 7px 16px;
  text-align: center;
  border: 1px solid var(--form-border-color);
  border-radius: 40px;
  vertical-align: middle;
  cursor: pointer;
  box-shadow: 0 1px 1px rgba(var(--border-color-rgb), 0.25);
}

.block-swatch__radio:checked + .block-swatch__item {
  box-shadow: 0 0 0 1px var(--accent-color);
  border-color: var(--accent-color);
  background: rgba(var(--accent-color-rgb), 0.06);
  color: var(--accent-color);
}

.block-swatch--disabled .block-swatch__item-text {
  position: relative;
  opacity: 0.5;
}

.block-swatch--disabled .block-swatch__item-text::after {
  position: absolute;
  content: "";
  width: calc(100% + 6px);
  height: 1px;
  top: calc(50% + 1px);
  left: -3px;
  background: currentColor;
}

/**
 * --------------------------------------------------------------------
 * VARIANT SWATCH
 * --------------------------------------------------------------------
 */

.variant-swatch-list {
  margin: -5px -5px -2px -4px;
}

.variant-swatch {
  display: inline-block;
  margin: 5px;
  vertical-align: middle;
}

.variant-swatch__radio {
  position: absolute;
  height: 0;
  width: 0;
  opacity: 0;
}

.variant-swatch__item {
  position: relative;
  display: block;
  width: 64px;
  padding: 2px;
  cursor: pointer;
  overflow: hidden;
  border: 2px solid transparent;
}

.variant-swatch__item svg {
  display: none;
}

.variant-swatch__radio:checked + .variant-swatch__item {
  border-color: var(--accent-color);
  border-radius: 40px;
  padding: 0;
  transition-duration: 0.3s;
}

/* Disabled variation */
.variant-swatch--disabled img {
  opacity: 0.5;
}

.variant-swatch--disabled svg {
  display: block;
  position: absolute;
  z-index: 1;
  width: 14px;
  height: 14px;
  top: calc(50% - 7px);
  left: calc(50% - 7px);
  color: #4a4a4a;
}

/**
 * --------------------------------------------------------------------
 * PRODUCT ITEM
 * --------------------------------------------------------------------
 */

.product-item {
   position: relative;
  padding: 20px;
  min-width: 0;
  flex-shrink: 0;
  background: var(--secondary-background);
  white-space: normal;
    transform: scale(.95);
    border-radius: 20px!important;
    box-shadow: 0px 5px 25px -26px black;
    transition: all 0.5s;
}

.product-item:hover {
  margin-top: -6px;
  margin-bottom: 6px;
  cursor: pointer;
}

.product-item::after {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  left: 0;
  top: 0;
  z-index: 2; /* needed to overlap the labels (if any) */
  pointer-events: none;
}

.product-item__image-wrapper {
  display: block;
  margin-bottom: 20px;
  overflow: hidden;
  border-radius: 10px;
}

.product-item__image-wrapper .placeholder-svg {
  height: auto;
}

.product-item__secondary-image {
  display: none;
}

.product-item__label-list {
  position: absolute;
  top: 0px;
  left: -1px;
  z-index: 2;
  font-size: 0;
}

.product-item__label-list > .product-label {
  display: block;
  border-radius: 30px;
  background: var(--product-on-sale-accent);
  margin: 15px;
  padding: 5px 10px 5px 10px;
}

.product-item__info {
  min-width: 0;
}

.product-item__price-list:first-child {
  margin-bottom: 10px;
}

/* This trick is done to add some spacing in case the prices fall into two lines */
.product-item__price-list {
  margin-top: -15px;
  margin-bottom: 20px;
}

.product-item__price-list .price {
  display: inline-block;
  margin-top: 5px;
  margin-bottom: 5px;
  
}

.product-item__vendor {
  display: block;
  margin-bottom: 6px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
  text-transform: uppercase;
}

.product-item__vendor,
.product-item__title {
  display: block;
  line-height: 1.55;
}

.product-item__title {
  margin-bottom: 25px;
}

.product-item__title + .product-item__vendor {
  margin-bottom: 12px;
  margin-top: -4px;
}

.product-item__swatch-list {
  margin: -2px 0 12px 0; /* On the collection page, we do not show more than one line */
  white-space: nowrap;
  overflow: hidden;
}

.product-item__price-info {
  margin-top: 10px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
  line-height: 1;
}

.product-item .price {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 18px));
}

.product-item .price--compare {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

.product-item__reviews-badge {
  display: block;
  margin: 3px 0;
  margin-bottom: 0px;
}

.product-item__inventory {
  margin-top: 14px;
}

.product-item__inventory::before {
  top: 0.3em;
}

.product-item__inventory {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
}

@media (-moz-touch-enabled: 0),(hover: hover) {
  .product-item__image-wrapper--with-secondary .product-item__primary-image,
  .product-item__image-wrapper--with-secondary .product-item__secondary-image {
    transition: opacity 0.2s ease-in-out, visibility 0.2s ease-in-out;
  }

  .product-item__image-wrapper--with-secondary .product-item__secondary-image {
    display: block;
    -o-object-fit: contain;
       object-fit: contain;
    -o-object-position: center;
       object-position: center;
    visibility: hidden;
    opacity: 0;
  }

  .product-item__image-wrapper--with-secondary:hover .product-item__primary-image {
    opacity: 0;
    visibility: hidden;
  }

  .product-item__image-wrapper--with-secondary:hover .product-item__secondary-image {
    visibility: visible;
  }

  .product-item__image-wrapper--with-secondary:hover .product-item__secondary-image.lazyloaded {
    opacity: 1;
  }
}

@media screen and (min-width: 641px) {
  .product-item__title {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  }

  .product-item--vertical .price:not(.price--compare),
  .product-item--list .price:not(.price--compare) {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 20px));
    font-weight: bold;
  }
}

@media screen and (min-width: 1000px) {
  .product-item__label-list {
    left: 0;
  }
}

/**
 * --------------------------------------------------------------------
 * PRODUCT ITEM (VERTICAL AND HORIZONTAL VARIATION)
 * --------------------------------------------------------------------
 */

.product-item--vertical .product-item__action-list,
.product-item--horizontal .product-item__action-list {
  margin: 20px 0 5px 0;
}

.product-item--vertical .product-item__action-button,
.product-item--horizontal .product-item__action-button {
  padding-left: 10px;
  padding-right: 10px;
}

.product-item--vertical .product-item__action-list--list-view-only,
.product-item--vertical .product-item__action-button--list-view-only,
.product-item--horizontal .product-item__action-list--list-view-only,
.product-item--horizontal .product-item__action-button--list-view-only {
  display: none;
}

.product-item--vertical .product-item__action-button--list-view-only + .product-item__action-button,
.product-item--horizontal .product-item__action-button--list-view-only + .product-item__action-button {
  margin-top: 0;
}

@media screen and (min-width: 1000px) {
  .product-item--vertical .product-item__action-list {
    margin: 15px -5px -5px -5px;
  }

  .product-item--vertical .product-item__action-button {
    flex: 1 0 auto;
    margin: 5px !important;
  }
}

/**
 * --------------------------------------------------------------------
 * PRODUCT ITEM (HORIZONTAL AND LIST VARIATION)
 * --------------------------------------------------------------------
 */

.product-item--horizontal,
.product-item--list {
  display: flex;
}

.product-item--horizontal .product-item__info,
.product-item--list .product-item__info {
  padding: 4px 0;
  flex: 1 0 0;
}

.product-item--horizontal .product-item__image-wrapper,
.product-item--list .product-item__image-wrapper {
  flex: none;
  width: 120px;
  margin: 0 20px 0 0;
}

.product-item--horizontal .product-item__action-list,
.product-item--list .product-item__action-list {
  align-self: center;
}

.product-item--horizontal .spr-starrating .spr-icon.spr-icon {
  font-size: 11px;
  width: 11px;
  height: 11px;
}

@media screen and (max-width: 640px) {
  .product-item--horizontal,
  .product-item--list {
    width: 100% !important;
  }

  .product-list--collection .product-item__label-list {
    left: 0;
  }

  .product-list--collection .spr-starrating .spr-icon.spr-icon {
    font-size: 11px;
    width: 11px;
    height: 11px;
  }
}

@media screen and (min-width: 641px) {
  .product-item--horizontal .product-item__image-wrapper {
    width: 110px;
    margin-right: 20px;
  }

  .product-item--horizontal .product-item__info {
    flex: 1 0 0;
  }
}

/**
 * --------------------------------------------------------------------
 * PRODUCT ITEM (LIST VARIATION)
 * --------------------------------------------------------------------
 */

@media screen and (max-width: 640px) {
  .product-item__action-list {
    margin-top: 20px;
  }
}

@media screen and (min-width: 641px) {
  .product-item--list {
    width: 100% !important;
    align-items: center;
    padding-right: 25px;
  }

  .product-item--list .product-item__title {
    font-size: 1rem;
  }

  .product-item--list .product-item__image-wrapper {
    width: 180px;
    margin-right: 30px;
  }

  .product-item--list .product-item__info {
    display: flex;
    justify-content: space-between;
    flex: 1 0 0;
    margin: 15px 0 15px 0;
  }

  .product-item--list .product-item__action-list {
    display: flex;
    margin-left: 30px;
    min-width: 180px;
  }
}

/**
 * --------------------------------------------------------------------
 * PRODUCT ITEM (COMPACT VARIATION)
 * --------------------------------------------------------------------
 */

.product-item--compact .product-item__info {
  padding-top: 0;
}

.product-item--compact .product-item__price-list:first-child {
  margin-bottom: 8px;
}

.product-item--compact .product-item__reviews-badge {
  margin: 15px 0;
}
.promo-block {
  position: relative;
  display: flex;
  min-height: 240px;
  padding: 20px 24px;
  border-radius: 3px;
  overflow: hidden;
}

.promo-block--small {
  min-height: 220px;
}

.promo-block--large {
  min-height: 260px;
}

.promo-block--top-left,
.promo-block--top-center,
.promo-block--top-right {
  align-items: flex-start;
}

.promo-block--middle-left,
.promo-block--middle-center,
.promo-block--middle-right {
  align-items: center;
}

.promo-block--bottom-left,
.promo-block--bottom-center,
.promo-block--bottom-right {
  align-items: flex-end;
}

.promo-block--top-right,
.promo-block--middle-right,
.promo-block--bottom-right {
  text-align: right;
  justify-content: flex-end;
}

.promo-block--top-center,
.promo-block--middle-center,
.promo-block--bottom-center {
  text-align: center;
  justify-content: center;
}

.promo-block--top-left,
.promo-block--middle-left,
.promo-block--bottom-left {
  text-align: left;
  justify-content: flex-start;
}

.promo-block__image-clip,
.promo-block__image-wrapper {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.promo-block__image-clip {
  overflow: hidden;
}

.promo-block__image-wrapper {
  background-repeat: no-repeat;
  background-position: right calc(100% + 15px);
  background-size: auto 185px;
  transition: opacity 0.2s ease-in-out, background-position 0.35s ease-in-out;
}

.promo-block__image-wrapper--cover {
  background-size: cover !important;
  background-position: center !important;
  transform: scale(1.01); /* The 1.01 is necessary to avoid some rounding issues on Chrome */
  transition: opacity 0.2s ease-in-out, transform 1.2s ease-in-out;
}

.promo-block__inner {
  position: relative;
  z-index: 1;
}

.promo-block__content {
  margin-bottom: 1em;
}

.promo-block__heading {
  margin-bottom: 3px;
  color: inherit;
}

.promo-block__cta {
  margin-top: 3px;
}

.promo-block--small .promo-block__image-wrapper {
  background-size: auto 155px;
}

/** Overlay variation **/
.promo-block--overlay::before {
  position: absolute;
  content: "";
  height: 100%;
  width: 100%;
  left: 0;
  top: 0;
  background: linear-gradient(to top, rgba(0, 0, 0, 0) 15%, rgba(0, 0, 0, 0.5));
  z-index: 1;
}

@media (-moz-touch-enabled: 0),(hover: hover) {
  .promo-block__image-wrapper {
    background-position: right calc(100% + 35px);
  }

  .promo-block:hover .promo-block__image-wrapper {
    background-position: right calc(100% + 15px);
  }

  .features--animate-zoom .promo-block:hover .promo-block__image-wrapper--cover {
    transform: scale(1.07);
  }
}

@media screen and (min-width: 641px) {
  .promo-block {
    min-height: 270px;
    padding: 26px 30px;
  }

  .promo-block--small {
    min-height: 240px;
  }

  .promo-block--large {
    min-height: 300px;
  }
}

@media screen and (min-width: 1000px) {
  .promo-block {
    min-height: 310px;
  }

  .promo-block--small {
    min-height: 280px;
  }

  .promo-block--large {
    min-height: 360px;
  }

  .promo-block__image-wrapper {
    background-size: auto 260px;
  }

  .promo-block--small .promo-block__image-wrapper {
    background-size: auto 220px;
  }

  .promo-block__heading {
    margin-bottom: 8px;
  }

  .promo-block__cta {
    margin-top: 8px;
  }
}
/**
 * --------------------------------------------------------------------
 * GENERAL
 *
 * IMPLEMENTATION NOTE: Shopify Reviews CSS overrides our own CSS, as a consequence
 *                      to increase the CSS specificity, I had to add a wrapping class
 *                      or using the "double class" (eg: .spr-icon.spr-icon) to take precedence
 * --------------------------------------------------------------------
 */

.spr-starrating.spr-starrating,
.spr-starratings.spr-starratings {
  position: relative;
  display: inline-flex;
  align-items: center;
  margin: 0;
  height: 14px;
}

.spr-starrating .spr-icon.spr-icon,
.spr-starratings .spr-icon.spr-icon {
  display: inline-block;
  top: 0;
  height: 13px;
  width: 13px;
  font-size: 13px;
  opacity: 1;
}

.spr-icon.spr-icon::before {
  content: "A" !important;
  display: inline-block;
  font-family: "font-theme-star";
  font-size: inherit;
  font-style: normal;
  font-weight: normal;
  vertical-align: top;
  line-height: 1em;
}

.spr-icon {
  color: var(--product-review-star-color);
}

.spr-icon-star-empty.spr-icon-star-empty {
  color: rgba(var(--text-color-rgb), 0.4) !important;
}

.spr-icon + .spr-icon {
  margin-left: 4px;
}

@media screen and (min-width: 641px) {
  .spr-summary-starrating .spr-icon.spr-icon,
  .spr-form-input .spr-icon.spr-icon {
    width: 17px;
    height: 17px;
    font-size: 17px;
  }
}

/**
 * --------------------------------------------------------------------
 * BADGE
 * --------------------------------------------------------------------
 */

.spr-badge {
  display: flex !important;
  align-items: center;
  line-height: 1;
}

.spr-badge .spr-badge-caption {
  margin-left: 7px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
}

/**
 * --------------------------------------------------------------------
 * MAIN REVIEW
 * --------------------------------------------------------------------
 */
#shopify-product-reviews {
  margin: 0 !important;
  overflow: visible !important;
}

#shopify-product-reviews .spr-container {
  padding: 0;
  border: none;
}

#shopify-product-reviews .spr-header {
  position: relative;
}

#shopify-product-reviews .spr-header-title {
  font-family: var(--heading-font-family);
  font-weight: var(--heading-font-weight);
  font-style: var(--heading-font-style);
  color: var(--heading-color);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 20px));
  line-height: 1.6;
  margin-bottom: 7px;
  text-align: left;
}

#shopify-product-reviews .spr-summary {
  display: flex;
  flex-wrap: wrap;
  text-align: left;
  align-items: center;
}

#shopify-product-reviews .spr-summary-caption {
  line-height: 1;
}

#shopify-product-reviews .spr-summary-actions {
  display: block;
  width: 100%;
}

#shopify-product-reviews .spr-summary-starrating {
  margin-right: 10px;
}

#shopify-product-reviews .spr-summary-actions-newreview,
#shopify-product-reviews .spr-button {
  position: relative;
  display: inline-block;
  padding: 0 30px;
  line-height: 48px;
  border-radius: 8px;
  text-align: center;
  font-weight: var(--text-font-bolder-weight);
  font-size: var(--base-text-font-size);
  cursor: pointer;
  transition: background 0.25s ease-in-out, color 0.25s ease-in-out, box-shadow 0.25s ease-in-out;
  float: none;
  background: var(--primary-button-background);
  color: var(--primary-button-text-color);
}

#shopify-product-reviews .spr-summary-actions-newreview:hover,
#shopify-product-reviews .spr-button:hover {
  background: rgba(var(--primary-button-background-rgb), 0.8);
}

#shopify-product-reviews .spr-form,
#shopify-product-reviews .spr-reviews {
  margin-top: 44px;
  border-top: 1px solid var(--border-color);
}

#shopify-product-reviews .spr-form-submitted + .spr-reviews {
  margin-top: 0;
  border-top: none;
}

#shopify-product-reviews .spr-review {
  position: relative;
  border-top: none;
  margin: 28px 0 0 0;
  padding: 0;
}

#shopify-product-reviews .spr-review + .spr-review {
  margin-top: 32px;
}

#shopify-product-reviews .spr-review-header-starratings {
  margin-bottom: 12px;
}

#shopify-product-reviews .spr-review-header-title {
  margin-bottom: 14px;
  color: var(--heading-color);
  font-weight: var(--text-font-bolder-weight);
  font-size: 1rem;
  line-height: 1.75;
}

#shopify-product-reviews .spr-review-header-byline {
  position: absolute;
  margin: 0;
  bottom: calc(1em + 12px);
  left: 0;
  opacity: 1;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
}

#shopify-product-reviews .spr-review-header-byline strong {
  font-weight: normal;
}

#shopify-product-reviews .spr-review-content,
#shopify-product-reviews .spr-review-reply {
  margin-bottom: calc(1em + 22px);
}

#shopify-product-reviews .spr-review-reply {
  margin-top: -1.4em;
  padding: 0 0 0 12px;
  background: none;
  border-left: 2px solid var(--border-color);
}

#shopify-product-reviews .spr-review-reply-shop {
  float: none;
}

#shopify-product-reviews .spr-review-content-body {
  line-height: 1.75;
  font-size: 1rem;
}

#shopify-product-reviews .spr-review-reportreview {
  color: var(--accent-color);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
  float: none;
  transition: color 0.2s ease-in-out;
}

#shopify-product-reviews .spr-review-reportreview:hover {
  text-decoration: underline; /*text-underline-position: under;*/
}

#shopify-product-reviews .spr-form {
  padding: 0;
}

#shopify-product-reviews .spr-form > form {
  padding-top: 22px;
}

#shopify-product-reviews .spr-form-title {
  display: none !important;
}

#shopify-product-reviews .spr-form-label {
  display: block;
  margin-bottom: 8px;
  color: var(--heading-color);
  font-weight: var(--text-font-bolder-weight);
  font-size: 1rem;
}

#shopify-product-reviews .spr-form-input-text,
#shopify-product-reviews .spr-form-input-textarea,
#shopify-product-reviews .spr-form-input-email {
  display: block;
  padding: 9px 14px;
  border-radius: 8px;
  border: none;
  background: #ededed;
  color: #8a8a8a;
  width: 100%;
  min-height: 48px;
  line-height: normal;
  -webkit-appearance: none;
  resize: none;
  transition: border-color 0.2s ease-in-out, box-shadow 0.2s ease-in-out, color 0.2s ease-in-out;
}

#shopify-product-reviews .spr-form-input-textarea {
  line-height: 1.87;
  max-height: 180px;
}

#shopify-product-reviews .spr-form-input-text:focus,
#shopify-product-reviews .spr-form-input-textarea:focus,
#shopify-product-reviews .spr-form-input-email:focus {
  border-color: var(--accent-color);
  box-shadow: 0 0 0 1px var(--accent-color);
  color: var(--heading-color);
  outline: none;
}

#shopify-product-reviews .spr-form-input::-webkit-input-placeholder {
  color: rgba(var(--text-color-rgb), 0.6);
}

#shopify-product-reviews .spr-form-input::-moz-placeholder {
  color: rgba(var(--text-color-rgb), 0.6);
}

#shopify-product-reviews .spr-form-input:-ms-input-placeholder {
  color: rgba(var(--text-color-rgb), 0.6);
}

#shopify-product-reviews .spr-form-input::-ms-input-placeholder {
  color: rgba(var(--text-color-rgb), 0.6);
}

#shopify-product-reviews .spr-form-input::placeholder {
  color: rgba(var(--text-color-rgb), 0.6);
}

#shopify-product-reviews .spr-form-input.spr-starrating {
  display: block;
}

#shopify-product-reviews .spr-form-contact-name,
#shopify-product-reviews .spr-form-contact-email,
#shopify-product-reviews .spr-form-contact-location,
#shopify-product-reviews .spr-form-review-rating,
#shopify-product-reviews .spr-form-review-title,
#shopify-product-reviews .spr-form-review-body {
  margin-bottom: 25px;
}

#shopify-product-reviews .spr-form-message {
  display: block;
  margin-top: 6px;
  padding: 10px 15px;
  white-space: normal;
  font-size: 1rem;
  word-break: break-all;
  word-break: break-word;
}

#shopify-product-reviews .spr-form-message-success {
  background: var(--success-background);
  color: var(--success-color);
}

#shopify-product-reviews .spr-form-message-error {
  background: var(--error-background);
  color: var(--error-color);
}

#shopify-product-reviews .spr-pagination {
  margin-top: 16px;
  color: var(--heading-color);
  font-weight: var(--text-font-bolder-weight);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  border-top: none;
}

#shopify-product-reviews .spr-pagination a {
  transition: color 0.2s ease-in-out;
}

#shopify-product-reviews .spr-pagination a:hover {
  color: var(--accent-color);
}

#shopify-product-reviews .spr-pagination-page {
  display: inline-block;
}

#shopify-product-reviews .spr-pagination-page a,
#shopify-product-reviews .spr-pagination-page.is-active {
  display: block;
  margin: 0 2px;
  padding: 8px 11px;
  line-height: 1;
}

#shopify-product-reviews .spr-pagination-page.is-active {
  display: inline-block;
  background: var(--accent-color);
  color: var(--secondary-background);
  border-radius: 3px;
}

#shopify-product-reviews .spr-pagination-next a,
#shopify-product-reviews .spr-pagination-prev a {
  display: flex;
  align-items: center;
}

#shopify-product-reviews .spr-pagination-next svg,
#shopify-product-reviews .spr-pagination-prev svg {
  position: relative;
  width: 8px;
  height: 12px;
}

#shopify-product-reviews .spr-pagination-prev svg {
  margin-right: 14px;
}

#shopify-product-reviews .spr-pagination-next svg {
  margin-left: 14px;
}

@media screen and (max-width: 640px) {
  #shopify-product-reviews .spr-form,
  #shopify-product-reviews .spr-reviews {
    margin-top: 24px;
    border-top: none;
    padding: 0;
  }

  #shopify-product-reviews .spr-form-submitted {
    margin-top: 0;
  }

  #shopify-product-reviews .spr-form::before,
  #shopify-product-reviews .spr-form:not(.spr-form-submitted) + .spr-reviews::before,
  #shopify-product-reviews .spr-pagination::before {
    position: relative;
    content: "";
    display: block;
    width: calc(100% + var(--mobile-container-gutter));
    height: 1px;
    background: var(--border-color);
  }

  #shopify-product-reviews .spr-pagination > div {
    padding-top: 20px;
  }

  #shopify-product-reviews .spr-summary-actions {
    margin-top: 20px;
  }
}

@media screen and (min-width: 641px) {
  #shopify-product-reviews .spr-header-title {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 21px));
    line-height: 1.5;
    margin-bottom: 15px;
  }

  #shopify-product-reviews.spr-reviews--has-reviews .spr-summary {
    margin-bottom: -13px;
  }

  #shopify-product-reviews .spr-summary-actions {
    position: absolute;
    right: 0;
    top: 0.5em;
    width: auto;
  }

  #shopify-product-reviews .spr-review + .spr-review {
    margin-top: 41px;
  }

  #shopify-product-reviews .spr-review:first-child {
    margin-top: 35px;
  }

  #shopify-product-reviews .spr-review-header-title {
    margin-bottom: 12px;
  }

  #shopify-product-reviews .spr-review-content,
  #shopify-product-reviews .spr-review-reply {
    margin: 0 0 17px 0;
  }

  #shopify-product-reviews .spr-review-footer {
    text-align: right;
  }

  #shopify-product-reviews .spr-review-reportreview {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
  }

  #shopify-product-reviews .spr-review-header-byline {
    bottom: 0;
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  }

  #shopify-product-reviews .spr-pagination {
    margin-top: 30px;
    padding-top: 30px;
    border-top: 1px solid var(--border-color);
  }
}
.rte {
  word-break: break-word; /* Prevent long words to go outside the container */
}

/* Simple, minimum clearfix added to every RTE text to avoid issue with float */
.rte::after {
  content: "";
  display: block;
  clear: both;
}

.rte h1,
.rte h2,
.rte h3,
.rte h4,
.rte h5,
.rte h6 {
  margin: 1em 0;
  font-family: var(--heading-font-family);
  font-weight: var(--heading-font-weight);
  font-style: var(--heading-font-style);
  color: var(--heading-color);
}

.rte h1:first-child,
.rte h2:first-child,
.rte h3:first-child,
.rte h4:first-child,
.rte h5:first-child,
.rte h6:first-child {
  margin-top: 0;
}

.rte h1 {
  margin: 1.4em 0 0.7em 0;
}

.rte h2 {
  margin: 1.55em 0 0.6em 0;
}

.rte h3 {
  margin: 1.8em 0 0.8em 0;
}

.rte h4 {
  margin: 1.9em 0 0.6em 0;
}

.rte h5 {
  margin: 2.2em 0 0.7em 0;
}

.rte h6 {
  margin: 2.5em 0 0.6em 0;
}

.rte img {
  display: block;
}

.rte p:not(:last-child),
.rte ul:not(:last-child),
.rte ol:not(:last-child) {
  margin-bottom: 0.7em;
}

.rte a:not(.button) {
  color: var(--link-color);
  transition: color 0.2s ease-in-out;
  -webkit-text-decoration: var(--text-link-decoration);
  text-underline-position: under;
}

.linkcarrinho {
  color: var(--link-color);
  margin-botton: 2px;
}

.rte a:not(.button):hover {
  color: var(--link-color-hover);
}

.rte p + .button {
  margin-top: 1em;
}

.rte ul, .rte ol {
  margin-left: 18px;
}

.rte ul li, .rte ol li {
  position: relative;
}

.rte ul li:not(:last-child), .rte ol li:not(:last-child) {
  margin-bottom: 5px;
}

.rte ul {
  list-style: none;
}

.rte ul li::before {
  position: absolute;
  content: "";
  left: -18px;
  top: 0.8em;
  height: 5px;
  width: 5px;
  border-radius: 100%;
  background: rgba(var(--text-color-rgb), 0.4);
}

.rte ol {
  list-style-position: outside;
}

.rte img,
.rte .video-wrapper {
  margin: 2.7em 0;
}

.rte blockquote {
  margin: 3em 0 3em 10px;
  padding-left: 20px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
  border-left: 5px solid rgba(var(--text-color-rgb), 0.4);
}

.rte table {
  margin-top: 2em;
}

@media screen and (min-width: 641px) {
  .rte blockquote {
    padding-left: 30px;
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 18px));
  }

  .rte img,
  .rte .video-wrapper {
    margin: 3em 0;
  }
}
.section {
  margin: 50px 0;
}

.section--tight {
  margin: 30px 0;
}

/* When isolated, sections use padding instead of margin (useful for sections that has plain background) */
.section--isolated {
  margin: 0 !important;
  padding: 50px 0;
}

.section--isolated.section--tight {
  padding: 40px 0;
}

.section--text-centered {
  text-align: center;
}

.section__header {
  display: flex;
  align-items: baseline;
  justify-content: space-between;
  margin-bottom: 15px;
  overflow: hidden;
}

.section__title {
  margin-bottom: 0;
}

.section__title::after {
    content: '';
    display: flex;
    bottom: 0;
    left: 0;
    right: 0;
    background: var(--accent-color);
    height: 6px;
    width: 90%;
    border-radius: 10px;
}

.section__action-link {
  margin-left: 20px;
  flex-shrink: 0;
  font-weight: var(--text-font-bolder-weight);
  color: var(--accent-color);
}

.section__action-link svg {
  display: none;
}

/* The header stack is used when we display more info like a countdown timer */
.section__header-stack {
  display: flex;
  flex-direction: column;
}

/* Isolated sections are isolated due to their usage of different background/color, so here we must inherit the heading color */
.section--isolated .heading {
  color: inherit;
}

@media screen and (max-width: 640px) {
  .section__header-stack > .section__title + * {
    margin-top: 10px;
  }
}

@media screen and (min-width: 641px) {
  .section {
    margin: 60px 0;
  }

  .section--tight {
    margin: 40px 0;
  }

  .section--isolated {
    padding: 60px 0;
  }

  .section__header {
    overflow: visible;
    margin-bottom: 20px;
  }

  .section__header--tight {
    margin-bottom: 14px;
  }

  .section__header-stack {
    flex-direction: row;
    align-items: center;
  }

  .section__action-link {
    transform: translateX(26px);
    transition: transform 0.35s cubic-bezier(0.645, 0.045, 0.355, 1);
  }

  .section__action-link svg {
    /*
    Note: for some strange reasons, on Safari (even last version), if we use a transform it cause a delay of up to 1 second on heavy home page before the
    animation starts. I couldn't find any explanation, but maybe the nested transforms (on both the link and SVG) does not work correctly on Safari. As a
    consequence, I've used a animation on right property (which is much slower but should be ok on this small piece of content)
    */
    position: relative;
    display: inline-block;
    height: 14px;
    width: 14px;
    vertical-align: -2px;
    margin-left: 8px;
    right: -5px;
    opacity: 0;
    transition: all 0.35s cubic-bezier(0.645, 0.045, 0.355, 1);
  }

  .section__header-stack > .section__title {
    margin: 0 16px 0 0;
  }
}

@media (-moz-touch-enabled: 0),(hover: hover) {
  .section__action-link:hover {
    transform: translateX(0);
  }

  .section__action-link:hover svg {
    opacity: 1;
    right: 0;
  }
}
.slideshow {
  height: 400px;
  overflow: hidden;
}

.slideshow--small {
  height: 350px;
}

.slideshow--large {
  height: 450px;
}

.slideshow__slide {
  position: relative;
  display: block;
  width: 100%;
  height: 100%;
}

.slideshow__slide-inner {
  position: absolute;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-size: cover;
  background-position: center;
}

.slideshow:not(.flickity-enabled) .slideshow__slide:not(.is-selected) {
  display: none;
}

.slideshow__placeholder {
  position: absolute;
  width: 100%;
  height: 100%;
  left: 0;
  top: 0;
  z-index: -1;
}

.slideshow__image-placeholder {
  height: 100%;
  fill: dimgrey;
  background: darkgrey;
}

.slideshow__title {
  margin-bottom: 7px;
  color: inherit;
}

.slideshow__content-wrapper {
  position: relative;
  z-index: 1;
  width: 100%;
  padding-top: 40px;
  padding-bottom: 25px;
}

.slideshow__content {
  max-width: 650px;
  margin: 0 auto 22px auto;
}

.slideshow .flickity-page-dots {
  bottom: 30px;
}

.slideshow .flickity-page-dots .dot {
  width: 12px;
  height: 12px;
  margin: 0 8px;
  background: #ffffff;
  border: 3px solid #ffffff;
  transform: none !important;
  transition: background 0.25s ease-in-out;
}

.slideshow .flickity-page-dots .dot::before {
  top: -10px;
  right: -10px;
  left: -10px;
  bottom: -10px;
}

.slideshow .flickity-page-dots .dot.is-selected {
  background: transparent;
}

/** Overlay variation **/
.slideshow__slide--overlay::before {
  position: absolute;
  content: "";
  height: 100%;
  width: 100%;
  left: 0;
  top: 0;
  background: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.3));
  z-index: 1;
}

/** Preserve ratio variation

 IMPLEMENTATION NOTE: I am using two different ways to center the content. If the slideshow is a fixed height, the theme uses a flexbox
                      based approach, while if the slideshow is not fixed (ie. respecting the image aspect ratio), I use a transform based
                      approach. I could have keep it simpler and use the transform based everywhere (which would have removed a lot of code),
                      but the transform based is proved to reduce sometimes the quality of the text and make it a bit blurry. This is why
                      there is another, more optimized way to position when it is possible
 **/
.slideshow--preserve-ratio {
  height: auto !important;
}

.slideshow--preserve-ratio .slideshow__slide {
  height: auto;
}

.slideshow--preserve-ratio .slideshow__slide-inner {
  position: relative;
  display: block;
  width: auto;
  height: auto;
}

.slideshow--preserve-ratio .slideshow__content-wrapper {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

@media screen and (min-width: 641px) {
  .slideshow:not(.slideshow--edge2edge) {
    margin: var(--desktop-container-gutter) 0;
  }

  .slideshow:not(.slideshow--edge2edge) .flickity-viewport {
    border-radius: 10px;
  }

  .slideshow__image-placeholder {
    height: auto;
    width: 100%;
  }

  /* Positioning for fixed height carousel */
  .slideshow__slide-inner--top-left,
  .slideshow__slide-inner--top-center,
  .slideshow__slide-inner--top-right {
    justify-content: flex-start;
  }

  .slideshow__slide-inner--bottom-left,
  .slideshow__slide-inner--bottom-center,
  .slideshow__slide-inner--bottom-right {
    justify-content: flex-end;
  }

  .slideshow__slide-inner--bottom-left .slideshow__content-wrapper,
  .slideshow__slide-inner--bottom-center .slideshow__content-wrapper,
  .slideshow__slide-inner--bottom-right .slideshow__content-wrapper {
    padding-bottom: 75px;
    padding-top: 25px;
  }

  .slideshow__slide-inner--top-left,
  .slideshow__slide-inner--middle-left,
  .slideshow__slide-inner--bottom-left {
    text-align: left;
  }

  .slideshow__slide-inner--top-left .slideshow__content,
  .slideshow__slide-inner--middle-left .slideshow__content,
  .slideshow__slide-inner--bottom-left .slideshow__content {
    margin-left: 0;
  }

  .slideshow__slide-inner--top-right,
  .slideshow__slide-inner--middle-right,
  .slideshow__slide-inner--bottom-right {
    text-align: right;
  }
  .slideshow__slide-inner--top-right .slideshow__content,
  .slideshow__slide-inner--middle-right .slideshow__content,
  .slideshow__slide-inner--bottom-right .slideshow__content {
    margin-right: 0;
  }

  /* Positioning for non-fixed height carousel */
  .slideshow--preserve-ratio .slideshow__slide-inner--top-left .slideshow__content-wrapper,
  .slideshow--preserve-ratio .slideshow__slide-inner--top-center .slideshow__content-wrapper,
  .slideshow--preserve-ratio .slideshow__slide-inner--top-right .slideshow__content-wrapper {
    top: 0;
    transform: translateX(-50%);
  }

  .slideshow--preserve-ratio .slideshow__slide-inner--bottom-left .slideshow__content-wrapper,
  .slideshow--preserve-ratio .slideshow__slide-inner--bottom-center .slideshow__content-wrapper,
  .slideshow--preserve-ratio .slideshow__slide-inner--bottom-right .slideshow__content-wrapper {
    top: auto;
    bottom: 0;
    transform: translateX(-50%);
  }
}

@media screen and (min-width: 1000px) {
  .slideshow {
    height: 430px;
  }

  .slideshow--small {
    height: 380px;
  }

  .slideshow--large {
    height: 520px;
  }
}
.team {
  margin-top: 45px;
  margin-bottom: 62px;
  text-align: center;
}

.team__block-list {
  margin-bottom: 45px;
}

.team__block-item {
  margin-bottom: 20px;
}

@media screen and (min-width: 641px) {
  .team {
    margin-top: 62px;
    margin-bottom: 80px;
  }

  .team__block-list {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    margin: -15px -15px 47px -15px;
  }

  .team__block-item {
    margin: 15px;
    flex: none;
    width: calc(50% - 30px);
  }
}

@media screen and (min-width: 1000px) {
  .team__block-item {
    width: calc(33.33333% - 30px);
  }
}

@media screen and (min-width: 1280px) {
  .team__block-item {
    width: calc(25% - 30px);
  }
}

/* Separator */

.team__section-title {
  margin-bottom: 25px;
}

@media screen and (min-width: 641px) {
  .team__section-title {
    margin-bottom: 40px;
  }
}

/* Member */

.team__member {
  padding: 30px 20px 20px 20px;
  border: 1px solid var(--border-color);
  border-radius: 3px;
  background: var(--secondary-background);
}

.team__member-pic {
  width: 144px;
  margin-bottom: 20px;
  border: 1px solid var(--border-color);
  padding: 8px;
  background: var(--background);
}

.team__member-pic--rounded {
  border-radius: 50%;
}

.team__member-title,
.team__member-subheading {
  margin-bottom: 0;
  line-height: 1.4;
}

.team__member-title {
  margin-bottom: 6px;
}

.team__member-link {
  display: inline-block;
  margin-top: 6px;
}

/* Promotion */

.team__promotion {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  border-radius: 3px;
  padding: 30px;
}

.team__promotion .heading {
  color: inherit;
  margin-bottom: 8px;
}

.team__promotion .button {
  min-width: 105px;
  margin-top: 22px;
}
.text-with-icons__item {
  width: 100%;
  line-height: 1.6;
}

.text-with-icons__title {
  margin-bottom: 4px;
  font-weight: bold;
  color: var(--accent-color);
}

.text-with-icons__icon-wrapper {
  margin-bottom: 15px;
}

.text-with-icons__icon-wrapper svg {
  width: 30px;
  height: 30px;
  vertical-align: middle;
}

.text-with-icons__icon-wrapper img {
  max-width: 30px;
}

.text-with-icons__content > p {
  margin-bottom: 0;
  font-size: 12px;
}

@media screen and (max-width: 640px) {
  .text-with-icons {
    padding-bottom: 28px;
    text-align: center;
    padding-left: 20px;
    padding-right: 20px;
    margin-bottom: 50px;
  }

  .text-with-icons::after {
    content: "flickity";
    display: none;
  }

  .text-with-icons--stacked {
    padding-bottom: 0;
  }

  .text-with-icons--stacked .text-with-icons__item:not(:last-child) {
    margin-bottom: 34px;
  }

  .text-with-icons--stacked::after {
    content: ""; /* Disable Flickity */
  }
}

@media screen and (min-width: 641px) {
  .text-with-icons {
    display: flex;
    flex-wrap: wrap;
    margin: 0 -40px -45px -40px;
  }

  /* When it follows a page__header element we slightly move it up */
  .page__header + .text-with-icons {
    margin-top: -5px;
  }

  .text-with-icons__item {
    padding: 15px 20px;
  }

  .text-with-icons__icon-wrapper {
    margin: 0.5em 18px 0 0;
  }
}

@media screen and (min-width: 1000px) {
  .text-with-icons {
    padding: 0 100px;
    justify-content: center;
  }

  .text-with-icons__item {
    display: flex;
    flex-basis: calc(50% - 140px);
  }
}

@media screen and (min-width: 1280px) {
  .text-with-icons {
    padding: 0;
    margin: 0 -35px;
    flex-wrap: nowrap;
    justify-content: space-around;
  }

  .text-with-icons__item {
    flex-basis: calc(25% - 70px);
    margin: 0 35px;
  }
}

/* Boxed variation */
.text-with-icons--boxed {
  display: block;
  text-align: center;
  padding-bottom: 0;
  border: 1px solid var(--border-color);
  border-radius: 3px;
}

.text-with-icons--boxed .text-with-icons__item {
  display: block;
  text-align: center;
  padding: 28px 35px;
}

.text-with-icons--boxed .text-with-icons__item:not(:first-child) {
  border-top: 1px solid var(--border-color);
}

.text-with-icons--boxed .text-with-icons__icon-wrapper {
  margin: 0 0 1em 0;
}

@media screen and (min-width: 641px) {
  .text-with-icons--boxed {
    display: flex;
    flex-wrap: nowrap;
    margin: 0;
    padding: 0;
  }

  .text-with-icons--boxed .text-with-icons__item {
    margin: 0;
    flex: 1 0 0;
  }

  .text-with-icons--boxed .text-with-icons__item:not(:first-child) {
    border-top: none;
    border-left: 1px solid var(--border-color);
  }
}
/**
 * --------------------------------------------------------------------
 * CLEARFIX
 * --------------------------------------------------------------------
 */

.clearfix::before,
.clearfix::after {
  display: table;
  content: "";
}

/**
 * --------------------------------------------------------------------
 * LIST
 * --------------------------------------------------------------------
 */

.list--unstyled {
  list-style: none;
}

/**
 * --------------------------------------------------------------------
 * COLLAPSIBLE
 * --------------------------------------------------------------------
 */

.collapsible {
  overflow: hidden;
  height: 0;
  transition: height 0.2s ease-in-out;
}

/**
 * --------------------------------------------------------------------
 * SOCIAL MEDIA
 * --------------------------------------------------------------------
 */

.social-media__item-list {
  display: flex;
  flex-wrap: wrap;
  margin: -5px;
}

.social-media__item {
  display: inline-block;
  margin: 5px;
}

.social-media__item > a {
  display: block;
}

.social-media__item svg {
  width: 28px;
  height: 28px;
  opacity: 0.4;
  transition: color 0.25s ease-in-out, opacity 0.25s ease-in-out;
  will-change: opacity;
}

/* Stacked variation */
.social-media__item-list--stack {
  display: block;
  margin: -10px 0;
}

.social-media__item-list--stack .social-media__item {
  display: block;
  margin: 0;
  padding: 7px 0;
}

.social-media__item-list--stack svg {
  vertical-align: top;
  margin-right: 12px;
}

@media (-moz-touch-enabled: 0),(hover: hover) {
  .social-media__item:hover svg {
    opacity: 1;
  }

  .social-media__item--facebook:hover svg {
    color: #3b5998;
  }

  .social-media__item--twitter:hover svg {
    color: #1da1f2;
  }

  .social-media__item--pinterest:hover svg {
    color: #bd081c;
  }

  .social-media__item--instagram:hover svg {
    color: #d83776;
  }

  .social-media__item--youtube:hover svg {
    color: #ff0000;
  }

  .social-media__item--vimeo:hover svg {
    color: #1ab7ea;
  }

  .social-media__item--linkedin:hover svg {
    color: #0077b5;
  }

  .social-media__item--snapchat:hover svg {
    color: #f5dc30;
  }

  .social-media__item--tumblr:hover svg {
    color: #35465c;
  }

  .social-media__item--fancy:hover svg {
    color: #494e58;
  }

  .social-media__item--rss:hover svg {
    color: #f26522;
  }
}

/**
 * --------------------------------------------------------------------
 * ALERT
 * --------------------------------------------------------------------
 */

.alert {
  display: block;
  padding: 12px 20px;
  margin-bottom: 20px;
  border-radius: 2px;
  white-space: normal;
  font-size: 1rem;
  word-break: break-all;
  word-break: break-word;
  background: var(--background);
  color: var(--heading-color);
  text-align: left;
}

.alert:last-child {
  margin-bottom: 0;
}

.alert--block {
  display: block;
}

.alert--center {
  text-align: center;
}

.alert--tight {
  padding: 6px 14px;
}

.alert--error {
  background: var(--error-background);
  color: var(--error-color);
}

.alert--success {
  background: var(--success-background);
  color: var(--success-color);
}

.alert__ribbon {
  margin-left: 5px;
  margin-right: 25px;
  align-self: center;
}
.alert__ribbon svg {
  display: block;
  width: 24px;
  height: 24px;
}

.alert__error-list {
  list-style: none;
}

.alert a {
  text-decoration: underline;
  transition: color 0.2s ease-in-out;
}

/**
 * --------------------------------------------------------------------
 * PAGINATION
 * --------------------------------------------------------------------
 */

.pagination {
  padding: 40px 0;
  color: var(--heading-color);
  font-weight: var(--text-font-bolder-weight);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
  border-top: 1px solid var(--border-color);
}

.pagination__inner {
  position: relative;
}

.pagination__prev,
.pagination__next {
  position: absolute;
  display: flex;
  align-items: center;
  top: 0;
  height: 100%;
}

.pagination__prev svg,
.pagination__next svg {
  position: relative;
  width: 8px;
  height: 12px;
}

.pagination__prev {
  left: 0;
}

.pagination__prev svg {
  margin-right: 14px;
}

.pagination__next {
  right: 0;
}

.pagination__next svg {
  margin-left: 14px;
}

.pagination__nav,
.pagination__page-count {
  display: block;
  text-align: center;
}

.pagination__nav {
  display: none;
}

.pagination__nav-item {
  display: inline-block;
  margin: 0 2px;
  padding: 8px 11px;
  line-height: 1;
}

.pagination__nav-item.is-active {
  background: var(--primary-button-background);
  color: var(--primary-button-text-color);
  border-radius: 3px;
}

/* If pagination is inside a card, we adapt the spacing */
.card .pagination {
  padding: 20px;
}

@media screen and (min-width: 641px) {
  .pagination__nav {
    display: block;
  }

  .pagination__page-count {
    display: none;
  }

  .card .pagination {
    padding: 20px 30px;
  }
}

/**
 * --------------------------------------------------------------------
 * SCROLLER
 * --------------------------------------------------------------------
 */

@media screen and (max-width: 999px) {
  .scroller {
    overflow: hidden;
    margin: 0 calc(-1 * var(--mobile-container-gutter)); /* On mobile we remove the container gutter to make sure the scroll is edge to edge */
  }

  .scroller--flush {
    margin: 0 !important;
  }

  .scroller__inner {
    padding-bottom: 20px;
    margin-bottom: -20px;
    overflow-x: auto;
    overflow-y: hidden;
    -webkit-overflow-scrolling: touch;
    -ms-scroll-snap-type: x mandatory;
        scroll-snap-type: x mandatory;
    white-space: nowrap;
  }
}

@media screen and (min-width: 641px) and (max-width: 999px) {
  .scroller {
    margin: 0 calc(-1 * var(--desktop-container-gutter));
  }

  .scroller__inner {
    scroll-padding-left: var(--desktop-container-gutter);
  }

  .scroller--mobile-only {
    margin: 0;
    overflow: visible;
  }

  .scroller--mobile-only > .scroller__inner {
    padding-bottom: 0;
    margin-bottom: 0;
    overflow: visible;
  }
}

/**
 * --------------------------------------------------------------------
 * SKELETON
 * --------------------------------------------------------------------
 */

@-webkit-keyframes skeletonShimmerAnimation {
  0% {
    opacity: 0.45;
  }
  100% {
    opacity: 0.9;
  }
}

@keyframes skeletonShimmerAnimation {
  0% {
    opacity: 0.45;
  }
  100% {
    opacity: 0.9;
  }
}

.skeleton-container {
  -webkit-animation: skeletonShimmerAnimation 1s linear infinite alternate;
          animation: skeletonShimmerAnimation 1s linear infinite alternate;
  will-change: opacity;
}

.skeleton-text {
  height: 10px;
  width: 100%;
  background: var(--border-color);
}

.skeleton-image {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  background: var(--border-color);
}

.skeleton-paragraph .skeleton-text {
  margin-bottom: 8px;
}

.skeleton-paragraph .skeleton-text:last-child {
  width: 38%;
  margin-bottom: 0;
}

/**
 * --------------------------------------------------------------------
 * PLUS BUTTON
 * --------------------------------------------------------------------
 */

.plus-button {
  display: block;
  position: relative;
  right: 0;
  top: calc(50% - 5px);
  width: 10px;
  height: 10px;
}

.plus-button::before,
.plus-button::after {
  position: absolute;
  content: "";
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%) rotate(-90deg);
  background-color: currentColor;
  transition: transform 0.35s ease-in-out, opacity 0.35s ease-in-out;
}

.plus-button::before {
  width: 10px;
  height: 2px;
  opacity: 1;
}

.plus-button::after {
  width: 2px;
  height: 10px;
}

[aria-expanded=true] .plus-button::before, [aria-expanded=true] .plus-button::after {
  transform: translate(-50%, -50%) rotate(90deg);
}

[aria-expanded=true] .plus-button::before {
  opacity: 0;
}

@media screen and (min-width: 641px) {
  .plus-button--large {
    width: 14px;
    height: 14px;
  }

  .plus-button--large::before {
    width: 14px;
  }

  .plus-button--large::after {
    height: 14px;
  }
}

/**
 * --------------------------------------------------------------------
 * SHOPIFY CHALLENGE
 * --------------------------------------------------------------------
 */

.shopify-challenge__container {
  margin-top: 50px;
  margin-bottom: 50px;
  text-align: center;
}

.shopify-challenge__button.shopify-challenge__button {
  position: relative;
  display: inline-block;
  padding: 9px 30px;
  min-height: 48px;
  line-height: normal;
  border-color: var(--secondary-button-background);
  border-radius: 2px;
  text-align: center;
  font-weight: var(--text-font-bolder-weight);
  font-size: var(--base-text-font-size);
  cursor: pointer;
  transition: background 0.25s ease-in-out, color 0.25s ease-in-out, border 0.25s ease-in-out;
  background: var(--secondary-button-background);
  color: var(--secondary-button-text-color);
}

.shopify-challenge__button.shopify-challenge__button:hover {
  background: rgba(var(--secondary-button-background-rgb), 0.8);
}

@media screen and (min-width: 641px) {
  .shopify-challenge__container {
    margin-top: 100px;
    margin-bottom: 100px;
  }
}

/**
 * --------------------------------------------------------------------
 * SHOPIFY POLICY CONTAINER
 * --------------------------------------------------------------------
 */

.shopify-policy__container {
  max-width: 800px;
}

.shopify-policy__title {
  margin: 30px 0;
}

.shopify-policy__title h1 {
  margin-bottom: 0;
  font-family: var(--heading-font-family);
  font-weight: var(--heading-font-weight);
  font-style: var(--heading-font-style);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 24px));
  line-height: 1.45;
  color: var(--heading-color);
}

@media screen and (min-width: 641px) {
  .shopify-policy__title {
    margin: 30px 0;
  }

  .shopify-policy__title h1 {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 28px));
    line-height: 1.45;
  }
}

/**
 * --------------------------------------------------------------------
 * ANNOUNCEMENT BAR
 * --------------------------------------------------------------------
 */

.announcement-bar {
  position: relative;
  display: block;
  font-weight: var(--text-font-bolder-weight);
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
}

.announcement-bar__content {
  display: block;
  padding: 4px 0;
  margin-bottom: 0;
}

.announcement-bar__content--center {
  text-align: center;
}

@media screen and (max-width: 640px) {
  .announcement-bar__inner {
    text-align: center; /* Always centered on mobile no matter the setting */
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 5px 0px 5px 0px;
    font-size: 14px;
  }
}

@media screen and (min-width: 641px) {
  .announcement-bar {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
    text-align: left;
  }

  .announcement-bar__inner {
    display: flex;
    align-items: center;
  	justify-content: center;
    width: 100%;
    padding: 5px 0px 5px 0px;
    font-size: 14px;
  }

  .announcement-bar__content {
    padding: 7px 0;
  }

  .announcement-bar__content--center {
    margin-left: auto;
    padding-left: 0px;
    padding-left: var(--announcement-bar-button-width, 0px); /* We have to shift by the button width to center visually */
  }

  .announcement-bar__button {
    padding: 7px 18px 7px 15px;
    background: var(--header-accent-color);
    color: var(--secondary-background);
    box-shadow: 0 1px var(--header-accent-color);
  }

  .announcement-bar__button svg {
    display: inline-block;
    width: 20px;
    height: 17px;
    margin-right: 12px;
    vertical-align: text-bottom;
  }

  .announcement-bar__close-container {
    position: relative;
  }

  .announcement-bar__close {
    position: absolute;
    top: 25px;
    right: 0;
    color: var(--heading-color);
    transition: color 0.2s ease-in-out;
  }

  .announcement-bar__close:hover {
    color: var(--accent-color);
  }

  .announcement-bar__close svg {
    width: 19px;
    height: 19px;
  }

  .announcement-bar__newsletter {
    height: 0;
    overflow: hidden;
    visibility: hidden;
    text-align: center;
    transition: height 0.5s cubic-bezier(0.77, 0, 0.175, 1), visibility 0.5s cubic-bezier(0.77, 0, 0.175, 1);
  }

  .announcement-bar__newsletter[aria-hidden=false] {
    visibility: visible;
  }

  .announcement-bar__newsletter-inner {
    margin: 50px 0;
  }
}

<!-- STYLE IMAGEM RESPONSIVA -->

@media (min-width: 992px)
.d-lg-block {
    display: block!important;
}


@media (min-width: 768px)
.d-md-block {
    display: block!important;
}

@media (min-width: 576px)
.d-sm-none {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.d-none {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
}

<!-- STYLE IMAGEM RESPONSIVA FIM -->

/**
 * --------------------------------------------------------------------
 * OFFER ITEM
 * --------------------------------------------------------------------
 */

.offer-item {
  padding: 20px;
  background: var(--secondary-background);
  border: 1px solid var(--border-color);
  border-radius: 3px;
}

.offer-item__image-wrapper {
  min-width: 70px;
  max-width: 70px;
  margin-bottom: 14px;
}

.offer-item__title {
  margin-bottom: 6px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 17px));
}

.offer-item__content {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 14px));
}

@media screen and (min-width: 641px) {
  .offer-item {
    padding: 28px 30px;
  }

  .offer-item__image-wrapper {
    min-width: 110px;
    max-width: 110px;
  }
}

@media screen and (min-width: 1280px) {
  .offer-item--inline {
    display: flex;
    align-items: center;
  }

  .offer-item--inline .offer-item__image-wrapper {
    margin: 0 30px 0 0;
  }
}


/**
 * --------------------------------------------------------------------
 * IMAGE WITH TEXT
 * --------------------------------------------------------------------
 */

.image-with-text {
  display: flex;
  flex-direction: column;
}

.image-with-text__image-container {
  margin-bottom: 25px;
}

@media screen and (max-width: 999px) {
  .image-with-text__image-container {
    width: 100% !important;
    order: -1; /* Make sure the image is always coming first on small screens */
  }
}

@media screen and (min-width: 1000px) {
  .image-with-text {
    flex-direction: row;
    align-items: center;
    justify-content: center;
  }

  .image-with-text__image-container {
    max-width: 50%; /* Make sure that we constraint a maximum and minimum width no matter what the merchant choose to keep the text readable */
    min-width: 30%;
  }

  .image-with-text__image-container,
  .image-with-text__text-container {
    width: 50%;
    margin: 0;
  }

  .image-with-text__text-container:last-child {
    padding-left: 60px;
  }

  .image-with-text__text-container:first-child {
    text-align: right;
    padding-right: 60px;
  }
  .image-with-text__text-container:first-child .image-with-text__text-aligner {
    display: inline-block;
    text-align: left;
  }
}

@media screen and (min-width: 1000px) {
  .image-with-text__image-container {
    max-width: none;
    min-width: 0;
  }
}

@media screen and (min-width: 1280px) {
  .image-with-text__text-container:last-child {
    padding-left: 75px;
  }

  .image-with-text__text-container:first-child {
    padding-right: 75px;
  }
}

/**
 * --------------------------------------------------------------------
 * NEWSLETTER
 * --------------------------------------------------------------------
 */

.newsletter {
  margin-top: 30px;
}

.newsletter__form {
  padding-bottom: 10px;
}

.newsletter__text {
  margin-top: 16px;
}

/* Compact variation */
.newsletter--compact .newsletter__form {
  padding-bottom: 0;
}

.newsletter--compact .newsletter__text {
  margin-top: 16px;
}

/**
 * --------------------------------------------------------------------
 * QUICK LINKS
 * --------------------------------------------------------------------
 */

.quick-links {
  display: flex;
  flex-wrap: wrap;
  text-align: center;
  border-radius: 3px;
  list-style: none;
  background: var(--secondary-background);
  border: 1px solid var(--border-color);
  font-size: calc(var(--default-text-font-size) + 1px);
}

.quick-links__link {
  display: flex;
  justify-content: center;
  align-items: center;
  flex: 0 0 auto;
  width: 50%; /* we cannot use flex-basis due to a bug in IE11 as flex-basis does not take into account padding in this browser */
  box-shadow: 1px 0 var(--border-color), 0 1px var(--border-color);
  padding: 20px 10px;
  word-break: break-all;
  word-break: break-word;
  -webkit-hyphens: auto;
      -ms-hyphens: auto;
          hyphens: auto;
  text-transform: none;
  transition: color 0.2s ease-in-out;
}

.quick-links__link:hover {
  color: var(--accent-color);
}

.quick-links__link--grow {
  flex-grow: 1;
}

.quick-links__image-container {
  display: block;
  margin: 0 auto;
  flex: 1 1 auto;
  font-size: 0;
}

.quick-links__image-ie-fix {
  margin: 0 auto;
  transition: transform 0.3s ease-in-out;
}

@media (-moz-touch-enabled: 0),(hover: hover) {
  .features--animate-zoom .quick-links__link:hover .quick-links__image-ie-fix {
    transform: scale(1.05);
  }
}

@media screen and (min-width: 641px) {
  .quick-links__link {
    padding: 24px;
    width: 33.333333%; /* we cannot use flex-basis due to a bug in IE11 as flex-basis does not take into account padding in this browser */
  }
}
@media screen and (min-width: 1000px) {
  .quick-links__link {
    width: 16.66666667%; /* we cannot use flex-basis due to a bug in IE11 as flex-basis does not take into account padding in this browser */
  }
}

/**
 * --------------------------------------------------------------------
 * BREADCRUMB
 * --------------------------------------------------------------------
 */

.breadcrumb__list {
  display: flex;
  align-items: center;
  list-style: none;
}

.breadcrumb__list svg {
  margin: 0 7px;
  width: 6px;
  height: 8px;
  vertical-align: inherit;
}

/**
 * --------------------------------------------------------------------
 * LOADING BAR
 * --------------------------------------------------------------------
 */

.loading-bar {
  position: fixed;
  top: 0;
  left: 0;
  height: 3px;
  width: 0;
  opacity: 0;
  background: var(--accent-color);
  transition: width 0.25s ease-in-out;
  z-index: 50;
  pointer-events: none;
}

.loading-bar.is-visible {
  opacity: 1;
}

/**
 * --------------------------------------------------------------------
 * EMPTY STATE
 * --------------------------------------------------------------------
 */

.empty-state {
  margin: 100px 0;
  text-align: center;
}

.empty-state--extra-tight {
  margin: 30px 0;
}

.empty-state--tight {
  margin: 40px 0;
}

.empty-state__heading {
  margin-bottom: 15px;
}

.empty-state__text {
  margin-bottom: 32px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 15px));
}

.empty-state__quick-form {
  max-width: 410px;
  margin: 40px auto 25px auto;
}

.empty-state__button-container {
  margin-top: 16px;
}

.empty-state__button {
  min-width: 230px;
}

.empty-state__icon {
  position: relative;
  display: inline-block;
  margin-bottom: 6px;
}

.empty-state__icon .icon--package {
  width: 46px;
  height: 46px;
}

.empty-state__icon .icon--address {
  width: 46px;
  height: 45px;
}

.empty-state__icon-description {
  margin-bottom: 30px;
}

.empty-state__count {
  position: absolute;
  top: 2px;
  right: -9px;
  height: 20px;
  width: 20px;
  line-height: 20px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
  font-weight: var(--text-font-bolder-weight);
  text-align: center;
  background: var(--accent-color);
  color: var(--header-text-color);
  border-radius: 100%;
}

@media screen and (min-width: 641px) {
  .empty-state {
    margin: 170px 0;
  }

  .empty-state--extra-tight {
    margin: 40px 0;
  }

  .empty-state--tight {
    margin: 105px 0;
  }
}

/**
 * --------------------------------------------------------------------
 * PAYMENT METHODS
 * --------------------------------------------------------------------
 */

.payment-list {
  display: flex;
  flex-wrap: wrap;
  display: block;
  text-align: center;
  top: -3px;
  position: relative;
}

.payment-list__item {
  width: 38px;
  height: 24px;
  margin: 4px;
}

.payment-list__item2 {
  width: 38px;
  height: 32px;
  margin: 2px;
}

.payment-list__item4 {
  width: 38px;
  height: 32px;
  margin: 1px;
}

.payment-list__item7 {
  width: 28px;
  height: 24px;
  margin: 1px;
}

.payment-list__item5 {
  width: 20px;
  height: 20px;
  margin-left: 1px;
  margin-right: 1px;
  margin-bottom: 8px;
  margin-top: 0px;
}

.payment-list__item8 {
  width: 16px;
  height: 16px;
  margin-left: 1px;
  margin-right: 1px;
  margin-bottom: 6px;
  margin-top: 0px;
}

.payment-list__item3 {
  width: 20px;
  height: 20px;
  margin-left: 2px;
  margin-right: 2px;
  margin-bottom: 8px;
  margin-top: 0px;
}

.payment-list__notice {
  margin-top: 8px;
}

/* Centered variation */
.payment-list--centered {
  justify-content: center;
}


/**
 * --------------------------------------------------------------------
 * LAYOUT
 *
 * Layout component can be used to create a two columns layout on laptop.
 * You can also create a smaller section by adding the "secondary" class
 * to a given layout section
 * --------------------------------------------------------------------
 */

.layout {
  margin-bottom: 70px;
}

.layout .layout {
  margin-top: 18px;
  margin-bottom: 0; /* nested layouts don't have margin bottom */
}

.layout__section {
  margin-bottom: 18px;
}

.layout .card:last-child {
  margin-bottom: 0;
}

@media screen and (max-width: 999px) {
  .layout--reverse {
    display: flex;
    flex-direction: column-reverse;
  }
}

@media screen and (min-width: 641px) {
  .layout {
    margin-bottom: 100px;
  }

  .layout .layout {
    margin-top: 30px;
  }
}

@media screen and (min-width: 1000px) {
  .layout {
    display: flex;
    margin-left: -15px;
    margin-right: -15px;
  }

  .layout--pad {
    padding-top: 25px;
  }

  .layout__section {
    margin: 0 15px; /* We need to use the individual properties instead of short hand due to a bug in IE11 */
    flex-grow: 1;
    flex-shrink: 0;
    flex-basis: 0;
  }

  .layout__section:only-child {
    max-width: 680px;
    margin-left: auto;
    margin-right: auto;
  }

  .layout__section--secondary {
    flex: none;
    width: 260px;
  }

  .layout__section--large-secondary {
    flex: none;
    width: 320px;
  }
}

@media screen and (min-width: 1280px) {
  .layout__section--secondary {
    width: 288px;
  }

  .layout__section--large-secondary {
    width: 365px;
  }
}

/**
 * --------------------------------------------------------------------
 * MODAL
 * --------------------------------------------------------------------
 */

.modal {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  margin: 0 auto;
  z-index: 10;
  visibility: hidden;
  pointer-events: none;
  opacity: 0;
  transition: opacity 0.2s ease-in-out, visibility 0.2s ease-in-out;
}

.modal::before {
  position: fixed;
  content: "";
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.35);
  pointer-events: none;
}

.modal[aria-hidden=false] {
  visibility: visible;
  opacity: 1;
  pointer-events: auto;
}

.modal[aria-hidden=false] .modal__dialog {
  transform: scale(1);
  transition: transform 0.4s cubic-bezier(0.18, 1.25, 0.4, 1), visibility 0.4s linear;
}

.modal__dialog {
  position: absolute;
  width: 100%;
  height: 100%;
  max-height: 100vh;
  background: var(--secondary-background);
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.3);
  overflow: auto;
  -webkit-overflow-scrolling: touch;
  transform: scale(0.9);
  transition: transform 0.25s ease-in-out, visibility 0.25s ease-in-out;
}

.modal__loader {
  display: none;
  padding: 60px 0;
  text-align: center;
}

.modal__loader .icon--search-loader {
  width: 35px;
  height: 35px;
  color: var(--accent-color);
}

.modal__header {
  position: -webkit-sticky;
  position: sticky;
  top: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-bottom: 1px solid var(--border-color);
  background: var(--secondary-background);
  z-index: 1;
}

.modal__header,
.modal__content {
  padding: 20px;
}

.modal__header + .modal__content {
  padding-top: 30px;
}

.modal__title {
  margin-bottom: 0;
  text-align: center;
}

.modal__description {
  display: block;
  margin-bottom: 30px;
  text-align: center;
}

.modal__close {
  color: var(--heading-color);
  z-index: 1;
}

.modal__close svg {
  display: block;
  width: 20px;
  height: 20px;
}

/* Ugly fix for border radius */
.modal .card {
  background: none;
}

/* Loading state */
.modal.is-loading .modal__loader {
  display: block;
}

.modal.is-loading .modal__inner {
  display: none;
}

@media screen and (max-width: 640px) {
  .modal__content--ios-push {
    padding-bottom: 45px;
    /* This allows to take into account the toolbar height of iOS to avoid annoying double click */
  }
}

@media screen and (min-width: 641px) {
  .modal {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .modal__dialog {
    width: 580px;
    height: auto;
    max-height: calc(100% - 80px);
    border-radius: 3px;
  }

  .modal__dialog--stretch {
    width: calc(100% - 80px);
    margin-left: auto;
    margin-right: auto;
    max-width: 1200px;
  }

  .modal__header,
  .modal__content {
    padding: 30px;
  }

  .modal__header {
    position: relative;
    display: block;
    padding-bottom: 0;
    text-align: center;
    border-bottom: none;
  }

  .modal__close {
    position: absolute;
    right: 28px;
    top: 28px;
  }

  .modal__description {
    margin-top: -18px;
  }
}

/**
 * --------------------------------------------------------------------
 * ICON STATE
 *
 * This allows to switch between two icons depending on an expanded status
 * --------------------------------------------------------------------
 */

.icon-state {
  position: relative;
  vertical-align: middle;
}
.icon-state .icon-state__primary,
.icon-state .icon-state__secondary {
  display: block;
  transition: opacity 0.35s ease-in-out, transform 0.35s ease-in-out;
}

.icon-state .icon-state__secondary {
  position: absolute;
  top: 50%;
  left: 0;
  opacity: 0;
  transform: translateY(-50%) scale(0.3);
}

.icon-state[aria-expanded=true] .icon-state__primary {
  opacity: 0;
  transform: scale(0.3);
}

.icon-state[aria-expanded=true] .icon-state__secondary {
  opacity: 1;
  transform: translateY(-50%) scale(1);
}

/**
 * ----------------------------------------------------------------------------
 * TOOLTIP
 * ----------------------------------------------------------------------------
 */

@media (-moz-touch-enabled: 0), (hover: hover) {
  [data-tooltip] {
    position: relative;
  }

  [data-tooltip]::before {
    position: absolute;
    content: attr(data-tooltip);
    bottom: calc(100% + 3px);
    left: 50%;
    padding: 2px 11px;
    white-space: nowrap;
    background: var(--accent-color);
    color: var(--secondary-background);
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
    pointer-events: none;
    visibility: hidden;
    opacity: 0;
    border-radius: 3px;
    box-shadow: 0 1px rgba(0, 0, 0, 0.065);
    transition: visibility 0.2s ease-in-out, opacity 0.2s ease-in-out;
    z-index: 1;
    transform: translateX(-50%);
  }

  [data-tooltip]::after {
    position: absolute;
    content: "";
    left: calc(50% - 7px);
    bottom: calc(100% - 2px);
    width: 0;
    height: 0;
    border-width: 6px;
    border-style: solid;
    border-color: transparent transparent var(--accent-color) var(--accent-color);
    visibility: hidden;
    z-index: 1;
    opacity: 0;
    transition: visibility 0.2s ease-in-out, opacity 0.2s ease-in-out;
    transform: rotate(-45deg);
    box-shadow: -1px 1px 1px 0 rgba(0, 0, 0, 0.1);
  }

  [data-tooltip]:hover::before, [data-tooltip]:hover::after {
    opacity: 1;
    visibility: visible;
  }

  [data-tooltip-position=bottom-left]::before {
    top: calc(100% + 4px);
    bottom: auto;
    left: auto;
    right: -6px;
    transform: none;
  }

  [data-tooltip-position=bottom-left]::after {
    top: calc(100% - 1px);
    transform: rotate(135deg);
    left: calc(50% - 6px);
  }
}

/**
 * --------------------------------------------------------------------
 * QUANTITY SELECTOR
 * --------------------------------------------------------------------
 */

.quantity-selector {
  display: inline-flex;
  align-items: center;
  height: 38px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 15px));
  border: none;
  border-radius: 30px;
  background: whitesmoke;
  box-shadow: 0 2px 5px -3px #0000005e;
  vertical-align: middle;
}

.quantity-selector svg:hover {
  opacity: 1;
}

.quantity-selector .icon--minus {
  width: 10px;
  height: 2px;
}

.quantity-selector .icon--plus {
  width: 10px;
  height: 10px;
}

.quantity-selector__button {
  display: flex;
  align-items: center;
  padding: 0 12px;
  color: rgba(var(--text-color-rgb), 0.6);
  height: 100%;
  transition: color 0.2s ease-in-out;
  touch-action: manipulation;
}

.quantity-selector__button:not([disabled]):hover {
  color: var(--heading-color);
}

.quantity-selector__value {
  -webkit-appearance: none;
  -moz-appearance: none;
       appearance: none;
  padding: 0 5px;
  min-width: 32px;
  text-align: center;
  border: none;
  background: transparent;
}

.quantity-selector__value:focus {
  outline: none;
}

/**
 * --------------------------------------------------------------------
 * SHIPPING ESTIMATOR
 * --------------------------------------------------------------------
 */

.shipping-estimator__results {
  margin: 24px 0 2px 0;
  font-size: 1rem;
}

.shipping-estimator__results p {
  margin-bottom: 6px;
}

.shipping-estimator__results ul {
  color: var(--heading-color);
  font-weight: var(--text-font-bolder-weight);
}

/**
 * --------------------------------------------------------------------
 * COOKIE BAR
 * --------------------------------------------------------------------
 */

.cookie-bar {
  position: fixed;
  bottom: 80px;
  left: 0;
  visibility: hidden;
  opacity: 0;
  transform: translateY(100%);
  width: 100%;
  z-index: 3;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 11px));
  transition: transform 0.35s ease-in-out, opacity 0.35s ease-in-out, visibility 0.35s ease-in-out;
}

.cookie-bar[aria-hidden=false] {
  visibility: visible;
  transform: translateY(0);
  opacity: 1;
}

.cookie-bar__inner {
  max-width: 960px;
  margin: 0 auto;
  padding: 15px;
  z-index: 4;
  border-radius: 10px;
  background: var(--secondary-background);
  box-shadow: 0 1px 4px 1px rgba(0, 0, 0, 0.1);
}

.cookie-bar__text {
  line-height: 1.45;
  color: #838383;
}

.cookie-bar__button {
  margin-top: 12px;
  padding: 0 16px;
  line-height: 30px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 12px));
  background: var(--primary-button-background);
  
}

@media screen and (min-width: 641px) {
  .cookie-bar {
    bottom: 25px;
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
  }

  .cookie-bar__inner {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 30px 20px 25px;
  }

  .cookie-bar__text {
    line-height: 1.25;
  }

  .cookie-bar__button {
    flex: none;
    margin-left: 25px;
    margin-top: 0;
    padding: 0 18px;
    line-height: 36px;
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
    
  }
}

/**
 * --------------------------------------------------------------------
 * CONTACT FORM
 * --------------------------------------------------------------------
 */

.contact {
  margin-bottom: 40px;
}

.contact__store-info {
  margin-top: 50px;
}

.contact__store-heading,
.contact__store-image {
  margin-bottom: 30px;
}

@media screen and (min-width: 641px) {
  .contact {
    margin-bottom: 90px;
  }
}

@media screen and (min-width: 1000px) {
  .contact__store-info {
    margin-top: 0;
    margin-left: 25px;
  }
}

/**
 * --------------------------------------------------------------------
 * PASSWORD PAGE
 * --------------------------------------------------------------------
 */

.password {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  height: 100vh;
  padding: 20px 0;
}

@supports (--css: variables) {
  .password {
    height: calc(100vh - 0px);
    height: calc(100vh - var(--header-height, 0px));
  }
}

.password__content {
  display: flex;
  align-items: center;
  flex: 1 0 auto;
  text-align: center;
}

.password__footer {
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 13px));
  text-align: center;
}

.password__footer-social {
  display: flex;
  justify-content: center;
  margin-top: 15px;
}

.password__social-text {
  margin-right: 20px;
}

.password__powered-by a {
  display: inline-block;
  margin-left: 4px;
  vertical-align: bottom;
}

.password__powered-by svg {
  width: 98px;
  height: 28px;
}

.password__admin-link {
  display: block;
  margin-left: 18px;
}

@media screen and (min-width: 1000px) {
  /* On password there is no search bar so we increase the header */
  .template-password .header {
    padding-top: 30px;
    padding-bottom: 30px;
  }

  .password {
    padding: 40px 0;
  }

  .password__footer {
    text-align: left;
  }

  .password__footer--with-social {
    display: flex;
    width: 100%;
    justify-content: space-between;
  }

  .password__admin-link {
    display: inline-block;
  }

  .password__footer-social {
    margin-top: 0;
  }
}

/**
 * --------------------------------------------------------------------
 * FAQ
 * --------------------------------------------------------------------
 */

.faq {
  margin: 40px 0 70px 0;
}

.faq__title {
  margin-bottom: 20px;
  text-align: center;
}

.faq__item {
  padding: 20px 20px;
  background: var(--secondary-background);
  border-top: 1px solid var(--border-color);
  border-bottom: 1px solid var(--border-color);
}
.faq__item + .faq__item {
  border-top: none;
}

.faq__question {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  text-align: left;
}
.faq__question .plus-button {
  margin-left: 40px;
}

.faq__answer-wrapper {
  overflow: hidden;
  height: 0;
  transition: height 0.2s ease-in-out;
}

.faq__answer {
  margin: 10px 30px 0 0;
}

.faq__group {
  margin-bottom: 30px;
}

.faq__group-title {
  text-align: center;
}

.faq__contact-info {
  margin-top: 50px;
}

@media screen and (min-width: 641px) {
  .faq {
    margin: 70px 0 115px 0;
  }

  .faq__title {
    margin-bottom: 25px;
    margin-left: 0;
  }

  .faq__item {
    padding: 20px 30px;
    border: 1px solid var(--border-color);
    border-radius: 3px 3px 0 0;
  }
  .faq__item + .faq__item {
    border-radius: 0;
  }
  .faq__item:last-child {
    border-radius: 0 0 3px 3px;
  }
}

@media screen and (min-width: 1000px) {
  .faq__group {
    margin-bottom: 0;
  }

  .faq__group + .faq__group {
    margin-top: 50px;
  }
}

/**
 * --------------------------------------------------------------------
 * POPUP NEWSLETTER
 * --------------------------------------------------------------------
 */

.modal--newsletter {
  bottom: 0;
  top: auto;
  height: auto;
}

.modal--newsletter .modal__dialog {
  position: relative;
  height: auto;
  padding: 48px 20px 20px 20px;
}

.popup-newsletter__title {
  text-align: center;
  margin-bottom: 10px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 20px));
}

.popup-newsletter__close {
  position: absolute;
  right: 20px;
  top: 16px;
  color: var(--heading-color);
}

.popup-newsletter__close svg {
  width: 15px;
  height: 15px;
}

.popup-newsletter__content {
  text-align: center;
}

.popup-newsletter__form {
  margin-top: 20px;
}

@media screen and (min-width: 641px) {
  .modal--newsletter {
    height: 100%;
  }

  .modal--newsletter .modal__dialog {
    max-width: 540px;
    padding: 64px 80px 80px 80px;
  }

  .popup-newsletter__close {
    position: absolute;
    right: 30px;
    top: 24px;
  }
  .popup-newsletter__close svg {
    width: 20px;
    height: 20px;
  }

  .popup-newsletter__title {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 28px));
  }

  .popup-newsletter__form {
    margin-top: 30px;
  }
}

/**
 * --------------------------------------------------------------------
 * EXIT POPUP NEWSLETTER
 * --------------------------------------------------------------------
 */

.modal--exit-popup {
  bottom: 0;
  top: auto;
  height: auto;
}

.modal--exit-popup .modal__dialog {
  position: relative;
  height: auto;
  padding: 48px 20px 20px 20px;
}

.exit-popup__title {
  text-align: center;
  margin-bottom: 8px;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 28px));
  line-height: 1.2;
}

.exit-popup__subheading {
  text-align: center;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 18px));
}

.exit-popup__close {
  position: absolute;
  right: 20px;
  top: 16px;
  color: var(--heading-color);
}

.exit-popup__close svg {
  width: 15px;
  height: 15px;
}

.exit-popup__form {
  margin-top: 20px;
}

.exit-popup__pay-more {
  display: block;
  margin-top: 20px;
  text-align: center;
  margin-left: auto;
  margin-right: auto;
}

@media screen and (min-width: 641px) {
  .modal--exit-popup {
    height: 100%;
  }

  .modal--exit-popup .modal__dialog {
    max-width: 540px;
    padding: 95px 80px 30px 80px;
  }

  .exit-popup__close {
    position: absolute;
    right: 30px;
    top: 24px;
  }

  .exit-popup__close svg {
    width: 20px;
    height: 20px;
  }

  .exit-popup__title {
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 48px));
  }

  .exit-popup__form {
    margin-top: 30px;
  }

  .exit-popup__pay-more {
    margin-top: 75px;
  }
}

/**
 * --------------------------------------------------------------------
 * DRAWER
 * --------------------------------------------------------------------
 */

.drawer {
  position: fixed;
  top: 0;
  right: 0;
  height: 100vh;
  width: 100vw;
  z-index: 5;
  visibility: hidden;
  transition: visibility 0.35s linear;
}

.drawer::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
  transition: opacity 0.35s ease-in-out;
  background: #000000;
}

.drawer__inner {
  position: absolute;
  right: 0;
  top: 0;
  width: 100%;
  height: 100%;
  max-width: 345px;
  margin-left: auto;
  background: white;
  transform: translateX(100%);
  transition: transform 0.35s cubic-bezier(0.645, 0.045, 0.355, 1);
}

.drawer[aria-hidden=false] {
  visibility: visible;
}

.drawer[aria-hidden=false]::before {
  opacity: 0.4;
}

.drawer[aria-hidden=false] .drawer__inner {
  transform: translateX(0);
}

/**
 * --------------------------------------------------------------------
 * SEARCH RESULTS
 * --------------------------------------------------------------------
 */

.link-search-results:not(:only-child) {
  margin-top: 40px;
}

.link-search-results__list {
  list-style: none;
}

.link-search-results__link {
  display: block;
  padding: 8px 20px;
  transition: color 0.15s ease-in-out, background 0.15s ease-in-out;
}

.link-search-results__link:hover, .link-search-results__link:focus {
  background: var(--accent-background);
  color: var(--accent-color);
  outline: none;
}

@media screen and (min-width: 641px) {
  .link-search-results:not(:only-child) {
    margin-top: 60px;
  }
}
/**
 * --------------------------------------------------------------------
 * EXPANDABLE CONTENT
 * --------------------------------------------------------------------
 */

.expandable-content[aria-expanded] {
  position: relative;
  max-height: 320px;
  overflow: hidden;
  transition: 0.2s ease-in-out;
  border-radius: 14px;
}

.expandable-content__toggle {
  position: absolute;
  display: flex;
  align-items: center;
  left: 0;
  border-radius: 25px;
  bottom: 0;
  width: 100%;
  padding: 16px 20px;
  visibility: hidden;
  opacity: 0;
  color: var(--accent-color);
  text-align: left;
  font-weight: var(--text-font-bolder-weight);
  background: var(--secondary-background);
  z-index: 1;
  transition: opacity 0.1s ease-in-out, visibility 0.1s ease-in-out;
}

.expandable-content__toggle::before {
  position: absolute;
  content: "";
  bottom: 100%;
  left: 0;
  width: 100%;
  height: 50px;
  pointer-events: none;
  background: linear-gradient(rgba(var(--secondary-background-rgb), 0), rgba(var(--secondary-background-rgb), 0.4) 15%, var(--secondary-background));
}

.expandable-content__toggle-icon {
  position: relative;
  margin-right: 15px;
  width: 10px;
  height: 10px;
  transition: transform 0.2s ease-in-out;
}

.expandable-content__toggle-icon::before, .expandable-content__toggle-icon::after {
  content: "";
  position: absolute;
  background: currentColor;
  transition: transform 0.2s ease-in-out;
  transform: translate(-50%, -50%);
  top: 50%;
  left: 50%;
}

.expandable-content__toggle-icon::before {
  width: 2px;
  height: 10px;
}

.expandable-content__toggle-icon::after {
  width: 10px;
  height: 2px;
}

.expandable-content--expandable[aria-expanded=true] .expandable-content__toggle-icon {
  transform: rotateZ(90deg);
}

.expandable-content--expandable[aria-expanded=true] .expandable-content__toggle-icon::after {
  display: none;
}

.expandable-content--expandable .expandable-content__toggle {
  visibility: visible;
  opacity: 1;
}

.expandable-content--expandable[aria-expanded=true] .expandable-content__toggle::before {
  height: 0;
}

@media (-moz-touch-enabled: 0),(hover: hover) {
  .expandable-content[aria-expanded=false] .expandable-content__toggle:hover .expandable-content__toggle-icon {
    transform: rotateZ(45deg);
  }
}

@media screen and (min-width: 641px) {
  .expandable-content__toggle {
    padding-left: 30px;
    padding-right: 30px;
  }
}

/**
 * --------------------------------------------------------------------
 * MENU (used exclusively in "custom content" section for now)
 * --------------------------------------------------------------------
 */

.menu-item__title {
  margin-bottom: 0.75em;
}

.menu-item__linklist {
  list-style: none;
}

.menu-item__link-item {
  padding: 5px 0;
}
/**
 * --------------------------------------------------------------------
 * VALUE PICKER
 *
 * This component allows to provide a replacement to dropdown select.
 * On mobile it used by opening a drawer box, while on desktop it looks
 * like a popover
 * --------------------------------------------------------------------
 */
.value-picker-button svg {
  width: 9px;
  height: 7px;
  margin-left: 10px;
  transition: transform 0.2s ease-in-out;
}

.value-picker-button svg path {
  stroke-width: 2.5px;
}

.value-picker-button--pill {
  position: relative;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  padding: 14px 20px;
  text-align: left;
  border-bottom: 1px solid var(--border-color);
  background: var(--secondary-background);
}

.value-picker-button--pill svg {
  width: 12px;
  height: 8px;
  transition: transform 0.2s ease-in-out;
}

.value-picker-button--pill path {
  stroke-width: 2px;
}

.value-picker-button[aria-expanded=true] svg {
  transform: rotateZ(180deg);
}

.value-picker {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100vw;
  height: 100vh;
  z-index: 5;
  font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 16px));
  visibility: hidden;
  transition: visibility 0.35s ease-in-out;
}

.value-picker::before {
  content: "";
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  opacity: 0;
  transition: opacity 0.35s ease-in-out;
  background: #000000;
}

.value-picker[aria-hidden=false] {
  visibility: visible;
}

.value-picker[aria-hidden=false]::before {
  opacity: 0.4;
}

.value-picker[aria-hidden=false] .value-picker__inner {
  transform: translateY(0);
}

.value-picker .icon--nav-triangle-borderless {
  display: none;
}

.value-picker__inner {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  background: var(--secondary-background);
  transform: translateY(100%);
  transition: visibility 0.2s ease-in-out, transform 0.2s ease-in-out;
}

.value-picker__header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 17px 20px 16px 20px;
  border-bottom: 1px solid var(--border-color);
}

.value-picker__header .icon--close {
  width: 17px;
  height: 17px;
  color: var(--heading-color);
}

.value-picker__title {
  margin: 0;
}

.value-picker__close svg {
  display: block;
}

.value-picker__choice-list {
  padding: 15px 0;
  max-height: 430px;
  overflow: auto;
  -webkit-overflow-scrolling: touch;
  -ms-scroll-chaining: none;
      overscroll-behavior: none;
  list-style: none;
}

.value-picker__choice-item {
  display: block;
  position: relative;
  width: 100%;
  text-align: left;
  padding: 8px 50px 7px 20px; /* Designer does not like symmetry, sorry :D */
}

.value-picker__choice-item svg {
  position: absolute;
  width: 13px;
  height: 11px;
  right: 20px;
  top: 17px;
  transform: scale(0);
  transition: transform 0.2s ease-in-out;
}

.value-picker__choice-item.is-selected {
  color: var(--accent-color);
  font-weight: var(--text-font-bolder-weight);
}

.value-picker__choice-item.is-selected svg {
  transform: scale(1);
}

/* On tablet and higher, the selector will look like a popover */
@media screen and (min-width: 641px) {
  /* This is the wrapper class on which elements are positioned relatively on desktop */
  .value-picker-wrapper {
    position: relative;
  }

  .value-picker {
    position: absolute;
    width: auto;
    height: auto;
    top: calc(100% + 10px);
    left: auto;
    right: -25px;
    bottom: auto;
    min-width: 160px;
    box-shadow: 0 1px 5px 2px rgba(0, 0, 0, 0.1);
    visibility: hidden;
    opacity: 0;
    transform: scale(0.9);
    background: #fff;
    color: #677279;
    z-index: 4;
    cursor: auto;
    border-radius: 3px;
    transition: opacity 0.25s ease-in-out, transform 0.25s ease-in-out, visibility 0.25s ease-in-out;
    will-change: transform;
  }

  .value-picker::before {
    display: none;
  }

  .value-picker[data-picker-position=top] {
    top: auto;
    bottom: calc(100% + 10px);
  }

  .value-picker[aria-hidden=false] {
    visibility: visible;
    opacity: 1;
    transform: scale(1.001);
    transition: opacity 0.4s cubic-bezier(0, 1, 0.4, 1), transform 0.4s cubic-bezier(0.18, 1.25, 0.4, 1), visibility 0.4s linear;
  }

  .value-picker .icon--nav-triangle-borderless {
    display: block;
    position: absolute;
    bottom: 100%;
    right: 20px;
    width: 18px;
    height: 8px;
    z-index: 2;
    -webkit-filter: drop-shadow(0 -2px 2px rgba(0, 0, 0, 0.12));
            filter: drop-shadow(0 -2px 2px rgba(0, 0, 0, 0.12));
  }

  .value-picker[data-picker-position=top] .icon--nav-triangle-borderless {
    bottom: auto;
    top: 100%;
    transform: rotateZ(180deg);
  }

  .value-picker__inner {
    position: relative;
    width: auto;
    transform: none !important;
    transition: none;
    border-radius: 3px;
  }

  .value-picker__header {
    display: none; /* Because of popover the context is clear and does not need header */
  }

  .value-picker__choice-list {
    padding: 15px 0;
    max-height: none;
    white-space: nowrap;
    font-size: calc(var(--base-text-font-size) - (var(--default-text-font-size) - 15px));
  }

  .value-picker__choice-item {
    display: block;
    padding: 2px 25px;
    cursor: pointer;
    transition: color 0.15s ease-in-out, background 0.15s ease-in-out;
  }

  .value-picker__choice-item.is-selected,
  .value-picker__choice-item:hover {
    background: var(--accent-background);
    color: var(--accent-color);
    font-weight: normal;
  }

  .value-picker__choice-item.is-selected svg,
  .value-picker__choice-item:hover svg {
    display: none;
  }

  /* Small variation */
  .value-picker--small {
    min-width: 105px;
    right: -2px;
  }

  .value-picker--small .value-picker__choice-list {
    padding: 10px 0;
    font-size: 0.85rem;
  }

  .value-picker--small .value-picker__choice-item {
    padding: 2px 18px;
  }

  .value-picker--small .icon--nav-triangle-borderless {
    right: 11px;
  }

  /* Auto variation */
  .value-picker--auto {
    min-width: 0;
  }
}

.boxPrevisualiza > p{
	display: none;
}

._1mVwsTnhAN7sNKiIn4mrTP{
       display: none!important
          }
     .sc-7dvmpp-1{
       display: none!important
     
  }

/**
 * Botão quantidade - Plus
 */
input.qtyplus {
    width: 40%;
    height: 40px;
    line-height: 0px;
    vertical-align: middle;
    color: #8188a1;
    font-weight: bold;
    font-size: 18px;
    border-radius: 0 30px 30px 0;
    background: #e8e9ef;
    border: none;
    text-align: center;
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

input.qtyminus {
    width: 40%;
    height: 40px;
    line-height: 0px;
    vertical-align: middle;
    color: #8188a1;
    font-weight: bold;
    font-size: 18px;
    border-radius: 30px 0 0 30px;
    background: #e8e9ef;
    border: none;
    text-align: center;
    box-sizing: border-box;
    padding: 0;
    margin: 0;
 }

.qty-align {
   display: flex;
   flex-direction: row;
   align-items: center;
}

@media (min-width: 641px) {
.qty-margin-top {
  margin-top: -2px;
}
}

@media (max-width: 640px) {
.qty-margin-top {
  margin-top: 10px;
}
}
  
.qty {
    font-weight: 600;
    width: 100%;
    height: 40px;
    text-align: center;
    border: none;
    background: #e8e9ef;
    margin: -4px;
    cursor: default;
    -webkit-appearance: none;
    display: inline-block;
    vertical-align: middle;
}

.mobileannouncement {
  text-align:center;
  margin-bottom:0vw;
}

.mobileannouncement {
  padding:0vw 0vw 0vw;
}


.mobileannouncement>img {
    max-height: 100%;
    margin: auto;
}

.img-responsive {
    display: block;
    max-width: 100%;
    height: auto;
}

.img-responsive2 {
      max-width: 100%;
  	  height: auto;
      border-style: none;
      vertical-align: top;
}

@media screen and (min-width: 639px) {
  .mobileannouncement {
      display: none;
  }
}

.desktopannouncement {
  	text-align: -webkit-center;
}

@media screen and (max-width: 639px) {
  .desktopannouncement {
      display: none;
  }
}

.hidden {
	display: none;
}

.apartirde {
    font-size: 10pt;
    font-weight: bold;
    color: var(--product-cor-do-preco);
    flex: auto;
    display: block;
}

.announcesvg {
    width: 22px;
    vertical-align: middle;
    display: inline-block;
    margin-right: 5px;
}

@media(min-width: 769px){
  .botaoflutuante{
  	display: none;
  }
}

#clicar{
	width: 100%;
}

@media(max-width: 768px){
 
  
  .botaoflutuante {
      position: fixed;
      bottom: 0;
      background: var(--primary-button-background);
      z-index: 99;
      width: 100%;
      padding: 0px;
	}
  
  .botaoflutuante button{
	width: 100%;
	}
}

.div-black-discount {
    background-color: #000;
    text-align: center;
    padding: 10px;
  font-size: 18px;
}

.span-black-discount {
    font-family: Montserrat,sans-serif;
    font-weight: 700;
    color: #fff;
}

.neon-black-friday {
    font-family: Montserrat,sans-serif;
    font-weight: 900;
    color: #fff;
    text-shadow: 0 0 1px #831d1c, 0 0 1px #831d1c, 0 0 1px #831d1c, 0 0 3px #FF2D3C, 0 0 15px #FF2D3C, 0 0 7px #FF2D3C, 0 0 20px #FF2D3C, 0 0 25px #FF2D3C;
}

.payment-list__item10 {
    width: 33px;
    height: 32px;
    margin: 4px;
}

.color-line2 {
    background: linear-gradient(to right,#191919 0,#FF2D3C 30%,#da0000 50%,#FF2D3C 75%,#191919 100%);
    width: 100%;
    height: 45px;
    padding: 5px;
    text-align: center;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
}

.blackweek-bar-img {
    height: 100%;
    margin-right: 10px;
}

.blackweek-span {
    font-family: Montserrat,sans-serif;
    font-weight: 600;
    font-size: 10pt;
    color: #fff;
}

.blackweek-bold {
    font-weight: 800;
}

@media (min-width: 576px){
.blackweek-bar-img {
    margin-right: 20px;
}
}

@media (min-width: 576px){
.color-line2 {
    height: 70px;
}
}

@media (min-width: 800px){
.blackweek-span {
    font-size: 25pt;
}
}

@media (min-width: 576px){
.blackweek-span {
    font-size: 20pt;
}
}

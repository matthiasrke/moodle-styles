# Folder 
Tested in Moodle 3.9, 3.10 and 3.11

### Before
![folder-browser-before](screenshots/folder-browser-before.png) 

### After
![folder-browser-after](screenshots/folder-browser-after.png) 

``` SCSS
// Folder.
.fp-filename-icon .icon {
    font-size: 24px;
    height: 24px;
    width: 24px;
}

.fp-icon {
    margin-top: -.25rem;
}

.fp-filename-icon {
    margin-top: 0;
}

.file-picker .ygtvtn,
.filemanager .ygtvtn,
.file-picker .ygtvtm,
.filemanager .ygtvtm,
.file-picker .ygtvtmh,
.filemanager .ygtvtmh,
.file-picker .ygtvtp,
.filemanager .ygtvtp,
.file-picker .ygtvtph,
.filemanager .ygtvtph,
.file-picker .ygtvln,
.filemanager .ygtvln,
.file-picker .ygtvlm,
.filemanager .ygtvlm,
.file-picker .ygtvlmh,
.filemanager .ygtvlmh,
.file-picker .ygtvlp,
.filemanager .ygtvlp,
.file-picker .ygtvlph,
.filemanager .ygtvlph,
.file-picker .ygtvdepthcell,
.filemanager .ygtvdepthcell {
    background: none;
    min-width: 2.5rem; // 2 or 2.5rem
    padding-left: 0;
    text-align: center;
}

.file-picker .ygtvtm::before,
.filemanager .ygtvtm::before,
.file-picker .ygtvtmh::before,
.filemanager .ygtvtmh::before,
.file-picker .ygtvlm::before,
.filemanager .ygtvlm::before,
.file-picker .ygtvlmh::before,
.filemanager .ygtvlmh::before {
    font-family: "FontAwesome";
    content: "\f107"; // f0d7 or f107
    font-size: 150%; // 110 or 150%
    color: $navbar-light-color;
    display: inline-block;
    transition: all .2s ease;
}

.file-picker .ygtvtp::before,
.filemanager .ygtvtp::before,
.file-picker .ygtvtph::before,
.filemanager .ygtvtph::before,
.file-picker .ygtvlp::before,
.filemanager .ygtvlp::before,
.file-picker .ygtvlph::before,
.filemanager .ygtvlph::before {
    font-family: "FontAwesome";
    content: "\f107"; // f0d7 or f107
    font-size: 150%; // 110 or 150%
    color: $navbar-light-color;
    display: inline-block;
    transition: all .2s ease;
    transform: rotate(-90deg);
}

.file-picker .ygtvtn,
.filemanager .ygtvtn,
.file-picker .ygtvln,
.filemanager .ygtvln {
    cursor: auto;
}

table.ygtvtable {
    width: 100%;
}

table.ygtvtable td {
    padding-top: .75rem;
    padding-bottom: .75rem;
    border-bottom: $card-border-width solid $card-border-color;
}

.file-picker td.ygtvfocus,
.filemanager td.ygtvfocus {
    background-color: $card-cap-bg;
    border-bottom: 0;
}

td.ygtvcell {
    //    padding-left: .5rem;
}

.file-picker .ygtvblankdepthcell,
.filemanager .ygtvblankdepthcell,
a.ygtvspacer,
.ygtvspacer {
    display: none;
}
```

# Atto fix
Tested in Moodle 3.9, 3.10 and 3.11

```
// Atto editor fix for Chrome.
.editor_atto_content p,
.editor_atto_content span,
.editor_atto_content strong,
.editor_atto_content b,
.editor_atto_content em,
.editor_atto_content i,
.editor_atto_content u,
.editor_atto_content a {
    font-size: $font-size-base;
}

// Atto editor underlining to show errors.
.editor_atto_content [style*="font-size"] {
    text-decoration: underline wavy $gray-600;
}

// Atto editor fix for button.
.atto_fontcolor_button .dropdown-menu {
    padding: .25rem;
}
```
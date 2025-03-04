# ACF Programmatic Fields

This is a collection of Visual Studio Code snippets for the
[Advanced Custom Fields](http://www.advancedcustomfields.com/) Wordpress plugin.
The snippets allow you to easily create fields and field groups in PHP without making use of the GUI.

## Installation
To install add the entire folder into your VS Code extensions folder: ```~/.vscode/extensions```.

## Release Notes

Users appreciate release notes as you update your extension.

### 0.3.0 (WIP)
- Added `acf_add_flex_content`. Now you can easily create flexible content! I don't know why this snippet didn't exist yet.

### 0.2.5
- Removed some persistent whitelines
- Added the `acf_add_repeater` snippet. Now you can easily create repeaters!

### 0.2.0
- Removed the comments
- Fixed some small bugs in some fields (missing commas, incorrect autotabbing stuff)

### 0.1.6
- the `acf_add_local_field()` function wrapped around each field is now a separate snippet. Allowing you to easily register any field inside a field group without needing to remove that outer function.
- Removed an empty whiteline below every 'name' property for consistency
- Patched in the missing `,` after each `'parent' => ''` property.
- Switched to indentation using tabstops rather than hardcoded spaces

### 0.1.5
- Fixed some variable placeholders that did not start with a $ like {4:PLACEHOLDER}
- Updated ${1:KEY} to start with the mandatory 'field_' for acf fields -> ${1:field_KEY}
- Updated ${1:KEY} to start with the mandatory 'group_' for acf field groups -> ${1:group_KEY}

### 0.1.0
- Initial release

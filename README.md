# 5eT Homebrew Snippets

A handy extension to make Homebrewers' lifes easier.  

![Example video](https://raw.githubusercontent.com/Git-GoR/5eT-homebrew-snippets/main/images/example.webp)

## Installation

Install the extension directly in VSCode through its Marketplace.

Alternatively, copy the extension into your VS Code extensions folder.  
 The default location is `%USERPROFILE%\.vscode\extensions`

---
## List of Snippets

### Meta block

The meta block is essential for every homebrew content you make.

| Prefix        | Purpose        |
|---------------|----------------|
| `meta` | Full basic `_meta` block. |
| `unixDate` | The number of seconds since the Unix epoch. Useful for updating `dateModified`. |

---

### Text entries

Different snippets for text entries, all found in the Renderer Demo.

| Prefix        | Purpose        |
|---------------|----------------|
| `section` | Section entry, creates a "basement" level `(-1)` |
| `entries` | General entry block |
| `quote` | Quote block|
| `inset` | Inset block |
| `insetReadaloud` | Inset block, but on blue color |
| `list` | List with style options |
| `item` | Item used within lists |
| `tableEntry` | Table block for text entries. Contains many optional fields |
| `abilityDC` | Centered text with the format "Name = 8 + prof + mod" |
| `abilityAttackMod` | Centered text with the format "Name attack modifier = prof + mod" |
| `abilityGeneric` | Centered text with the format "Name  = text mod" |
| `image` | External image link |

---

### Class and Subclass

Be aware that these snippets are long and wordy with many optional parts, make sure you delete those that do not apply to the homebrew you are converting to prevent errors.

| Prefix        | Purpose        |
|---------------|----------------|
| `class` | Full class skeleton |
| `classFeature` | Skeleton of class feature |
| `classFeatureRef` | Reference a class feature inside a class |
| `subclass` | Full subclass skeleton |
| `subclassFeature` | Skeleton of subclass feature |
| `subclassFeatureRef` | Reference a subclass feature inside a subclass feature list, do not mistake with `refSubclassFeature` |
| `refSubclassFeature` | Reference a subclass feature in the entries of a different subclass feature, used to create nested subclass features |

---

### General Categories

Snippets for 

| Prefix        | Purpose        |
|---------------|----------------|
| `action` | Full action skeleton |
| `background` | Full background skeleton |
| `boon` | Full boon skeleton |
| `condition` | Full condition skeleton |
| `cult` | Full cult skeleton |
| `deity` | Full deity skeleton. Most data is optional. |
| `disease` | Full disease skeleton |
| `feat` | Full feat skeleton. Check the prerequisites structure. |
| `hazard` | Full hazard skeleton |
| `language` | Full language skeleton. Most data is optional. |
| `optionalFeature` | Full optional feature skeleton. Check prerequisites structure. |
| `race` | Full race skeleton |
| `variantRule` | Full variant rule skeleton |
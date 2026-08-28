# wiki-assets

Small public host for images that need a plain HTTPS URL.

It exists because Notion page icons can only be an emoji, a workspace custom
emoji, or an external image URL. The API rejects an uploaded file with
`Invalid page icon URL`, so icons used on the wiki have to live somewhere
Notion's servers can fetch them.

## Logos

Application icons, extracted at 256px from the installed applications and used
as page icons on the internal wiki.

| File | Application | Icon URL |
|---|---|---|
| `logos/mari.png` | Foundry Mari 7.5v2 | https://raw.githubusercontent.com/rgscicchitano/wiki-assets/main/logos/mari.png |
| `logos/substance-3d-painter.png` | Adobe Substance 3D Painter 12.1.2 | https://raw.githubusercontent.com/rgscicchitano/wiki-assets/main/logos/substance-3d-painter.png |
| `logos/substance-3d-designer.png` | Adobe Substance 3D Designer 16.0.4 | https://raw.githubusercontent.com/rgscicchitano/wiki-assets/main/logos/substance-3d-designer.png |
| `logos/maya.png` | Autodesk Maya 2027 | https://raw.githubusercontent.com/rgscicchitano/wiki-assets/main/logos/maya.png |
| `logos/nuke.png` | Foundry Nuke 17.1v1 | https://raw.githubusercontent.com/rgscicchitano/wiki-assets/main/logos/nuke.png |
| `logos/zbrush.png` | Maxon ZBrush 2026 | https://raw.githubusercontent.com/rgscicchitano/wiki-assets/main/logos/zbrush.png |

Maya's Commons file is a 635x157 wordmark, which letterboxes badly as an icon, so
the application icon is used instead.

## Sourced from Wikimedia instead

These already have a square icon on Commons, so they are linked directly and are
not duplicated here.

| Application | Icon URL |
|---|---|
| SideFX Houdini | https://upload.wikimedia.org/wikipedia/commons/1/15/Houdini3D_icon.png |
| Adobe Photoshop | https://upload.wikimedia.org/wikipedia/commons/3/30/Adobe_Photoshop_CC_2026_icon.svg |
| Adobe Illustrator | https://upload.wikimedia.org/wikipedia/commons/f/fb/Adobe_Illustrator_CC_icon.svg |

Houdini is not here. Its icon comes from Wikimedia Commons, which already has
one: `upload.wikimedia.org/wikipedia/commons/1/15/Houdini3D_icon.png`. Check
Wikimedia first when adding a new application, and only add a file here when
nothing suitable exists.

## Adding an application

Drop a square PNG in `logos/`, named after the application in lower case with
hyphens, then push. The raw URL follows the pattern above.

## Trademarks

Each logo is the trademark of its owner: Foundry Visionmongers for Mari, Adobe
for the Substance 3D applications. They are reproduced here only to label
documentation pages about those applications.

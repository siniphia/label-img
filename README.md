# LabelImg

Forked from the
[LabelImg](https://github.com/tzutalin/labelImg/blob/master/labelImg.py)
repo by [tzutalin](https://github.com/tzutalin).
Updated to work with DICOMs.

## Modification
190905 : deleted series selection dialog to work with single 2D dcm files (eg. conventional radiographs)


## Usage

### Create pre-defined classes

You can edit the file in `data/predefined_classes.txt` to define your own
classes.


### Keyboard Shortcuts

| Keys           | Description                              |
|----------------|------------------------------------------|
| `w`            | Create a bounding box                    |
| `d`            | Next image                               |
| `a`            | Previous image                           |
| `cmd + scroll` | Zoom in/out                              |
| `cmd + s`      | Save                                     |
| `cmd + d`      | Copy the current label and bounding box  |
| `del`          | Delete the selected bounding box         |
| `space`        | Mark the current image as verified       |
| `cmd + '+'`    | Zoom in                                  |
| `cmd + '-'`    | Zoom out                                 |
| `↑ → ↓ ←`     | Move selected bounding box               |


## License

Free software: [MIT license](https://github.com/tzutalin/labelImg/blob/master/LICENSE)

Citation: Tzutalin. LabelImg. Git code (2015). https://github.com/tzutalin/labelImg

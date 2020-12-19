# MQB-FPA
This repository is about driving profiles customization for MQB platform cars (also known as FPA fahrprofilauswahl). It's mainly focused on research, reverse engineering of the FPA datasets and implementing customizations.

![ ](https://github.com/jilleb/MQB-FPA/blob/main/images/header.png?raw=true)

## Requirements
- A MQB platform vehicle
- 3Q0907530 Gateway
- Hex-editing skills
- [010 editor](https://www.sweetscape.com/010editor/)
- A good pair of brains
- Common sense
- No fear of bricking your gateway or losing your warranty
- An inquisitive mindset
- No bad intentions.

## Usage
This repository consists of 3 parts:

### fpa_dataset.bt
This is the main template, which can parse raw binary data from a dataset in 010 editor.

### fpa_dataset_save.1sc
The 010 editor script to convert raw hex data to 0x00-shaped data.


## Wiki
The place where the entire dataset is described and explored. Check it out [here](../..//wiki).

## Contributing

Everyone can contribute to this project in some way. You can make your own dataset changes and test them, and report back. See the discussion for all topics.  If you have any suggestions or chagnes to the template or script, feel free to make a pull request.



<!-- LICENSE -->
## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.

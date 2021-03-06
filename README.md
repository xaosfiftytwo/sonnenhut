# Sonnenhut

A crude Python script for photographers. Displays basic information such as current weather conditions and golden hour for a specified location.

<img src="sonnenhut.png" alt="Sonnenhut">

The script provides the following information:

 - Golden hour start and duration
 - Brief weather summary
 - Current temperature, wind speed, and humidity
 - Precipitation warning

The script also shows notes from the accompanying *sonnenhut.txt* file (created automatically during the fist run).

## Installation

### openSUSE

1. Install Python 3 and Git: `sudo zypper in python3 git`
2. Install the *Astral* module: `sudo pip install astral`
3. Install the *pyowm* module: `sudo pip install pyown`
4. Clone the Git repository: `git clone https://github.com/dmpop/sonnenhut.git`

Alternatively, run the following command:

    sudo zypper in python3 git; sudo pip install astral; sudo pip install pyowm; git clone https://github.com/dmpop/sonnenhut.git;

## Usage

1. Switch to the *sonnenhut* directory
2. Run the `./sonnenhut.py fürth` command (replace *fürth* with the desired city)

For quick access, create an alias in the *~/.bashrc* file (replace *fürth* with the desired city):

    alias sonnenhut='/path/to/sonnenhut.py fürth'

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin new-feature`
5. Submit a pull request

## History

 - 2017-01-23 Added basic error handling
 - 2017-01-22 Added the notes feature
 - 2017-01-21 Initial release

## Credits

Thanks to Thomas Schraitle for help and guidance.

## License

[The GNU General Public License version 3](https://www.gnu.org/licenses/gpl-3.0.txt)

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=U7KDYY9UB9PMY)

# Wuxiaworld-2-eBook
This Python script will download chapters from novels availaible on wuxiaworld.com and saves them into the .epub format.

Visit [novel-ebook.com](https://novel-ebook.com) for a webapp with the same functionality but with over 2000 supported novels! Beware this site is still in beta and you may experience problems.

## Getting Started

To run this script you'll need to have Python 3.6.x installed which you can find [here](https://www.python.org/downloads/ "Python Download Link").

### Features

- Download and save you favorite Novels from wuxiaworld.com into a .epub file
- Automatically adds some metadata like author, title and cover

### Prerequisites

As mentioned before this script was written for Python version 3.6.x. It may work with other versions too but none are tested.
Additionally the Python image library (Pillow), lxml and Beautifulsoup4 are required.
To install all dependencies just use the console to navigate into the project folder and write

```
pip install -r requirements.txt
```

### Usage

Download the script and navigate to the folder using the console then write

```
python wuxiaworld2ebook.py
```

or just use the start.bat file. If you didn't add Python to the PATH variable during the installation or afterwards the write

```
path/where/you/installed/python.exe wuxiaworld2ebook.py
```

After that just select the novel you want to read, enter the chapter range you want to include to the eBook, enter the book number of the novel you want to read (if applicable) and hit the "Generate" Button. Keep it mind that it will take some time for the script to finish, so don't close the window or the console if the program doesn't respond.

## Keep in mind!

If you come across bug's or suggestion's for future updates don't hesitate to open up a "new Issue" in the issue tab or write me a e-mail at bloodvioletssword@gmail.com.

Novels that are not included and won't be included in the near future:

- Charm of Soul Pets
- Demon Hunter
- Heavenly Jewel Change
- I Reincarnated for Nothing
- Red Storm
- Terror Infinity
- Unrivaled Tang Sect

### For Mac Users

You'll likely experience SSL Certificate problems. Please check Issue #35 for a way to resolve this bug.

### Related Projects

Here are some related projects you can check out if you experience problems or don't like this application:

- [novel-ebook.com](https://novel-ebook.com) -  Spiritual successor of this script as a web application with more novels, better user experience, faster downloads, consistency between operating systems and Android/iOS support. All without downloading any software!

- [EternalTrail's fork of this script](https://github.com/EternalTrail/Novel-2-EBook) - that is basically a rewrite. Clean code, easy install, lightweight, good looking UI and support for GravityTales (and more to come)!

- [LordKBX's fork of this script](https://github.com/LordKBX/wuxiaworld_export_ebook)

- [KietSam's fork of this script](https://github.com/KietSam/Wuxiaworld-2-eBook) - If you plan on uploading the generated .epub files to Google Books, try this fork.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone on stackexchange who helped me in my most dire times

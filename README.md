![Shazam2Spotify](https://github.com/jclosadev/Shazam2Spotify/blob/master/header.jpg?raw=true)

# Shazam2Spotify

[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/navendu-pottekkat/awesome-readme?include_prereleases)](https://img.shields.io/github/v/release/navendu-pottekkat/awesome-readme?include_prereleases)

a tool that lets you quickly and automatically transfer your entire library of Shazam recognized songs to Spotify. This tool creates a new Spotify playlist with all the songs you’ve identified, so you can enjoy them all in one place without the need for manual searching and adding.

# Installation

> **Note**: For longer README files, I usually add a "Back to top" buttton as shown above. It makes it easy to navigate.

**1. Clone the Repository**

Start by cloning the repository to your local machine. Run the following command in your terminal:
```shell
git clone https://github.com/jclosadev/Shazam2Spotify.git
cd Shazam2Spotify
```
**2. Install Dependencies**

Make sure you have Python installed. Then, install the required dependencies with:
```shell
pip install -r requirements.txt
```
3. Get your Shazam Library file

Now go to [My Shazam](https://www.shazam.com/es-es/myshazam) Log in, and on the right side, click on **Download CSV** and you will get a *Sshazamlibrary.csv* and now go to the project where you cloned the repository and put the file in the library folder.



# Usage
[(Back to top)](#table-of-contents)

**1. Open a Terminal**

and go to the repository folder and run the app with the following command

```shell
cd Shazam2Spotify
python app.py
```
**2. Log in with your Spotify Account**

Once you have executed the program, a Spotify login page will open in your browser. Log in with your Spotify account, where Shazam2Spotify will do its magic. Afterward, you will see "Authentication Successful" in the browser if the authentication was correct, and then in the terminal, you will see an output like this:
```shell
Logged in as: jclosadev
Playlist 'Shazam2Spotify' created with ID: 1LgH0v9zO9uPaWpba7maLd
Searching: Binding Lights - The Weekend
Added to the Playlist: Binding Lights - The Weekend
```
and when Shazam2Spotify has finished adding all the songs, it will open the link to the created playlist in the browser, while it finishes adding songs, you can check your Spotify where you can see the playlist created and how the number of songs in the playlist is increasing every half second, Thank you for using it, and I hope it’s helpful! And if you liked it, please leave a star! :)


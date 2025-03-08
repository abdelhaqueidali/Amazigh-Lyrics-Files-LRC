# Amazigh Lyrics Files (LRC)

This repository contains a collection of LRC (lyric) files for Amazigh songs. These files can be used with music players that support LRC format to display synchronized lyrics while listening to the songs.  This repo is intended to be used with my other project: [LRC & YouTube Player](https://github.com/abdelhaqueidali/LRC-And-YouTube-Player). You can test how these files work with the songs here: [https://abdelhaqueidali.github.io/LRC-And-YouTube-Player/](https://abdelhaqueidali.github.io/LRC-And-YouTube-Player/)

## About

This collection aims to preserve and share the lyrics of Amazigh songs in a time-synchronized format.  LRC files provide a line-by-line display of lyrics, enhancing the listening experience and making it easier to follow along with the songs.

## Repository Structure

The repository consists primarily of `.lrc` files. Each file is named after the song it represents. The names generally follow this structure:

`Song Title - Artist.lrc` or `Artist - Song Title.lrc` or using the original title and extension as is from the source file.

Example:

*   `Adrar inu (Ma montagne) - Idir.lrc`
*   `Imghrane - Innayyi Baba (Officiel Audio).lrc`
*   `TARWA N-TINIRI - IFAW UL NNEGH (Official Videoclip).lrc`
*   `makid yuayn abu wizar(MP3_128K).lrc`


**How to Use:**

1.  **Download the LRC file:** Download the `.lrc` file for the song you want to listen to. You can download the entire repository as a ZIP file using this link: [https://github.com/abdelhaqueidali/Amazigh-Lyrics-Files-LRC/archive/refs/heads/main.zip](https://github.com/abdelhaqueidali/Amazigh-Lyrics-Files-LRC/archive/refs/heads/main.zip) or you can download individual files.
2.  **Place the LRC file in the same directory as the song:** Make sure the LRC file and the corresponding audio file (e.g., MP3, M4A) are in the same folder. The filenames *must* match (except for the extension).  For example:

    *   `MySong.mp3`
    *   `MySong.lrc`
3.  **Open the song with your LRC-compatible player:** Your music player should automatically detect and display the lyrics.

## Contributing

Contributions to this repository are welcome! If you have LRC files for Amazigh songs that are not included here, please feel free to submit a pull request. Please follow these guidelines:

1.  **Fork the repository.**
2.  **Create a new branch:**  `git checkout -b my-new-song`
3.  **Add your LRC file(s).**
4.  **Commit your changes:** `git commit -m "Added lyrics for [Song Title] by [Artist]"`
5.  **Push to your branch:** `git push origin my-new-song`
6.  **Create a pull request.**

If you have corrections or improvements to existing LRC files, please also submit a pull request.

## LRC Format

LRC files are plain text files with a specific format.  Each line typically follows this structure:
Use code with caution.
Markdown
[mm:ss.xx]Lyric text

*   `mm`: Minutes
*   `ss`: Seconds
*   `xx`: Hundredths of a second (sometimes thousandths: `xxx`)
*   `Lyric text`: The text of the lyric for that timestamp.

Example:
Use code with caution.
[00:12.34]This is the first line of the song.
[00:15.67]This is the second line.
[00:20.00]And so on...

There can also be metadata tags at the beginning of the file, such as:
Use code with caution.
[ar:Artist Name]
[ti:Song Title]
[al:Album Title]
[by:LRC Creator]

These metadata tags are optional but helpful for organizing and identifying the lyrics.

## Disclaimer

The lyrics in this repository are provided for educational and personal use only.  The copyright for the lyrics belongs to the respective artists and songwriters. I do not own any copyrights related to these lyrics.

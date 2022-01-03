# Invidious

A small terminal Ruby script to watch YouTube videos through an Invidious
instance.

Invidious instances are listed [here](https://api.invidious.io/).

By default it will use
[https://invidious.snopyta.org](https://invidious.snopyta.org) but you can
change the instance URL changing the `INSTANCE_URL` constant on the top of the
script.

## Dependencies

This script has the following dependencies:

### Ruby

You'll need Ruby installed. The script was tested on Ruby version 2.7.1.

### Ruby gems

Make sure to have the following gems installed:

```bash
gem install 'rest-client'
gem install 'tty-prompt'
```

### MPV

The script uses `mpv` to play the videos. On `macOS`, for example, you can
install
`mpv` using:

```bash
brew install mpv
```

## Usage

Just fire up the script on the terminal typing:

```bash
./invidious
```

## Keys and navigation

On the search prompt you can exit by typing `quit` and pressing `enter`.

On the results pages, you can use the `arrow keys` to navigate through the
results, `spacebar` to select a video and `enter` to play the selected videos.
You can select multiple videos and they will play in order.

To load the next results page press `n`. Press `p` to load the previous one.

To perform a new search, type `s`.

To quit, press `q`.

## License

This script is provided as open source under the terms of the [MIT
License](https://opensource.org/licenses/MIT).

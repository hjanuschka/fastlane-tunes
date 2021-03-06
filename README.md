# fastlane tunes 🎶

[![fastlane Plugin Badge](https://rawcdn.githack.com/fastlane/fastlane/master/fastlane/assets/plugin-badge.svg)](https://rubygems.org/gems/fastlane-plugin-tunes)

## Getting Started

This project is a [fastlane](https://github.com/fastlane/fastlane) plugin. To get started with `fastlane-tunes`, add it to your project by running:

```bash
fastlane add_plugin tunes
```

## About tunes

Play music using fastlane, because you can.

```ruby
# Play a specific song
tunes(file_path: '/Library/Audio/Apple Loops/Apple/01 Hip Hop/City Lights Beat.caf')

# Play all mp3s from a specific directory
tunes(directory: '/Users/yatusabes/Music/')
```

<img src="assets/FastfileScreenshot.png" width="550" />
<img src="assets/FilesScreenshot.png" width="550" />
<img src="assets/OutputScreenshot.png" width="550" />

## Example

Check out the [example `Fastfile`](fastlane/Fastfile) to see how to use this plugin. Try it by cloning the repo, running `fastlane install_plugins` and `bundle exec fastlane test`.

## Run tests for this plugin

To run both the tests, and code style validation, run

```
rake
```

To automatically fix many of the styling issues, use 
```
rubocop -a
```

## Issues and Feedback

For any other issues and feedback about this plugin, please submit it to this repository.

## Troubleshooting

If you have trouble using plugins, check out the [Plugins Troubleshooting](https://github.com/fastlane/fastlane/blob/master/fastlane/docs/PluginsTroubleshooting.md) doc in the main `fastlane` repo.

## Using `fastlane` Plugins

For more information about how the `fastlane` plugin system works, check out the [Plugins documentation](https://github.com/fastlane/fastlane/blob/master/fastlane/docs/Plugins.md).

## About `fastlane`

`fastlane` is the easiest way to automate building and releasing your iOS and Android apps. To learn more, check out [fastlane.tools](https://fastlane.tools).

# Zoom Launcher Workflow

<!-- ABOUT THE PROJECT -->
## About

An [Alfred](https://www.alfredapp.com/) workflow to easily launch Zoom meetings without launching the browser. 

### Features:
* Launch from Meeting ID, URL, or bookmarked meeting
* Add/remove meeting bookmarks
* Start meetings with Personal Meeting ID

<!-- GETTING STARTED -->
## Getting Started

### Download the latest version from the [releases](https://github.com/ArianOmidi/alfred-zoom-launcher/releases) page.

### Enviroment Variables

Set the following enviroment variables for full functionality.

```sh
personalId : PERSONAL_MEETING_ID
invite : PERSONAL_LINK
```

<!-- USAGE EXAMPLES -->
## Usage

### `zma`
Add a meeting bookmark by entering the bookmark name with `zma <name>` and then enter the meeting id or url `<id|url>`.
  
### `zmd`
Delete a meeting bookmark by entering `zmd` and select the bookmark from the dropdown.

### `zm`
Launch a meeting with `zm` and select option from dropdown menu or enter the meeting id or url `<id|url>`.

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Aurooba Ahmed's Zoom Workflow](https://github.com/aurooba/alfred-workflow-zoom-meetings)

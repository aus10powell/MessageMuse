# MessageMuse

## Data
### Exploration
#### Exporting personal messages from iphone
* 1) Install imessage explorer using brew [here](https://github.com/ReagentX/imessage-exporter/tree/develop)
* 2) Move iphone *chat.db* from default location `/Users/username/Library/Messages/chat.db` to something like `/Users/Downloads/chat.db` in order to avoid write permissions from imessage-explorer library
* 3) Run a command like: `imessage-exporter -p /Users/aus10powell/Downloads/chat.db -f txt -o output -c efficient` to explort all message conversations to text file format to current directory and create folder "output"

* Other:
    * SQLite Viewer extension on VScode can be used to explort the chat.db and create custom datasets
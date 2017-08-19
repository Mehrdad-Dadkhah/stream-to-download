# StreamToDownload
Send data chunk to client for download it

## Installation

```
composer require mehrdad-dadkhah/stream-to-download
```

## Usage

```PHP
use MehrdadDadkhah\Video\StreamToDownload;

$streamToDownload = new StreamToDownload();
$streamToDownload->downloadFile('path-or-url-to-file.mp4', 'output-file-name.mp4');
```

## License

hls-video-generater is licensed under the [GPLv3 License](http://opensource.org/licenses/GPL).
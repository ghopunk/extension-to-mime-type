# extension-to-mime-type
Extension to Mime Type PHP

Convert extension to Mime type
$extension = 'jpg';
$mime = extensionToMimeType($extension);
echo $mime; // image/jpeg

$mime = 'application/json';
$extension = mimeTypeToExtension($mime);
echo $extension; // json


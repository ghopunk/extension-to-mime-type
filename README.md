# extension-to-mime-type

Convert Extension to Mime-type

$extension = 'jpg';

$mime = extensionToMimeType($extension);

echo $mime; // image/jpeg



Convert Mime-type to Extension

$mime = 'application/json';

$extension = mimeTypeToExtension($mime);

echo $extension; // json

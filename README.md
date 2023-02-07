# Extension to Mime Type

Convert Extension to Mime-type or Mime-type to Extension

# Sample Extension to Mime-type
$extension = 'jpg';<br>
$mime = extensionToMimeType($extension);<br>
echo $mime; // image/jpeg

# Sample Mime-type to Extension
$mime = 'application/json';<br>
$extension = mimeTypeToExtension($mime);<br>
echo $extension; // json

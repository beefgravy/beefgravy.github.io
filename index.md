# The Title of the First Page
This is submitted by way of a test, doing things the way they should be done.
## Commit, Push etc.
Hopefully this has worked.

<?php
$files = scandir('/path/to/folder');
sort($files);
foreach($files as $file){
   echo'<a href="/path/to/folder/'.$file.'">'.$file.'</a>';
}
?>
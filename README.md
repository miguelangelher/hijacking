# hijacking
This repository has two files in. One of them is aimed to perform a redirection to the page containing a reflected XSS. This is done by the file redir.html.

The other one is aimed to be placed in a server which supports PHP. The hook present in the XSS file must refer to the URL where the showme.php file is published. After a successful XSS exploit, the attacker will have available the victims cookie in a text file server side.

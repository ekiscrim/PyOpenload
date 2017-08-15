========
Examples
========

:samp:`username` and :samp:`key` can be found in `openload user settings <https://openload.co/account#usersettings>`_.

Account
=======

Account Infos
-------------

Get everything account related (total used storage, reward, ...).

.. literalinclude:: ../examples/account_infos.py

   
Download
========

Download Ticket
---------------

Generate a download token, will be used to generate direct download link.

.. literalinclude:: ../examples/download_ticket.py

   
Download Link
-------------

Generate a download link, after generating a download ticket.

.. literalinclude:: ../examples/download_link.py

   
Full example
------------

1) Generate a download token.
2) Solve captcha if needed.
3) Generate direct download url.

.. literalinclude:: ../examples/download_full.py

   
File Info
---------

Check the status of a file (id, status, name, size, sha1, content_type).

.. literalinclude:: ../examples/file_info.py

   
Upload
======

Get an Upload URL
-----------------

You may need to use this method only if you want to re-implement :samp:`upload_file` in a different way.

Generate upload url, will be used to upload a file.

.. literalinclude:: ../examples/upload_link.py

   
Upload File
-----------

.. literalinclude:: ../examples/upload_link.py
   

Remote Upload
=============

Add Remote Upload
-----------------

Upload lastest pyopenload documentation pdf.

.. literalinclude:: ../examples/remote_upload.py


Check Remote Upload Status
--------------------------

Check the status of queued remote uploads.

.. literalinclude:: ../examples/check_remote_upload.py


File/Folder Management
======================

List Folder
-----------

List :samp:`Home` (The main directory).

.. literalinclude:: ../examples/list_folder.py


Converting files
================

Convert a file
--------------

Show running file converts
--------------------------

Show failed file converts
-------------------------

Get splash image
----------------
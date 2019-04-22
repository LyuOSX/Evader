Telethon
========
.. epigraph::

  ⭐️ Thanks **everyone** who has starred the project, it means a lot!

|logo| **Telethon** is an asyncio_ **Python 3**
MTProto_ library to interact with Telegram_'s API
as a user or through a bot account (bot API alternative).



Evader
========
.. epigraph::

  tnx for https://www.codeproject.com/Articles/5035/How-to-Write-a-Simple-Packer-Unpacker-with-a-Self
  tnx for https://www.youtube.com/watch?v=bQWRW0VUXR4

It's a exe packer which will encrypt your PE exe input file and add it as resource to the end of the output new exe file

the encryption key size and complexity can be given as input

Usage of packer
-----------------

    packer.exe <input-path> <output-path> <key-size> <start-ascii> <end-ascii>
  
The complexity of encryption key will be determined by <start-ascii> and <end-ascii>
  
for example this command will lead to keys from AAAA to ZZZZ

    packer.exe <input-path> <output-path> 4 65 90

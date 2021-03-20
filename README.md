# text2speech_speech2text
<pre>
To encrypt a file:
$ openssl enc -e -aes256 -in speechrecog.py >speechrecog.py.aes
enter aes-256-cbc encryption password:
Verifying - enter aes-256-cbc encryption password:

To decrypt a file
$ openssl enc -d -aes256 -in speechrecog.py.aes >speechrecog.py
enter aes-256-cbc decryption password:
</pre>

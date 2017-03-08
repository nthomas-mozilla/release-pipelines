This repo contains our attempts to capture (and hopefully improve) Mozilla
release processes.

Validation
----------

Initial setup is to create a virtualenv, eg
 ```virutalenv venv
    . venv/bin/activate
    pip install -r requirements.txt

And to validate
    scripts/validate <file1.yml> [<file2.yml> ...]

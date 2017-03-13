This repo contains our efforts to capture (and hopefully improve) Mozilla
release processes.

Validation
----------

Initial setup is to create a virtualenv, eg

    virtualenv venv
    . venv/bin/activate
    pip install -r requirements.txt

And to validate

    scripts/validate file1.yml [file2.yml ...]

Visualisation
-------------

You'll need graphviz installed with your package manager, and a virtualenv as above. Then

    scripts/drawDAG file1.yml [file2.yml ...]

This will create `file1.gv.pdf` etc.

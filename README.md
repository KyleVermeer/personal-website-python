To make sure gunicorn watches static files changes as well, try running with:

gunicorn app:app --reload --reload-extra-file templates/* --reload-extra-file static/css/*

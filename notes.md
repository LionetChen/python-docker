To get dependent packages
```bash
pip3 freeze | grep Flask >> requirements.txt
pip3 freeze | grep mysql-connector-python >> requirements.txt
```

To make flask auto reload on code change:
`export FLASK_DEBUG=1`

This note is for testing committing before rebasing.
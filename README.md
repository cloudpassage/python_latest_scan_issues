# python_latest_scan_issues
<b> Description </b>
This program archives the latest scan issues for all active servers and deactivated servers that were last seen 24 hours ago.

<b> Prerequisities: </b>

1. cloudpassage sdk (install via pip install cloudpassage)

2. Copy the API Key_id and Secret Key from your Halo account into `portal.yml` located in `configs/portal.yml`

    ```
    key_id: 12345
    secret_key: abcabcabcabcabc
    ```

<b> Dependencies: </b>

1. Python 2.7.10
2. cloudpassage python package
3. dateutil.parser (install via pip install python-dateutil)
4. logbook (install via pip install logbook)

<b> Program Usage: </b>

Run the following command to see program usage:

```
python latest_scan_issues.py
```

<b> Program Output </b>

The archive scan issue data will be stored in the `data` directory.
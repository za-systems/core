# core
Web Server and Utils

- Core is the system module
- Apps will be defined in a separate folder, in core's parent directory
    - core will contain a config file pointing at default app, location.
            * .zaconfig
        ```
            {
                "default-module-name":"app",
                "default-module-location":"app/"
            }
        ```
    - each app folder will have a config file 
    - Config file:
        - Port to run the app
            * .zaconfig
        ```
            {
                "port": 8000
            }
        ```




# Commands 

| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 | 
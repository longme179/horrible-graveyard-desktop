# Restoring this backup

Run the matching restore tool from your rice-backup checkout:

    bin/rice-restore.sh --from <this repository URL>

Restore is dry-run by default and applies section by section; read README.md
first. Package lists are never executed automatically: review the generated
script before running anything with sudo.

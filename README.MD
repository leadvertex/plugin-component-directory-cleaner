CLI command based on [Symfony/Console](https://github.com/symfony/console), that can remove files in some directory, that
older than some hours.

Usage (remove files older than 24 hours in "/var/html/app/logs/")
```bash
php console.php cleaner:run "/var/html/app/logs/" 24
```
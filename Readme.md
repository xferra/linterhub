# FAQ
  - How to prepare:
    - Install [Docker Toolbox], [Oracle Virtual Box], [Cygwin] (for Windows).
    - Update envinorement variable PATH with pathes to installed software.
  - How to start:
    -  Open terminal (command line), navigate to the root folter of this project.
    -  Exec `sh linter.sh setup` (for Windows just `linter setup`), pay attention to Warnings and Errors.
  - How to test:
    - Exec `sh linter.sh --help`, it displays the list of available commands.
    - Exec `sh linter.sh analyze "linter":"command":"output.file" "/path/to/project"` to analyse the project .
  - How to add new linter:
    - Create a new issue with: name, description, url, supported languages, license of linter.

   [Docker Toolbox]: <https://www.docker.com/products/docker-toolbox>
   [Oracle Virtual Box]: <https://www.virtualbox.org>
   [Cygwin]: <https://www.cygwin.com>
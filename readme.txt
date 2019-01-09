1) install composer
2) $composer require symfony/console

structure of directories shold be next.

|-- bin   --new
|   -- console
|-- composer.json
|-- composer.lock
|-- src   --new
|   -- App
|       -- Commands
|           -- HelloworldCommand.php
|-- vendor

3) Create console file
File console must be executable!!:
sudo chmod +x /bin/console
4) Create HelloworldCommand.php
Create src/App/Commands/HelloworldCommand.php

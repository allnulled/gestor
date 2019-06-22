# gestor

Manage your tasks through json files and a web application.

# Install

`$ npm i -g gestor`

# Usage

`$ gestor`

This will create a `gestor.json` file (in case it is not present already) in the current working directory.

Otherwise, you can specify a specific file like:

`$ gestor --file otherfile.json`

Or abbreviatedly:

`$ gestor -f otherfile.json`

Once you run this command, a server will be automatically created.

This server will start working in the first available port, from the `5000` to the `6000`.

Also, a web application will be opened from your preferred browser automatically.

# Explanation

The `json` file is used as database. The changes made by the app are reflected and synchronized with this file.


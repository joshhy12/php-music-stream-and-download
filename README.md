# PHP Music Application

This is a PHP-based web application for managing and playing music. It allows users to upload, view, and listen to music tracks.

## Features

- **User Authentication**: Secure login for admin and user accounts.
- **Music Management**: Add, edit, and delete music tracks.
- **File Upload**: Upload music banners and audio files.
- **Streaming**: Stream music tracks directly from the browser.
- **User Permissions**: Manage user accounts and their permissions.
- **Responsive Design**: Accessible on both desktop and mobile devices.
- **Database Integration**: Store and manage music data using MySQL.
- **Search Functionality**: Easily search for music tracks.
- **Playlist Creation**: Create and manage playlists (if applicable).
- **Download Option**: Allow users to download music tracks (if applicable).

## Prerequisites

Before running the application, make sure you have the following installed:

- Apache Web Server
- PHP (version 7.0 or higher)
- MySQL or MariaDB

## Installation

1. Clone the repository or download the source code.
2. Create a new MySQL database and import the `mgs_db.sql` file located in the `database` directory.
3. Rename the `config.php.sample` file to `config.php` and update the database credentials.
4. Move the entire project directory to your web server's document root (e.g., `/var/www/html/`).
5. Make sure the `uploads` directory is writable by the web server.
6. Access the application in your web browser using the appropriate URL (e.g., `http://localhost/php-music-app`).

## Usage

1. Log in to the admin panel using the default credentials (username: `admin`, password: `password`).
2. Navigate to the "Musics" section to add, edit, or delete music tracks.
3. Upload music banners and audio files for each track.
4. Manage user accounts and permissions (if applicable).
5. Users can browse and listen to the available music tracks.

## Bash Script

The `deploy.sh` bash script is provided to automate the deployment process. Here's how to use it:
 
## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

```bash
# Navigate to the project directory
cd /path/to/php-music-app

# Run the deployment script
./deploy.sh


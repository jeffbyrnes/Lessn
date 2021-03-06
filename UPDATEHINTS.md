# Update Hints

## Updating to 1.2.0 from 1.1.1

1. Create a backup of all files.
2. Replace all files except `/-/config.php` on your server.

## Updating to 1.1.1 from 1.1

1. Replace `/-/SIDB423.php` with the updated version in this
   archive.
2. Upload `/-/SIDB5.php` to your server.

## Updating to 1.1 from 1.0.7

1. Upload `/-/SIDB423.php` to your server.
2. Replace `/-/index.php` and `/-/db.php` with the updated
   versions in this archive.
3. Replace `/index.php` with the updated version in this
   archive (minding any changes you might have made, diff
   before replacing if necessary).

## Updating to 1.0.7 from 1.0.6

1. Replace `/-/index.php` with the updated version in this
   archive.
2. Replace `/index.php` with the updated version in this
   archive (minding any changes you might have made, diff
   before replacing if necessary).
3. Replace `/-/pages/done.php` with the updated version in
   this archive.

## Updating to 1.0.6 from 1.0.5

1. Replace `/-/index.php` with the updated version in this
   archive (only `LESSN_VERSION` changed).
2. In `/index.php` replace line 9 with lines 9-10 from the
   updated version in this archive.

## Updating to 1.0.5

1. Replace all files and directories in `/-/` with the updated
   versions in this archive except `/-/config.php`.
2. (Optional) Define a customized `API_SALT` in `/-/config.php`

## Updating from 1.0.1

1. Using a tool like PHPMyAdmin or the MySQL CLI change the
   checksum index type to `INDEX` (from `UNIQUE`).
2. Replace all files and directories in `/-/` with the updated
   versions in this archive except `/-/config.php`.
3. (Optional) Define a customized `API_SALT` in `/-/config.php`

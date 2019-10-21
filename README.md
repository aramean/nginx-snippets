# Nginx

## Snippets

This package contains a set of config files with best practices that you can include in your Nginx Server Blocks (Virtual Hosts).

- `letsencrypt.conf`: Enable ACME Challenge support on Server Block.
- `non-www-to-www+ssl.conf`: Redirect non-www to www with https (SSL).
- `non-www-to-www.conf`: Redirect non-www to www.

## Usage

```conf
server {
  include snippets/[the-name-of-the-snippet].conf;
}

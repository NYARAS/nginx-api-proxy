# Recipe App API Proxy

NGINX Proxy for Django API app deployment

## Usage

Proxy is used to server static files

### Environment Variables

  * `LISTEN_PORT` - Port to listen on (default: `8000`)
  * `APP_HOST` - Hostname of the app to forward requests to (default: `app`)
  * `APP_PORT` - Port of the app to forward requests to(default: `9000`)

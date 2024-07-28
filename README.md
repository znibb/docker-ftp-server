FTP server via Docker Compose for local UNSECURE use only

## Usage
Connect to the local ip/hostname of the server using FTP_USER//FTP_PASS and port 21.

Mounts `./uploads` as target directory for FTP uploads, set `TARGET_DIR` to an absolute file path to override this location.

## Docker Setup
1. Initialize config by running init.sh: `./init.sh`
2. Input personal information into `.env`
3. Run `docker compose up` and check logs
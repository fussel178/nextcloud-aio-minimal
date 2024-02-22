# Nextcloud AIO Minimal

A minimal setup of the Nextcloud AIO Docker setup

## Usage

1. Clone this repository:

   ```shell
   git clone https://github.com/fussel178/nextcloud-aio-minimal.git
   cd nextcloud-aio-minimal
   ```

2. Create a copy of the `example.env` file named `.env`:

   ```shell
   cp example.env .env
   ```

3. Next, open the `.env` file with your favorite editor, read through every environment variable and change it accordingly:

   ```shell
   $EDITOR .env
   ```

4. Finally, start all containers by running:

   ```shell
   docker compose up -d
   ```

   > Note: After this command, Nextcloud needs a little bit of time to setup your Nextcloud instance.
   > To watch the current process, take a look at the container logs:
   >
   > ```shell
   > docker compose logs -f
   > ```

## Acknowledgments

Container images and variable defaults are from <https://github.com/nextcloud/all-in-one>.

# gotenberg-google-fonts

A custom Docker image for [Gotenberg](https://gotenberg.dev/) that adds the ["Rethink Sans"](https://github.com/hans-thiessen/Rethink-Sans) Google Font.

## Features

- Extends the `gotenberg/gotenberg:8` image.
- Adds the "Rethink Sans" font, including all variable and static font files.

## Usage

### Build the Docker Image

To build the custom Docker image, run the following command in your terminal:

```sh
docker build -t gotenberg-google-fonts .
```

### Run the Docker Image

Once the image is built, you can run it using the following command:

```sh
docker run -d -p 3000:3000 gotenberg-google-fonts
```

This will start a Gotenberg container with the "Rethink Sans" font available for all your PDF conversions.

## Font Information

This image includes the "Rethink Sans" font, which is licensed under the SIL Open Font License, Version 1.1. You can find the full license text in the `fonts/Rethink_Sans/OFL.txt` file.

The Rethink Sans font project can be found on GitHub: [https://github.com/hans-thiessen/Rethink-Sans](https://github.com/hans-thiessen/Rethink-Sans)

## Project License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

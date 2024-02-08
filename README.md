# QR Code Generator with Logo Overlay

This Python script generates a QR code with a specified URL or text and overlays a logo in the center. It uses the `qrcode` and `PIL` (Pillow) libraries to achieve this.

## Prerequisites

Make sure you have Python installed on your machine. Install the required libraries using the following command:

```
pip install qrcode[pil]
```

## Usage

1. Replace `Logo_link` with the path to your logo image.

```
Logo_link = 'path/to/your/logo.png'
```

2. Adjust the `basewidth` variable to set the desired width for the QR code.

```
basewidth = 100
```

3. Set the `url` variable to the desired URL or text for the QR code.

```
url = 'https://example.com'
```

4. Optionally, change the `QRcolor` variable to set the fill color of the QR code. You can add color code html for the colors 

```
QRcolor = 'black'
```

5. Run the script:

```
python python .\qrcode-gen.py
```

The generated QR code with the logo overlay will be saved as `mygithubqr.png`.

## Example

![GitHub QR Code with Logo Overlay](mygithubqr.png)

## Customization

Feel free to customize the script according to your needs. If you encounter any issues or have suggestions, please open an [issue](https://github.com/your_username/your_repository/issues).

## Dependencies

- [qrcode](https://pypi.org/project/qrcode/)
- [Pillow](https://pypi.org/project/Pillow/)

## Credits

- [qrcode](https://github.com/lincolnloop/python-qrcode)
- [Pillow (PIL Fork)](https://github.com/python-pillow/Pillow)

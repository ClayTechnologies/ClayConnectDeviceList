# Device Spec
## V1
`? means optional`
* `version`: Should always be 1
* `uuid`: A UUID (NOT BLUETOOTH!) that must be specified in your code and will be used to uniquely identify your device
* `name`: The name that will be displayed on the app
* `images`: An object containing all of the images required for the device (See Appendix 1)
* `repo`? If your device is open-source, you may specify where it's design and/or source code is located here

# Appendices
## Appendix 1
The Image object contains the following properties:
`? means optional`
`See  Appendix 2 for a definition of an Imaga Carrousel`
* `big`: An Image Carrousel containing the image that will be shown on the settings and connect page
* `brand`? An Image Carrousel containing the image that will be shown as the icon for the brand

## Appendix 2
An Image Carrousel is an object containing the different resolutions available.
Every property of this object should follow the `<WIDTH>x<HEIGHT>` scheme and it's value should be a url to a file with the JPG, JPEG or PNG file extension.
Sorry, no WEBP, SVG or any of those fancier formats

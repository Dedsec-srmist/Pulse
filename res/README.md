## Project Resources

This folder contains various resources used by the project:

* **images:** Stores all image assets used in the project (icons, logos, backgrounds, etc.).
* **fonts:** Custom fonts used for specific UI elements.
* **config.json:** Configuration file containing project settings.

**Usage:**

* Images can be accessed using the project's resource loader or by directly referencing the file path.
    * Example: `myImage = loadImage("path/to/image.png")`
* Fonts can be loaded and applied to UI elements using the appropriate methods.
* The `config.json` file can be parsed to retrieve configuration values.
    * Example: `const apiKey = JSON.parse(fs.readFileSync("config.json")).apiKey`

**Additional Notes:**

* All image assets are licensed under AGPL V3.0 License.

**Feel free to modify this template to suit the specific needs of your project and resource structure.**

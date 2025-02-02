# Android String XML Translator

This is a web page that can be used to translate Android string XML files.

## How to Use

You can customize the repository, path, and branch by adding query parameters to the URL. Here are the available parameters:

- **repo**: The GitHub repository in the format `username/repo`. Default is `emanuele-f/PCAPdroid`.
- **path**: The path to the strings.xml file within the repository. Default is `app/src/main/res`.
- **branch**: The branch of the repository. Default is `master`.

### Example URL

```plaintext
https://ramazansancar.github.io/AndroidStringXmlTranslator/index.html
?repo=yuliskov/SmartTube
&path=common/src/main/res
&branch=master
```

### Steps

1. Open the HTML file in a browser or use the provided URL with the parameters set.
2. Select the target language. (The source language is the language of the `strings.xml` file.)
3. Click on the "Translate" button.
4. The translated XML file will be downloaded.

### Notes

The tool uses the `strings.xml` file as the source and provides translations in the selected target language.

## How It Works

The translator uses HTML and JavaScript to translate the XML files.

## Source

- [GitHub Repo](https://github.com/yuliskov/SmartTube)
- [Translator for Android Apps (strings.xml)](https://jtbrinkmann.de/tools/android-strings.xml-translator.html)
- [Developer](https://github.com/jtbrinkmann)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

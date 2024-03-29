
![Logo](https://souciencia.unifesp.br/images/logos/Sou_Cincia_RGB_1Linha_Oficial_Color.png)


# Automation of Uploads to the Internet Archive

Python Script for automating data uploads to the Internet Archive via API, Using Metadata Stored in a JSON File. Initially, it reads the JSON file, which contains detailed information about various items. For each item in the file, the script checks for the existence of a unique identifier ('identifier'). If this identifier is present, the script proceeds with extracting the mandatory metadata, such as title, media type, and the path of the file to be uploaded. After extracting this information, the metadata is removed from the item so that additional metadata can be dynamically included during the upload. The code then attempts to upload the specified file to the Internet Archive, providing the extracted and additional metadata. During this process, the script handles possible Unicode encoding errors and other types of exceptions, reporting the success or failure of each item's upload. A specific error message is displayed if an item in the JSON lacks an identifier, ensuring that all uploads are tracked and verified efficiently.

## Author

- [Antonio Serrano](https://www.linkedin.com/in/antoniogsserrano/)


## License

[Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)

## Acknowledgements

 - [Data Science Team of SoU_Ciência Institute](https://souciencia.unifesp.br/sobre)
 - [Tide Setubal Foundation](https://fundacaotidesetubal.org.br/tide-setubal-foundation/)
 - [Serrapilhera Institute](https://serrapilheira.org/en/)
 - [Legislative Amendments](https://www2.camara.leg.br/english/the-national-congress-1/types-of-legislation)

## Get in Touch

- antonioserranopro@gmail.com 
- souciencia@unifesp.br

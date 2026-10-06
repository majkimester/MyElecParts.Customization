# MyElecParts.Customization
Customization files for MyElecParts electronic component search and inventory application:
https://myelecparts.hu/

If you would like to contribute and translate the MyElecParts into your native language and you
have good electronics domain knowledge, please contact me. Here is a short description how to start:

## Create new translation

In Languages.xml you can add a new language like this with the 2 letter ISO639 language code (es). Use the native language name here

```
    <system:String x:Key="Language_es">Español</system:String>
```

Then you can copy all *_en.xaml file to your language for example *_es.xaml as a base for your translation.

Then you can edit your new language files, but keep the order and other formats, only edit the texts itself.
please be careful with texts with parameters or newlines. They shall remain in the same format. 
For example {1} is a parameter, and its content will be filled by the app.
'xml:space="preserve"' tells that the newlines are also preserved and the text will be presented according to the new lines in xaml file.








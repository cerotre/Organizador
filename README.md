# Organizador
Este programa es una herramienta para organizar tus archivos de manera automática. Al ejecutarlo, revisa todos los archivos **en la carpeta donde se encuentra** y los mueve a carpetas específicas según su tipo de archivo (creadas por el programa).

Por ejemplo, si tienes archivos de imágenes, los moverá a una carpeta llamada "Fotos". Si tienes videos, los colocará en una carpeta llamada "Videos". Lo mismo ocurre con archivos de audio, documentos, archivos comprimidos y otros archivos desconocidos. De esta manera, podrás mantener tus archivos ordenados y encontrarlos más fácilmente.

El programa no mueve ni modifica su propia ubicación ni el archivo de registro que genera, asegurándose de no afectar su funcionamiento.

Una vez que se ha ejecutado el programa, se generará un archivo de registro llamado "logs.txt" que registra las acciones realizadas, como los archivos movidos y cualquier problema que pueda ocurrir durante el proceso.

## Formatos

| Categoría  | Tipos de archivo                                                                              |
|------------|-----------------------------------------------------------------------------------------------|
| Fotos      | jpg, png, gif, jpeg, bmp, tiff, svg, webp, raw, psd, cr2, nef, arw, eps, tiff, svgz, jfif    |
| Videos     | mp4, mov, avi, wmv, mkv, flv, mpeg, 3gp, webm, ogv, m4v, rm, vob, 3g2, webm                   |
| Audios     | mp3, wav, flac, aac, ogg, wma, mp2, amr, aiff, ac3, alac                                      |
| Documentos | pdf, doc, docx, ppt, pptx, xls, xlsx, txt, rtf, csv, odp, odt, epub, mobi, djvu, ods, odf, xml, iml |
| Comprimidos| zip, rar, 7z, tar, gzip, bzip2, xz, tar.gz, bz2, lzma, z, xz, gz, jar                         |
| Otros      | Cualquier otro tipo de archivo que no se encuentre en las categorías anteriores               |

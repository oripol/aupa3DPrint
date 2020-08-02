# aupa3DPrint
Com iniciar-se al FreeCAD, impressió 3D... (https://oripol.github.io/aupa3DPrint/)

[Curs de FreeCAD de ObiJuan:](https://www.youtube.com/playlist?list=PLmnz0JqIMEzWQV-3ce9tVB_LFH9a91YHf)

<iframe width="1000" height="500" src="https://www.youtube.com/embed/videoseries?list=PLmnz0JqIMEzWQV-3ce9tVB_LFH9a91YHf" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Adaptador per al maniqui d'uniformitat tomogràfica:

[Unif tomo](https://github.com/oripol/aupa3DPrint/blob/master/uniftomo_v3.stl)

# Adaptador per al Detector Microdiamond i la cuba petita:

[SupotMicroDiamond](https://github.com/oripol/aupa3DPrint/blob/master/suportMicroDiamond.stl)

# Columna lumbar:

[Lumbar Spine](https://github.com/oripol/aupa3DPrint/blob/master/lumbar.stl)

# Com passar de DICOM a STL (amb 3D Slicer)

1. Exportem el CT i les estructures a DICOM. 
2. Obrim el programa 3D Slicer (hem de tenir el complement de RT Slicer per que entengui les estructures)
3. Obrim el DCM browser i naveguem fins la carpeta DICOM, la carreguem i premem el botó Examine. Carregarà i ja podem donar al de "load".
4. Agafem el mòdul de "segmentation" i a la part inferior tenim la part de "Export to files" que nos permite generar el STL.



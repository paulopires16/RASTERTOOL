# RASTERTOOL

Ferramenta de interação automática com imagens e linha de comando

# Exemplos de chamadas de funções (batch):
```batch
CALL "C:\cpc_apps\rastertool\rastertool.exe" createwatermark D:\temp\600.tif
CALL "C:\cpc_apps\rastertool\rastertool.exe" createcompress D:\temp\28_ext.tif
CALL "C:\cpc_apps\rastertool\rastertool.exe" createmirror FLIP_LEFT_RIGHT D:\temp\28_ext.tif
CALL "C:\cpc_apps\rastertool\rastertool.exe" createtransparency D:\temp\28.tif 255,255,255
CALL "C:\cpc_apps\rastertool\rastertool.exe" cmyk2rgb D:\temp\28.tif
CALL "C:\cpc_apps\rastertool\rastertool.exe" cmyk2index 28 D:\temp\28.tif
```

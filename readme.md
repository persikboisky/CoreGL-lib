# CoreGL
CoreGL - это библиотека для создания 3D и 2D игр, приложений\
на базе OpenGL.

## Об CoreGL
>[!NOTE]
> Написана на c++ 20\
> Формат .lib\
> режим компилятора - release x64

## линковка для VS
1.Заходим в свойства проекта\
2.Прописываем путь к папке include\
![](./icon/inc.png)\
3.Прописываем путь к папкe lib\
![](./icon/lib.png)\
4.Прописываем зависимости
```h
opengl32.lib
CoreGL.lib
```
![](./icon/value.png)\
5.Закидываем папку res в папку с проектом,\
а в последсвии к файлу .exe

# qmtile
cesium qm tile terain  base on cesium terrain builder 0.41 version



依赖库：存放于3rdParty文件加下

cgal 4.12版本；ctb 0.41版本 gdal：2.01版本



编译过程中几个重要的预处理项：

_USE_MATH_DEFINES：解决M_PI找不到

CPL_DISABLE_DLL： 解决ctb gdal相关的外部依赖找不到
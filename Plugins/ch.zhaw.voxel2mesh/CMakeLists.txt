project(ch_zhaw_voxel2mesh)

mitk_create_plugin(
  EXPORT_DIRECTIVE VOXEL2MESH_EXPORT
  EXPORTED_INCLUDE_SUFFIXES src
  MODULE_DEPENDS MitkQtWidgetsExt
)

set( MinimalPathExtraction_SRC
itkIterateNeighborhoodOptimizer.cxx
)

add_library(MinimalPathExtraction ${MinimalPathExtraction_SRC})
target_link_libraries(MinimalPathExtraction ${ITKOptimizers_LIBRARIES})
itk_module_target(MinimalPathExtraction)

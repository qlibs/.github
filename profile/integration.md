```
include(FetchContent)

FetchContent_Declare(
  qlibs.LIBRARY
  GIT_REPOSITORY https://github.com/qlibs/LIBRARY
  GIT_TAG v1.0.0
)
```

```
FetchContent_MakeAvailable(qlibs.LIBRARY)
target_link_libraries(${PROJECT_NAME} PUBLIC qlibs.LIBRARY);
```

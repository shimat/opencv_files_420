# opencv_files_420
OpenCV 4.2.0 libs and include files (VC++ v142 x86/x64)

## cv::getBuildInformation
```
General configuration for OpenCV 4.2.0 =====================================
  Version control:               4.2.0-dirty
  Extra modules:
    Location (extra):            C:/lib/opencv_contrib/modules
    Version control (extra):     4.2.0
  Platform:
    Timestamp:                   2019-12-21T06:48:19Z
    Host:                        Windows 10.0.18362 AMD64
    CMake:                       3.16.2
    CMake generator:             Visual Studio 16 2019
    CMake build tool:            C:/Program Files (x86)/Microsoft Visual Studio/2019/Community/MSBuild/Current/Bin/MSBuild.exe
    MSVC:                        1924
  CPU/HW features:
    Baseline:                    SSE SSE2
      requested:                 SSE2
    Dispatched code generation:  SSE4_1 SSE4_2 FP16 AVX
      requested:                 SSE4_1 SSE4_2 AVX FP16
      SSE4_1 (13 files):         + SSE3 SSSE3 SSE4_1
      SSE4_2 (1 files):          + SSE3 SSSE3 SSE4_1 POPCNT SSE4_2
      FP16 (0 files):            + SSE3 SSSE3 SSE4_1 POPCNT SSE4_2 FP16 AVX
      AVX (4 files):             + SSE3 SSSE3 SSE4_1 POPCNT SSE4_2 AVX
  C/C++:
    Built as dynamic libs?:      NO
    C++ Compiler:                C:/Program Files (x86)/Microsoft Visual Studio/2019/Community/VC/Tools/MSVC/14.24.28314/bin/Hostx64/x86/cl.exe  (ver 19.24.28314.0)
    C++ flags (Release):         /DWIN32 /D_WINDOWS /W4 /GR  /D _CRT_SECURE_NO_DEPRECATE /D _CRT_NONSTDC_NO_DEPRECATE /D _SCL_SECURE_NO_WARNINGS /Gy /bigobj /Oi  /fp:precise  /arch:SSE /arch:SSE2 /EHa /wd4127 /wd4251 /wd4324 /wd4275 /wd4512 /wd4589 /MP12   /MT /O2 /Ob2 /DNDEBUG 
    C++ flags (Debug):           /DWIN32 /D_WINDOWS /W4 /GR  /D _CRT_SECURE_NO_DEPRECATE /D _CRT_NONSTDC_NO_DEPRECATE /D _SCL_SECURE_NO_WARNINGS /Gy /bigobj /Oi  /fp:precise  /arch:SSE /arch:SSE2 /EHa /wd4127 /wd4251 /wd4324 /wd4275 /wd4512 /wd4589 /MP12   /MTd /Zi /Ob0 /Od /RTC1 
    C Compiler:                  C:/Program Files (x86)/Microsoft Visual Studio/2019/Community/VC/Tools/MSVC/14.24.28314/bin/Hostx64/x86/cl.exe
    C flags (Release):           /DWIN32 /D_WINDOWS /W3  /D _CRT_SECURE_NO_DEPRECATE /D _CRT_NONSTDC_NO_DEPRECATE /D _SCL_SECURE_NO_WARNINGS /Gy /bigobj /Oi  /fp:precise  /arch:SSE /arch:SSE2   /MP12    /MT /O2 /Ob2 /DNDEBUG 
    C flags (Debug):             /DWIN32 /D_WINDOWS /W3  /D _CRT_SECURE_NO_DEPRECATE /D _CRT_NONSTDC_NO_DEPRECATE /D _SCL_SECURE_NO_WARNINGS /Gy /bigobj /Oi  /fp:precise  /arch:SSE /arch:SSE2   /MP12  /MTd /Zi /Ob0 /Od /RTC1 
    Linker flags (Release):      /machine:X86  /NODEFAULTLIB:atlthunk.lib /INCREMENTAL:NO  /NODEFAULTLIB:libcmtd.lib /NODEFAULTLIB:libcpmtd.lib /NODEFAULTLIB:msvcrtd.lib
    Linker flags (Debug):        /machine:X86  /NODEFAULTLIB:atlthunk.lib /debug /INCREMENTAL  /NODEFAULTLIB:libcmt.lib /NODEFAULTLIB:libcpmt.lib /NODEFAULTLIB:msvcrt.lib
    ccache:                      NO
    Precompiled headers:         YES
    Extra dependencies:          comctl32 gdi32 ole32 setupapi ws2_32
    3rdparty dependencies:       ittnotify libprotobuf zlib libjpeg-turbo libwebp libpng libtiff libjasper IlmImf quirc ippiw ippicv
  OpenCV modules:
    To be built:                 aruco bgsegm bioinspired calib3d ccalib core datasets dnn dnn_objdetect dnn_superres dpm face features2d flann fuzzy hfs highgui img_hash imgcodecs imgproc line_descriptor ml objdetect optflow phase_unwrapping photo plot quality reg rgbd saliency shape stereo stitching structured_light superres surface_matching text tracking video videoio videostab xfeatures2d ximgproc xobjdetect xphoto
    Disabled:                    gapi java_bindings_generator python_bindings_generator python_tests world
    Disabled by dependency:      -
    Unavailable:                 cnn_3dobj cudaarithm cudabgsegm cudacodec cudafeatures2d cudafilters cudaimgproc cudalegacy cudaobjdetect cudaoptflow cudastereo cudawarping cudev cvv freetype hdf java js matlab ovis python2 python3 sfm ts viz
    Applications:                -
    Documentation:               NO
    Non-free algorithms:         YES
  Windows RT support:            NO
  GUI: 
    Win32 UI:                    YES
    VTK support:                 NO
  Media I/O: 
    ZLib:                        build (ver 1.2.11)
    JPEG:                        build-libjpeg-turbo (ver 2.0.2-62)
    WEBP:                        build (ver encoder: 0x020e)
    PNG:                         build (ver 1.6.37)
    TIFF:                        build (ver 42 - 4.0.10)
    JPEG 2000:                   build (ver 1.900.1)
    OpenEXR:                     build (ver 2.3.0)
    HDR:                         YES
    SUNRASTER:                   YES
    PXM:                         YES
    PFM:                         YES
  Video I/O:
    DC1394:                      NO
    FFMPEG:                      YES (prebuilt binaries)
      avcodec:                   YES (58.54.100)
      avformat:                  YES (58.29.100)
      avutil:                    YES (56.31.100)
      swscale:                   YES (5.5.100)
      avresample:                YES (4.0.0)
    GStreamer:                   NO
    DirectShow:                  YES
  Parallel framework:            Concurrency
  Trace:                         YES (with Intel ITT)
  Other third-party libraries:
    Intel IPP:                   2019.0.0 Gold [2019.0.0]
           at:                   C:/lib/opencv_builds/4.2.0_win-x86_vc2019/3rdparty/ippicv/ippicv_win/icv
    Intel IPP IW:                sources (2019.0.0)
              at:                C:/lib/opencv_builds/4.2.0_win-x86_vc2019/3rdparty/ippicv/ippicv_win/iw
    Lapack:                      NO
    Eigen:                       NO
    Custom HAL:                  NO
    Protobuf:                    build (3.5.1)
  OpenCL:                        YES (NVD3D11)
    Include path:                C:/lib/opencv2/3rdparty/include/opencl/1.2
    Link libraries:              Dynamic load
  Python (for build):            C:/Program Files (x86)/Microsoft Visual Studio/Shared/Python37_64/python.exe
  Install to:                    C:/lib/opencv_builds/4.2.0_win-x86_vc2019/install
-----------------------------------------------------------------

```

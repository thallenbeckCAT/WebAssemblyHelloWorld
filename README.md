# WebAssemblyHelloWorld
TO GET THIS WORKING:
- cd emsdk
- ./emsdk install --build=Release sdk-incoming-64bit binaryen-master-64bit
- ./emsdk activate --build=Release sdk-incoming-64bit binaryen-master-64bit
- source ./emsdk_env.sh --build=Release
- cd ..
- cd hello
- emrun --no_browser --port 8080 .
- open browser and navigate to http://localhost:8081/

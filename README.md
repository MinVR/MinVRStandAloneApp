# MinVR Stand Along Application

MinVRStandAlongApp is a simple example application which shows how to use the MinVR library.

## Getting Started

### Install MinVR Dependency

#### Download MinVR Repository

  ```
  git clone http://github.com/MinVR/MinVR
  git checkout beta
  ```
  
#### Build and Install MinVR

* Linux and Mac (command line)

  ```
  cd MinVR
  mkdir build
  cd build
  cmake ..
  make
  make install
  cd ../..
  ```

* Mac (Xcode)

  ```
  mkdir build
  cd build
  cmake .. -G Xcode
  # Open project in Xcode - build and install
  cd ../..
  ```
    
* Windows (Visual Studio)

  ```
  mkdir build
  cd build
  cmake .. -G "Visual Studio 12 Win64"
  # Open project in Visual Studio - build and install
  cd ../..
  ```

### Build Application

#### Download Application

  ```
  git clone http://github.com/MinVR/MinVRStandAloneApp
  cd MinVRStandAloneApp

  ```

#### Build Application

* Linux and Mac (command line)

  ```
  make
  ```

* Mac (Xcode)

  ```
  mkdir build
  cd build
  cmake .. -G Xcode
  # Open project in Xcode - build
  cd ../..
  ```
    
* Windows (Visual Studio)

  ```
  mkdir build
  cd build
  cmake .. -G "Visual Studio 12 Win64"
  # Open project in Visual Studio - build
  cd ../..
  ```

#### Run Application

  ```
  ./build/bin/MinGraphicsExample desktop.xml
  ```


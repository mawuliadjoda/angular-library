# angular-library
https://www.samarpaninfotech.com/blog/how-to-create-library-in-angular-tutorial/

ng new custom-loader
cd custom-loader
npm start
ng generate library my-lib

ng build my-lib
Built Angular Package!
 - from: C:\Users\koffi\Documents\dev\git\angular-library\custom-loader\projects\my-lib
 - to:   C:\Users\koffi\Documents\dev\git\angular-library\custom-loader\dist\my-lib

 use the library

 ng new use-lib
 cd use-lib
 install the library -> C:\Users\koffi\Documents\dev\git\angular-library\custom-loader\dist\my-lib
 npm install C:\Users\koffi\Documents\dev\git\angular-library\custom-loader\dist\my-lib

 ==> add schemas: [ CUSTOM_ELEMENTS_SCHEMA ] to app.module.ts in use-lib project
 


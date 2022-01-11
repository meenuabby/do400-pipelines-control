
de('nodejs') {
 stage('Checkout') {
 git branch: 'main',
 url: 'https://github.com/meenuabby/do400-pipelines-control'
 }
 stage('Backend Tests') {
 sh 'node ./backend/test.js'
 }
 stage('Frontend Tests') {
294 DO400-OCP4.6-en-5-20211123
Chapter 5 | Authoring Pipelines
 sh 'node ./frontend/test.js'
   }
}

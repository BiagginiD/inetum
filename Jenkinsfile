// Pipeline declarativo
pipeline {
   
    // Ejecutar el pipeline desde cualquier agente (nodo-maquina) disponible
    agent any
   
    // Definicion de fases
    stages {
       
        stage('Stage 1 - Build') {
           
            //Conjunto de pasos que componen la fase
            steps{
               
                echo 'Fase 1 de Stage Build';
               
            }
        }
       
        stage('Stage 2 - Test') {
           
            //Conjunto de pasos que componen la fase
            steps{
               
                echo 'Running Unit Test....';
                echo 'Running Integration Test....';
                echo 'Running Aceptacion Test....';
               
            }
        }
       
        stage('Stage 3 - Deploy') {
           
            //Conjunto de pasos que componen la fase
            steps{
               
                echo 'Deploying artifact!!!';
               
            }
        }
       
    }
   
}

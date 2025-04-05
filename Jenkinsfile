// Jenkinsfile clase 13, pasamos el scrip de 
// informacion del sistema a un job de jenkins

pipeline { 
    agent any
    stages{
        stage("agregar permisos"){
            steps{
                echo "Agregar los permisos de ejecucion"
                bash "chmod +x ./informe_del_sistema.sh"
        }
        stage("etapa1"){
            steps{
                echo "Ejecutar el informe de sistema"
                bash "./informe_del_sistema.sh" 
                }
            }
        }
    }
}
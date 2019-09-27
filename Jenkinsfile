node{
    stage('SCM Checkout'){
     git 'https://github.com/schakka-tech/airflow_files'
    }
    stage('Compile-Package){
     sh 'mvn package'
    }
    }

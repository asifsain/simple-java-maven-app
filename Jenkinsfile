@Library('Asif-Hussain')
import com.hello.groovy.MathFunctions
node {
	def a = 10;
	def b = 20;
    stage('Build') {
	echo new MathFunctions().Add(a,b)	
        echo 'App Building....'
    }
    stage('Test') {
	println("Hey There !!");
        echo 'App Testing....'
    }
    stage('Deploy') {
        echo 'New Clear App Deploying....'
    }
}

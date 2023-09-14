pipeline{
  agent any{
  }
  stages{
    stage{
      steps(Git Checkout){
        git branch: "main", url: "https://github.com/Desmondotutu/htmltodockerimage.git"
        }
    }
    stage{
      steps(Say Hellow){
        sh "Hello world!"
      }
    }
  }
}

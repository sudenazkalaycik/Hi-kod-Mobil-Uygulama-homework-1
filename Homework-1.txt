   
    Exercise 1 

void main() {
    print("Hello,World");
}

    Exercise 2

void main(){
  String name ="Sümeyye";
  int age=20;
  double height=1.64;
  bool isStudent=true;
  
  print("Name: $name");
  print("Age: $age");
  print("Height: $height cm");
  if(isStudent==true){
    print("I am a student");
  }
  else{
    print("I am not a student");
  }
}

   Exercise 3

void main(){
  int a=10,b=5,c=2;
  double result;
  
  int sum = a + b;
  int dif = a - b;
  int pro= a * b*c;
  
  result=(dif*c/sum)*pro;
  
  print("Result: $result");
}

   Exercise 4

void main(){
  int charge=101;
  
  if(charge==100){
    print("Telefon şarj edildi.");
  }
  else if(charge<20 && charge>=10){
    print("Telefonunuzu şarj edin.");
  }
  else if(charge<10){
    print("Kritik batarya seviyesi.");
  }
  else if(charge<100){
    print("Telefonunuzun şarjı $charge .");
  }
  else{
    print("Telefon uzaydan geldi herhalde!");
  }
}

   Exercise 5

void main(){
  String name="Sümeyye";
  int age=20;
  double height=1.64;
  String favoriteColor="sarı";
  
  display(name,age,height,favoriteColor);
  
}

void display(String name,int age,double height,String favoriteColor){
  print("Merhaba,ben $name,$age yaşındayım.Boyum $height ve en sevdiğim renk $favoriteColor.");
}


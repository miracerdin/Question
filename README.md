# Question = Takes the first name from the user and compares it to yours, Then if the name the user entered is the same as yours, print out such as : "Hello, Joseph! The password is : W@12", If the name the user entered is not the same as yours, print out such as : "Hello, Amina! See you later."


user_name = "mirac"
password = "1234"
      
name = str(input("write a name: "))
değer = {True : ("merhaba " + user_name + " sizin şifreniz : " + password + "' dir"), False :"Merhaba " + name+ " daha sonra görüşürüz" }
print(değer[user_name == name])

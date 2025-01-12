
* text=auto
email = input("Enter your e mail : ")
if email[0].isalpha():
    if email.count("@") == 1:
        if email.count(".") or email[-4] == ".":
            if email.islower():
                if email.isspace():
                    print("valid")
                else:
                    print("spaces present ")
            else:
                print("your characaters are not in lower case")

        else:
            print("place . at right place and only one time ")

    else:
        print("error in @ may be one is present or not present ")

else:
    print("wrong")

# Hello-World
First repository
# Here is a Python Program that accesses a dictionary with user input


# Write a program to allow user to input course number and display corresponding
# room number, instructor, and meeting time

def main():
    # Create dictionary
    dictionary = {"CS101": [3004, "Heynes", "8:00AM"], "CS102": [4501, "Alvarado", "9:00AM"], "CS103": [6755, "Rich", "10:00AM"], "NT110": [1244, "Burke", "11:00AM"], "CM241": [1411, "Lee", "1:00PM"]}
    # Get user input course number
    user = str(input("Enter Course Number: "))

    # Ask user if they want to enter another course number
    again= "y"
    while again!= "n" or again!= "N":

        print ( user +str(dictionary[user]))
        user= input("Enter another course number or n to quit: ")

        # If user enters input to discontinue program, end it
        if user == "n" or user == "N":
            print("Thanks for using the program!")
            break

# Call the main function
main()

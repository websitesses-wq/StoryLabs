print("WELCOME TO LIFE DECISION SIMULATOR")
print("---------------------------------")
while True:
    print("\nChoose a situation:")
    print("1. Morning Routine")
    print("2. Exam Day")
    print("3. Health Choice")
    print("4. Money Decision")
    print("5. Free Time Choice")
    choice = input("Enter 1 to 5: ")
    print("\nEnter your response:\n")
    action = input("Enter your choice (single word): ") #Enter the word relevant to the choice
    effort = input("Enter effort level (low/medium/high): ")
    print("\n----- RESULT -----\n")
    if choice == "1":
        print("You chose:", action)
        if effort == "high":
            print("You feel energetic and productive all day.")
        else:
            print("You feel lazy and tired.")
    elif choice == "2":
        print("Your exam approach was:", action)
        if effort == "high":
            print("You feel confident after the exam.")
        else:
            print("You regret not preparing enough.")
    elif choice == "3":
        print("Health choice:", action)
        if effort == "high":
            print("Your health improves slowly.")
        else:
            print("You feel weak and unhealthy.")
    elif choice == "4":
        print("Money decision:", action)
        if effort == "high":
            print("You save money for the future.")
        else:
            print("You struggle at the end of the month.")
    elif choice == "5":
        print("Free time activity:", action)
        if effort == "high":
            print("You learn something useful.")
        else:
            print("Time passes without benefit.")
    else:
        print("Invalid choice.")
    print("\n------------------")
    again = input("Try another situation? (yes/no): ")
    if again != "yes":
        print("\nSimulation ended.")
        break

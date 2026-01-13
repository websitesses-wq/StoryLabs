import matplotlib.pyplot as plt
import numpy as np

print("Welcome to EduExpense_Visuals")
print("------------------------------")

while True:

    print("1. Money_Spent")
    print("2. Marks_Scored")
    print("3. Exit")

    Choice_Problem = int(input("Enter your choice within 1-3: "))

    if Choice_Problem == 1:
        Months = ["January", "February", "March", "April", "May", "June","July", "August", "September", "October", "November", "December"]
        Money_Spent = []
        for i in Months:
            Money=int(input(f"Enter the money spent in {i}:"))
            Money_Spent.append(Money)    
        while True:
            Choice_Graph = int(input("Enter your choice :\n1.Bar_Graph\n2.Pie_Chart\n3.Exit_Graphs"))
            if Choice_Graph == 1:
    
                plt.figure()
                plt.bar(Months, Money_Spent)
                plt.title("Monthly-Money_Spent")
                plt.xlabel("Months")
                plt.ylabel("Money_Spent")
    
                plt.xticks(rotation=45)
                plt.tight_layout()
    
                for i, v in enumerate(Money_Spent):
                    plt.text(i, v, str(v), ha='center', va='bottom')
    
                plt.show()
                continue
    
            elif Choice_Graph == 2:
    
                plt.figure()
                plt.pie(Money_Spent, labels=Months, autopct="%1.1f%%")
                plt.title("Monthly_Money-spent")
    
                plt.show()
                continue
    
            else:
                print("Exitting_Graphs")
                break

    elif Choice_Problem == 2:

        subjects = []
        marks = []

        sub = int(input("Enter number of subjects: "))
        for i in range(1, sub + 1):
            name = input(f"Subject {i}: ")
            mark = int(input(f"Marks for {name}: "))
            subjects.append(name)
            marks.append(mark)

        while True:
            Choice_Graph = int(input("Enter your choice :\n1.Bar_Graph\n2.Pie_Chart\n3.Exit"))
            if Choice_Graph == 1:
    
                plt.figure()
                plt.bar(subjects, marks)
                plt.title("Marks Scored")
                plt.xlabel("Subjects")
                plt.ylabel("Marks")
    
                plt.xticks(rotation=45)
                plt.tight_layout()
    
                for i, v in enumerate(marks):
                    plt.text(i, v, str(v), ha='center', va='bottom')
    
                plt.show()
                continue
    
            elif Choice_Graph == 2:
    
                plt.figure()
                plt.pie(marks, labels=subjects, autopct="%1.1f%%")
                plt.title("Marks Distribution")
    
                plt.show()
                continue
    
            else:
                print("Exitting graph")
                break

    else:
        print("Thanks for using EduExpense_Visuals ")
        break

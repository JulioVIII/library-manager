books=[]

def menu():
    print("\n--- BOOK MANAGER ---")
    print("1.add book")
    print("2.view books")
    print("3.search book")
    print("4.exit")  


def add_book():
    book=input("enter book title:")
    books.append(book)

def view_books():
    if not books:
        print("no books found")
        return
    for book in books:
        print(book)
def search_book():
    title=input("Enter book tittle to search")
    for book in books:
        if book==title:
            print("book found")
            return
    print("book not found")
while True:
    menu()
    option=input("choose an option:")

    if option=="1":
        add_book()
    elif option=="2":
        view_books()
    elif option=="3":
        search_book()
    elif option=="4":
        print("goodbye")
        break
    
    else:
        print("invelid option")

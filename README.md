# Quiz-game
print("Quiz")
questions = [
    ["What is the capital of India?", "Mumbai", "New Delhi", "Kolkata", "Chennai", 2],
    ["Which river is known as the 'Ganges' in India?", "Yamuna", "Godavari", "Ganga", "Narmada", 3],
    ["What is the national animal of India?", "Tiger", "Lion", "Elephant", "Peacock", 1],
    ["Who is known as the 'Father of the Nation' in India?", "Jawaharlal Nehru", "Mahatma Gandhi", "Subhas Chandra Bose", "Bhagat Singh", 2],
    ["Which Indian festival is known as the 'Festival of Lights'?", "Holi", "Diwali", "Durga Puja", "Navratri", 2],
    ["The famous 'Taj Mahal' is located in which Indian city?", "Jaipur", "Mumbai", "Agra", "Hyderabad", 3],
    ["Who wrote the Indian national anthem 'Jana Gana Mana'?", "Rabindranath Tagore", "Bankim Chandra Chattopadhyay", "Sarojini Naidu", "Subramania Bharati", 1],
    ["What is the currency of India?", "Dollar", "Rupee", "Yen", "Euro", 2],
    ["Who is the current President of India?", "Narendra Modi", "Ram Nath Kovind", "Amit Shah", "Manmohan Singh", 2],
    ["The Indian Space Research Organisation (ISRO) was established in which year?", "1947", "1957", "1969", "1972", 3]
]
levels = [1000, 2000, 5000, 10000, 20000, 50000,100000,200000,500000,1000000]
final = [0,1000, 2000, 5000, 10000, 20000, 50000,100000,200000,500000,1000000]


for i in range(len(questions)):
  print(f"\nHere is your Question for Rs{levels[i]}\n", questions [i][0])
  print(f"1.{questions[i][1]}     2.{questions [i][2]}")
  print(f"3.{questions [i][3]}     4.{questions [i][4]}")
  a=int(input("enter correct answer(1/2/3/4)"))
  if a==questions[i][5]:
    print("your answer is correct")
    print(f"you won Rs.{levels[i]}")
  elif a>4:
    print("enter valid option i.e (1/2/3/4)")
   
    
    
  else:
   print(f"wrong answer the correct answer is {questions[i][5]}")
   print(f"your take home money is{final[i]}")
   break






         

  

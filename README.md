1.ভেরিয়েবল ঘোষনা (Declare) করে ইউজার থেকে ইনপুট নিয়ে আউতপুট প্রিন্ট করে এমণ একটি পোগ্রাম।




2.দুইটি সংখা ইনপুট নিয়ে যোগ, বিয়গ , গুন , ভাগ করে ফলাফল প্রিন্ট করে এমন একটি পোগ্রাম।
x = int(input("Enter Number :"))
y = int(input("Enter Number :"))
s = x+y
min = x-y
mult = x*y
dev = x/y
mod = x%y
print(f"sum :{s},min :{min}, mult :{mult}, dev :{dev}, mod : {mod}")

3. x=str(input("Enter Number:")
   y=str(input("Enter Number:")
   sum = x+y
   print(sum)

x=str(input("Enter Number :"))
y=str(input("Enter Number :"))
sum = x+y
print(sum)

x=float(input("Enter your name :"))
y=float(input("Enter your name :"))
sum = x+y
print(sum)

একটি পোগ্রাম লিখুন যা একটি আয়তখেত্রের দৈঘ্য এবং প্রস্থ  ইনপুট নিয়ে একটি হিসাব কর
Length = int(input("Enter Length :"))
Width = int(input("Enter Width :"))
area = Length * Width

print(area)


একজন শিক্ষাথী পরিক্ষা উওীণ হবে কিনা তা চেক করার জন্য একটি পোগ্রাম লিখুন । শিক্ষাথী  পাস করবে যদি তাদের স্কোর ৩৩ এর  বেশি বা সামান হয় এবং তাদের উপস্থিতি ৭৫% এর বেশি হয়।
হিন্টঃ >= নাকি <= কোনটি কাজে লাগবে?

Anas_Number = 60
Anas_Attendance = 1
if Anas_Number >= 33 and Anas_Attendance  0.75:
    print("you have passed")
else:
    print("you Have failed") 

মডুলাস অপারেটার (%) ব্যবহার করে প্রদত্ত সংখ্যাটি জোড় বা বিজোড়  কিনা তা পরিখ্যা করার জন্য একটি পগ্রাম লিখুন
হিন্টঃ ৬ জোড়, কারণ  ২ দিয়ে নিঃশেষে বিভাজ্য।


number = int(input("Enter Number : "))
if number % 2 == 0:
    print("true")
else:
    print("false")    

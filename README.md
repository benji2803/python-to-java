# python-to-java
I want to convert this into python
# create list  

my_list = []  

#get input

min_val=0;

total_input = int(input("Enter total number of elements : "))  

for i in range(0, total_input):  

       

   input_val = int(input())  

   if i==0:

       min_val=input_val

   if input_val < min_val:

       min_val=input_val

   my_list.append(input_val)

     

print(my_list)  

print(min_val)  

for i in range(0, total_input):  

  my_list[i]=my_list[i]-min_val

print(my_list)  

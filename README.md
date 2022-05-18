# OS-Directory
import os def main():
directory = input("Enter the directory that you want to save the file :")
filename = input("Enter the file name :")
name = input("Enter name :")
address = input("Enter address :")
phone = input("Enter phone number :")
file.write(",".join([name,address,phone]) + "n")
print("{}/{}.csv contents".format(directory,filename))

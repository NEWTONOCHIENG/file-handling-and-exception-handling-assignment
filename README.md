# file-handling-and-exception-handling-assignmentad 

# read from the original file and write a modiofied version to a new file
with open (''input . txt'' , ''r'') as infile
content = infile . read () # read the entire file content 
# modify the content (example;convert the upercase)
modified_content = content . upper()
# write the modified content to a new file
with open (''output . txt'', ''w'') as outfile;
outfile.write(modified_content)
print(''file modification complete.check ''output.txt''.'')

filename = is equal to input(''enter file the filename :) # ask for the file name
try:
    with open (filename, ''r'') as file
    content = file.read() # read file content
    print(''\nfile content;\n'')
    print( content # display file contentdcexcept fileNotfoundError;
print(''Error ;the file doesnt exist .'') 
except permission error
print (Error: you do not have permission to read this file.'')
except Exception as e:
         print(f''an unexpected error occured; {e}'')

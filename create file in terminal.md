# Create a new file using Terminal Window

1. **touch Command**

   Access a terminal window and use the touch command to create a new text file called test.txt:

```terminal
touch test.txt
```

2. **Path directory**

   Since no directory was specified, the touch command created the file in the current directory. Use the following template to create a new file in a specific directory:

```terminal
touch /path_to_directory/file_name
```

3. **cat Command**

   The cat command is used to output the contents of a file, several files, or even part of a file on the terminal screen. If the file doesn’t exist, the command creates it.

> Enter the following command to create an empty test2.txt file:

```terminal
cat > test2.txt
```

4. **echo Command**

   The echo command outputs text to the terminal, but it can also be used with the redirection operator > to create files and write text into them.

> Enter the following command to create a file called test3.txt and write Random sample text into it:

```terminal
echo 'Random sample text' > test3.txt
```

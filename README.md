# alt+K
Simple bash script to emulate in Linux/zsh the cmd +  K from macOS or OSX 

1. create a bash file with this content
````
echo -e '\0033\0143'
````
2. Give execution permissions (chmod +x)
3. add in your zshrc/zshprofile the following entry
````
bindkey -s '<code_keys>' '/path/to/your_file.sh\n'
````
You can use showkey -a to get the code_keys value


https://user-images.githubusercontent.com/245020/160958810-bc262954-7bbe-4673-89de-d0bb30531f77.mp4



